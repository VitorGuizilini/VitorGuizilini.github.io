---
title: '
NeuralRemaster: Phase-Preserving Diffusion for Structure-Aligned Generation
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
Standard diffusion corrupts data using Gaussian noise whose Fourier coefficients have random magnitudes and random phases. While effective for unconditional or text-to-image generation, corrupting phase components destroys spatial structure, making it ill-suited for tasks requiring geometric consistency, such as re-rendering, simulation enhancement, and image-to-image translation. We introduce Phase-Preserving Diffusion (\phi-PD), a model-agnostic reformulation of the diffusion process that preserves input phase while randomizing magnitude, enabling structure-aligned generation without architectural changes or additional parameters. We further propose Frequency-Selective Structured (FSS) noise, which provides continuous control over structural rigidity via a single frequency-cutoff parameter. \phi-PD adds no inference-time cost and is compatible with any diffusion model for images or videos. Across photorealistic and stylized re-rendering, as well as sim-to-real enhancement for driving planners, \phi-PD produces controllable, spatially aligned results. When applied to the CARLA simulator, \phi-PD significantly improves sim-to-real planner transfer performance. The method is complementary to existing conditioning approaches and broadly applicable to image-to-image and video-to-video generation.
</a></p>
<p><img src="/images/publications/090_neuralremaster.png" align="right" width="100%" style="margin:0 0 20px 0"></p>
<p><img src="/images/icons/empty.png"></p>
'
venue: '
<p>
Yu Zeng, Charles Ochoa, Mingyuan Zhou, Vishal M. Patel, Vitor Guizilini, Rowan McAllister
<br>
<b>arXiv 2025</b>
</p>
'
links: '
<a href="https://arxiv.org/abs/2512.05106">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/arxiv.png"></a>
<a href="https://yuzeng-at-tri.github.io/ppd-page/">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/project.png"></a>
<a href="/bibtex/090_neuralremaster.txt">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/bibtex.png"></a>
'
---
