---
layout: post
title: "加入 LaTeX 公式支持"
date: 2015-04-28
comments: true
categories: update
tag: 
  - LaTeX 
  - kramdown
---
参考了这两个博客：
[Jekyll中使用MathJax][1]

[Octopress中使用Latex写数学公式][2]

在 Mathjax 的[官方文档][3]里也有对行间公式表示方法的说明，上面的第一个博客使用了 Mathjax 不太推荐的方案，即启用了`$...$`单美元符号，我可能考虑在以后去掉这一做法。

示例：

$$ 
\begin{aligned} \dot{x} &= \sigma(y-x) \\ 
\dot{y} &= \rho x - y - xz \\ 
\dot{z} &= -\beta z + xy \end{aligned} 
$$

$E=mc^2$ is a inline formula

[1]: http://www.pkuwwt.tk/linux/2013-12-03-jekyll-using-mathjax/ "Jekyll中使用MathJax"
[2]: http://dreamrunner.org/blog/2014/03/09/octopresszhong-shi-yong-latexxie-shu-xue-gong-shi/ "Octopress中使用Latex写数学公式"
[3]: http://docs.mathjax.org/en/latest/start.html
