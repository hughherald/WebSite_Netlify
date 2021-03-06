---
title: 脑纹识别算法挑战赛
date: "2022-05-24T00:00:00+01:00"
draft: false
share: false
commentable: false
editable: false

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""
---

这项挑战是**世界人工智能大会**(拟)的一部分。

## **介绍**

- 人脑产生的具有个体特质的脑电波被称为“脑纹”。在信息时代对身份识别有着重要需求的背景下，有别于传统的指纹，声纹，脸部识别等身份识别方式，脑纹识别技术在不可窃取、不可伪造、不易受损、必须活体检测等方面具有独特的优势，能为身份识别提供更安全的生物识别方法，被称为**最安全的下一代密码**。
- 然而目前脑纹识别的发展仍处于探索阶段，存在数据样本量小、测试时段单一、记录范式单一等一系列局限性。同时，目前没有公开的脑纹识别竞赛，缺乏统一的测试基准和平台阻碍了该领域的发展。
- 在此次竞赛中，我们推出一个超过100人的多范式跨时段脑电数据集，针对脑纹识别中的识别(Identification)和验证(Verification)问题提出公开的竞赛目标。

![](/media/competition.png)

## **任务**

1. 识别（Identification）：判断给定的脑电信号所对应的被试是否在注册集中，如果是进一步判断其被试编号(subject ID)；
2. 验证（Verification）：判断给定的脑电信号是否与给出的特定被试(subject ID)匹配。

## **日程**
- **2022年6月**：网站上线。
- **2022年7-8月**：开始比赛。
- **2022年9月**：公布结果。

## **数据集介绍**
一个可靠的脑纹识别系统应能够抵御个体的精神状态变化（跨范式测试），并且能在数天返回后仍能成功识别个体（跨时段测试）。这里我们建立了一个包含106名被试、不同天的两次实验、多种范式的脑电数据库。其中95名被试参加了两次实验，间隔超过一周。实验包含静息态、任务态、脑机接口等6种脑电常见范式。据我们所知，以前的研究没有在超过100个被试的测试规模下评估脑纹识别算法在跨范式和跨时段场景下的测试性能。

![](/media/M3CV.png)

## **竞赛规则**

充分利用脑电个体间差异发展人工智能算法实现鲁棒有效的脑纹识别。鼓励参赛队伍利用多范式脑电数据进行跨时段的脑纹识别，提出针对个体内差异具有较好鲁棒性的脑纹识别算法。

### **数据集划分**

该数据集包含106名被试，其中95名被试完成了两次实验。数据集分割方式如下：

1. 校准集（Calibration Set）

- 帮助参赛者理解数据格式，观察分析不同被试、不同天、不同范式脑电数据间的差异和共同之处；供参赛者进行不同模型离线比较分析。

2. 注册集（Enrollment Set）

- 供参赛者进行脑纹识别模型的训练。

3. 测试集（Test Set）

- 要求参赛者对其中的每个被试根据识别和验证不同任务完成预测


### **竞赛网站（待公布）**

### **引文**

本次挑战中使用的脑电数据是以下论文中 M3CV数据集的一部分。

```
@article{huanggan2022m3cv,
    title={M3CV：A Multi-subject, Multi-session, and Multi-task database for EEG-based Biometrics challenge},
    author={Gan Huang, Zhenxin Hu, Weize Chen, Zhen Liang, Linling Li, Li Zhang, and Zhiguo Zhang},
    journal={in revision},
    year={2022}
}
```