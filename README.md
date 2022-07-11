### 项目说明

该项目 webServer2.0 使用 epoll + 线程池实现，可以实现GET、POST方法的部分内容
的解析，可以解析的文件类型有html、js、css、jpg、png、ico、mp3等。服务器可以
稳定的运行，关闭连接由客户端发起。

### 使用说明

该项目使用时，需要在目录中放置一个mp3文件，并命名为1.mp3，具体位置为
webServer2.0目录下。使用make进行编译连接源文件，使用`./server port`运行
程序。其中，`port`为端口号。以8080端口为例，终端输入`./server 8080`，打
开浏览器，输入`localhost:8080`，即可看到网页显示。
# webServer
