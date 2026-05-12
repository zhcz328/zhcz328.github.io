---
title: "MedSynapse-V: Bridging Visual Perception and Clinical Intuition via Latent Memory Evolution"
authors:
- admin
- Jiaqi Zeng
- Junyu Jiang
- Jianxin Lin
- Yijun Wang
date: "2026-05-12T00:00:00Z"
doi: "10.48550/arXiv.2604.26283"

publication_types: ["3"]
publication: "arXiv preprint, 2026"
publication_short: "arXiv 2026"

abstract: "High-precision medical diagnosis relies not only on static imaging features but also on the implicit diagnostic memory experts instantly invoke during image interpretation. We pinpoint a fundamental cognitive misalignment in medical VLMs caused by discrete tokenization, leading to quantization loss, long-range information dissipation, and missing case-adaptive expertise. To bridge this gap, we propose MedSynapse-V, a framework for latent diagnostic memory evolution that simulates the experiential invocation of clinicians by dynamically synthesizing implicit diagnostic memories within the model's hidden stream. Specifically, it begins with a Meta Query for Prior Memorization mechanism, where learnable probes retrieve structured priors from an anatomical prior encoder to generate condensed implicit memories. To ensure clinical fidelity, we introduce Causal Counterfactual Refinement (CCR), which leverages reinforcement learning and counterfactual rewards derived from region-level feature masking to quantify the causal contribution of each memory, thereby pruning redundancies and aligning latent representations with diagnostic logic. This evolutionary process culminates in Intrinsic Memory Transition (IMT), a privileged-autonomous dual-branch paradigm that internalizes teacher-branch diagnostic patterns into the student-branch via full-vocabulary divergence alignment. Comprehensive empirical evaluations across multiple datasets demonstrate that MedSynapse-V significantly outperforms existing state-of-the-art methods, particularly chain-of-thought paradigms, in diagnostic accuracy."
summary: "A latent diagnostic memory evolution framework that bridges visual perception and clinical intuition in medical VLMs."

tags:
- featured
- Medical AI
- Medical Vision-Language Models
- Multimodal Large Language Models
- Latent Memory

featured: true

links:
- name: Paper
  url: https://arxiv.org/abs/2604.26283

url_pdf: ''
url_code: ''
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

MedSynapse-V bridges visual perception and clinical intuition via latent diagnostic memory evolution for medical vision-language models.
