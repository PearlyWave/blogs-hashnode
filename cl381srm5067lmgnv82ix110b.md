---
title: "数据分析入门笔记 1"
datePublished: Mon May 16 2022 01:29:04 GMT+0000 (Coordinated Universal Time)
cuid: cl381srm5067lmgnv82ix110b
slug: 1
cover: https://cdn.hashnode.com/res/hashnode/image/unsplash/xG8IQMqMITM/upload/v1652664488185/swL56Np3S.jpeg
tags: data-science

---

在这里简单地做些记录来回顾一下学到的东西。我的视角会有四个：普通人、独立开发者、数据分析师和企业。新手入门，请各位前辈不吝赐教。


我想通过回答问题的方式来回顾。

1. 什么是数据分析·数据分析的定义
2. 为什么要数据分析·数据分析的作用
3. 如何进行数据分析·步骤是什么
4. 迷思：初创需要数据分析吗


# 1. 什么是数据分析
数据分析，从字面意思上看就是对数据进行分析。这项活动的主体是人。对象是数据。交互方式是分析。

人有很多种，可能是分析自己开销状况的普通人，又或是看不同作品被观看次数的内容生产者。
在企业中的独立数据分析部门或者分散在各部门的数据分析人员就是通常我们所说的**数据分析师**。

**数据**是事实的集合,是对现实中产生的信息的有选择的记录。比如说过去一个月的支出和收入记录、每个视频的点赞数或者是企业生产运营中收集到的数据。

![image.png](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/e298f2a9829d4f2db1a26d9434bae7c2~tplv-k3u1fbpfcp-watermark.image?)

先看看广义的“分析”，它在我们的日常生活中也很常见。[维基百科](https://en.wikipedia.org/wiki/Analysis)中对“分析”一词的定义是：分析是这样一个过程，它将一个复杂的主题拆解成更小的部分来更加理解这个主题。你在读的这篇文章就是我对数据分析的分析。我试图从几个维度（更小的部分）来理解数据分析。分析有定量、定性等类型。姑且认为数据分析是一种定量的分析方式。作为分析大家庭的一员，我便期望它能带给我对某些主题的更深的理解。

## 数据分析的定义
Google 数据分析课程[^1]中对数据分析的定义如下：

| 名称 | 含义 |
| --- | --- |
|Data analysis|The collection, transformation, and organization of data in order to draw conclusions, make predictions, and drive informed decision-making |

翻译一下就是：

通过对数据的收集、转换和组织来得出结论、做出预测并推动知情决策。

# 2. 数据分析有什么用
人们为什么要做数据分析呢，做这样一件事有什么好处？

依旧采用第一节的例子。

例子1：普通人通过对收入支出的分析来了解他的经济情况，他是否要少花点钱，这个月能攒多少钱。

例子2：视频制作者通过对作品的分析来了解观众的偏好。这样他便知道哪些主题的内容可以多做一点。

例子3：企业通过对消费者的购买数量的分析来预测未来的销售量，可以帮助决策者决定下一阶段的生产数量和供应链配置。

（那么是否有定量的方法来指出到底有多少收益呢？）

下面这句话表明了数据和使用数据的能力（两者缺一不可）的重要性。

> 从数据中获取有用知识的能力和数据本身，都应被视作关键的战略性资产。——《商战数据挖掘》

# 3. 如何进行数据分析

数据分析的简要步骤如下[^1]<sup>, </sup>[^2]：

![image.png](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/a56b7ba14e1f45e4877edf93223e459d~tplv-k3u1fbpfcp-watermark.image?)

具体的细节之后的笔记再补充。

下面谈谈数据分析的实战须知：

- 数据分析要与业务结合，数据分析人员要与相关领域的专家合作。《数据分析思维》[^2]中的第二部分实战篇（4 至15 章）分析了电商、金融、零售等 12 个不同的行业应用，可以参考。
- 不同的业务需要不同分析方式（的组合）。单个的具体的分析方法请看 5.3 节方法一览。


# 4. 迷思：数据分析的时机
Q：数据分析是大企业做的事情，初创企业不需要做这个，应该把精力放到别的事上

A：《精益数据分析》[^3]这本书讲了如何利用数据更快、更好地创业。作者认为：

- 人常常处于妄想之中，而创业者症状最严重
- 直觉重要但需要验证
- “精益数据分析”保证了数据的收集与分析。这种思维提出正确的问题，并重点关注那项可达成期望结果的**关键指标**
- 精益数据分析与精益创业这两个概念从根本上改变了人们对创业公司创立和发展的看法。这不仅是一种方法，还是一种**思维模式**。


# 5. 附录
## 5.1 术语表

上文中出现的：

| 中文 | 英文 |
| --- | --- |
|数据分析|Data Analysis|
| 数据分析师 | Data Analyst
|分析|Analysis|

本文中未使用但学到的（摘自 Google 课程）：

| 英文 |解释|
| --- |---|
|Data-driven decision-making|Using facts to guide business strategy|
| Data ecosystem|The various elements that interact with one another in order to produce, manage, store, organize, analyze, and share data|
|Data science|A field of study that uses raw data to create new ways of modeling and understanding the unknown |

## 5.2 指标的定义与常用指标

《数据分析思维》[^2]中介绍的常用指标如下图。

![image.png](https://p1-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/9ac0a9da78034e2abb23849da3162f19~tplv-k3u1fbpfcp-watermark.image?)

## 5.3 数据分析的方法一览

《数据分析思维》[^2]中第二章分析方法讲了 11 种分析方法，如下图。

![image.png](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/a859ddcaaa124926bdf8a65e818cdbd1~tplv-k3u1fbpfcp-watermark.image?)


[^1]:https://www.coursera.org/learn/foundations-data

[^2]:猴子·数据分析学院著.数据分析思维.清华大学出版社.2020

[^3]:[加] 阿里斯泰尔·克罗尔,[加] 本杰明·尤科维奇著.精益数据分析.人民邮电出版社·图灵出品.2015