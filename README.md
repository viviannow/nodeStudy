# nodeStudy
用版本管理工具nvm去管理在同一台机器，同时安装多个版本的node.js

nodejs知识总结
module
  module对象
  module.exports属性
  exports变量

package.jsong文件
  package.json文件内部就是一个JSON对象，该对象的每一个成员就是当前项目的一项设置
  
npm模块管理器

fs模块 该模块提供本地文件的读写能力

path模块 路径

process对象 process对象是Node的一个全局对象，提供当前Node进程的信息。它可以在脚本的任意位置使用，不必通过require命令加载。该对象部署了EventEmitter接口。

buffer对象 Buffer对象是Node处理二进制数据的一个接口。它是Node原生提供的全局对象，可以直接使用，不需要require('buffer')。

Event模块 Events模块是Node对“发布/订阅”模式（publish/subscribe）的实现。一个对象通过这个模块，向另一个对象传递消息。

stream接口 ”流“（stream）这个概念，最简单的理解，就是在数据还没有接收完成时，就开始处理它。

child process模块 child_process模块用于新建子进程。子进程的运行结果储存在系统缓存之中（最大200KB），等到子进程运行结束以后，主进程再用回调函数读取子进程的运行结果。

http模块 http模块主要用于搭建HTTP服务。使用Node搭建HTTP服务器非常简单。

assert模块 assert模块是Node的内置模块，主要用于断言。如果表达式不符合预期，就抛出一个错误。该模块提供11个方法，但只有少数几个是常用的。

cluster模块 cluster模块允许设立一个主进程和若干个worker进程，由主进程监控和协调worker进程的运行。

os 模块 os模块提供与操作系统相关的方法。

Net模块与DNS模块 net模块用于底层的网络通信。DNS模块用于解析域名。

Express框架 Express是目前最流行的基于Node.js的Web开发框架，可以快速地搭建一个完整功能的网站。

Koa框架 Koa是一个类似于Express的Web开发框架，创始人也是同一个人。它的主要特点是，使用了ES6的Generator函数，进行了架构的重新设计。也就是说，Koa的原理和内部结构很像Express，但是语法和内部结构进行了升级。
