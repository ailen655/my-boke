---
title: Java学习笔记
date: 2022-09-18 20:07:37
tags: Java, 学习笔记
---
# Java学习笔记

## Java基础知识

Java是一种面向对象的编程语言，具有跨平台特性，广泛应用于软件开发领域。以下是Java的一些基础知识：

### 数据类型

Java中的数据类型包括基本数据类型和引用数据类型。常见的基本数据类型有int、double、boolean等，引用数据类型包括类、接口、数组等。

```java
// 示例代码：定义一个整型变量并赋值
int num = 10;
System.out.println("整型变量num的值为：" + num);
控制流程
Java提供了条件语句（if-else）、循环语句（for、while、do-while）和跳转语句（break、continue）等控制流程的语法结构。

// 示例代码：使用if-else语句判断变量值
if (num > 0) {
    System.out.println("num是正数");
} else if (num < 0) {
    System.out.println("num是负数");
} else {
    System.out.println("num是零");
}
面向对象编程
Java是一种面向对象的编程语言，具有封装、继承和多态等特性。面向对象编程的核心概念包括类、对象、方法、继承、接口等。

类和对象
在Java中，类是对象的模板，对象是类的实例。通过定义类和创建对象，可以实现数据的封装和行为的抽象。

// 示例代码：定义一个简单的类和对象
class Person {
    String name;
    int age;

    public void displayInfo() {
        System.out.println("姓名：" + name + "，年龄：" + age);
    }
}

Person person1 = new Person();
person1.name = "Alice";
person1.age = 25;
person1.displayInfo();
以上是我对Java学习的一些笔记总结，希望这些示例代码能帮助你更好地理解和学习Java编程。持续学习，不断进步！