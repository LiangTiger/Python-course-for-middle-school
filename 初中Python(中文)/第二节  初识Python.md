## 第二节  初识Python

### 项目名称：人机对话

#### 教学目标：

1. 了解Python编程的基础知识和常用函数
2. 熟悉Python中的输入输出函数
3. 掌握Python环境的配置方法

#### 教学重点：

1. 常见数据类型（整数、浮点数、字符串）
2. 输入输出函数（print()和input()函数）

#### 教学难点：

1. 数据类型的概念和区分
2. 输入输出函数的参数和使用方法

#### 教学过程：

#### 一、引入

##### 1.什么是编程语言？

​		编程语言是一种人与计算机进行交互的语言，它可以使人们能够用计算机完成特定的任务。如果没有编程语言，那么计算机就只是一堆废铁。我们可以把编程语言看做是人与计算机之间的桥梁，它可以使我们能够用计算机去实现我们的想法和梦想。

​		据说全世界存在过的程序设计语言超过2500种，相当于人类语言种类的一半，但是多数程序设计语言使用比较少，有些甚至被彻底遗忘。程序设计语言的发展历经了从低级到高级的过程，其发展的核心思想就是“让人更容易编程”。



<img src="https://www.jeesell.com//upload/default/20200331/179e8bc0e3981666614f85c9ff890c3d.png" alt="img" style="zoom:33%;" />

##### 2.了解Python



<img src="https://liangtingjia.oss-cn-beijing.aliyuncs.com/20230213095331.png" alt="image-20230213095331321" style="zoom:33%;" />

​		Python是一种简单、易学、功能强大的编程语言。它由荷兰人Guido van Rossum在上世纪90年代初开发，当时他是荷兰阿姆斯特丹大学的一名计算机科学教授。据说，Guido在开发Python的时候，他的灵感来自于他喜欢的一部电视剧，名字叫做《Monty Python的飞行马戏团》。因此，他把这种新的编程语言叫做Python，以纪念这部电视剧。

##### 3.Python长什么样子？

```python
if age<12:
	print("你可以购买儿童票")
else:
    print("你需要购买全价票")
```

与c++做对比：

<img src="https://liangtingjia.oss-cn-beijing.aliyuncs.com/20230213100251.png" alt="image-20230213100251167" style="zoom: 50%;" />

语言简洁，更容易理解，阅读起来非常的舒服。

##### 4.Python可以做什么？

​		Python被广泛应用于Web开发、数据分析、人工智能、机器学习等领域。它的语法简洁明了，易于理解和学习，适合初学者学习编程。同时，Python也具有很强的可移植性，可以在不同的操作系统上运行，包括Windows、MacOS和Linux等。

<img src="https://liangtingjia.oss-cn-beijing.aliyuncs.com/20230213100344.png" alt="image-20230213100343988" style="zoom:33%;" /><img src="https://liangtingjia.oss-cn-beijing.aliyuncs.com/20230213100408.png" alt="image-20230213100408403" style="zoom:33%;" /><img src="https://liangtingjia.oss-cn-beijing.aliyuncs.com/20230213100457.png" alt="image-20230213100457610" style="zoom:33%;" />



<img src="https://liangtingjia.oss-cn-beijing.aliyuncs.com/20230213100514.png" alt="image-20230213100514142" style="zoom:33%;" /><img src="https://liangtingjia.oss-cn-beijing.aliyuncs.com/20230213100529.png" alt="image-20230213100529812" style="zoom:33%;" /><img src="https://liangtingjia.oss-cn-beijing.aliyuncs.com/20230213100553.png" alt="image-20230213100553417" style="zoom:33%;" />

#### 二、理论讲解

#### 1.Python环境搭建：

Python3 最新源码，二进制文档，新闻资讯等可以在 Python 的官网查看到：

Python 官网：https://www.python.org/

你可以在以下链接中下载 Python 的文档，你可以下载 HTML、PDF 和 PostScript 等格式的文档。

Python文档下载地址：https://www.python.org/doc/

##### 2.1 Window 平台安装 Python:

以下为在 Window 平台上安装 Python 的简单步骤。

打开 WEB 浏览器访问 https://www.python.org，鼠标点击Downloads，即可下载最新版的Python。x86 表示是 32 位机子的，x86-64 表示 64 位机子的。

<img src="https://liangtingjia.oss-cn-beijing.aliyuncs.com/20230213100635.png" alt="image-20230213100635350" style="zoom:33%;" />

记得勾选 **Add Python 3.6 to PATH**。

<img src="https://www.runoob.com/wp-content/uploads/2018/07/20180226150011548.png" alt="img" style="zoom: 33%;" />

按 **Win+R** 键，输入 cmd 调出命令提示符，输入 python:

<img src="https://www.runoob.com/wp-content/uploads/2018/07/20170707155742110.png" alt="img" style="zoom: 33%;" />

也可以在开始菜单中搜索 **IDLE**：

<img src="https://www.runoob.com/wp-content/uploads/2018/07/460F6DFB-3BBF-4683-BEA0-23BE8DF021B0.jpg" alt="img" style="zoom: 33%;" />



##### 3.编辑器介绍：

##### 2.4 Window 平台安装 Wing101:

<img src="https://liangtingjia.oss-cn-beijing.aliyuncs.com/20230213101004.png" alt="image-20230213101004394" style="zoom:33%;" />

下载并安装后，从开始菜单中找到Wing101运行。

<img src="https://liangtingjia.oss-cn-beijing.aliyuncs.com/20230213101039.png" alt="image-20230213101039754" style="zoom:33%;" />



##### 4.数据类型

介绍Python编程语言中常见的三种数据类型（整数、浮点数、字符串）；

- 整数：表示没有小数部分的数字，例如 123；
- 浮点数：表示有小数部分的数字，例如 3.14；
- 字符串：表示一串字符，用单引号或双引号括起来，例如 'hello world'。

##### 5.输入输出函数

详细讲解Python中的输入输出函数，包括print()和input()函数的参数和使用方法。

- print()函数：用于输出信息到屏幕上，可以输出字符串和变量等；
- input()函数：用于从键盘上获取用户输入的信息，返回的是一个字符串。

运行wing101：

输出函数：

```python
print('Hello world')
```

输入函数：

```python
a=input('你的名字：')
print(a)
print('我是'+a)
```

##### 三、实践操作

- 提供练习题和代码示例，让学生亲自操作并测试代码；

  示例1：输出信息到屏幕上，例如 print('hello world')；

  示例2：获取用户输入的信息，例如 name = input('请输入你的名字：')；

  示例3：计算两个整数的和，例如 num1 = 10，num2 = 20，print(num1 + num2)；

- 引导学生思考并尝试解决实际问题，例如：

  1. 编写一个程序，将你的名字和年龄输出到屏幕上。
  2. 编写一个程序，将两个数相加并输出结果。
  3. 编写一个程序，计算一个圆的面积并输出结果。

##### 四、拓展练习

账号登录：

```c++
a=input("请输入账号：")
b=input("请输入密码：")
print(a+"成功登录！")
```

计算器：

```python
print("欢迎使用计算器程序！！")
a=int(input("请你输入第一个数："))
b=int(input("请你输入第二个数："))
print("a+b=",a+b)
print("a-b=",a-b)
print("a*b=",a*b)
print("a/b=",a/b)
```

输出自己最喜欢的一首诗

##### 五、总结

- 确认学生的学习收获，鼓励学生继续探索Python编程的世界；
- 引导学生思考如何应用Python编程解决现实问题。

#### 教学反思：





