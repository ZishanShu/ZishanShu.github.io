---
title: "WaveFormer: Frequency-Time Decoupled Vision Modeling with Wave Equation"
collection: publications
category: manuscripts
permalink: https://arxiv.org/abs/2601.08602
excerpt: 'Vision modeling has advanced rapidly with Transformers, whose attention mechanisms capture visual dependencies but lack a principled account of how semantic information propagates spatially. We revisit this problem from a wave-based perspective: feature maps are treated as spatial signals whose evolution over an internal propagation time (aligned with network depth) is governed by an underdamped wave equation. In this formulation, spatial frequency—from low-frequency global layout to high-frequency edges and textures—is modeled explicitly, and its interaction with propagation time is controlled rather than implicitly fixed. We derive a closed-form, frequency–time decoupled solution and implement it as the Wave Propagation Operator (WPO), a lightweight module that models global interactions in $\mathcal{O}(N \log N)$ time—far lower than attention. Building on WPO, we propose a family of WaveFormer models as drop-in replacements for standard ViTs and CNNs, achieving competitive accuracy across image classification, object detection, and semantic segmentation, while delivering up to $1.6\times$ higher throughput and 30\% fewer FLOPs than attention-based alternatives. Furthermore, our results demonstrate that wave propagation introduces a complementary modeling bias to heat-based methods, effectively capturing both global coherence and high-frequency details essential for rich visual semantics. Codes are available at: https://github.com/ZishanShu/WaveFormer.'
date: 2026-01-13
venue: 'The 40th Annual AAAI Conference on Artificial Intelligence'
paperurl: 'https://arxiv.org/pdf/2601.08602'
citation: 'Zishan Shu and Juntong Wu and Wei Yan and Xudong Liu and Hongyu Zhang and Chang Liu and Youdong Mao and Jie Chen, "WaveFormer: Frequency-Time Decoupled Vision Modeling with Wave Equation," in The 40th Annual AAAI Conference on Artificial Intelligence, Jan 2026.'
---
