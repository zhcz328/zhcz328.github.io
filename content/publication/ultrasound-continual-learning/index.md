---
title: "Advancing Ultrasound Medical Continuous Learning with Task-Specific Generalization and Adaptability"
authors:
- admin
- Jianxin Lin
- Guanghua Tan
- Ningbo Zhu
- Kenli Li
- Chunlian Wang
- Shengli Li
date: "2024-12-03T00:00:00Z"
doi: ""

publication_types: ["1"]
publication: "IEEE International Conference on Bioinformatics and Biomedicine (BIBM), 2024"
publication_short: "BIBM 2024"

abstract: "As artificial intelligence progresses in the field of medical ultrasound image analysis, mitigating catastrophic forgetting during continuous learning processes in disease diagnosis and fetal ultrasound assistance is crucial. Inspired by the significant performance improvements achieved in various downstream visual tasks through advanced visual representations, we introduce a novel approach called Masked Ultrasound Image Modeling (MUIM) to prevent forgetting of new disease diagnosis tasks. In this approach, MUIM initially pre-trains on ultrasound images specific to the current task. By utilizing a masked autoencoder to train on unlabeled ultrasound images, it learns highly abstract representations of task-relevant information. To ensure the model's adaptability to new tasks, we propose contrastive Historical-Current Learning strategy, which enhances the model's ability to retain and integrate knowledge from previous tasks while learning new ones. By incorporating knowledge distillation loss and the exponential moving average (EMA) technique for joint inference and continuously updating new knowledge into the historical expert model, our approach enables the model to adaptively learn new tasks while preventing forgetting of old ones."
summary: "Task-specific continual learning for ultrasound medical image analysis."

tags:
- Medical AI
- Ultrasound
- Continual Learning
- Knowledge Distillation

featured: true

links:
- name: Paper
  url: https://ieeexplore.ieee.org/document/10822568/

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

This work addresses catastrophic forgetting in ultrasound medical image analysis with masked ultrasound image modeling and contrastive historical-current learning.
