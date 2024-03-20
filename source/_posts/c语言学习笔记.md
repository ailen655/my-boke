---
title: c语言学习笔记
date: 2024-03-20 09:29:25
categories:
  - 学习笔记
tags:
  - C语言
---

# C语言学习笔记

## 介绍

$C$语言是一种通用的高级编程语言，广泛应用于系统软件开发和应用软件开发。下面是一些基本概念：

- C语言是一种过程化语言
- C语言是一种编译型语言
- C语言是一种强类型语言

## 第一个C程序

下面是一个简单的Hello World程序：

```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}

数据类型
C语言有各种数据类型，包括整型、浮点型、字符型等。常用的数据类型有：

int
float
double
char
控制流
C语言支持各种控制流结构，如if语句、for循环、while循环等。示例：

int x = 10;

if (x > 5) {
    printf("x大于5\n");
} else {
    printf("x不大于5\n");
}
函数
函数是C语言中的基本组成单元。示例：

int add(int a, int b) {
    return a + b;
}

int main() {
    int result = add(3, 5);
    printf("3 + 5 = %d\n", result);
    return 0;
}
这些是C语言学习笔记的基本内容，希望对你有所帮助！