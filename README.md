# Tiny C++ Network Library


## 项目介绍

本项目是参考 muduo 实现的基于 Reactor 模型的多线程网络库。使用 C++ 11 编写去除 muduo 对 boost 的依赖，内部实现了一个小型的 HTTP 服务器，可支持 GET 请求和静态资源的访问，且附有异步日志监控服务端情况。

项目已经实现了 Channel 模块、Poller 模块、事件循环模块、HTTP 模块、定时器模块、异步日志模块、内存池模块、数据库连接池模块。   


## 感谢
- 《Linux高性能服务器编程》
- 《Linux多线程服务端编程：使用muduo C++网络库》
- https://github.com/chenshuo/muduo
