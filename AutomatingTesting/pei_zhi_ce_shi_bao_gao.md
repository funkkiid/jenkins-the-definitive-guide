# 配置测试报告

一旦构建过程产生了测试结果，你需要配置Jenkins来展示它们。

对于Maven项目，你需要做下面两步：
- 在构建中加入`mvn test`；
- 在确保执行了测试之后，需要告诉Jenkins测试报告的路径；

>提示：对于非JAVA项目，需要安装`xUnit插件`。安装完成插件之后需要配置测试报告的路径。因为Jenkins需要将这些报告转化为Junit报告以便他们能在Jenkins中展示。
