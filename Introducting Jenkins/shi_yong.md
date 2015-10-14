# 使用

# 开始使用Jenkins

## 环境准备
CI工具最基本的功能是监视版本控制系统中代码，并且当代码改变的时候拉去和构建最新的版本。

###安装Java
安装完成之后，通过java -version检测是否安装正确。

###安装Git
- Ubuntu或其它Debian系统：```sudo apt-get install git-core```
- Fedora或其它基于RPM的系统：```sudo yum install git-core```

### 创建GitHub账号
1. 配置SSH keys 

    ```
    ssh-keygen -t rsa -b 4096 -C "gwpost@qq.com"
    sudo apt-get install xclip
    xclip -sel clip < ~/.ssh/id_rsa.pub
    ``` 

2. fork示例代码仓库  

    ```git clone git@github.com:gwpost/game-of-life.git```
