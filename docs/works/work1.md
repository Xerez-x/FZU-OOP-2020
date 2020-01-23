# 第一次作业

1. 安装C++开发环境(见附录)。
2. 完成问答题、实践题及编程题
3. 发布博客

------------
## 问答题

回答以下问题：
1. 如果你不了解C++请回答以下问题：你认为C语言有什么缺陷（你觉得哪里用的不顺手）。
如果你已经了解C++请回答以下问题：你觉得C++和C语言比有什么优点。

2. 查阅相关资料，简述一下C语言/C++的编译过程。

-----------

## 实践题

自己动手，完成以下任务：

1. 查看自己的C++编译器版本。

2. 使用**命令行**编译一份C语言/C++代码。

----------

## 编程题

请使用C语言或者C++完成以下题目;

中国文化博大精深，从仓颉造字开始，汉字一直流传到了今天。我们在感叹汉字的源远流长时，也不禁感慨，为什么没有一门使用汉字编程的语言？
汉字真的不能编程吗？最近[文言文编程](https://github.com/LingDong-/wenyan-lang)火了一把，`吾有一數。曰三。名之曰「甲」。`这朴实无华的变量定义无疑不是几千年来中华文化的发展中一朵奇葩。
今天小王同学想，文言文能编程那白话文呢？他找到了你，让你帮帮他。

**编程要求**
编写一个程序，输入满足以下语法要求的一段文字，输出运行后的结果。
变量定义：整数 钱包 等于 零 
运算（加法）：钱包 增加 四 
运算（减法）：钱包 减少 四 
输出：看看 钱包 

**样例**
输入：
> 整数 钱包 等于 零 
> 钱包 增加 四 
> 钱包 减少 三
> 看看 钱包 

输出：

> 一

注意：
1. 输入输出用例均为GBK编码，推荐使用vscode把文本切换为GBK编码。
2. 数字只会出现以下 零一二三四五六七八九十 。

编程题要求：
0. 读题，提取出题目的要求。
1. 分解需求，把需求分解为几个你觉得不太相关的模块。
2. 思考每个模块怎么写，可以从简单的模块开始写。
3. 对于不会的问题进行查阅资料。
4. 对于每一个模块设计测试用例。
5. 详细记录下以上每一步，并写在博客中。
6. 不要求完全做出来，但要求记录详细。
7. 建议博客长度不少于1000字（不包含代码）。

-----------
## 博客作业

在完成了以上作业后，写一篇博客体现你完成作业的过程和内容，推荐包括以下内容：
- 问答题的答案，和思考过程。
- 实践题的截图（禁止拍屏），和遇到的问题。
- 编程题的主要实现过程、思考过程和遇到的问题。
- 你查阅的资料的网址。

-----------------
## 附录

C++开发环境由编译器，和编辑器组成，简而言之，是一个用来编译代码的软件，和一个用来写代码的软件。

编译器推荐使用msvc,gcc或clang，可以根据你的系统来自行选择。其中msvc不能单独安装，需和vs一起安装。

编辑器推荐Visual Studio 2019，vscode,或者clion。其中前两个有提供免费的版本，clion针对学生有提供免费许可。

针对window用户：

如果你是新手小白，我们建议你安装Visual Studio 2019和msvc。这里有一个简单的教程：https://blog.csdn.net/qq_43058685/article/details/96837923

如果你比较喜欢折腾，你可以使用gcc+vscode/clion，因为vs比较难卸载干净。这里有一个简单的教程：https://blog.csdn.net/bat67/article/details/76095813

针对其他操作系统的用户,我们默认你有自己搞定的能力。

附录2：

如果你遇到了无法找到指令的问题，请检查你的PATH，Path的具体内容自行搜索。