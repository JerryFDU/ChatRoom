# ChatRoom
一个python + socket实现的简单Cli版本聊天室

## 使用
你只需要安装python3环境即可运行脚本，项目下有两个包，一个叫做client，一个叫做server。client是客户端类的封装，server是服务器类的封装。里面是核心代码。项目根目录下还有两个_start.py文件，分别对应服务器和客户端程序的启动。

这里的服务器监听IP默认设在本机作为演示，如果你想部署在服务器上需要自己手动更改IP。

使用的时候需要先运行服务器程序，运行之后可以看到服务器日志：
```
[Server] 服务器正在运行......
```
接着开启客户端程序，客户端将自动连接到服务器程序，使用如下指令登录：
```
login '用户名'
```
输入该指令之后便可以开始聊天了，使用如下指令发送讯息：
```
send '消息'
```
发送之后，服务器将会自动将你的消息转发到所有在线的客户端，客户端收到消息后会自动显示，这样就完成了聊天室的功能。

## 作者的话
相信大家很多人都是为了交计网作业或者是想学习socket开发，才会找我这么一个小项目，希望大家能够用的开心，学的开心。

创作不易，如果觉得喜欢，还是尽量follow一哈我并且给项目点上小星星哦！

ヾ(◍°∇°◍)ﾉﾞ ✨