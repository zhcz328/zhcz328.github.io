---
title: "PACE: Pareto-Adaptive Compression for Efficient Native MLLMs"
authors:
- 'Lei Tian¹'
- 'Chunzheng Zhu†'
- 'Kai WU¹'
- 'YiFan Zhang²'
- 'Haihua Yang¹'
date: "2026-09-29T00:00:00Z"
doi: ""

publication_types: ["1"]
publication: "Advances in Neural Information Processing Systems (NeurIPS), 2026"
publication_short: "NeurIPS 2026"

abstract: "Native multimodal large language models (native MLLMs) jointly encode visual and linguistic sequences within a unified autoregressive Transformer, emerging as a promising paradigm for multimodal understanding. Unlike conventional ViT-based MLLMs that rely on an external vision encoder, ViT-free native MLLMs tokenize every pixel patch directly, which is intuitively expected to suffer from severe visual token redundancy. To examine this hypothesis, we conduct a pilot study and find that, unlike ViT-based models which degrade under compression, ViT-free MLLMs tolerate aggressive compression with near-lossless or even improved performance. Existing compression methods are built exclusively for the ViT-based setting, whereas native MLLMs, which stand to gain the most from visual token compression, remain entirely unexplored. To close this gap, we introduce an analysis pipeline for native backbones, centered on two metrics, i.e., token discriminability and cross-dimensional heterogeneous redundancy, which together reveal the following two findings: (i) redundancy is distributed independently and heterogeneously along the height and width axes, and (ii) in early layers, visual tokens are indiscriminable and uniformly redundant. Guided by these findings, we propose PACE (Pareto-Adaptive Compression for Efficient Native MLLMs), the first visual token compression framework tailored for native MLLMs with Multimodal-RoPE. Leveraging the dimensional decoupling of position encoding, PACE decomposes attention into two orthogonal spatial saliency estimates along height and width, gated by a positional attention signal, yielding a direction-aware importance measure with negligible overhead. It further casts token budget allocation as a Pareto optimization over three objectives, i.e., performance preservation, inference efficiency, and spatial coverage, which jointly identify the optimal compression depths and retention ratios. Experiments show that PACE maintains near-lossless performance at only 25%–50% visual token retention, and even achieves performance gains on several benchmarks, while delivering over 2× FLOPs reduction."
summary: "Pareto-adaptive visual token compression for efficient native multimodal language models."

tags:
- featured
- Multimodal Large Language Models
- Visual Token Compression
- Efficient Inference
- Pareto Optimization

featured: true

links: []

url_pdf: 'paper.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: '¹ ByteDance. ² Institute of Automation, Chinese Academy of Sciences. † Work conducted during Chunzheng Zhu''s internship at ByteDance.'
  focal_point: Smart
  preview_only: false
---

PACE performs direction-aware visual token compression for native MLLMs while preserving performance and reducing computation.

Lei Tian, Kai WU, and Haihua Yang are affiliated with ByteDance. YiFan Zhang is affiliated with the Institute of Automation, Chinese Academy of Sciences. This work was conducted during Chunzheng Zhu's internship at ByteDance.
