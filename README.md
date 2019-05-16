![互联网 Java 多线程那些事](https://raw.githubusercontent.com/qiurunze123/imageall/master/thread100.png)

> 邮箱 : [QiuRunZe_key@163.com](QiuRunZe_key@163.com)

> Github : [https://github.com/qiurunze123](https://github.com/qiurunze123)

> QQ : [3341386488](3341386488)

> QQ群 :

 ![整体流程](https://raw.githubusercontent.com/qiurunze123/imageall/master/qq.png)
 
 多线程从基础到进阶，分析入坑出坑，以及工作实操,最后会分享一个项目，针对如何进行大数据量（经测试几亿数据完全搞的定）进行安全高可用的策略，
 示例为高可用高可靠高性能 三高导入系统 DEMO分析 ,如何进行数据分片,数据导入,计算,多线程策略等等 本文属于进阶系列，有问题或者更好的想法可以一起探讨！ 
 一点小建议：学习本系列知识之前，如果你完全没接触过 `SpringBoot`、`CountDownLatch`、`线程池`、`工作队列`、`工作窃取等` 等，那么我建议你可以先在网上搜一下每一块知识的快速入门， 也可以下载本项目边做边学习，
 我的项目完全是实战加讲解不想写一堆的文章，浪费我们的生命，你还不懂内层含义，想要明白就边实际操作边学习，效果会更好！加油💪💪
 
 
 [![Travis](https://img.shields.io/badge/language-Java-yellow.svg)](https://github.com/qiurunze123)
    
###  [如要提交代码请先看--提交合并代码规范提交者的后面都会有署名方便大家问问题](/docs/code-criterion.md)
###  [多线程之前更新版本 -- 请进代码路径：com.geek.threadandjuc](/docs/thread-base-1.md)

####  [java并行程序基础](/docs/thread-base-3.md)

####  [java内存模型和线程安全](/docs/thread-base-4.md)

####  [valatile 专题解析](/docs/thread-base-5.md)

| ID | Problem  | Article | 
| --- | ---   | :--- |
| 000 |volatile是什么 | [解决思路](/docs/volatile.md) |
| 001 |JMM内存模型值之可见性 | [解决思路](/docs/volatile.md) |
| 002 |可见性验证说明 | [解决思路](/docs/volatile.md) |
| 003 |volatile不保证原子性 | [解决思路](/docs/volatile.md) |
| 004 |volatile指令重构排序 | [解决思路](/docs/volatile.md) |
| 005 |单例模式在多线程下可能存在的问题 | [解决思路](/docs/volatile.md) |
| 006 |单例模式volatile分析| [解决思路](/docs/volatile.md) |

####  [无锁类 CAS , ABA , Atomic ......](/docs/thread-base-6.md)

| ID | Problem  | Article | 
| --- | ---   | :--- |
| 000 |CAS是什么 | [解决思路](/docs/CASandABA.md) |
| 001 |CAS底层原理 | [解决思路](/docs/CASandABA.md) |
| 002 |CAS缺点 | [解决思路](/docs/CASandABA.md) |
| 003 |ABA问题 | [解决思路](/docs/CASandABA.md) |
| 004 |AtomicReference原子引用 | [解决思路](/docs/CASandABA.md) |
| 005 |AtomicStampedReference版本号原子引用 | [解决思路](/docs/CASandABA.md) |
| 006 |ABA问题的解决| [解决思路](/docs/CASandABA.md) |

####  [AQS .....](/docs/thread-base-14.md)

####  [JDK并发包 reentrantlock , condition , semaphone , readwritelock ,CountDownLatch,BlockingQueue.....](/docs/thread-base-7.md)

####  [JDK并发包 ConcurrentHashMap 精度分析](/docs/thread-base-8.md)

####  [JDK 线程池高度解析 ](/docs/thread-base-9.md)

####  [JDK ForkJoin 模式精度分析  ](/docs/thread-base-10.md)

####  [JDK 单例模式 不变模式 Future模式 生产者 消费者 .......  ](/docs/thread-base-11.md)

####  [NIO AIO 详解  ](/docs/thread-base-12.md)

####  [并发断点调试 JDK新特性 .....  ](/docs/thread-base-13.md)

####  [锁优化 .....  ](/docs/thread-base-13.md)


=========================================================================


##### 高可用高可靠高性能 三高导入系统 DEMO分析 
| ID | Problem  | Article | 
| --- | ---   | :--- |
| 000 |数据如何分片 | [解决思路](/docs/code-solve.md) |
| 001 |如何实现高可用 | [解决思路](/docs/code-solve.md) |
| 003 |如何实现高性能|[解决思路](/docs/code-solve.md)  |
| 003 |如何实现高可靠 |[解决思路](/docs/code-solve.md)  |
| 004 |如何自定义线程池以及使用与导入🙋🐓 |[解决思路](/docs/code-solve.md)  |
| 005 |如何利用CountDownLatch使用与导入|[解决思路](/docs/code-solve.md)  |
| 006 |表的设计与思考 |[解决思路](/docs/code-solve.md)  |
| 007 |如何控制数据一致性 |[解决思路](/docs/code-solve.md)  |
| 008 |如何实现幂等性 |[解决思路](/docs/code-solve.md)  |
| 009 |如何使用ForkJoin进行使用与导入 |[解决思路](/docs/code-solve.md)  |
| 010 |如何使用栅栏进行使用与导入 |[解决思路](/docs/code-solve.md)  |
| 011 |数据的导入性能 -- 数据 |[解决思路](/docs/code-solve.md)  |
| 012 |为什么需要一个环境隔离系统来维护环境数据 |[解决思路](/docs/code-solve.md)  |
| 013 |定时任务的开启与一些小的技巧|[解决思路](/docs/code-solve.md)  |
| 014 |服务波动怎么解决数据不丢失 |[解决思路](/docs/code-solve.md) |
| 015 |数据报警?(简单版) |[解决思路](/docs/code-solve.md) |


##### Guava 全操作 DEMO分析


| ID | Problem  | Article | 
| --- | ---   | :--- |
| 000 |Guava Joiner | [解决思路](/docs/Guava.md) |
| 000 |Guava Splitter | [解决思路](/docs/Guava.md) |
| 000 |Guava Preconditions&Objects&assert | [解决思路](/docs/Guava.md) |
| 000 |Guava Objects&MoreObjects&ComparisonChain | [解决思路](/docs/Guava.md) |
| 000 |Guava Strings&Charsets&CharMatcher | [解决思路](/docs/Guava.md) |
| 000 |Guava Guava之函数式接口 | [解决思路](/docs/Guava.md) |
| 000 |Guava StopWatch和JDK之ServiceLoader | [解决思路](/docs/Guava.md) |
| 000 |Guava Files | [解决思路](/docs/code-solve.md) |
| 000 |Guava CharSource和CharSink源码剖析 | [解决思路](/docs/Guava.md) |
| 000 |Guava ByteSource和ByteSink源码剖析 | [解决思路](/docs/Guava.md) |
| 000 |Guava CharStreams和ByteStreams源码剖析 | [解决思路](/docs/Guava.md) |
| 000 |Guava Closer使用和原理剖析 | [解决思路](/docs/code-solve.md) |
| 000 |Guava Base64原理详解，手动实现base64的Encoding | [解决思路](/docs/Guava.md) |
| 000 |Guava EventBus的使用详解 | [解决思路](/docs/Guava.md) |
| 000 |Guava EventBus和NIO2.0 WatchService综合实战 | [解决思路](/docs/Guava.md) |
| 000 |Guava Monitor使用讲解 | [解决思路](/docs/Guava.md) |
| 000 |Guava RateLimiter在漏桶限流算法中的使用 | [解决思路](/docs/Guava.md) |
| 000 |Guava ListenableFuture,FutureCallBack讲解 | [解决思路](/docs/Guava.md) |
| 000 |Guava LRU算法原理以及两种LRU算法的实现 | [解决思路](/docs/Guava.md) |
| 000 |Guava SoftReference，WeakReference，PhantomReference精讲 | [解决思路](/docs/Guava.md) |
| 000 |Guava SoftReference加LRU算法实现InMemoryCache | [解决思路](/docs/Guava.md) |
| 000 |Guava CacheLoader，CacheBuilder，LoadingCache以及两种驱逐策略讲解 | [解决思路](/docs/Guava.md) |
| 000 |Guava WeakKey，SoftValues，时间逐出的两种策略 | [解决思路](/docs/Guava.md) |
| 000 |Guava NullValue，Removal通知，Refresh，预加载等 | [解决思路](/docs/Guava.md) |
| 000 |Guava RecordStats，CacheBuilderSpec详解 | [解决思路](/docs/Guava.md) |
| 000 |Guava Collections之FluentIterable详细讲解 | [解决思路](/docs/Guava.md) |
| 000 |Guava Collections之Lists详细介绍 | [解决思路](/docs/Guava.md) |
| 000 |Guava Collections之Sets讲解 | [解决思路](/docs/Guava.md) |
| 000 |Guava Maps,BiMap,MultiMap详细介绍 | [解决思路](/docs/Guava.md) |
| 000 |Guava Table,Range用法详细介绍 | [解决思路](/docs/Guava.md) |
| 000 |Guava Range,RangeMap详细讲解 | [解决思路](/docs/Guava.md) |
| 000 |Guava Immutable Collections,Sorted Collections | [解决思路](/docs/Guava.md) |
