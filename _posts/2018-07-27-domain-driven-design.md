---
title: 领域驱动设计
categories:
 - 模型
tags:
 - 领域驱动
 - 模型
---

# 领域驱动模型

## 在领域驱动设计中，3个基本用途决定模型选择
1. 模型和设计的核心互相影响  
`模型和实现之间紧密联系使得模型变得有用，实现上可以基于正确的模型分析产品核心业务逻辑`
1. 模型是团队所有成员使用的通用语言    
`由于程序开发者和领域专家都有各自不同的专业术语，业务需求沟通起来比较困难，而模型则起到了建立通用语言的功能`
1. 模型是浓缩的知识   
`模型是团队一致认同的领域知识的组织方式和重要元素的区分方式，模型主要记录的就是我们看待领域的方式，能够促进我们高效协作`

## 遇到的几个重要问题
1. 开发人员不能够全面了解客户需求背后的实际业务需求
1. 模型只是基于业务专家的意见，知识只是朝一个方向流动，不会有任何积累
1. 项目知识零散地分散在很多人和文档中，其中还夹杂其他一些无关的信息，因此我们甚至不知道哪些是真正需要的知识，而且大部分需求通过口头传递，容易造成各种误差或遗漏等等
1. 各行业的专业术语和业务逻辑都比较复杂，对于开发人员来说理解困难，而且沟通过程中经常出现误以为理解却理解错误的情况
1. 系统经常会不断增加其他业务模块或逻辑，但由于原来没有一个模型的支撑，系统代码越来越乱，甚至需要重新重构（而且是经常）

## 有效建模的要素
1. 模型和实现绑定
1. 建立一种基于模型的语言
1. 开发一个蕴含丰富知识的模型
1. 提炼模型
1. 头脑风暴和实验

```
ps: 
1.策略一般指定义一组算法，将每一个算法封装起来，并且使它们 之间可以互换，优点是软件可以由许多可替换的部分组成，各个部分之间是弱连接的关系，这样软件就有更强的可扩展性、维护性和重用性
2.领域模型和相应的设计可用来保护和共享知识
```