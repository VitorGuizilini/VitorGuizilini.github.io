---
title: '
<a href="https://mvgd.github.io/" style="text-decoration:none;color:#000000;text-align:justify;"> 
Zero-Shot Novel View and Depth Synthesis with Multi-View Geometric Diffusion
</a>
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
Current methods for 3D scene reconstruction from sparse posed images employ intermediate 3D representations such as neural fields, voxel grids, or 3D Gaussians, to achieve multi-view consistent scene appearance and geometry. In this paper we introduce MVGD, a diffusion-based architecture capable of direct pixel-level generation of images and depth maps from novel viewpoints, given an arbitrary number of input views. Our method uses raymap conditioning to both augment visual features with spatial information from different viewpoints, as well as to guide the generation of images and depth maps from novel views. A key aspect of our approach is the multi-task generation of images and depth maps, using learnable task embeddings to guide the diffusion process towards specific modalities. We train this model on a collection of more than 60 million multi-view samples from publicly available datasets, and propose techniques to enable efficient and consistent learning in such diverse conditions. We also propose a novel strategy that enables the efficient training of larger models by incrementally fine-tuning smaller ones, with promising scaling behavior. Through extensive experiments, we report state-of-the-art results in multiple novel view synthesis benchmarks, as well as multi-view stereo and video depth estimation.
</a></p>
<p><img src="/images/publications/mvgd.png" align="right" width="100%" style="margin:0 0 20px 0"></p>
'
venue: '
<p>
Vitor Guizilini, Muhammad Zubair Irshad, Dian Chen, Greg Shakhnarovich, Rares Ambrus
<br>
<b>CVPR 2025</b>
</p>
'
citation: '
@inproceedings{tri-mvgd,
      author={Vitor Guizilini and Muhammad Zubair Irshad and Dian Chen and Greg Shakhnarovich and Rares Ambrus},
      title={Zero-Shot Novel View and Depth Synthesis with Multi-View Geometric Diffusion}, 
      booktitle = {Proceedings of the International Conference on Computer Vision and Pattern Recognition (CVPR)},
      year={2025}
}'

links: '
<a href="https://arxiv.org/abs/2501.18804">
<img style="margin-right:10px" align="right" width="40" src="/images/arxiv.png"></a>
'
---
