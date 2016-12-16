# RocketMQ-Learning

<p align="center"><img src ="logo.png" alt="RocketMQ-Learning logo" /></p>

RocketMQ是一个性能很好的消息中间件，他在阿里内部有着广泛的使用。这本书适合于希望理解**RocketMQ设计原理**的读者，建议结合带注释的源码一起阅读。<br>

为什么我们要阅读这本mini书？
* 这本书的目的是为了**弥补官方文档以及源码注释的稀少**。<br>
* 即使你没有使用过RocketMQ，通过本书你也能很快入门。<br>
* 通过本书，你可以学习到RocketMQ的设计理念(为什么可以做到如此高效？)。同时，你也能学习到计算机网络，操作系统相关的知识<br>
* 本书同时提供了带注释的源代码，结合源码理解完本教程你甚至可以进行**二次开发**，定制你自己想要的功能。<br>

本书从浅入深的介绍了RocketMQ的使用与设计原理，**运用了大量的图示**，即使是初学者也能很好的理解文章希望表达的意思。<br>
推荐初学者从第1章开始阅读。<br>

## 文章索引

#### [1.Overview](book/1-overview.md)
* Glossary explanation
* Start your own example

#### [2.How components work together](book/2-components.md)
* RocketMQ' Architecture
* The flow of messages in the component:message send, message store, push/pull message, consume message.

#### [3.What is NameServer](book/3-nameserver.md)

#### [4.The core of RocketMQ - Broker(1)](book/4-broker1 overview.md)
* Broker's Responsibilities:Coordinate message flow, message store

#### [5.The core of RocketMQ - Broker(2)](book/5-broker2 commit log.md)
* Commit log's implementation

#### [6.The core of RocketMQ - Broker(3)](book/6-broker3 consume queue.md)
* How consume queue works

#### [5.The core of RocketMQ - Broker(4)](book/7-broker4 index service.md)
* Index Service

#### [6.Consumer](book/8-consumer.md)
* How messgaes are consumed

#### [7.Producer](book/ch1-components.md)
* How messages are sent 
* Order message 





