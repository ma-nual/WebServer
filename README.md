

WebServer
===============

Linux下C++轻量级Web服务器

* 使用 **线程池 + 非阻塞socket + epoll(ET和LT均实现) + 事件处理(Reactor和模拟Proactor均实现)** 的并发模型
* 使用**状态机**解析HTTP请求报文，支持解析**GET和POST**请求
* 访问服务器数据库实现web端用户**注册、登录**功能，可以请求服务器**图片和视频文件**
* 实现**同步/异步日志系统**，记录服务器运行状态
* 经Webbench压力测试可以实现**上万的并发连接**数据交换


框架
-------------

<div align=center><img src="http://ww1.sinaimg.cn/large/005TJ2c7ly1ge0j1atq5hj30g60lm0w4.jpg" height="765"/> </div>

