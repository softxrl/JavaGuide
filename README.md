Java后端技术交流群(限工作一年及以上，架构视频免费领取) ：[![QQ群](https://img.shields.io/badge/QQ%E7%BE%A4-869815609-red.svg)](https://jq.qq.com/?_wv=1027&k=5QqyxIx) 

强烈推荐七牛云CEO老许的[架构专栏](#架构)，微信扫描二维码购买后，[加我好友](#联系我)私聊我领取24元返现。129元的课程相当于75入手。

<h1 align="center">Java 学习/面试指南</h1>
<p align="center">
<a href="https://github.com/Snailclimb/JavaGuide" target="_blank">
	<img src="https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-3/logo - 副本.png" width=""/>
</a>
</p>

<p align="center">
  <a href="https://snailclimb.gitee.io/javaguide"><img src="https://img.shields.io/badge/阅读-read-brightgreen.svg" alt="阅读"></a>
  <a href="#联系我"><img src="https://img.shields.io/badge/chat-微信群-blue.svg" alt="微信群"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-JavaGuide-lightgrey.svg" alt="公众号"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/PDF-Java面试突击-important.svg" alt="公众号"></a>
  <a href="#投稿"><img src="https://img.shields.io/badge/support-投稿-critical.svg" alt="投稿"></a>
<h2 align="center">Special Sponsors</h2>
</p>

<p align="center">
<a href="https://e.coding.net/?utm_source=JavaGuide" target="_blank">
  <img src="https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-3/Coding Devops.png" width=""/>
 </a>
</p>

推荐一下我的另外一个正在维护的项目：[programmer-advancement](https://github.com/Snailclimb/programmer-advancement) (技术人员成长必备！)

推荐使用 <https://snailclimb.top/JavaGuide/> 在线阅读(访问速度慢的话，请使用 <https://snailclimb.gitee.io/javaguide> )，在线阅读内容本仓库同步一致。这种方式阅读的优势在于：有侧边栏阅读体验更好，Gitee pages 的访问速度相对来说也比较快。

## 目录

- [Java](#java)
    - [基础](#基础)
    - [容器](#容器)
    - [并发](#并发)
    - [JVM](#jvm)
    - [I/O](#io)
    - [Java 8](#java-8)
    - [编程规范](#编程规范)
- [网络](#网络)
- [操作系统](#操作系统)
    - [Linux相关](#linux相关)
- [数据结构与算法](#数据结构与算法)
    - [数据结构](#数据结构)
    - [算法](#算法)
- [数据库](#数据库)
    - [MySQL](#mysql)
    - [Redis](#redis)
- [系统设计](#系统设计)
    - [设计模式](#设计模式)
    - [常用框架](#常用框架)
    - [数据通信](#数据通信)
    - [网站架构](#网站架构)
- [面试指南](#面试指南)
    - [备战面试](#备战面试)
    - [常见面试题总结](#常见面试题总结)
    - [面经](#面经)
- [工具](#工具)
    - [Git](#git)
    - [Docker](#Docker)
- [资料](#资料)
    - [书单](#书单)
    - [Github榜单](#Github榜单)
- [待办](#待办)
- [说明](#说明)

## Java

### 基础

* [Java 基础知识回顾](docs/java/Java基础知识.md)
* [J2EE 基础知识回顾](docs/java/J2EE基础知识.md)
* [Collections 工具类和 Arrays 工具类常见方法](docs/java/Basis/Arrays%2CCollectionsCommonMethods.md)
* [Java常见关键字总结：static、final、this、super](docs/java/Basis/final、static、this、super.md) 

### 容器

* **常见问题总结：**
  * [这几道Java集合框架面试题几乎必问](docs/java/这几道Java集合框架面试题几乎必问.md)
  * [Java 集合框架常见面试题总结](docs/java/Java集合框架常见面试题总结.md)
* **源码分析：**
  * [ArrayList 源码学习](docs/java/ArrayList.md) 
  * [【面试必备】透过源码角度一步一步带你分析 ArrayList 扩容机制](docs/java/ArrayList-Grow.md)    
  * [LinkedList 源码学习](docs/java/LinkedList.md)   
  * [HashMap(JDK1.8)源码学习](docs/java/HashMap.md)  

### 并发

* [并发编程面试必备：synchronized 关键字使用、底层原理、JDK1.6 之后的底层优化以及 和ReenTrantLock 的对比](docs/java/synchronized.md)
* [并发编程面试必备：乐观锁与悲观锁](docs/essential-content-for-interview/面试必备之乐观锁与悲观锁.md)
* [并发编程面试必备：JUC 中的 Atomic 原子类总结](docs/java/Multithread/Atomic.md)
* [并发编程面试必备：AQS 原理以及 AQS 同步组件总结](docs/java/Multithread/AQS.md)
* [BATJ都爱问的多线程面试题](docs/java/Multithread/BATJ都爱问的多线程面试题.md)
* [并发容器总结](docs/java/Multithread/并发容器总结.md)

### JVM

* [可能是把Java内存区域讲的最清楚的一篇文章](docs/java/可能是把Java内存区域讲的最清楚的一篇文章.md)
* [搞定JVM垃圾回收就是这么简单](docs/java/搞定JVM垃圾回收就是这么简单.md)
* [《深入理解Java虚拟机》第2版学习笔记](docs/java/Java虚拟机（jvm）.md)

### I/O

* [BIO,NIO,AIO 总结 ](docs/java/BIO-NIO-AIO.md)
* [Java IO 与 NIO系列文章](docs/java/Java%20IO与NIO.md)

### Java 8 

* [Java 8 新特性总结](docs/java/What's%20New%20in%20JDK8/Java8Tutorial.md)
* [Java 8 学习资源推荐](docs/java/What's%20New%20in%20JDK8/Java8教程推荐.md)

### 编程规范

- [Java 编程规范](docs/java/Java编程规范.md)

## 网络

* [计算机网络常见面试题](docs/network/计算机网络.md)
* [计算机网络基础知识总结](docs/network/干货：计算机网络知识总结.md)
* [HTTPS中的TLS](docs/network/HTTPS中的TLS.md)

## 操作系统

### Linux相关

* [后端程序员必备的 Linux 基础知识](docs/operating-system/后端程序员必备的Linux基础知识.md)  
* [Shell 编程入门](docs/operating-system/Shell.md)  

## 数据结构与算法

### 数据结构

- [数据结构知识学习与面试](docs/dataStructures-algorithms/数据结构.md)

### 算法

- [算法学习资源推荐](docs/dataStructures-algorithms/算法学习资源推荐.md)  
- [算法总结——几道常见的子符串算法题 ](docs/dataStructures-algorithms/几道常见的子符串算法题.md)
- [算法总结——几道常见的链表算法题 ](docs/dataStructures-algorithms/几道常见的链表算法题.md)   
- [剑指offer部分编程题](docs/dataStructures-algorithms/剑指offer部分编程题.md)
- [公司真题](docs/dataStructures-algorithms/公司真题.md)
- [回溯算法经典案例之N皇后问题](docs/dataStructures-algorithms/Backtracking-NQueens.md)

## 数据库

### MySQL

* [MySQL 学习与面试](docs/database/MySQL.md)
* [一千行MySQL学习笔记](docs/database/一千行MySQL命令.md)
* [MySQL高性能优化规范建议](docs/database/MySQL高性能优化规范建议.md)
* [搞定数据库索引就是这么简单](docs/database/MySQL%20Index.md)
* [事务隔离级别(图文详解)](docs/database/事务隔离级别(图文详解).md)
* [一条SQL语句在MySQL中如何执行的](docs/database/一条sql语句在mysql中如何执行的.md)

### Redis

* [Redis 总结](docs/database/Redis/Redis.md)
* [Redlock分布式锁](docs/database/Redis/Redlock分布式锁.md)
* [如何做可靠的分布式锁，Redlock真的可行么](docs/database/Redis/如何做可靠的分布式锁，Redlock真的可行么.md)

## 系统设计

### 设计模式

- [设计模式系列文章](docs/system-design/设计模式.md)

### 常用框架

#### Spring

- [Spring 学习与面试](docs/system-design/framework/Spring学习与面试.md)
- [Spring中bean的作用域与生命周期](docs/system-design/framework/SpringBean.md)
- [SpringMVC 工作原理详解](docs/system-design/framework/SpringMVC%20%E5%B7%A5%E4%BD%9C%E5%8E%9F%E7%90%86%E8%AF%A6%E8%A7%A3.md)

#### ZooKeeper

- [可能是把 ZooKeeper 概念讲的最清楚的一篇文章](docs/system-design/framework/ZooKeeper.md)
- [ZooKeeper 数据模型和常见命令了解一下，速度收藏！](docs/system-design/framework/ZooKeeper数据模型和常见命令.md)

### 数据通信

- [数据通信(RESTful、RPC、消息队列)相关知识点总结](docs/system-design/data-communication/数据通信(RESTful、RPC、消息队列).md)
- [Dubbo 总结：关于 Dubbo 的重要知识点](docs/system-design/data-communication/dubbo.md)
- [消息队列总结：新手也能看懂，消息队列其实很简单](docs/system-design/data-communication/message-queue.md)
- [一文搞懂 RabbitMQ 的重要概念以及安装](docs/system-design/data-communication/rabbitmq.md)

### 网站架构

- [一文读懂分布式应该学什么](docs/system-design/website-architecture/分布式.md)
- [8 张图读懂大型网站技术架构](docs/system-design/website-architecture/8%20张图读懂大型网站技术架构.md)
- [【面试精选】关于大型网站系统架构你不得不懂的10个问题](docs/system-design/website-architecture/【面试精选】关于大型网站系统架构你不得不懂的10个问题.md)

## 面试指南

### 备战面试

* [【备战面试1】程序员的简历就该这样写](docs/essential-content-for-interview/PreparingForInterview/程序员的简历之道.md)
* [【备战面试2】初出茅庐的程序员该如何准备面试？](docs/essential-content-for-interview/PreparingForInterview/interviewPrepare.md)
* [【备战面试3】7个大部分程序员在面试前很关心的问题](docs/essential-content-for-interview/PreparingForInterview/JavaProgrammerNeedKnow.md)
* [【备战面试4】Github上开源的Java面试/学习相关的仓库推荐](docs/essential-content-for-interview/PreparingForInterview/JavaInterviewLibrary.md)
* [【备战面试5】如果面试官问你“你有什么问题问我吗？”时，你该如何回答](docs/essential-content-for-interview/PreparingForInterview/如果面试官问你“你有什么问题问我吗？”时，你该如何回答.md)
* [【备战面试6】美团面试常见问题总结（附详解答案）](docs/essential-content-for-interview/PreparingForInterview/美团面试常见问题总结.md)

### 常见面试题总结

* [第一周（2018-8-7）](docs/essential-content-for-interview/MostCommonJavaInterviewQuestions/第一周（2018-8-7）.md) (为什么 Java 中只有值传递、==与equals、 hashCode与equals)
* [第二周（2018-8-13）](docs/essential-content-for-interview/MostCommonJavaInterviewQuestions/第二周(2018-8-13).md)(String和StringBuffer、StringBuilder的区别是什么？String为什么是不可变的？、什么是反射机制？反射机制的应用场景有哪些？......)
* [第三周（2018-08-22）](docs/java/这几道Java集合框架面试题几乎必问.md) （Arraylist 与 LinkedList 异同、ArrayList 与 Vector 区别、HashMap的底层实现、HashMap 和 Hashtable 的区别、HashMap 的长度为什么是2的幂次方、HashSet 和 HashMap 区别、ConcurrentHashMap 和 Hashtable 的区别、ConcurrentHashMap线程安全的具体实现方式/底层具体实现、集合框架底层数据结构总结）
* [第四周(2018-8-30).md](docs/essential-content-for-interview/MostCommonJavaInterviewQuestions/第四周(2018-8-30).md) （主要内容是几道面试常问的多线程基础题。）

### 面经

- [5面阿里,终获offer(2018年秋招)](docs/essential-content-for-interview/BATJrealInterviewExperience/5面阿里,终获offer.md)
- [蚂蚁金服2019实习生面经总结(已拿口头offer)](docs/essential-content-for-interview/BATJrealInterviewExperience/蚂蚁金服实习生面经总结(已拿口头offer).md)

## 工具

### Git

* [Git入门](docs/tools/Git.md)

### Docker

* [Docker 入门](docs/tools/Docker.md)
* [一文搞懂 Docker 镜像的常用操作！](docs/tools/Docker-Image.md)

## 资料test

### 书单

- [Java程序员必备书单](docs/data/java-recommended-books.md)

### Github榜单

- [Java 项目月榜单](docs/github-trending/JavaGithubTrending.md)

***

## 待办

- [x] [Java 8 新特性总结](docs/java/What's%20New%20in%20JDK8/Java8Tutorial.md)
- [x] [Java 8 新特性详解](docs/java/What's%20New%20in%20JDK8/Java8教程推荐.md)
- [ ] Java 多线程类别知识重构(---正在进行中---)
- [x] [BIO,NIO,AIO 总结 ](docs/java/BIO-NIO-AIO.md)
- [ ] Netty 总结(---正在进行中---)
- [ ] 数据结构总结重构(---正在进行中---)

## 说明

### 介绍

*  **对于 Java 初学者来说：** 本文档倾向于给你提供一个比较详细的学习路径，让你对于Java整体的知识体系有一个初步认识。另外，本文的一些文章
也是你学习和复习 Java 知识不错的实践；
*  **对于非 Java 初学者来说：** 本文档更适合回顾知识，准备面试，搞清面试应该把重心放在那些问题上。要搞清楚这个道理：提前知道那些面试常见，不是为了背下来应付面试，而是为了让你可以更有针对的学习重点。

Markdown 格式参考：[Github Markdown格式](https://guides.github.com/features/mastering-markdown/)，表情素材来自：[EMOJI CHEAT SHEET](https://www.webpagefx.com/tools/emoji-cheat-sheet/)。

利用 docsify 生成文档部署在 Github pages: [docsify 官网介绍](https://docsify.js.org/#/)

### 关于转载

如果你需要转载本仓库的一些文章到自己的博客的话，记得注明原文地址就可以了。

### 如何对该开源文档进行贡献

1. 笔记内容大多是手敲，所以难免会有笔误，你可以帮我找错别字。
2. 很多知识点我可能没有涉及到，所以你可以对其他知识点进行补充。
3. 现有的知识点难免存在不完善或者错误，所以你可以对已有知识点的修改/补充。

### 为什么要做这个开源文档？

初始想法源于自己的个人那一段比较迷茫的学习经历。主要目的是为了通过这个开源平台来帮助一些在学习 Java 或者面试过程中遇到问题的小伙伴。

### 投稿

由于我个人能力有限，很多知识点我可能没有涉及到，所以你可以对其他知识点进行补充。大家也可以对自己的文章进行自荐，对于不错的文章不仅可以成功在本仓库展示出来更可以获得作者送出的 50 元左右的任意书籍进行奖励(当然你也可以直接折现50元)。

### 联系我

添加我的微信备注“Github”,回复关键字 **“加群”** 即可入群。

![我的微信](https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-2/JavaGuide.jpg)


### 架构

<a href="https://time.geekbang.org/column/intro/166?code=-qJu3VIe2PPcts3jpNEti1EflIaCAZwLkQhd2mF4ESg%3D&utm_term=SPoster" target="_blank">
	<img src="https://my-blog-to-use.oss-cn-beijing.aliyuncs.com/2019-3微信图片_20190411230100.jpg" width="300px"/>
</a>

### Contributor

下面是笔主收集的一些对本仓库提过有价值的pr或者issue的朋友，人数较多，如果你也对本仓库提过不错的pr或者issue的话，你可以加我的微信与我联系。下面的排名不分先后！


<a href="https://github.com/spikesp">
    <img src="https://avatars0.githubusercontent.com/u/12581996?s=460&v=4" width="45px"></a>
<a href="https://github.com/fanofxiaofeng">
    <img src="https://avatars0.githubusercontent.com/u/3983683?s=460&v=4" width="45px"></a>
<a href="https://github.com/Gene1994">
    <img src="https://avatars3.githubusercontent.com/u/24930369?s=460&v=4" width="45px">
</a>
<a href="https://github.com/illusorycloud">
    <img src="https://avatars3.githubusercontent.com/u/31980412?s=460&v=4" width="45px">
</a>
<a href="https://github.com/LiWenGu">
    <img src="https://avatars0.githubusercontent.com/u/15909210?s=460&v=4" width="45px">
</a>
<a href="https://github.com/kinglaw1204">
    <img src="https://avatars1.githubusercontent.com/u/20039931?s=460&v=4" width="45px">
</a>
<a href="https://github.com/jun1st">
    <img src="https://avatars2.githubusercontent.com/u/14312378?s=460&v=4" width="45px">
</a>"
<a href="https://github.com/fantasygg">  
    <img src="https://avatars3.githubusercontent.com/u/13445354?s=460&v=4" width="45px">
</a>
<a href="https://github.com/debugjoker">  
    <img src="https://avatars3.githubusercontent.com/u/26218005?s=460&v=4" width="45px">
</a>
<a href="https://github.com/zhyank">  
    <img src="https://avatars0.githubusercontent.com/u/17696240?s=460&v=4" width="45px">
</a>
<a href="https://github.com/Goose9527">  
    <img src="https://avatars2.githubusercontent.com/u/43314997?s=460&v=4" width="45px">
</a>
<a href="https://github.com/yuechuanx">  
    <img src="https://avatars3.githubusercontent.com/u/19339293?s=460&v=4" width="45px">
</a>

### 公众号

如果大家想要实时关注我更新的文章以及分享的干货的话，可以关注我的公众号。

**《Java面试突击》:** 由本文档衍生的专为面试而生的《Java面试突击》V2.0 PDF 版本[公众号](#公众号)后台回复 **"Java面试突击"** 即可免费领取！

**Java工程师必备学习资源:** 一些Java工程师常用学习资源[公众号](#公众号)后台回复关键字 **“1”** 即可免费无套路获取。 

![我的公众号](https://user-gold-cdn.xitu.io/2018/11/28/167598cd2e17b8ec?w=258&h=258&f=jpeg&s=27334)
