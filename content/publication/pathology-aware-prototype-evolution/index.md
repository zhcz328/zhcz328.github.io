---
title: "Pathology-Aware Prototype Evolution via LLM-Driven Semantic Disambiguation for Multicenter Diabetic Retinopathy Diagnosis"
authors:
- admin
- Yangfang Lin
- Jialin Shao
- Jianxin Lin
- Yijun Wang
date: "2025-01-01T00:00:00Z"
doi: "10.1145/3746027.3754562"

publication_types: ["1"]
publication: "Proceedings of the 33rd ACM International Conference on Multimedia (ACM MM), 2025"
publication_short: "ACM MM 2025"

abstract: "Diabetic retinopathy (DR) grading plays a critical role in early clinical intervention and vision preservation. Recent explorations predominantly focus on visual lesion feature extraction through data processing and domain decoupling strategies. However, they generally overlook domain-invariant pathological patterns and underutilize the rich contextual knowledge of foundation models, relying solely on visual information, which is insufficient for distinguishing subtle pathological variations. Therefore, we propose integrating fine-grained pathological descriptions to complement prototypes with additional context, thereby resolving ambiguities in borderline cases. Specifically, we propose a Hierarchical Anchor Prototype Modulation (HAPM) framework to facilitate DR grading. First, we introduce a variance spectrum-driven anchor prototype library that preserves domain-invariant pathological patterns. We further employ a hierarchical differential prompt gating mechanism, dynamically selecting discriminative semantic prompts from both LVLM and LLM sources to address semantic confusion between adjacent DR grades. Finally, we utilize a two-stage prototype modulation strategy that progressively integrates clinical knowledge into visual prototypes through a Pathological Semantic Injector (PSI) and a Discriminative Prototype Enhancer (DPE). Extensive experiments across eight public datasets demonstrate that our approach achieves pathology-guided prototype evolution while outperforming state-of-the-art methods."
summary: "LLM-driven pathology-aware prototype evolution for multicenter diabetic retinopathy diagnosis."

tags:
- featured
- Medical AI
- Diabetic Retinopathy
- Large Language Models
- Domain Generalization

featured: true

links:
- name: Paper
  url: https://dl.acm.org/doi/10.1145/3746027.3754562

url_pdf: ''
url_code: 'https://github.com/zhcz328/HAPM'
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

This work integrates fine-grained pathological descriptions with visual prototypes to resolve semantic ambiguity in multicenter diabetic retinopathy grading.
