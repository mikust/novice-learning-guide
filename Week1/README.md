# Week 1

## C语言

- 完成K&R中第一、二、三章的所有习题
  - 对于难度较大的习题，可以跳过，但要标记出来。
  - 汇总答题记录，编撰文档，叙述做题过程中遇到的困难。
  - 中英文PDF以及标准答案均已放置于"resources/C"路径下。
  - 遇到困难多问百度，善用搜索引擎，但不允许直接百度答案。实在没头绪的，再参考标准答案。

## 汇编语言

- 阅读王爽老师的《汇编语言》前两章，完成课后习题。PDF书及标准答案已放置于"resources/Assembly"目录。同目录下还有热心网友的学习笔记可供参考。

- 要求写前两章的学习笔记，课后题也要做。

- 如果直接看书觉着有困难，可以适当看鱼哥的视频解惑，他讲得节奏很慢，确实是零基础。链接<https://www.bilibili.com/video/av28132657?from=search&seid=3662599447355533171>


## 数据结构与算法

- 阅读严蔚敏的《数据结构(C语言版)》的第二章——线性表。理解线性表的概念，搞清楚顺序存储和链式存储的区别与优劣性。书放在"resources/DataStructures&Algorithms"目录下。要求撰写学习笔记。

  > 其实严的这本书写得非常一般，但却非常适合不想深入研究数据结构与算法，仅仅只是普及向的学生来阅读。第一章不需要阅读，你在学习数据结构与算法时，遇到的一切数学推导、时间空间复杂度的计算都直接跳过，不要深入进去。这门课实际上算内功，深入的东西不是一朝一夕可以练就的，在你外家功夫练到一定程度之后有需要时再进修。

- **使用C语言独立完成顺序存储和链式存储两种线性表的实现。要求独立封装功能模块，编写测试代码。**

  > 通俗的讲，可以组织成seqlist.c/seqlist.h/main.c三个文件，seqlist.c实现顺序表的接口功能函数，seqlist.h对外声明接口，main.c中在main函数中编写测试代码。

  - <https://github.com/kangjianwei/Data-Structure>汇总了教材的习题与源码，可供参考。
  - <https://www.cnblogs.com/kangjianwei101/p/5221816.html>是上一repo的使用说明。

## Windows SDK

- 阅读《Windows程序设计》第5版的前两章。重点理解Windows环境以及字符集、编码的概念。教材放在"resources/Windows/SDK"目录下。

- git clone该repo：<https://github.com/liuxuanhai/WindowsProgrammingNotes>，作为日后学习的参考。用VS调试前两章的代码，自己随便折腾折腾，看看效果。

  > 对于Windows SDK的学习，不要求从0到1自己独立写出完整的代码，这也没什么意义。我们往往直接在模板程序上做改动，这和学习编程语言是不一样的，学习SDK本质上就是学习接口函数的使用套路。

