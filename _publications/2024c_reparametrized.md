---
title: '
<a href="https://lukoianov.com/sdi" style="text-decoration:none;color:#000000;text-align:justify;"> 
Score Distillation via Reparametrized DDIM
</a>
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
While 2D diffusion models generate realistic, high-detail images, 3D shape generation methods like Score Distillation Sampling (SDS) built on these 2D diffusion models produce cartoon-like, over-smoothed shapes. To help explain this discrepancy, we show that the image guidance used in Score Distillation can be understood as the velocity field of a 2D denoising generative process, up to the choice of a noise term. In particular, after a change of variables, SDS resembles a high-variance version of Denoising Diffusion Implicit Models (DDIM) with a differently-sampled noise term: SDS introduces noise i.i.d. randomly at each step, while DDIM infers it from the previous noise predictions. This excessive variance can lead to over-smoothing and unrealistic outputs. We show that a better noise approximation can be recovered by inverting DDIM in each SDS update step. This modification makes SDS generative process for 2D images almost identical to DDIM. In 3D, it removes over-smoothing, preserves higher-frequency detail, and brings the generation quality closer to that of 2D samplers. Experimentally, our method achieves better or similar 3D generation quality compared to other state-of-the-art Score Distillation methods, all without training additional neural networks or multi-view supervision, and providing useful insights into relationship between 2D and 3D asset generation with diffusion models.
</a></p>
<p><img src="/images/publications/reparametrized.gif" align="right" width="100%" style="margin:0 0 20px 0"></p>
'
venue: '
<p>
Artem Lukoianov, Haitz Borde, Kristjan Greenewald, Vitor  Guizilini, Timur Bagautdinov, Vincent Sitzmann, Justin Solomon
<br>
<b>arXiv 2024</b>
</p>
'
citation: '
@misc{lukoianov2024score,
      title={Score Distillation via Reparametrized DDIM}, 
      author={Artem Lukoianov and Haitz Sáez de Ocáriz Borde and Kristjan Greenewald and Vitor Campagnolo Guizilini and Timur Bagautdinov and Vincent Sitzmann and Justin Solomon},
      eprint={2405.15891},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      year={2024}
}'
links: '
<a href="https://arxiv.org/abs/2405.15891">
<img style="margin-right:10px" align="right" width="40" src="/images/arxiv.png"></a>
'
---
