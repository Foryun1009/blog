---
title: 开坑：用Unity复刻仙剑一
date: 2021-06-07 01:27:45
updated: 2021-06-07 01:27:45
categories: 记录
tags: 开坑 | Unity | 复刻 | 仙剑
---

2021-6-10

- 发现将C语言版的mkf解压逻辑翻译成C#对我来说，有点困难，指针和二进制的操作不熟练，在C#里面没有现成的工具，需要自己造轮子，写了几天，虽然已经造了几个轮子，但是进度比我想象中慢。想到后面花大量时间翻译C代码，可能对我来说，意义不大，而且后面可能因为侵权问题，也不能发布，所以觉得按照自己的设定，做个3D版的仙剑一。所有的美术资源全部在网上找。主要表达游戏流程。等流程跑完，可能会加入一些自己YY的功能。



2021-6-7

- 写了两个小时，处理了一下资源，为了简化开发流程，把音频资源从.mid转成了.mp3，其他资源后缀改成.bytes，统一通过Resources进行加载。
- 定了一下资源加载流程，游戏启动，将所有资源全部缓存起来，保存在字典里，以便后期使用。这里暂时不考虑性能问题。



2021-6-7 开坑前言

- 今天无意间听到了蝶恋，回想起自己玩的第一款游戏，仙剑奇侠传一，感慨万分。刚好最近也比较迷茫，从事游戏行业这么多年，做的游戏都不赚钱，不禁让我反思，自己的做游戏的初心是什么。
- 伴随着自己成长的，都是RPG游戏，仙剑，天之痕，古剑奇谭，侠客风云传，金庸群侠传。这些经典的国产游戏，深深的感动着我，让我怀揣着梦想，想通过游戏，讲述一个自己的侠客故事。时隔多年，虽然，我走上了游戏开发的道路，但却一直做着所谓的商业游戏，快餐游戏，连我自己都无法打动。
- 这么多年的开发经验，目前已经解决了温饱问题，是时候，尝试实现自己的梦想了，人没有梦想，跟咸鱼又有什么区别呢？所以，第一步，当前致敬经典，复刻仙剑。向前辈学习。
- 曾今也开过无数坑，不知道这个坑能不能填满。但愿自己能坚持做完吧。
- 开发进度，我会定期在博客和B站上更新，有兴趣的同学，可以多多关注，多多鼓励。
- 开源项目地址：[UnityPAL: 尝试用Unity复刻仙剑一 (gitee.com)](https://gitee.com/foryun/UnityPAL)

