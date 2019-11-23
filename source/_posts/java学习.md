---
title: JAVA简介
date: 2019-11-20 10:58:31
categories:
- JAVA
tags:
---

Java最早是由SUN公司（已被Oracle收购）的[詹姆斯·高斯林](https://en.wikipedia.org/wiki/James_Gosling)（高司令，人称Java之父）在上个世纪90年代初开发的一种编程语言。运行在JVM之上，所以，第一事情就是安装JDK。从[Oracle官网]( https://www.oracle.com/technetwork/java/javase/downloads/index.html )下载JavaSE:

![Java下载](https://www.liaoxuefeng.com/files/attachments/1304706360016962/l)

### 设置环境变量

安装完JDK后，需要设置一个<font color=Blue>JAVA_HOME</font>的环境变量，它指向JDK的安装目录。在Windows下，它是安装目录，类似：

C:\Program Files\Java\jdk-13

然后，把<font color=blue>JAVA_HOME</font>的<font color=blue>bin</font>目录附加到系统环境变量<font color=blue>PATH</font>上。在Windows下，它长这样：

Path=%JAVA_HOME%\bin;<<font color=blue>现有的其他路径</font>>

 把<font color=blue>JAVA_HOME</font>的<font color=blue>bin</font>目录添加到<font color=blue>PATH</font>中是为了在任意文件夹下都可以运行<font color=blue>java</font>。打开命令提示符窗口，输入命令<font color=blue>java--version</font>，如果一切正常，你会看到如下输出： 

![image-20191121191504520](C:\Users\godwu\AppData\Roaming\Typora\typora-user-images\image-20191121191504520.png)

