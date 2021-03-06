在开始聊Shell编程之前，我们先来看看计算机编程语言的都有哪些类型。

计算机语言可以分为两大类：
1. 低级语言
2. 高级语言

低级语言包括：**机器语言**和**汇编语言**。

高级语言包括：**静态语言**和**动态语言**。

这里就不对机器语言和汇编语言做介绍了，今天的主角是高级语言下的动态语言。

### 动态语言
**动态语言又叫做脚本语言。**

它和传统的静态语言的区别就在于:
```
前者的运行过程为：编写->解释->执行
而后者的运行过程为：编写->编译->链接->执行
```
脚本语言的优势就在于 只要有一个可以写代码的编辑器和能解释执行的脚本解释器就行了。

这样一想，也就明白了为什么搭建`Python`的开发环境远比`C#`要快，因为它只要安装一个解释器就好了。

> 动态语言与静态语言存在的争议之一：

在静态语言中，写代码时必须知道每个变量的类型; 而在动态语言中，随便什么时候，你都可以把变量设为任意类型的值。

### Shell编程
之前在学习`Shell`脚本时，产生过这样一个问题：
**为什么还能用`PHP`写`Shell`脚本？**

当时就很不理解。这里就反应了两个问题：
1. 对`PHP`的理解不深
2. 对`Shell`脚本的理解不深

**理论上讲，只要一门语言提供了解释器，这门语言就可以胜任脚本编程。**

所以用 `PHP` 可以写 `Shell` 脚本，就没有什么好奇怪的了。
你可能会问：这句话里面的 `Shell`怎么理解？

还记得吗，`Shell`的概念是什么？

> `Shell` 脚本就是将一堆的 `Shell` 命令以及指定执行 `Shell` ，通过放在一个文件中来执行。

### 脚本语言的分类
脚本语言又可以分为以下两大类：
1. `Shell`脚本
2. 通用动态语言

##### 常见的Shell脚本：
* sh
* bash
* csh
* ksh
* tcsh
* zsh
* AppleScript 

##### 常见的脚本语言
* JavaScript
* Perl
* PHP
* Python
* Ruby
* VBScript
