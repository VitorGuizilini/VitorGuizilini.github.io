---
title: '
<a style="text-decoration:none;color:#000000;text-align:justify;"> 
Viewpoint equivariance for multi-view 3d object detection
</a>
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
Autonomous vehicles and robots need to operate over a wide variety of scenarios in order to complete tasks efficiently and safely. Multi-camera self-supervised monocular depth estimation from videos is a promising way to reason about the environment, as it generates metrically scaled geometric predictions from visual data without requiring additional sensors. However, most works assume well-calibrated extrinsics to fully leverage this multi-camera setup, even though accurate and efficient calibration is still a challenging problem. In this work, we introduce a novel method for extrinsic calibration that builds upon the principles of self-supervised monocular depth and ego-motion learning. Our proposed curriculum learning strategy uses monocular depth and pose estimators with velocity supervision to estimate extrinsics, and then jointly learns extrinsic calibration along with depth and pose for a set of overlapping cameras rigidly attached to a moving vehicle. Experiments on a benchmark multi-camera dataset (DDAD) demonstrate that our method enables self-calibration in various scenes robustly and efficiently compared to a traditional vision-based pose estimation pipeline. Furthermore, we demonstrate the benefits of extrinsics self-calibration as a way to improve depth prediction via joint optimization. 
</a></p>
<img src="/images/viewpoint.png" align="right" width="100%" margin-bottom="50px">
'
venue: '
<p>
Dian Chen, Jie Li, Vitor Guizilini, Rares Ambrus, Adrien Gaidon
<br>
International Conference on Computer Vision and Pattern Recognition (<b>CVPR 2023</b>)
</p>
'
citation: '
@inproceedings{chen2023viewpoint,
  title={Viewpoint Equivariance for Multi-View 3D Object Detection},
  author={Chen, Dian and Li, Jie and Guizilini, Vitor and Ambrus, Rares and Gaidon, Adrien},
  booktitle = {Proceedings of the International Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2023}
}
'
links: '
<a href="https://arxiv.org/abs/2303.14548">
<img style="margin-right:10px" align="right" width="40" src="/images/arxiv.png"></a>
<a href="https://github.com/TRI-ML/VEDet">
<img style="margin-right:10px" align="right" width="40" src="/images/github.png"></a>
'
---
