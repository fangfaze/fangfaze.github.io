---
layout: post
title:  "java知识图谱"
date:   2018-05-17 00:00:00
categories: java
tags: 图谱 目录
---

* content
{:toc}

知识技能的积累,离不开一个深邃复杂的知识图谱的建立.

选择服务器方向java也是如此,需要各个方面的知识技能准备,这是一个长期的过程,不要妄图短时间速成.

如果对一个体系没有一个整体的认识,很难成为专家.所以,建立关于服务器java的知识图谱是当务之急.这个图谱其实不难建立,而困难是在未来的工作学习中,不断的完成充实相应的内容.





# 认识java

- `java语言`是一门编程语言.
- `java语言`编写出的文件是`java源代码`
- `java源代码`经过编译生成`java字节码`
- `java字节码`在`java虚拟机`上运行
- `java虚拟机`是一台虚拟的计算机,依赖于所在`操作系统`的具体实现

![](http://p8t4291gd.bkt.clouddn.com/markdown-image-paste-1526632977198)


![](http://p8t4291gd.bkt.clouddn.com/markdown-image-paste-1526633004607)

在不同的操作系统中实现的不同型号的虚拟机,都是符合java虚拟机的架构设计,虽然是不同的实现,但是都可以执行java字节码.以此保证java跨平台性(一次编译到处运行)
> 对于IOS系统来说,并非不能运行java程序,而是因为其虚拟机被开发出来之后不能被发行,所以IOS设备才不具备运行java程序的能力.

# java内外
java有多个Edition,分别为`JavaSE`(1.8集成了`JavaFX`),`JavaEE`,`JavaME`,`Java Card`,`Java for Android`.不同的平台有不同的应用前景和方向.
而服务器方向,主要是JavaEE体系,但需要JavaSE的知识结构作为基础.

体系|方向
---|---
JavaSE|开发和部署桌面、服务器以及嵌入设备和实时环境中的Java应用程序(同时也是基础)
JavaFX|GUI组件,用以开发RIA客户端
JavaEE|开发和部署企业级应用,主要指服务器研发,让服务器运行可复用,安全的Servlet等web技术等.
JavaME|开发和部署嵌入式应用,提供优化的运行环境,使嵌入式设备运行Java Applet
Java Card|智慧卡或相近的装置上，以具有安全防护性的方式来执行小型的Java Applet
Java for Android|为android系统开发应用

`java web`与`JavaEE`不是一个层次上的概念.前者泛指使用java技术开发网页,其中的java技术很大程度上就是后者.java web还包含了html等范畴的东西.


> `java`与`javascript`(`ECMAScript`)是不同的两种语言,两者没有关系.


# 知识架构

![](http://p8t4291gd.bkt.clouddn.com/markdown-image-paste-1526612010561)


