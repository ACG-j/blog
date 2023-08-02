---
title: Java 学习：Scanner
date: 2023-08-02 15:13:02
tags:
- Control flow
categories:
- Java
---

## Scanner 对象

* 功能：

  获取用户输入

* 基本语法

  ```java
  Scanner s = new Scanner(System.in);
  ```

* **next()**
  * 一定要读取有效字符后才可以结束输入
  * 对输入有效字符之前遇到的空白，next()方法会自动将其去掉
  * 只有输入有效字符后才将后面输入的空白作为分隔符或者结束符
  * <font color=red>next() 不能得到带有空格的字符串</font> 
* **nextLine()**
  * 以Enter为结束符，也就是说nextLine()方法返回的是输入回车之前的所有字符
  * 可以获得空白



#### 代码笔记

​	https://git.sgxi.cn/ation_ciger/java_learn/src/branch/master/src/cn/sgxi/Scanner
