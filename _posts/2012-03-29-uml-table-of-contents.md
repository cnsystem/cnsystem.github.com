---
title: UML学习笔记
author: cnsystem
layout: post
permalink: /uml-table-of-contents.html
categories:
  - 小技巧
tags:
  - UML
  - 面向对象
---
UML不是一种方法学，而是一种描述语言。作为面一种描述语言，在OOA、OOD、OOP中，有着非常重要的作用。在项目初期的需求分析、功能分析中，在设计阶段的模块设计、类设计及对象状态，到了编程的时候可以很快的从UML转换为源代码。

对小项目，UML的优势不明显，无须过多的需求分析，所有的一想就出来了。但是面对复杂的业务时，这种描述语言的存在（此处仅针对UML），使得思路清晰。

UML图分为三类：

  1. 静态图：包括用例图、对象图、类图、组件图、部署图
  2. 动态图：协作图、序列图、活动图、状态图
  3. 物理图：文件、数据库等

&nbsp;

1、用例图

帮助开发团队以一种可视化的方式来理解系统的功能需求。

什么是用例？用例是指系统的功能，是系统某个功能的执行动作的集合。从用户的观点告诉系统要做的一些特定的事情。

符号：**椭圆**（用例）、**人形符号**（用户或角色)

2、类图和对象图

类间关系：

  * 继承
  * 关联
  * 依赖
  * 聚合
  * 组合

3、序列图

序列图用来显示具体用例图的详细流程，显示流程中不同对象的交互关系，以及相互的各种调用。

序列图有两个维度：

  * 水平：对象实例之间的交互
  * 垂直：以发生时间顺序显示消息/调用的序列

对象之间的交互：

  * 调用（call）
  * 返回（return）
  * 发送（send）
  * 创建（create）
  * 销毁（destroy）

4、状态图

状态图表示某个类所处的不同状态和该类的状态转换信息。

符号：

  * 初始起点 ========>>实心圆
  * 状态之间的转换====>>带箭头的线段
  * 状态 ===========>>圆角矩形
  * 判断点==========>>空心圆
  * 终止点==========>>内部包含实心圆的圆

PS：每个类都有状态，但不一定有状态图

5、活动图

活动图是状态图的一个变体，用来描述执行算法的工作流程中涉及的活动，描述一组顺序或并发的活动。活动状态代表一个活动： 一个工作流步骤或一个操作的执行。

泳道（<a title="swimlane-维基百科" href="http://en.wikipedia.org/wiki/Swim_lane" target="_blank">swimlane</a>）表示实际执行活动的对象。

6、组件图

组件图担任物理视图，它的用途是显示系统中的软件与其他软件的依赖关系。

7、部署图

部署图表示该软件系统如何部署到硬件环境中。

&nbsp;

PS：呃，本文纯属笔记。看到最后其实发现什么都没有讲清楚，所以还是好好看书。但是不得不强调一点题外话：UML只是面向对象技术中的描述语言，真正重要的还是要对“面向对象”理解。

书目：

《面向对象设计与分析》——纯粹对面向对象讲解的书

《UML参考书》——UML图详解

《设计模式》——你懂的