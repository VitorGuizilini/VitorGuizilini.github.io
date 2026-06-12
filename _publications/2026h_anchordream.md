---
title: '
AnchorDream: Repurposing Video Diffusion for Embodiment-Aware Robot Data Synthesis
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
The collection of large-scale and diverse robot demonstrations remains a major bottleneck for imitation learning, as real-world data acquisition is costly and simulators offer limited diversity and fidelity with pronounced sim-to-real gaps. While generative models present an attractive solution, existing methods often alter only visual appearances without creating new behaviors, or suffer from embodiment inconsistencies that yield implausible motions. To address these limitations, we introduce AnchorDream, an embodiment-aware world model that repurposes pretrained video diffusion models for robot data synthesis. AnchorDream conditions the diffusion process on robot motion renderings, anchoring the embodiment to prevent hallucination while synthesizing objects and environments consistent with the robot's kinematics. Starting from only a handful of human teleoperation demonstrations, our method scales them into large, diverse, high-quality datasets without requiring explicit environment modeling. Experiments show that the generated data leads to consistent improvements in downstream policy learning, with relative gains of 36.4% in simulator benchmarks and nearly double performance in real-world studies. These results suggest that grounding generative world models in robot motion provides a practical path toward scaling imitation learning.
</a></p>
<p><img src="/images/publications/anchordream.png" align="right" width="100%" style="margin:0 0 20px 0"></p>
'
venue: '
<p>
Junjie Ye, Rong Xue, Basile Van Hoorick, Pavel Tokmakov, Muhammad Zubair Irshad, Yue Wang, Vitor Guizilini
<br>
<b>ICRA 2026</b>
</p>
'
citation: '
@inproceedings{tri_anchordream,
  title={AnchorDream: Repurposing Video Diffusion for Embodiment-Aware Robot Data Synthesis},
  author={Ye, Junjie and Xue, Rong and Van Hoorick, Basile and Tokmakov, Pavel and Irshad, Muhammad Zubair and Wang, Yue and Guizilini, Vitor},
  booktitle={IEEE International Conference on Robotics and Automation (ICRA)},
  year={2026}
}
'

links: '
<a href="https://arxiv.org/abs/2512.11797>
<img style="margin-right:10px" align="right" width="40" src="/images/icons/arxiv.png"></a>
<a href="https://junjieye.com/AnchorDream/">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/project.png"></a>
'
---
