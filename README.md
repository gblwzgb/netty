# 源码调试
clone了最新的代码，将代码导入IDEA中，运行`EchoServer.java`的时候，会发现单元测试有编译错误。

搜索了半天，还是不行。

最后切换到`4.0.27-Final`的tag分支上才可以。

如果你发现切换到`4.0.27-Final`分支上，Common包的target目录下有编译报错，则`mvn clean compile`该jar包即可。