---
layout: post
title:  "多版本jdk并存"
date:   2018-06-02 00:00:00
categories: java
tags: jdk 搭环境 工具
---

* content
{:toc}


# MAC
## 安装多版本jdk

1.6版本以前,在苹果处下载安装:
> https://support.apple.com/kb/DL1572?locale=zh_CN

1.7以后,在oracle处安装:
> http://www.oracle.com/technetwork/java/javase/overview/index.html

查看已安装版本命令:`/usr/libexec/java_home -V`





## jenv工具

- 安装jevn工具:`curl -s get.jenv.io | bash`
- 配置jdk实际安装路径的软连接到jevn候补目录

```
ln -s /Library/Java/JavaVirtualMachines/1.6.0.jdk/Contents/Home/bin ~/.jenv/candidates/java/1.6
```
- 切换jdk:`jenv default java 1.8`或`jenv use java 1.8`


# Windows

TBD



# 参考资料
- [MAC下安装多版本JDK和切换几种方式](https://blog.csdn.net/tianxiawuzhei/article/details/48263789)
- [Mac 下的 Java 版本管理工具 jenv](https://blog.csdn.net/kmyhy/article/details/52764058)
- [Mac下查看已安装的jdk版本及其安装目录](https://blog.csdn.net/caoxiaohong1005/article/details/73611424/)
- [jenv官网](http://jenv.io)

