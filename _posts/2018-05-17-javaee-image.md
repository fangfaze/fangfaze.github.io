---
layout: post
title:  "java知识图谱"
date:   2018-05-17 00:00:00
categories: java
tags: 图谱 目录
original: true
---

* content
{:toc}

知识技能的积累,离不开一个知识图谱的建立.

选择服务器方向java也是如此,需要各个方面的知识技能准备,这是一个长期的过程,不要妄图短时间速成.

如果对一个体系没有一个整体的认识,很难成为专家.所以,建立关于服务器java的知识图谱是当务之急.这个图谱其实不难建立,而困难是在未来的工作学习中,不断的完成充实相应的内容.

随着对各个层面的理解,终于知识图谱也将变得深入复杂.任何时候,新学习的只是概念都可以和以往的知识积累形成关联,融入到新的版本的图谱当中.





# 图谱v1.0

![](http://p8t4291gd.bkt.clouddn.com/markdown-image-paste-1527052996097)

> `java`是一系列相关内容的总称.其体系包括了诸多的概念.

- JDK是java开发工具,包括了编译器和JRE.可以将`java源代码`编译成`java字节码`,语法与编译规则,根据JDK版本会有不同.
- JRE是运行时环境,包括了运行时类库和JVM.
- JVM是`java虚拟机`,可以解释执行`java字节码`.通过虚拟机`java字节码`被解释成为`机器码`.
- 操作系统执行`机器码`.


## java漫画(1)-虚拟机

![](http://p8t4291gd.bkt.clouddn.com/markdown-image-paste-1526632977198)

![](http://p8t4291gd.bkt.clouddn.com/markdown-image-paste-1526633004607)

在不同的操作系统中实现的不同型号的虚拟机,都是符合java虚拟机的架构设计,都可以执行java字节码.以此保证java跨平台性(一次编译到处运行)
> 对于IOS系统来说,并非不能运行java程序,而是因为其虚拟机被开发出来之后因为政策原因没有发行,所以IOS设备才不具备运行java程序的能力.



# java版本

> `java`与`javascript`(`ECMAScript`)是不同的两种语言,两者没有直接关系.

java体系有多个版本(Edition),分别为`JavaSE`(1.8集成了`JavaFX`),`JavaME`,`JavaEE`,`Java Card`,`Java for Android`,不同的平台有不同的应用前景和方向.
主要是指javaSE
而服务器方向,遵循JavaEE体系规则,但需要JavaSE的知识结构作为基础(其中也与Spring框架有关).

java语言经历过多个版本(Version),每个版本都会引入一些新的特性,并且向前兼容.目前仍支持的最新的版本是`javaSE8`.

> `javaSE9`已经发布,虽然引入了新的特性,但更多的是一个过渡版本.10年9月即将发行的`javaSE10`.


体系|方向
---|---
JavaSE|开发和部署桌面、服务器以及嵌入设备和实时环境中的Java应用程序(同时也是基础)
JavaFX|GUI组件,用以开发RIA客户端
JavaEE|开发和部署企业级应用,主要指服务器研发,让服务器运行可复用,安全的Servlet等web技术等.
JavaME|开发和部署嵌入式应用,提供优化的运行环境,使嵌入式设备运行Java Applet
Java Card|智慧卡或相近的装置上，以具有安全防护性的方式来执行小型的Java Applet
Java for Android|为android系统开发应用

`java web`与`JavaEE`不是一个层次上的概念.前者泛指使用java技术开发网页,其中的java技术很大程度上就是后者.java web还包含了html等范畴的东西.




# 知识架构

![](http://p8t4291gd.bkt.clouddn.com/markdown-image-paste-1526612010561)


