---
title: "MedCausalX: Adaptive Causal Reasoning with Self-Reflection for Trustworthy Medical Vision-Language Models"
authors:
- "Jianxin Lin*"
- "Chunzheng Zhu*"
- Peter J. Kneuertz
- Yunfei Bai
- Yuan Xue
date: "2026-03-24T00:00:00Z"
doi: "10.48550/arXiv.2603.23085"

publication_types: ["1"]
publication: "IEEE/CVF Conference on Computer Vision and Pattern Recognition Findings (CVPR Findings), 2026"
publication_short: "CVPR Findings 2026"

abstract: "Vision-Language Models (VLMs) have enabled interpretable medical diagnosis by integrating visual perception with linguistic reasoning. Yet, existing medical chain-of-thought (CoT) models lack explicit mechanisms to represent and enforce causal reasoning, leaving them vulnerable to spurious correlations and limiting their clinical reliability. We pinpoint three core challenges in medical CoT reasoning: how to adaptively trigger causal correction, construct high-quality causal-spurious contrastive samples, and maintain causal consistency across reasoning trajectories. To address these challenges, we propose MedCausalX, an end-to-end framework that explicitly models causal reasoning chains in medical VLMs. We first introduce the CRMed dataset providing fine-grained anatomical annotations, structured causal reasoning chains, and counterfactual variants that guide the learning of causal relationships beyond superficial correlations. Building upon CRMed, MedCausalX employs a two-stage adaptive reflection architecture equipped with causal and verify tokens, enabling the model to autonomously determine when and how to perform causal analysis and verification. Finally, a trajectory-level causal correction objective optimized through error-attributed reinforcement learning refines the reasoning chain, allowing the model to distinguish genuine causal dependencies from shortcut associations. Extensive experiments on multiple benchmarks show that MedCausalX consistently outperforms state-of-the-art methods, improving diagnostic consistency by +5.4 points, reducing hallucination by over 10 points, and attaining top spatial grounding IoU."
summary: "Adaptive causal reasoning with self-reflection for trustworthy medical vision-language models."

tags:
- featured
- Medical AI
- Vision-Language Models
- Causal Reasoning
- Trustworthy AI

featured: true

links:
- name: Paper
  url: https://arxiv.org/abs/2603.23085

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: '* Equal contribution.'
  focal_point: Smart
  preview_only: false
---

MedCausalX explicitly models causal reasoning chains in medical VLMs to reduce spurious correlations and improve trustworthy diagnosis.
