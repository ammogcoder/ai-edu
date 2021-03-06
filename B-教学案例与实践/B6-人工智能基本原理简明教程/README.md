﻿# AI基本原理简明教程的目录

## 写在前面，为什么要出这个系列的教程呢？

  总的说来，我们现在有了很多非常厉害的深度学习框架，比如tensorflow，pytorch，paddlepaddle，caffe2等等等等。然而，我们用这些框架在搭建我们自己的深度学习模型的时候，到底做了一些什么样的操作呢？我们试图去阅读框架的源码来理解框架到底帮助我们做了些什么，但是……很难！很难！很难！因为深度学习是需要加速啦，分布式计算啦，所以框架做了很多很多的优化，也让像我们这样的小白难以理解这些框架的源码。所以，为了帮助大家更进一步的了解神经网络模型的具体内容，我们整理了这样一个系列的教程。

对于这份教程的内容，如果没有额外的说明，我们通常使用如下表格的命名约定

| 符号 | 含义|
|:------------:|-------------|
| X | 输入样本 |
| Y | 输入样本的标签 |
| Z | 各层运算的结果|
| A | 激活函数结果|
| 大写字母 | 矩阵或矢量，如A,W,B|
| 小写字母 | 变量，标量，如a,w,b|

## 适用范围
  
  没有各种基础想学习却无从下手哀声叹气的玩家，请按时跟踪最新博客，推导数学公式，跑通代码，并及时提出问题，以求最高疗效；

  深度学习小白，有直观的人工智能的认识，强烈的学习欲望和需求，请在博客的基础上配合代码食用，效果更佳；

  调参师，训练过模型，调过参数，想了解框架内各层运算过程，给玄学的调参之路添加一点心理保障；

  超级高手，提出您宝贵的意见，给广大初学者指出一条明路！

## 前期准备

  环境：
  
  windows（Linux也行），python（最好用3），anaconda（或者自己装numpy之类的），tensorflow（嫌麻烦地请看这里[《AI应用开发实战 - 从零开始配置环境》](https://www.cnblogs.com/ms-uap/p/9123033.html)，tools for AI（按照链接教程走的就不用管这个了）。
  
  自己：

  清醒的头脑（困了的同学请自觉泡茶），纸和笔（如果像跟着推公式的话），闹钟（防止久坐按时起来转转），厚厚的衣服（有暖气的同学请忽略）

## 目录
+ [神经网络的基本工作原理](./1-神经网络的基本工作原理.md)
+ [神经网络中反向传播与梯度下降的基本概念](./2-反向传播与梯度下降.md)
+ [损失函数](./3-损失函数.md)
+ [一层神经网络单输出能做什么](./4-一层神经网络单输出能做什么.md)
+ [一层神经网络单输出能做什么](./5-多入单出的一层神经网络.md)
+ [一层神经网络单输出能做什么](./6-多入多出的一层神经网络.md)
+ [激活函数](./7-激活函数.md)
+ [单入单出的两层神经网络](./8-单入单出的两层神经网络.md)
+ 多入多出的两层神经网络
+ 多入多出的多层神经网络
+ 模型内部
+ 徒手搭建CNN网络（上）
+ 徒手搭建CNN网络（下）
+ 徒手搭建RNN网络
+ 附录：[基本数学导数公式](./0-基本数学导数公式.md)