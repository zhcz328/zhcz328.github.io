---
title: "MedEyes: Learning Dynamic Visual Focus for Medical Progressive Diagnosis"
authors:
- admin
- Yangfang Lin
- Shen Chen
- Yijun Wang
- Jianxin Lin
date: "2026-03-14T00:00:00Z"
doi: "10.1609/aaai.v40i16.38401"

publication_types: ["1"]
publication: "Proceedings of the AAAI Conference on Artificial Intelligence, 2026"
publication_short: "AAAI 2026"

abstract: "Accurate medical diagnosis often involves progressive visual focusing and iterative reasoning, characteristics commonly observed in clinical workflows. While recent vision-language models demonstrate promising chain-of-thought (CoT) reasoning capabilities via reinforcement learning with verifiable rewards (RLVR), their purely on-policy learning paradigm tends to reinforce superficially coherent but clinically inaccurate reasoning paths. We propose MedEyes, a novel reinforcement learning framework that dynamically models clinician-style diagnostic reasoning by progressively attending to and interpreting relevant medical image regions. By incorporating off-policy expert guidance, MedEyes converts expert visual search trajectories into structured external behavioral signals, guiding the model toward clinically aligned visual reasoning. We design the Gaze-guided Reasoning Navigator (GRN) to emulate the diagnostic process through a dual-mode exploration strategy, scanning for systematic abnormality localization and drilling for detailed regional analysis. To balance expert imitation and autonomous discovery, we introduce the Confidence Value Sampler (CVS), which employs nucleus sampling and adaptive termination to create diverse yet credible exploration paths. Finally, the dual-stream GRPO optimization framework decouples on-policy and off-policy learning signals, mitigating reward assimilation and entropy collapse. Experiments demonstrate that MedEyes achieves an average performance improvement of +8.5% across multiple medical VQA benchmarks, validating MedEyes's potential in building trustworthy medical AI systems."
summary: "A reinforcement learning framework that models clinician-style dynamic visual focusing for medical progressive diagnosis."

tags:
- featured
- Medical AI
- Multimodal Large Language Models
- Reinforcement Learning
- Medical VQA

featured: true

links:
- name: Paper
  url: https://ojs.aaai.org/index.php/AAAI/article/view/38401

url_pdf: ''
url_code: 'https://github.com/zhcz328/MedEyes'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: ''
  focal_point: Smart
  preview_only: false
---

MedEyes dynamically models clinician-style diagnostic reasoning by progressively attending to and interpreting relevant medical image regions.
