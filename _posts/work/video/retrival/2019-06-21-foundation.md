---
layout: article
title:  "「VIDEO」 检索资源汇总"
date:   2019-06-21 18:06:40 +0800
key: video-retrival-foundation-20190621
aside:
  toc: true
category: [video, video_retrival]
tags: 资源
---
<span id='head'></span>
>**相似视频检索**: 相似指的是通过修改原视频的到新的视频；      

<!--more-->
`video retrieval`； `duplicate video detection` · `near-duplicate`； `Video Copy Detection`； `video localization`； `Local Features` · `Global Features`； `Performance Measures`；         


*发现这方面论文很凌乱，很少；关键字都有很多个版本；*      

# 1 综述

# 2 理论

1. [A distance measure for video sequence similarity matching](http://www.cs.cuhk.edu.hk/~king/PUB/adjeroh98b.pdf)   
*1998* [paper](http://www.cs.cuhk.edu.hk/~king/PUB/adjeroh98b.pdf)    


# 3 重复视频检测
`duplicate video detection` · `near-duplicate`；；

## 3.1 综述
1. [Survey on Web Scale Based Near Duplicate Video Retrieval](https://pdfs.semanticscholar.org/c6b0/0a76cb8c540b4824369ddbf7def551720394.pdf)   
*2016* [paper](https://pdfs.semanticscholar.org/c6b0/0a76cb8c540b4824369ddbf7def551720394.pdf)    

1. [GVoS: A General System for Near-Duplicate Video Related Applications on Storm](http://net.pku.edu.cn/~cuibin/Papers/2017%20TOIS.pdf)    
*2017* [paper](http://net.pku.edu.cn/~cuibin/Papers/2017%20TOIS.pdf)    

1. [A Systematic Review of Near Duplicate Video Retrieval Techniques](https://acadpubl.eu/hub/2018-118-24/3/569.pdf)    
*2018-05-27* [paper](https://acadpubl.eu/hub/2018-118-24/3/569.pdf)    
>太简单，就是一个粗糙的博客；没有思考性的东西，也缺乏大量实验比对；图表模糊，不合格；     


## 3.2 理论

## 3.3 其他
1. [Efficient Near-duplicate Detection and Sub-image Retrieval](http://www.cs.cmu.edu/~rahuls/pub/mm2004-pcasift-rahuls.pdf)     
*2004* [paper](http://www.cs.cmu.edu/~rahuls/pub/mm2004-pcasift-rahuls.pdf)    

1. [A Framework for Handling Spatiotemporal Variations in Video Copy Detection](http://mclab.cs.ccu.edu.tw/files/ken2585699/A%20Framework%20for%20Handling%20Spatiotemporal%20Variations%20in%20Video%20Copy%20Detection/A%20Framework%20for%20Handling%20Spatiotemporal%20Variations%20in%20Video%20Copy%20Detection.rar)   
*2008* [rar](http://mclab.cs.ccu.edu.tw/files/ken2585699/A%20Framework%20for%20Handling%20Spatiotemporal%20Variations%20in%20Video%20Copy%20Detection/A%20Framework%20for%20Handling%20Spatiotemporal%20Variations%20in%20Video%20Copy%20Detection.rar)    
1. [Multiple feature hashing for real-time large scale near-duplicate video retrieval](https://nanopdf.com/download/multiple-feature-hashing-for-real-time-large-scale-near_pdf)     
*2011-12* [ppt](https://nanopdf.com/download/multiple-feature-hashing-for-real-time-large-scale-near_pdf)    
发布了数据集 [UQ_VIDEO](http://staff.itee.uq.edu.au/shenht/UQ_VIDEO/)     

1. [VCDB: A Large-Scale Database for Partial Copy Detection in Videos](http://www.yugangjiang.info/publication/eccv14-VCDB.pdf)    
*2014* [paper](http://www.yugangjiang.info/publication/eccv14-VCDB.pdf)    
发布了数据集    

1. [SHOT AGGREGATING STRATEGY FOR NEAR-DUPLICATE VIDEO RETRIEVAL](https://www.eurasip.org/Proceedings/Eusipco/Eusipco2015/papers/1570097527.pdf)    
*2015* [paper](https://www.eurasip.org/Proceedings/Eusipco/Eusipco2015/papers/1570097527.pdf)    

1. [Pattern-Based Near-Duplicate Video Retrieval and Localization on Web-Scale Videos](https://www.semanticscholar.org/paper/Pattern-Based-Near-Duplicate-Video-Retrieval-and-on-Chou-Chen/b0a2b8945c947816ff0efa5605016c5ab25ef6a8)   
*2015* [paper](https://www.semanticscholar.org/paper/Pattern-Based-Near-Duplicate-Video-Retrieval-and-on-Chou-Chen/b0a2b8945c947816ff0efa5605016c5ab25ef6a8)    

1. [Near-Duplicate Video Detection Based on an Approximate Similarity Self-Join Strategy](https://hal.inria.fr/hal-01305691/document)    
*2016-04* [paper](https://hal.inria.fr/hal-01305691/document)    

1. [Near Duplicate Video Retrieval using Spatio Temporal Approach with Multifeature Mechanism](http://www.ijirset.com/upload/2016/june/174_Near.pdf)    
*2016-06* [paper](http://www.ijirset.com/upload/2016/june/174_Near.pdf)    

1. [Detecting near-duplicate videos by aggregating features from intermediate CNN layers](https://www.researchgate.net/publication/221572367_Detection_and_location_of_near-duplicate_video_sub-clips_by_finding_dense_subgraphs)    
*2016-08* [paper](https://www.researchgate.net/publication/221572367_Detection_and_location_of_near-duplicate_video_sub-clips_by_finding_dense_subgraphs) | [tensorflow](https://github.com/Chinmay26/Near-Duplicate-Video-Detection)        

1. [Near-Duplicate Video Retrieval with Deep Metric Learning](http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w5/Kordopatis-Zilos_Near-Duplicate_Video_Retrieval_ICCV_2017_paper.pdf)         
ICCV 2017 [paper](http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w5/Kordopatis-Zilos_Near-Duplicate_Video_Retrieval_ICCV_2017_paper.pdf)     

1. [A Coarse-to-fine Deep Convolutional Neural Network Framework for Frame Duplication Detection and Localization in Forged Videos](http://cn.arxiv.org/abs/1811.10762)    
*2018-11-27* [paper](https://arxiv.org/abs/1811.10762)   


# 4 视频拷贝检测
>Content Based Copy Detection, CDBC: 作用等同于水印，主要用于版权保护；不同之处在与他是直接从视频本身提取一些特征；     

`Video Copy Detection` · `Video Forgery Detection`；    

## 4.1 综述
1. [Video Copy Detection: a Comparative Study](https://www.irisa.fr/vista/Papers/2007_civr_law-to.pdf)   
*2007* [paper](https://www.irisa.fr/vista/Papers/2007_civr_law-to.pdf)    

1. [A Survey On Video Forgery Detection](http://cn.arxiv.org/abs/1503.00843)    
*2015-03-03* [paper](https://arxiv.org/abs/1503.00843)   

1. [Recent advances in content based video copy detection](http://cn.arxiv.org/abs/1610.09087)    
*2016-10-28* [paper](https://arxiv.org/abs/1610.09087)   

## 4.2 理论

## 4.3 其他
1. [Partial Copy Detection in Videos: A Benchmark and An Evaluation of Popular Methods](http://yugangjiang.info/publication/TBD-VCDB.pdf)   
[paper](http://yugangjiang.info/publication/TBD-VCDB.pdf)   

1. [Scalable mining of large video databases using copy detection](http://cedric.cnam.fr/~crucianm/src/poullot08scalable.pdf)   
*2008* [paper](http://cedric.cnam.fr/~crucianm/src/poullot08scalable.pdf)   

1. [A compact, effective descriptor for video copy detection](http://www.csie.ntnu.edu.tw/~myeh/papers/mm09.pdf)   
*2009* [paper](http://www.csie.ntnu.edu.tw/~myeh/papers/mm09.pdf)    

1. [Video copy detection by fast sequence matching](http://aifc2011.csie.ntnu.edu.tw/~myeh/papers/civr09.pdf)    
*2009* [paper](http://aifc2011.csie.ntnu.edu.tw/~myeh/papers/civr09.pdf)   

1. [A PatchMatch-based Dense-field Algorithm for Video Copy-Move Detection and Localization](http://cn.arxiv.org/abs/1703.04636)    
*2017-03-14* [paper](https://arxiv.org/abs/1703.04636)    
发布了新的数据集；     

1. [Simple Yet Efficient Content Based Video Copy Detection](http://cn.arxiv.org/abs/1804.07019)   
*2018-04-19* [paper](https://arxiv.org/abs/1804.07019)   

1. Geometrically robust video hashing based on ST-PCT for video copy     


# 5 基于内容的视频检索
>Content Based Video Retrival, CBVR: 用于相似场景检测；    


# 6 跨模态检索
## 6.1 图片

1. [Video2Shop: Exactly Matching Clothes in Videos to Online Shopping Images](http://cn.arxiv.org/abs/1804.05287)  
CVPR 2017 *2018-04-14* 西南交大、阿里巴巴 [paper](https://arxiv.org/abs/1804.05287)     
**AsymNet**: 用 FasterRCNN 检测出物体，然后进行比对；          

## 6.2 文本
1. [Dual Encoding for Zero-Example Video Retrieval](http://cn.arxiv.org/abs/1809.06181)    
CVPR 2019 *2018-09-17* [paper](https://arxiv.org/abs/1809.06181) | [pytorch](https://github.com/danieljf24/dual_encoding)-offical | [解读](/video/video_retrival/paper_reading/2019/06/23/Dual-Encoding-for-Zero-Example-Video-Retrieval-reading.html)    

## 6.3 音频

1. [Content-Based Video-Music Retrieval Using Soft Intra-Modal Structure Constraint](http://cn.arxiv.org/abs/1704.06761)  
*2017-04-22* [paper](https://arxiv.org/abs/1704.06761) | [示例](https://youtu.be/ZyINqDMo3Fg) | [tensorflow](https://github.com/csehong/VM-NET)-offical    


1. [Cross-modal Embeddings for Video and Audio Retrieval](http://cn.arxiv.org/abs/1801.02200)  
*2018-01-07* [paper](https://arxiv.org/abs/1801.02200) | [Youtube-8m](https://github.com/surisdi/youtube-8m)-训练   


-------------------  
[End](#head)
{:.warning}  


# 附录
## A 参考资料
1. [Cross-Modal Retrieval](https://paperswithcode.com/task/cross-modal-retrieval)-paper_with_code     

## B 报告
1. ICIP 2017 [Near-Duplicate Video Detection Exploiting Noise Residual Traces](https://pdfs.semanticscholar.org/e604/9608e35f9633bb3c2cf50896f2d26d29a9cd.pdf)    

## C 数据集

重复视频检测：    

| 名称 | 类型 | 数量(训练/测试) | 说明 | 发布日期 |
| --- | --- | --- | --- | --- |
| [TRECVID](https://trecvid.nist.gov/) & [data](https://www-nlpir.nist.gov/projects/trecvid/trecvid.data.html) |  |  |  | 2001~2019 |
| [CC_WEB_VIDEO](http://vireo.cs.cityu.edu.hk/webvideo/) |  |  | 包含颜色亮度变换，画面编辑和拼接 | 2007 |
| [MuscleVCD ST1](https://www.video-comparer.com/product-benchmark.php) |  |  |  |  |
| [UQ_VIDEO](http://staff.itee.uq.edu.au/shenht/UQ_VIDEO/) |  | 169,952 | 查询视频 400 个，检索视频 20 万；单个视频对应的检索视频最多 1000 个；<br>提取到的关键帧有 3,305,525 个；<br>共 15G； | 2011 |
| [Copy-move forgeries dataset](https://sites.google.com/site/rewindpolimi/downloads/datasets/video-copy-move-forgeries-dataset) |  |  |  |  |
| [VCDB](http://www.yugangjiang.info/research/VCDB/) |  |  | 8G | 2014 |
|  |  |  |  |  |


## D 开源项目
1. [ThreatExchange](https://developers.facebook.com/docs/threat-exchange/v4.0): [code](https://github.com/facebook/ThreatExchange) | [TMK + PDQF](https://github.com/facebook/ThreatExchange/tree/master/hashing/tmk)-相似视频识别 | [PDQ](https://github.com/facebook/ThreatExchange/tree/master/hashing/pdq)-相似图片识别       