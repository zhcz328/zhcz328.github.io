---
title: "Trustworthy Medical Concept Recalibration through Logic-Aware Multimodal Evidence Fusion"
authors:
- Lei Zhao
- 'Chunzheng Zhu*'
- Zhan Gao
- Pengchen Liang
- Xiaoyun Liang
- Alex Chit-Yuen Cheng
- Chi-Man Pun
date: "2026-09-19T00:00:00Z"
doi: ""

publication_types: ["2"]
publication: "Information Fusion, 2026"
publication_short: "Information Fusion 2026"

abstract: "Concept Bottleneck Models (CBMs) enhance interpretable medical image diagnosis by mapping inputs to human-understandable intermediate concepts. However, existing concept intervention methods rely heavily on labor-intensive manual corrections, incurring prohibitive annotation costs, introducing subjective variability, and limiting clinical scalability. To overcome these limitations, we propose ConChecker, an autonomous concept intervention framework that dynamically recalibrates concept assignments while reducing reliance on human intervention. Formulating initial CBM predictions as primary diagnostic hypotheses, ConChecker conducts targeted self-critique anchored in visual evidence. Specifically, it employs vision-language models to extract rich pathological descriptions from medical images and subsequently verifies each concept via Concept Attribute Fidelity (CAF), a mechanism that models the directional relationships among heterogeneous evidence sources to quantify net concept-text support. ConChecker then derives fine-grained soft interventions through Group Verifiable Concept Policy Optimization (GVCPO), significantly improving diagnostic reliability while preserving concept fidelity. Comprehensive evaluations across multiple medical benchmarks demonstrate that ConChecker substantially reduces the need for human-in-the-loop intervention and achieves state-of-the-art performance. Furthermore, its modular plug-and-play design enables seamless integration into standard CBM architectures without structural modifications."
summary: "ConChecker autonomously recalibrates medical concepts through logic-aware multimodal evidence fusion and verifiable policy optimization."

tags:
- featured
- Medical AI
- Concept Bottleneck Models
- Multimodal Large Language Models
- Reinforcement Learning
- Trustworthy AI

featured: true

links: []

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: '* Corresponding author.'
  focal_point: Smart
  preview_only: false
---

ConChecker replaces labor-intensive manual concept correction with autonomous, evidence-driven recalibration for trustworthy medical diagnosis.
