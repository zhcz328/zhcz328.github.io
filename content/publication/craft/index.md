---
title: "CRAFT: Causal Responsibility and Failure Tracing in Medical Vision Language Models"
authors:
- admin
- Jiaqi Zeng
- Hongbo Zhao
- Yihang Chen
- Yijun Wang
- Jianxin Lin
date: "2026-09-29T00:00:00Z"
doi: ""

publication_types: ["1"]
publication: "Advances in Neural Information Processing Systems (NeurIPS), 2026 (Spotlight)"
publication_short: "NeurIPS 2026 Spotlight"

abstract: "As vision language models are increasingly deployed in clinical diagnosis, understanding how they internally resolve competing visual and textual signals becomes a safety imperative. Existing mechanistic analyses remain confined to unimodal text and offer no explanation for why a single misleading sentence can override a correct image based diagnosis, or why a model commits to a confident answer despite insufficient visual evidence. We find that these two safety risks, arbitration failure where textual context overrides visual grounding and brake failure where the model commits without adequate evidence, are mediated by spatially disjoint attention head populations: arbitration heads form a mid-to-deep wideband reflecting cross-layer evidence competition, while brake heads concentrate in a narrow middle-to-late layer band that regulates evidence sufficiency and abstention behavior. To ground these observations in causal circuitry, we introduce CRAFT, which localizes each failure mode to a minimal causal head set via dual criteria and verifies necessity and sufficiency through temporal probes and Tuned Lens trajectory analysis. Excising arbitration heads sharply reduces conflict following with negligible degradation on clean inputs, while excising brake heads restores appropriate abstention under degraded visual evidence. The two interventions target spatially disjoint head sets and produce distinct corrective effects, underscoring the mechanistic separability of the failure modes. Experiments across multiple medical VQA benchmarks and VLM architectures validate both the localization and interventions, demonstrating that the identified heads causally drive each failure mode and that targeted modulation generalises without retraining."
summary: "Causal tracing and targeted intervention for arbitration and brake failures in medical vision language models."

tags:
- featured
- Medical AI
- Vision-Language Models
- Mechanistic Interpretability
- Causal Intervention
- Trustworthy AI

featured: true

links: []

url_pdf: 'paper.pdf'
url_code: 'https://anonymous.4open.science/r/CRAFT-B3CA'
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

CRAFT identifies and intervenes on distinct causal attention head circuits responsible for arbitration and brake failures in medical vision language models.
