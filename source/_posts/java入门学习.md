---
title: java入门学习
date: 2022-01-14 10:30:49
tags:
  - java
abbrink: 2a
---
# string和int之间是转换
int类型转string最简单的办法就是在int后面加个空字符，或者通过方法转换
```JAVA
int i = 1；

String.valueOf(i);

Integer.toString(i);

i + '';//最简单
```
string转int只能通过方法实现。
```JAVA
String a = "123"
int b = Integer.parseInt(a);
```
# 面向对象
public 公共的
private 私有的
protected 只有子类可以访问
final 固定的，一旦初始化，不能被修改
extend 继承，只能继承一个
abstract 抽象类，定义规范，不能实例化，由子类实现具体业务逻辑
interface 接口,比抽象类更抽象，不能定义实例字段，可以定义静态固定字段（public static final）修饰符可以省略，可以被继承
implements 实现接口的关键字，可以实现多个接口
default 使用后，实现接口，不强制覆写该方法
static 静态的，可以不实例化，直接使用