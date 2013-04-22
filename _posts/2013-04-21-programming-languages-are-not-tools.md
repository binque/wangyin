---
layout: default
title: 程序语言不是工具
---

在谈论到程序语言的好坏的时候，总是有人说：“程序语言只是一种工具。只要你的算法好，不管用什么语言都能写出一样好的程序。”在本科第一堂编程课上，我的教授就这么对我们说。可是现在我却发现，这是一个根本错误的说法。

我不知道这种说法确切的来源，然而昨天在浏览网页的时候，偶然发现了 C++ 的设计者 Bjarne Stroustrup 的一些类似的说法。这些说法来自于 2007 年 MIT Technology Review 对 Stroustrup 的[采访](http://www.technologyreview.com/qa/407076/bjarne-stroustrup)。

* 问：一个好的语言是什么样的？<br>
  Stroustrup：所有能帮助人们表达他们的想法的东西都会让语言更好。一个语言在一个好的工匠手里应该能胜任每天的任务。语言是否优美是次要的问题。被认为是丑陋的语言开发出来的有用的系统，比优美的语言开发出来的系统要多得多。

* 问：优雅难道不重要吗？<br>
  Stroustrup：优雅很重要，可是你如何衡量“优雅”？可以表达问题答案的最少字数？我觉得我们应该看构造出来的应用程序的优雅程度，而不是语言自身的优雅程度。就像你不能把木工的一套复杂的工具（很多是危险的工具）叫做“优雅”一样。但是我的餐桌和椅子却真的很优雅，很美。当然，如果一个语言本身也很美，那当然最好。


### 一些基本的错误

对这两个回答，我都不满意，我觉得这只是他对于 C++ 的恶劣设计的借口而已。下面我对其中几个说法进行质疑：

> 所有能帮助人们表达他们的想法的东西都会让语言更好。

作为一个程序语言，并不是好心想“帮助人”就可以说是好的。如果是这样的话，那么我就可以把所有国家的脏话都加到你的语言里面，因为它们可以帮助我们骂人。

> 被认为是丑陋的语言开发出来的有用的系统，比优美的语言开发出来的系统要多得多。

系统的数量再多也不能说明这个语言好。正好相反，众多的系统由于语言的一些设计失误，把人们的生命置于危险之中，这说明了这个语言的危害性之大。一种像炸药一样的语言，用的人越多越是危险。


### 语言不是工具，而是材料

我这篇文章想说的最关键的部分，其实是他所支持的“语言工具论”的错误。

Stroustrup 说：

> 我觉得我们应该看构造出来的应用程序的优雅程度，而不是语言自身的优雅程度。就像你不能把木工的一套复杂的工具（很多是危险的工具）叫做“优雅”一样。但是我的餐桌和椅子却很优雅，很美。

他的言下之意就是把程序语言比作木工的工具，而餐桌也椅子就是这些工具做出来的产品。比方的威力是很大的，很多人一见到“大牛”给出这么形象的比方，就盲目的接受了。如果你不仔细分析的话，这貌似一个恰当的比方，然而经过仔细推敲，这却是错误的比方。这是因为程序语言其实不是一种“工具”，而是一种“材料”。

木工不会把自己的锯子，墨线等东西放进餐桌和椅子里面，而程序员却需要把语言的代码放到应用程序里面。虽然这些程序经过了编译器的转化，但是程序本身却仍然带有语言的特征。这就像一种木材经过墨线和锯子的加工，仍然是同样的木材。一个 C++ 的程序 编译之后有可能产生内存泄漏和下标越界等低级错误，而更加安全的语言却不会出现这个问题。所以在这个比方里面，程序语言所对应的应该是木工所用的木料，钉子和粘胶等“材料”，而不是锯子和墨线等“工具”。这些材料其实随着应用程序一起，到了用户的手里。

那么对应木工工具的是什么呢？是 Emacs, vi, Eclipse，Visual Studio 等编程环境，以及各种编译器，调试器，make，界面设计工具……

现在你还觉得程序语言的优雅程度是次要的问题吗？一个复杂而不安全的语言就像劣质的木料和粘胶。它不但会让餐桌和椅子的美观程度大打折扣，而且会造成它们结构的不可靠。同时它还可能会造成木工的工作效率低下以及工伤的产生。

这也许就是为什么我的一个同事说，他看某些人的 C++ 代码的时候都会带上 OSHA（美国职业安全与健康署）颁发的护目镜。

<img src="http://www.yinwang.org/images/osha-goggle.jpg">