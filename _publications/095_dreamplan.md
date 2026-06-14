---
title: '
DreamPlan: Efficient Reinforcement Fine-Tuning of Vision-Language Planners via Video World Models
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
Robotic manipulation requires sophisticated commonsense reasoning, a capability naturally possessed by large-scale Vision-Language Models (VLMs). While VLMs show promise as zero-shot planners, their lack of grounded physical understanding often leads to compounding errors and low success rates when deployed in complex real-world environments, particularly for challenging tasks like deformable object manipulation. Although Reinforcement Learning (RL) can adapt these planners to specific task dynamics, directly fine-tuning VLMs via real-world interaction is prohibitively expensive, unsafe, and sample-inefficient. To overcome this bottleneck, we introduce DreamPlan, a novel framework for the reinforcement fine-tuning of VLM planners via video world models. Instead of relying on costly physical rollouts, DreamPlan first leverages the zero-shot VLM to collect exploratory interaction data. We demonstrate that this sub-optimal data is sufficient to train an action-conditioned video generation model, which implicitly captures complex real-world physics. Subsequently, the VLM planner is fine-tuned entirely within the "imagination" of this video world model using Odds Ratio Policy Optimization (ORPO). By utilizing these virtual rollouts, physical and task-specific knowledge is efficiently injected into the VLM. Our results indicate that DreamPlan bridges the gap between semantic reasoning and physical grounding, significantly improving manipulation success rates without the need for large-scale real-world data collection. 
</a></p>
<p><img src="/images/publications/095_dreamplan.png" align="right" width="100%" style="margin:0 0 20px 0"></p>
<p><img src="/images/icons/empty.png"></p>
'
venue: '
<p>
Emily Yue-Ting Jia, Weiduo Yuan, Tianheng Shi, Vitor Guizilini, Jiageng Mao, Yue Wang
<br>
<b>arXiv 2026</b>
</p>
'
links: '
<a href="http://arxiv.org/abs/2603.16860">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/arxiv.png"></a>
<a href="https://psi-lab.ai/DreamPlan/">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/project.png"></a>
<a href="/bibtex/095_dreamplan.txt">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/bibtex.png"></a>
'
---
