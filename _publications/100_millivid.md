---
title: '
MilliVid: Hierarchical Latents for Long-Range Consistency in Video Generation
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
Video generative models have become increasingly powerful, but long-range consistency remains challenging to achieve because even a few dozen frames require impractically long transformer sequence lengths. We show that this issue can be mitigated by generating video using coarse-to-fine rollout within a multi-scale token space. Our approach is simple: first, we pre-train an autoencoder that compresses each frame into a hierarchy of tokens, with levels ranging from the typical latent resolution to only a handful of tokens per frame. The coarsest levels capture the most consequential information, such as scene layout and semantics, while finer levels add high-frequency appearance and texture. Then, we train a video diffusion model to generate these tokens using coarse-to-fine rollout. By carefully controlling the level of detail at which frames are generated and used as context during each rollout step, we are able to preserve long-range consistency in geometry and object permanence while spending less compute on the long-range consistency of less perceptually relevant details. We validate this approach using a custom dataset of long Minecraft videos, where it produces substantially more consistent rollouts compared to existing baselines.
</a></p>
<p><img src="/images/publications/100_millivid.png" align="right" width="100%" style="margin:0 0 20px 0"></p>
<p><img src="/images/icons/empty.png"></p>
'
venue: '
<p>
Ishaan Preetam Chandratreya, David Charatan, Basile Van Hoorick, Sergey Zakharov, Vitor Guizilini, Phillip Isola, Vincent Sitzmann
<br>
<b>arXiv 2026</b>
</p>
'
links: '
<a href="https://arxiv.org/abs/2606.09056">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/arxiv.png"></a>
<a href="https://davidcharatan.com/millivid/">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/project.png"></a>
<a href="/bibtex/100_millivid.txt">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/bibtex.png"></a>
'
---
