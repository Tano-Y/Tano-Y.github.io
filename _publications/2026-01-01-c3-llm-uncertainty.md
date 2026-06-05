---
title: "Conditional Contrastive Confidence-Based Uncertainty Quantification for LLMs"
collection: publications
category: conferences
permalink: /publication/2026-01-01-c3-llm-uncertainty
excerpt: "A sampling-free uncertainty quantification method for LLMs that estimates response-level uncertainty through contrastive token-distribution shifts."
date: 2026-01-01
venue: "PAKDD 2026"
citation: "Yifan Zhang, Yuzhe Ou, Kangshuo Li, and Feng Chen. Conditional Contrastive Confidence-Based Uncertainty Quantification for LLMs. Accepted at PAKDD 2026."
---

This work proposes C3, a sampling-free uncertainty quantification method for large language models that estimates response-level uncertainty through contrastive token-distribution shifts under learned system-instruction perturbations.

The method uses a gradient-guided search objective to discover perturbations that separate confident and hallucination-prone response regions, requiring only one additional forward pass. Across five LLM backbones and two QA benchmarks, C3 achieved strong AUROC/AUPR results against state-of-the-art baselines while reducing inference cost by more than 97%.

Contribution: I led the project end to end, including research conception, method development, experimental design, implementation, result analysis, and initial manuscript writing.
