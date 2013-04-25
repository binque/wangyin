---
layout: default
title: 什么是“为什么”
published: false
---


1. 我在 Cornell 的时候经常遇到这样的问题，那就是一上课教授就在黑板上写长篇的“定理证明”，全体同学认认真真在下面抄笔记。有些写字速度慢的人就不得不带上小型录音机，把教授的课全都录下来，要不就是之后去借别人的笔记来抄。


2. 有一次，某 Cornell 知名教授照着讲义在黑板上板书了大半节课，写下好几版的证明，证明的是 simply typed lambda calculus （STLC）的 strong normalization 特性。刚写完就到下课时间了，他才回过头来看着我们喘了一口气，说：“Any questions？”没有人啃声，于是他说：“很好，下课！”

   之后我问他，你证明了 STLC 有这个特性，然而你却没有告诉我们它“为什么”有这个特性。他神气的看了我一眼：“你没听懂吗？”我说：“我听懂了大部分。可是你还是没有告诉我它‘为什么’有这个特性。我的意思是，你怎么才能从无到有想出这个证明。”他说：“你需要非常聪明，并且需要经过大量的努力才能想出这样的证明。”

3. 两年之后，我在 Indiana 上了另外一堂程序语言理论课。教授是我的导师 Amr Sabry。他上课从来不带讲义，也貌似也没有准备，却每次都能讲清楚问题的关键。于是有一天他也开始讲 STLC 的这个性质。他说：“我不想写下这个证明让你们抄，我只告诉你们大概怎么去想。strong normalization 的意思就是程序肯定会‘终止’。所有会终止的问题，都会有一个‘特征值’会随着程序的运行而减小。你需要做的就是找到这个随着 STLC 的运行而缩小的东西。”


4.有一次 Cornell 操作系统考试，出了这么一道题：一条河的两遍各有5只猴子要过河。可是河上只有一根绳子。如果两只猴子在绳子中间遇上了就会掉进河里。请你使用 semaphore 写出一个程序可以让这些猴子都可以安全过河。
