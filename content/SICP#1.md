Title:接触《计算机程序的构造和解释》(SICP)
Date:2015-08-11
Tags:SICP, Lambda
> 从开始接触编程到想要去了解程序，到现在主动去追求知识，已经过了四年有余了，其实国内很多大学一开始就让同学们学习C／C++等说明性语言是不对的，在我看来，还是应该采取国外许多一流大学的做法，从Lisp这种过程性语言开始教学。

MIT出的计算机编程入门书--《[计算机程序的构造和解释](https://mitpress.mit.edu/sicp/)》（[中文版地址](http://vdisk.weibo.com/s/uIq1xR9IcEdTB)）正是如此，它采用了MIT－scheme（一种Lisp方言）来说明计算机程序的构造过程和解释器的原理。
结合《[MIT的6.037课程讲义](http://web.mit.edu/alexmv/6.037/)》，以及《[网友贡献的习题答案](http://wenku.baidu.com/link?url=t8qOUrtf-Sp9IsA6cXbKRIX_s2P5vEg9jg5F4r1eOdg8wLMMYtRSrycZNA1ieYsXkM_op_U2uycH26gILzYG3CNWka6pmTirgdOpw2OzNh7)》，我们在阅读这本书的过程中确实是一件非常愉快，令人赏心悦目的事情。

特别是看着自己可以实现以前在C/C++语言中实现的程序，如第一个完整的程序－－开平方根，自己内心是很欣慰的，因为又对程序运行的环境有了进一步的了解。

其实想要阅读这本《[计算机程序的构造和解释](https://mitpress.mit.edu/sicp/)》，也并不是想象中的那么容易，首先安装配置MIT－Scheme就是一个颇费周折的事情，尤其是在MAC上面。

很久很久以前或许我就是卡在这个上面，也或许是当时轻视对普通数字的处理程序上面，而这本书同大多数程序书一样，都是从介绍数字的处理程序开始的。而到了现在，知道读了这本书中一个观点，就是其实计算机中对数字的处理并不是那么简单，而真正让我改变这一想法的就是我亲手用scheme写了好一些处理数字的程序以后，我发现真的是这样。
	
	书中讲到了应用序和正则序，这两种序列是解释器求值的顺序，一种是逐步展开求值（规约），一种是完全展开然后再求值。
	完成了书中习题1.5和1.6之后，我就完全体会到了这两个顺序的异同。

在翻看《[6.037第一章节讲义](http://web.mit.edu/alexmv/6.037/l1.pdf)》的过程中，我看到了让我心驰神往的lambda表达式。在实验了书中代码以后，结合讲义，我明白了原来lambda表达式就是一种在Lisp语言中通用的表达形式，它可以用来定义变量，同我今天练熟的普通定义变量的方式是相通的。（其实在SICP书中第一张并未提到lambda表达式，而是直接给出了lambda 表达式的语法糖（sytantical sugar），也就是一种外包装，使用lambda表达式的语句才是最基本的表达方式）。

	阅读SICP，学习一种过程性语言（如Scheme，在这种语言中，我们可以将一个计算的过程存为一个变量， 而这个变量可以作为一个谓词，也即是一个运算符号来参与运算)，确实是对编程有很大帮助的。

我在大约一，两年以前开始了解Lisp这种语言，后来又在去年的thoughtworks培训中又隐约了解到了程序语言的发展，加上阅读了一些博客的文章，在我看来，未来的语言发展将向Lisp这类过程性语言靠拢。
