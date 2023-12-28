---
author: zYosous0000
title: "Diffusion Model"
date: 2023-12-28
slug: diffusionmodel
description: "教是最好的学"
Draft: true
---





## Background Knowledge

扩散模型的灵感来自非平衡热力学. 典型例子是一滴会在水中扩散的墨水. 从墨水滴到水中的聚状物(难以描述的复杂, 浑沌分布)到扩散到水中整体呈现的淡蓝色墨水(均匀, 简单的分布). 非平衡热力学的思想是将墨水扩散过程中的每一步的概率分布都描述出来. 

> 由物理学得知, 扩散过程每一步都是可逆的, 所以只要时间步足够小, 就可以从简单的分布再推断出最初复杂的分布.

### U-Net

U-Net是一种**Encoder-Decoder**结构的模型.

### Monte Carlo Methods

蒙特卡洛方法是指通过观测一个概率分布中的大量随机样本对分布的某些性质做出进行近似准确的求解. 该方法不是因为提出者叫做蒙特卡洛, 而是出自摩纳哥的蒙特卡洛赌场. 因为它们使用了随机性, 就像赌场中的游戏一样.

蒙特卡洛方法是一类基于概率的方法的统称, 不是特指一种方法.



## reference

[1] Ho, Jonathan, Ajay Jain, and Pieter Abbeel. "Denoising diffusion probabilistic models." *Advances in neural information processing systems* 33 (2020): 6840-6851.

[2] [蒙特卡罗方法详解 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/369099011)

[3] 笔者与ChatGPT3.5的对话

[4] [物理改变图像生成：扩散模型启发于热力学 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/599013984)
