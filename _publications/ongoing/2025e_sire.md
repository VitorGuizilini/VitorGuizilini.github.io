---
title: '
<a href="https://arxiv.org/abs/2503.07739" style="text-decoration:none;color:#000000;text-align:justify;"> 
SIRE: SE(3) Intrinsic Rigidity Embeddings
</a>
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
Motion serves as a powerful cue for scene perception and understanding by separating independently moving surfaces and organizing the physical world into distinct entities. We introduce SIRE, a self-supervised method for motion discovery of objects and dynamic scene reconstruction from casual scenes by learning intrinsic rigidity embeddings from videos. Our method trains an image encoder to estimate scene rigidity and geometry, supervised by a simple 4D reconstruction loss: a least-squares solver uses the estimated geometry and rigidity to lift 2D point track trajectories into SE(3) tracks, which are simply re-projected back to 2D and compared against the original 2D trajectories for supervision. Crucially, our framework is fully end-to-end differentiable and can be optimized either on video datasets to learn generalizable image priors, or even on a single video to capture scene-specific structure - highlighting strong data efficiency. We demonstrate the effectiveness of our rigidity embeddings and geometry across multiple settings, including downstream object segmentation, SE(3) rigid motion estimation, and self-supervised depth estimation. Our findings suggest that SIRE can learn strong geometry and motion rigidity priors from video data, with minimal supervision.
</a></p>
<p><img src="/images/publications/sire.png" align="right" width="100%" style="margin:0 0 20px 0"></p>
'
venue: '
<p>
Cameron Smith, Basile Van Hoorick, Vitor Guizilini, Yue Wang
<br>
<b>arXiv 2025</b>
</p>
'
citation: '
@misc{tri-sire,
      title={SIRE: SE(3) Intrinsic Rigidity Embeddings}, 
      author={Cameron Smith and Basile Van Hoorick and Vitor Guizilini and Yue Wang},
      eprint={2503.07739},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      year={2025}
}'


links: '
<a href="https://arxiv.org/abs/2412.14172">
<img style="margin-right:10px" align="right" width="40" src="/images/arxiv.png"></a>
'
---
