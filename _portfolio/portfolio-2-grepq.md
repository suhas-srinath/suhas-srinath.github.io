---
title: "GRepQ: Data-Efficient Image Quality Assessment"
excerpt: "Quality-aware contrastive learning framework achieving state-of-the-art performance with minimal labeled data. Published at WACV 2024 (Oral - Top 3%)."
collection: portfolio
---

## Learning Generalizable Perceptual Representations for Quality Assessment

**Project Overview**

GRepQ addresses a fundamental challenge in image quality assessment: how to build accurate quality prediction models without requiring large annotated datasets. The framework learns generalizable quality representations that work across different distortion types and image content.

**Key Innovation**

The project introduces a dual-pathway approach:

**Low-Level Quality Features:**
- Novel quality-aware contrastive learning strategy
- Weights training pairs based on perceptual similarity
- Learns features invariant to distortion types
- Brings similar-quality images closer in latent space regardless of their distortion

**High-Level Quality Features:**
- Unsupervised fine-tuning of CLIP vision-language model
- Group-contrastive learning with quality-relevant antonym prompts
- Separates higher and lower quality image groups
- Captures semantic quality information

**Technical Approach**

- Self-supervised learning framework requiring no human quality annotations during training
- Simple linear regressor trained with very few labeled samples on target datasets
- Zero-shot quality prediction capability
- Combines both low-level and high-level quality representations

**Results**

- State-of-the-art performance across multiple IQA datasets (CLIVE, KonIQ, CSIQ, LIVE, PIPAL)
- Superior data-efficient performance: achieves competitive results with as few as 10% of training data
- Effective zero-shot quality prediction without any fine-tuning
- Oral presentation at WACV 2024 (Top 3% of accepted papers)

**Impact**

GRepQ enables practical deployment of quality assessment systems in scenarios where large-scale annotation is infeasible, making it particularly valuable for emerging imaging technologies and evolving distortion types.

**Links**
- [Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Srinath_Learning_Generalizable_Perceptual_Representations_for_Data-Efficient_No-Reference_Image_Quality_Assessment_WACV_2024_paper.pdf)
- [Code](https://github.com/suhas-srinath/GRepQ)

**Technologies:** PyTorch, CLIP, Contrastive Learning, Self-supervised Learning
