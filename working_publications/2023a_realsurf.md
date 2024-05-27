---
title: '
Surface Representation in LiDAR Scenes
'
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: '<a style="text-decoration:none;color:#000000;text-align:center;">
Learning from point clouds entails knowledge of local shape geometry. Recent efforts have succeeded in representing synthetic point clouds as surfels. However, these methods struggle to deal with LiDAR point clouds captured from real scans, which are sparse, uneven, and larger-scale. In this paper, we introduce \textbf{RealSurf}, a general framework that processes point clouds under extreme conditions like autonomous driving scenarios. We identify several key challenges in applying surface representations to real scans and propose solutions to these challenges: Point Sliding Module that jitters point coordinates within the reconstructed surfels for geometric feature computation, and LiDAR-based surfel reconstruction process that enables models to directly construct surfels from LiDAR point clouds by attenuating unevenness. We evaluate our approach on a diverse set of benchmarks, including nuScenes, SemanticKITTI, and Waymo. RealSurf, with a simple PointNet++ backbone, outperforms its counterparts by a significant margin while remaining efficient. By achieving state-of-the-art results on three benchmarks through a fair and unbiased comparison, RealSurf brings renewed attention to the effectiveness of point-based methods in LiDAR segmentation. 
</a>
<br><br><img src="/images/map2lidar.gif" align="right" width="100%" margin-bottom="50px">
'
venue: '
<p>
    Haoxi Ran, Xiangru Huang, Vitor Guizilini, Yue Wang
    <a href="https://arxiv.org/abs/2404.00815"><img style="float:right;margin-right:50px" width="40" src="/images/arxiv.png"></a> &nbsp; &nbsp; &nbsp;
    <a href="https://github.com/hancyran/LiDAR-Diffusion"><img style="float:right" width="40" src="/images/github.png"></a> &nbsp; &nbsp; &nbsp;
    <a href="https://www.youtube.com/watch?v=Vj7DubNZnDo"><img style="float:right" width="40" src="/images/youtube.png"></a> &nbsp; &nbsp; &nbsp;
    <a href="http://www.g---
title: '
<a href="https://sites.google.com/view/tri-sesc" style="text-decoration:none;color:#000000;text-align:justify;"> 
Robust Self-Supervised Extrinsic Self-Calibration
</a>
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
Autonomous vehicles and robots need to operate over a wide variety of scenarios in order to complete tasks efficiently and safely. Multi-camera self-supervised monocular depth estimation from videos is a promising way to reason about the environment, as it generates metrically scaled geometric predictions from visual data without requiring additional sensors. However, most works assume well-calibrated extrinsics to fully leverage this multi-camera setup, even though accurate and efficient calibration is still a challenging problem. In this work, we introduce a novel method for extrinsic calibration that builds upon the principles of self-supervised monocular depth and ego-motion learning. Our proposed curriculum learning strategy uses monocular depth and pose estimators with velocity supervision to estimate extrinsics, and then jointly learns extrinsic calibration along with depth and pose for a set of overlapping cameras rigidly attached to a moving vehicle. Experiments on a benchmark multi-camera dataset (DDAD) demonstrate that our method enables self-calibration in various scenes robustly and efficiently compared to a traditional vision-based pose estimation pipeline. Furthermore, we demonstrate the benefits of extrinsics self-calibration as a way to improve depth prediction via joint optimization. 
</a></p>
<img src="/images/map2lidar.gif" align="right" width="100%" margin-bottom="50px">
'
venue: '
<p>
Takayuki Kanai, Igor Vasiljevic, Vitor Guizilini, Adrien Gaidon, Rares Ambrus <br>
IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2023)
</p>
'
citation: '
@inproceedings{tri_sesc_iros23,
  author = {Takayuki Kanai and Igor Vasiljevic and Vitor Guizilini and Adrien Gaidon and Rares Ambrus},
  title = {Robust Self-Supervised Extrinsic Self-Calibration},
  booktitle = {The IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  year = {2023}
}
'
links: '
<a href="https://arxiv.org/abs/2404.00815">
<img style="margin-right:10px" align="right" width="40" src="/images/arxiv.png"></a>
<a href="https://github.com/hancyran/LiDAR-Diffusion">
<img style="margin-right:10px" align="right" width="40" src="/images/github.png"></a>
<a href="https://www.youtube.com/watch?v=Vj7DubNZnDo">
<img style="margin-right:10px" align="right" width="40" src="/images/youtube.png"></a>
<a href="http://www.google4.com">
<img style="margin-right:10px" align="right" width="40" src="/images/music.png"></a>
'
---
oogle4.com"><img style="float:right" width="40" src="/images/music.png" margin-right="200px"></a> &nbsp; &nbsp; &nbsp;
</p>
'
citation: '
@inproceedings{ran2024towards,
    title={Towards Realistic Scene Generation with LiDAR Diffusion Models},
    author={Ran, Haoxi and Guizilini, Vitor and Wang, Yue},
    booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
    year={2024}
}
'

---

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.


