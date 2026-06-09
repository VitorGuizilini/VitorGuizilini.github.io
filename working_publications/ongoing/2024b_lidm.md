---
title: '
<a href="https://lidar-diffusion.github.io" style="text-decoration:none;color:#000000;text-align:justify;"> 
Towards Realistic Scene Generation with LiDAR Diffusion Models
</a>
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
Diffusion models (DMs) excel in photo-realistic image synthesis, but their adaptation to LiDAR scene generation poses a substantial hurdle. This is primarily because DMs operating in the point space struggle to preserve the curve-like patterns and 3D geometry of LiDAR scenes, which consumes much of their representation power. In this paper, we propose LiDAR Diffusion Models (LiDMs) to generate LiDAR-realistic scenes from a latent space tailored to capture the realism of LiDAR scenes by incorporating geometric priors into the learning pipeline. Our method targets three major desiderata: pattern realism, geometry realism, and object realism. Specifically, we introduce curve-wise compression to simulate real-world LiDAR patterns, point-wise coordinate supervision to learn scene geometry, and patch-wise encoding for a full 3D object context. With these three core designs, our method achieves competitive performance on unconditional LiDAR generation in 64-beam scenario and state of the art on conditional LiDAR generation, while maintaining high efficiency compared to point-based DMs (up to 107× faster). Furthermore, by compressing LiDAR scenes into a latent space, we enable the controllability of DMs with various conditions such as semantic maps, camera views, and text prompts. 
</a></p>
<p><img src="/images/publications/lidm.gif" align="right" width="100%" style="margin:0 0 20px 0"></p>
'
venue: '
<p>
Haoxi Ran, Vitor Guizilini, Yue Wang
<br>
<b>CVPR 2024</b>
</p>
'
citation: '
@misc{ran2024lidm,
      author={Haoxi Ran and Vitor Guizilini and Yue Wang},
      title={Towards Realistic Scene Generation with LiDAR Diffusion Models}, 
      booktitle = {Proceedings of the International Conference on Computer Vision and Pattern Recognition (CVPR)},
      year={2024}
}'
links: '
<a href="https://arxiv.org/abs/2404.00815">
<img style="margin-right:10px" align="right" width="40" src="/images/arxiv.png"></a>
<a href="https://github.com/hancyran/LiDAR-Diffusion">
<img style="margin-right:10px" align="right" width="40" src="/images/github.png"></a>
'
---
