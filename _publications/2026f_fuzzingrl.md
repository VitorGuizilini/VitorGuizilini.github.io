---
title: '
DreamPlan2: Efficient Reinforcement Fine-Tuning of Vision-Language Planners via Video World Models
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
Robotic manipulation requires sophisticated commonsense reasoning, a capability naturally possessed by large-scale Vision-Language Models (VLMs). While VLMs show promise as zero-shot planners, their lack of grounded physical understanding often leads to compounding errors and low success rates when deployed in complex real-world environments, particularly for challenging tasks like deformable object manipulation. Although Reinforcement Learning (RL) can adapt these planners to specific task dynamics, directly fine-tuning VLMs via real-world interaction is prohibitively expensive, unsafe, and sample-inefficient. To overcome this bottleneck, we introduce DreamPlan, a novel framework for the reinforcement fine-tuning of VLM planners via video world models. Instead of relying on costly physical rollouts, DreamPlan first leverages the zero-shot VLM to collect exploratory interaction data. We demonstrate that this sub-optimal data is sufficient to train an action-conditioned video generation model, which implicitly captures complex real-world physics. Subsequently, the VLM planner is fine-tuned entirely within the "imagination" of this video world model using Odds Ratio Policy Optimization (ORPO). By utilizing these virtual rollouts, physical and task-specific knowledge is efficiently injected into the VLM. Our results indicate that DreamPlan bridges the gap between semantic reasoning and physical grounding, significantly improving manipulation success rates without the need for large-scale real-world data collection. 
</a></p>
<p><img src="/images/publications/dreamplan.png" align="right" width="100%" style="margin:0 0 20px 0"></p>
'
venue: '
<p>
Emily Yue-Ting Jia, Weiduo Yuan, Tianheng Shi, Vitor Guizilini, Jiageng Mao, Yue Wang
<br>
<b>arXiv 2026</b>
</p>
'
citation: '
@misc{tri_dreamplan,
      title={DreamPlan: Efficient Reinforcement Fine-Tuning of Vision-Language Planners via Video World Models}, 
      author={Emily Yue-Ting Jia and Weiduo Yuan and Tianheng Shi and Vitor Guizilini and Jiageng Mao and Yue Wang},
      year={2026},
      eprint={2603.16860},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2603.16860}, 
}
'

links: '
<a href="http://arxiv.org/abs/2603.16860">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/arxiv.png"></a>
<a href="https://psi-lab.ai/DreamPlan/">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/project.png"></a>
'
---

<!-- 
---
title: '
FuzzingRL: Reinforcement Fuzz-Testing for Revealing VLM Failures
'
project: '
'
collection: publications
excerpt: '<p align=justify><a style="text-decoration:none; color:#000000; align:justify;">
Vision Language Models (VLMs) are prone to errors, and identifying where these errors occur is critical for ensuring the reliability and safety of AI systems. In this paper, we propose an approach that automatically generates questions designed to deliberately induce incorrect responses from VLMs, thereby revealing their vulnerabilities. The core of this approach lies in fuzz testing and reinforcement finetuning: we transform a single input query into a large set of diverse variants through vision and language fuzzing. Based on the fuzzing outcomes, the question generator is further instructed by adversarial reinforcement fine-tuning to produce increasingly challenging queries that trigger model failures. With this approach, we can consistently drive down a target VLM's answer accuracy -- for example, the accuracy of Qwen2.5-VL-32B on our generated questions drops from 86.58\% to 65.53\% in four RL iterations. Moreover, a fuzzing policy trained against a single target VLM transfers to multiple other VLMs, producing challenging queries that degrade their performance as well.
</a></p>
<p><img src="/images/publications/fuzzingrl.png" align="right" width="100%" style="margin:0 0 20px 0"></p>
'
venue: '
<p>
Jiajun Xu, Jiageng Mao, Ang Qi, Weiduo Yuan, Alexander Romanus, Helen Xia, Vitor Campagnolo Guizilini, Yue Wang
<br>
<b>arXiv 2026</b>
</p>
'
citation: '
@misc{tri_fuzzingrl,
      title={FuzzingRL: Reinforcement Fuzz-Testing for Revealing VLM Failures}, 
      author={Jiajun Xu and Jiageng Mao and Ang Qi and Weiduo Yuan and Alexander Romanus and Helen Xia and Vitor Campagnolo Guizilini and Yue Wang},
      year={2026},
      eprint={2603.06600},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2603.06600}, 
}
'

links: '
<a href="https://arxiv.org/abs/2603.06600">
<img style="margin-right:10px" align="right" width="40" src="/images/icons/arxiv.png"></a>

'
--- -->
