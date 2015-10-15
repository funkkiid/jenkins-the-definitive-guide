# 自动化测试
如果你没有在CI中使用自动化测试，那么你将错过许多项目中重要的东西。没有自动化测试的CI只是用来进行自动化构建的一个工具。CI的一个重要的原则就是每一次buid都是应该是可信的，你必须客观地决定是否某个build能够继续之后的build过程。如果没有自动化测试，你必须进行手工测试，这在CI中是非常不可取的。

在你的应用中集成自动化测试可以使用以下两种方法：
- 测试驱动开发（TDD）和行为驱动开发（BDD）
- 单元测试

> Jenkins还可以做其它类型的自动化测试，如：integration tesing,web testing,functional testing,performance testing,load testing。


Jenkins也可以和