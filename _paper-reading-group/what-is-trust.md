---
title: "Trust"
collection: paper-reading-group
permalink: /paper-reading-group/what-is-trust
---

## What is "Trust"

Building Trust in Artiﬁcial Intelligence, Machine Learning, and Robotics
这篇文章虽然只是发表在相对一般的刊物，但是获得了380多次引用。不同于软工，它提供了一个偏重于信息管理学的视角去讲可信/值得信任的要素，对探讨“可信”的涵义可能会有一些启发。
有意思的地方两点：

1. 可信是“动态”的，是不断变化的。一个实体可能刚开始时可信的，后来变得不可信，或者刚开始不可信，之后慢慢取得信任。于是它提出了一个“初始可信”（initial trust）和 “持续可信”（continuous trust）的概念，提出“可信”是需要维护的。启发就是我们在判断或者度量某个实体可信性的时候，不仅仅要考虑初始可信，是否也要考虑持续可信性？比如是否需要多次反复的去验证该实体的可信性，同时加入失信机制（类比信用卡的机制）。“从不相信，反复核实”---这个也正好符合“零信任模型”的思路。

2. 可以考虑将可信和机器学习结合起来，针对机器学习训练/推理过程进行可信性的度量/测试/标准方面的工作
