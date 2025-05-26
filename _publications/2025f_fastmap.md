---
title: '
<a href="https://github.com/pals-ttic/fastmap" style="text-decoration:none;color:#000000;text-align:justify;"> 
FastMap: Revisiting Dense and Scalable Structure from Motion
</a>
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
We propose FastMap, a new global structure from motion method focused on speed and simplicity. Previous methods like COLMAP and GLOMAP are able to estimate high-precision camera poses, but suffer from poor scalability when the number of matched keypoint pairs becomes large. We identify two key factors leading to this problem: poor parallelization and computationally expensive optimization steps. To overcome these issues, we design an SfM framework that relies entirely on GPU-friendly operations, making it easily parallelizable. Moreover, each optimization step runs in time linear to the number of image pairs, independent of keypoint pairs or 3D points. Through extensive experiments, we show that FastMap is faster than COLMAP and GLOMAP on large-scale scenes with comparable pose accuracy.
</a></p>
<p><img src="/images/publications/fastmap.png" align="right" width="100%" style="margin:0 0 20px 0"></p>
'
venue: '
<p>
Jiahao Li, Haochen Wang, Muhammad Zubair Irshad, Igor Vasiljevic, Matthew R. Walter, Vitor Campagnolo Guizilini, Greg Shakhnarovich
<br>
<b>arXiv 2025</b>
</p>
'
citation: '
@article{2505.04612v1,
    Author        = {Jiahao Li and Haochen Wang and Muhammad Zubair Irshad and Igor Vasiljevic and Matthew R. Walter and Vitor Campagnolo Guizilini and Greg Shakhnarovich},
    Title         = {FastMap: Revisiting Dense and Scalable Structure from Motion},
    Eprint        = {2505.04612v1},
    ArchivePrefix = {arXiv},
    PrimaryClass  = {cs.CV},
    Year          = {2025},
    Month         = {May},
    Url           = {http://arxiv.org/abs/2505.04612v1},
    File          = {2505.04612v1.pdf}
}'

links: '
<a href="https://arxiv.org/abs/2505.04612">
<img style="margin-right:10px" align="right" width="40" src="/images/arxiv.png"></a>
'
---
