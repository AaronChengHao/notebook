下面列了我读过的一些编程相关的书籍，写了一些对书的印象，都是个人观点。书名后是我个人对书的推荐强烈度打的分（10分满分），都是拍脑袋打的。

我比较习惯读纸质书，买书也比较谨慎，踩的坑少（围笑），分打得可能比较高一些。

#操作系统
**《Linux内核设计与实现》**10分：全书都在讲 Linux 内核的设计思想，实现并不多，作为操作系统的入门书非常适合。没有很多复杂的接口，思想也容易理解。对我个人来说，解开了我很多对操作系统运行的疑惑，也对编程很有借鉴意义。建议对操作系统不清楚的早读这本书。

**《Unix环境高级编程》**8分：著名的 APUE，编程刚入门时看的，当时没什么基础，详细内容忘得差不多了，印象很深的就是文件操作接口的参数很多。书里介绍了很多操作系统常用接口，新手可以大概看一遍对系统提供的接口有个印象。我准备再读一遍。

**《Unix网络编程 卷二 进程间通信》**10分：把 UNP 放在这里是因为卷二讲了很多系统内部的 IPC，一直在用的 unix domain sockets 是真神器，推荐后端工程师一定要看这本书。

#网络
**《TCP/IP详解 卷一》**10分：从链路层到传输层把各种网络协议都介绍了一遍，TCP 的各种实现也讲得非常细，新手可以略翻一下理解一下网络。对应用层协议熟悉了之后再回过来仔细读一下本书。

**《Unix网络编程 卷一 套接字联网API》**8分：UNP。讲了很多网络 socket 相关接口，有很多客户端和服务器代码实现，同样我还得再读一遍。

**《Web性能权威指南》**6分：书的重点是性能，分别从传输层协议、无线网络和HTTP协议讲怎么做性能优化。最后还介绍了浏览器、websocket 和 WebRTC，最后一个做 B/S 的真心没听过，也算开了下眼界。

**《构建高性能Web站点》**9分：全书也在重点讲 Web 性能，不过更偏向于服务端架构的实践，还在读。

#数据库
**《Redis设计与实现》**8分：从底层介绍了 Redis 多种数据结构的设计与实现，还有多种配套策略的实现，如数据持久化、集群等。可以说对 Redis 所有部分的设计都介绍得很清楚，毕竟是作者是分析过全部源码的。推荐 Redis 运维或对 Redis 的实现感兴趣的读。

**《MySQL技术内幕：Innodb存储引擎》**7分：如副标题，全书都在讲 Innodb 存储引擎。通过各个模块的设计实现，再给出我们使用 Innodb 时的需要注意的点和优化方案。推荐中级开发工程师读。

#编程语言
**《C Primer Plus》**7分：C 语言入门的推荐书，主要是 C 的语法，详细而权威，没什么好说的。

#数据结构与算法
**《数据结构与算法分析 - C语言实现》**5分：作为一个数学渣，对算法有本能的恐惧，这本书是咬着牙读下去的，还跳过了很多部分。书很生硬，没有形象的比喻，通过一堆堆的代码和数学公式去理解算法真的挺不容易的。

#代码
**《Head First 设计模式》**7分：跟外面的那些技术书籍一点也不一样，全书充满了插图，每一个设计模式都通过一个浮夸的故事来讲（外国人嘛）。文中代码中用 Java 实现，不过都是最基本的语法。好像只写了 16 个设计模式？不过我觉得用来学习设计模式完全 OK。

**《代码大全 第二版》**7分：中文名是真的俗，代码百货？不过书不是代码展览馆，而是教人怎么写出优良的代码的。可能我个人一直对代码质量比较在意，让我眼前一亮的地方不是特别的多，不过不可否认书真的不错，建议新手早读一遍。

**《重构：改善既有代码的设计》**4分：在一次重构之前买来看的，讲得是对小块代码的重构方式，全书就像一个整齐排放的货架，上面全是对一些代码重构方式的抽象，列得让人有点懵，如果新手看这本书并对照着重构代码的话，我觉得效果应该不会太好（委婉）。

书还在读，列表也会增加，之前读过的书还可能会再读一遍写一些新的感受，欢迎关注。