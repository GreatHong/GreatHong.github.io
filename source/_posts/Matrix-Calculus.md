---
title: 矩阵求导规则总结
date: 2019-09-25 21:58:36
catagries:
    - notebook
       - Machine Learning 
tags:
    - Neural Network
    - math
mathjax: true
---

最近在看机器学习的一些基础，看到数学推导的时候发现自己还是对基础的推到过程不是很了解。这一篇总结记录一下矩阵的求导运算的基础知识供以后自己查询。
矩阵的求导（Matrix Derivative）也叫矩阵微分（Matrix Differential），在机器学习的一些基本推导中经常用到。在机器学习领域很多计算都是基于矩阵和向量来进行的，所以学习和矩阵相关的一些数学运算是很有必要的，有利于更好的理解数学基础，可以加深对于机器学习模型的认识。Here we go!

# 布局约定(Layout conventions)

## 布局(Layout)
在矩阵求导中有两种布局，分别是分母布局(denominator layout)和分子布局(numerator layout)。这两种不同的布局的求导规则是不一样的。
$$y_1$$