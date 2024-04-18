---
title: python学习笔记
date: 2024-04-18 20:10:20
tags: Python, 学习笔记
---
# Python学习笔记

## Python基础知识

Python是一种高级编程语言，具有简洁易读的语法和强大的功能库，适用于各种应用场景。以下是Python的一些基础知识：

### 数据类型

Python中的数据类型包括整型、浮点型、字符串、列表、元组、字典等。Python是一种动态类型语言，变量的数据类型可以根据赋值自动确定。

```python
# 示例代码：定义一个列表并遍历输出
fruits = ['apple', 'banana', 'cherry']
for fruit in fruits:
    print(fruit)
控制流程
Python提供了条件语句（if-elif-else）、循环语句（for、while）和异常处理等控制流程的语法结构，使程序逻辑更清晰和灵活。

# 示例代码：使用if-elif-else语句判断变量值
num = 10
if num > 0:
    print("num是正数")
elif num < 0:
    print("num是负数")
else:
    print("num是零")
函数和模块
Python支持函数和模块的封装和重用，通过定义函数和导入模块可以实现代码的模块化和复用。

# 示例代码：定义一个简单的函数并调用
def greet(name):
    print("Hello, " + name + "!")
    
greet("Alice")
以上是我对Python学习的一些笔记总结，希望这些示例代码能帮助你更好地理解和学习Python编程。持续学习，不断进步！