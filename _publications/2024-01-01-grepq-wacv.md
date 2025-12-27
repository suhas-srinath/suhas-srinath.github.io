---
title: "Learning Generalizable Perceptual Representations for Data-Efficient No-Reference Image Quality Assessment"
collection: publications
permalink: /publication/2024-01-01-grepq-wacv
excerpt: 'Novel quality-aware contrastive learning for low-level features and group-contrastive CLIP fine-tuning for high-level quality features. State-of-the-art performance in data-efficient and zero-shot IQA settings.'
date: 2024-01-01
venue: 'IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)'
slidesurl: ''
paperurl: ''
---

**Oral Presentation (Top 3% of accepted papers)**

This paper introduces GRepQ (Generalizable Representations for Quality), a framework for learning generalizable image quality representations through self-supervised learning to design data-efficient NR-IQA models. The key contributions include:

- A quality-aware contrastive loss that weighs positive and negative training pairs using a soft perceptual similarity measure to enable representation learning invariant to distortion types
- An unsupervised task-specific adaptation of a vision-language model (CLIP) to capture semantic quality information by separating higher and lower-quality groups based on quality-relevant antonym text prompts
- Superior performance over existing methods in both data-efficient and zero-shot settings across multiple IQA datasets (CLIVE, KonIQ, CSIQ, LIVE, PIPAL)

[Download paper here](https://openaccess.thecvf.com/content/WACV2024/papers/Srinath_Learning_Generalizable_Perceptual_Representations_for_Data-Efficient_No-Reference_Image_Quality_Assessment_WACV_2024_paper.pdf)

[Code](https://github.com/suhas-srinath/GRepQ)

Recommended citation: Srinath, S., Mitra, S., Rao, S., and Soundararajan, R. (2024). "Learning Generalizable Perceptual Representations for Data-Efficient No-Reference Image Quality Assessment." *Proc. IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)*. pp. 22-31.
