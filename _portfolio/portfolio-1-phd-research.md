---
title: "PhD Thesis: Self-Supervised Domain Generalization"
excerpt: "PhD thesis on building computer vision models that generalize from seen to unseen domains through self-supervised learning."
collection: portfolio
---

## From Seen to Unseen: Self-Supervised Learning for Domain Generalization

**PhD Thesis Overview**

**Thesis Title:** "From Seen to Unseen: Self-Supervised Learning for Domain Generalization in Computer Vision Applications"

**Institution:** Indian Institute of Science (IISc), Bengaluru  
**Department:** Electrical Communication Engineering  
**Advisor:** Prof. Rajiv Soundararajan and Prof. Prathosh A.P.

**Research Vision**

Building robust computer vision systems that generalize across diverse, unseen domains without requiring extensive labeled data from every possible scenario. This work demonstrates how self-supervised learning and physics-informed approaches enable models to handle distribution shifts effectively.

**Core Research Themes**

### 1. Quality-Aware Representation Learning
Developed novel contrastive learning frameworks that learn quality representations invariant to distortion types, enabling data-efficient quality assessment across diverse image degradations.

**Key Innovation:** Quality-aware contrastive loss that weights training pairs based on perceptual similarity rather than distortion type.

### 2. Physics-Informed Domain Adaptation
Created underwater computer vision systems that incorporate physical models of light propagation to achieve robust performance across varying water conditions and depths.

**Key Innovation:** Beer-Lambert law-based augmentations integrated with contrastive learning for physics-aware feature representations.

### 3. Generative Priors for Enhancement
Leveraged generative models to learn powerful priors for image and video enhancement, enabling robust restoration across multiple degradation factors.

**Key Innovation:** Unsupervised adaptation of vision-language models and diffusion models for domain-specific tasks.

### 4. Test-Time Adaptation
Developed frameworks for adapting models during deployment without access to source training data, enabling continuous improvement in production environments.

**Key Innovation:** Source-free adaptation strategies for diffusion-based generative models.

**Applications Across Domains**

The research spans four major application areas:

1. **Image Quality Assessment (GRepQ)**
   - Data-efficient learning with minimal annotations
   - Zero-shot quality prediction
   - Generalization across distortion types

2. **Underwater Video Enhancement (UnDIVE)**
   - Physics-informed generative priors
   - Robust across water conditions
   - Temporal consistency in videos

3. **Underwater Object Tracking (MANTA)**
   - Physics-based contrastive learning
   - Novel evaluation metrics
   - State-of-the-art benchmark performance

4. **Virtual Try-On (Test-Time Adaptation)**
   - Source-free adaptation
   - Diffusion model specialization
   - Domain shift handling

**Unified Methodology**

All projects share a common methodological foundation:
- **Self-supervised learning** to reduce annotation requirements
- **Contrastive learning** for robust feature representations
- **Domain-specific priors** (physics or generative) for targeted generalization
- **Evaluation frameworks** with novel metrics for specific challenges

**Publications**

- 2 papers at WACV (1 oral - Top 3%)
- 1 paper in IEEE Transactions on Medical Imaging
- 2 papers under review (WACV 2026, ICLR 2026)

**Impact**

This research demonstrates that:
1. Self-supervised learning can effectively capture domain-invariant features
2. Physics-informed approaches enhance generalization in specific domains
3. Generative priors enable robust handling of complex degradations
4. Test-time adaptation provides practical deployment flexibility

**Technical Contributions**

- Novel self-supervised learning objectives for quality and tracking
- Physics-informed augmentation strategies
- Evaluation metrics for underwater computer vision
- Comprehensive benchmarking frameworks
- Source-free adaptation methodologies

**Future Directions**

The framework naturally extends to:
- Multimodal learning (vision-language models)
- Video understanding tasks
- Medical imaging applications
- Cross-domain transfer learning
- Real-time adaptation systems

**Tools:** PyTorch, Diffusion Models, CLIP, Contrastive Learning, Physics-Informed ML, Test-Time Adaptation

**Status:** Thesis submitted December 2025 | Colloquium completed November 2025
