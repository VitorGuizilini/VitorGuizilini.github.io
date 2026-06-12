---
title: '
Fiducial Exoskeletons: Image-Centric Robot State Estimation
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
We introduce Fiducial Exoskeletons, an image-based reformulation of 3D robot state estimation that replaces cumbersome procedures and motor-centric pipelines with single-image inference. Traditional approaches - especially robot-camera extrinsic estimation - often rely on high-precision actuators and require time-consuming routines such as hand-eye calibration. In contrast, modern learning-based robot control is increasingly trained and deployed from RGB observations on lower-cost hardware.
Our key insight is twofold. First, we cast robot state estimation as 6D pose estimation of each link from a single RGB image: the robot-camera base transform is obtained directly as the estimated base-link pose, and the joint state is recovered via a lightweight global optimization that enforces kinematic consistency with the observed link poses (optionally warm-started with encoder readings). Second, we make per-link 6D pose estimation robust and simple - even without learning - by introducing the fiducial exoskeleton: a lightweight 3D-printed mount with a fiducial marker on each link and known marker-link geometry.
This design yields robust camera-robot extrinsics, per-link SE(3) poses, and joint-angle state from a single image, enabling robust state estimation even on unplugged robots. Demonstrated on a low-cost robot arm, fiducial exoskeletons substantially simplify setup while improving calibration, state accuracy, and downstream 3D control performance. We release code and printable hardware designs to enable further algorithm-hardware co-design.
</a></p>
<p><img src="/images/publications/fidexo.png" align="right" width="100%" style="margin:0 0 20px 0"></p>
'
venue: '
<p>
Cameron Smith, Basile Van Hoorick, Vitor Guizilini, Yue Wang
<br>
<b>arXiv 2026</b>
</p>
'
citation: '
@misc{tri_fidexo,
      title={Fiducial Exoskeletons: Image-Centric Robot State Estimation}, 
      author={Cameron Smith and Basile Van Hoorick and Vitor Guizilini and Yue Wang},
      year={2026},
      eprint={2601.08034},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2601.08034}, 
}
'

links: '
<a href="https://arxiv.org/abs/2601.08034">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/arxiv.png"></a>
<a href="https://psi-lab.ai/DreamPlan/">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/project.png"></a>
'
---
