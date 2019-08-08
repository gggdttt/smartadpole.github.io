---
layout: article
title:  "「VIDEO」 关键帧提取资源汇总"
date:   2019-06-12 18:16:40 +0800
key: keyframe-foundation-20190612
aside:
  toc: true
category: [video, key_frame]
tags: 资源
---
<span id='head'></span>

<!--more-->
`key frame extraction` · `bag of keyframes` · `key frame detection`    

# 1 综述

# 2 理论

# 3 关键帧提取
1. [Video Key Frame Extraction using Entropy value as Global and Local Feature](http://cn.arxiv.org/abs/1605.08857)   
*2016-05-28* [Paper](https://arxiv.org/abs/1605.08857)   
自注意力机制助力视频字幕提取；    
>摘要不是很好，核心不清晰；   

# 4 镜头边界检测
1. [TransNet: A deep network for fast detection of common shot transitions](https://arxiv.org/abs/1906.03363)   
*2019-06-08* [paper](https://arxiv.org/abs/1906.03363) | [code](https://github.com/soCzech/TransNet)       


# 5 应用
## 5.1  手势识别
1. [Fast and Robust Dynamic Hand Gesture Recognition via Key Frames Extraction and Feature Fusion](http://cn.arxiv.org/abs/1901.04622)   
*2019-01-15* [Paper](https://arxiv.org/abs/1901.04622)   
基于图像熵和视频聚类提取到视频中的关键帧，一次提高手势识别的准确度；   
[数据，代码](https://github.com/Ha0Tang/HandGestureRecognition) 待发布；   


## 5.2 动作识别
1. [Deep Keyframe Detection in Human Action Videos](http://cn.arxiv.org/abs/1804.10021)   
*2018-04-26* [Paper](https://arxiv.org/abs/1804.10021)   
人体行为关键帧的特点：这些关键帧的类别区分度最强；   
做法：  
- 生成关键帧的label   
    - 利用 Imagenet 预训练的 VGG-16 提取每一帧的特征   
    - 根据每个视频的类别，将同一类别的帧组成 Vc   
    - 对于每一类，利用 LDA 学习一个矩阵，最大化与其他类别的距离    
每一帧的得分为：     
    - 利用生成的 label，训练一个关键帧得分生成网络   
收获：   
    - 关键帧的分布与原序列的分布一致（多样性）  
    - 关键帧的信息冗余尽可能少（离散型）  
    - 关键帧的个数应该尽可能的少  
    - 关键帧能够很容易识别出该 id（判别性）  

1. [A Key Volume Mining Deep Framework for Action Recognition](https://zpascal.net/cvpr2016/Zhu_A_Key_Volume_CVPR_2016_paper.pdf)   
CVPR 2016 *2016* [paper](https://zpascal.net/cvpr2016/Zhu_A_Key_Volume_CVPR_2016_paper.pdf)   
motivation：视频中包含大量静止画面，如果把这些帧送入网络，会对网络的训练起到一个反向的作用；   
做法：将多个帧输入到网络中，只优化对于在目标类中取得最大概率的帧的loss；   
思考：用分类来提取关键帧，类别分数越高，越有可能成为关键帧；   
问题：测试时输入的帧也有可能不含有动作信息，为什么还要将各个帧的得分平均？是不是也可以考虑像训练集那样只考虑关键帧的预测结果；   

-------------------  
[End](#head)
{:.warning}  


# 附录
## A 参考资料