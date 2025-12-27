---
title: "MANTA: Physics-Informed Underwater Object Tracking"
excerpt: "Novel underwater tracking framework combining physics-based augmentations with contrastive learning. State-of-the-art results across multiple benchmarks."
collection: portfolio
---

## Physics-Informed Generalized Underwater Object Tracking

**Project Overview**

MANTA tackles the unique challenges of underwater object tracking where wavelength-dependent attenuation and scattering severely distort object appearance across depths and water conditions. Existing terrestrial trackers fail to generalize to these physics-driven degradations.

**Core Innovation**

**Dual-Positive Contrastive Learning:**
- Couples temporal consistency with physics-informed augmentations
- Integrates Beer-Lambert law-based transformations
- Learns features robust to both temporal dynamics and underwater distortions
- Novel augmentation strategy that simulates realistic underwater degradations

**Multi-Stage Tracking Pipeline:**
- Motion-based tracking augmented with physics-informed secondary association
- Geometric consistency and appearance similarity for re-identification
- Handles occlusion and drift scenarios effectively
- Adaptive to varying underwater conditions

**Novel Evaluation Metrics**

Introduced two new metrics to complement standard IoU:
- **Center-Scale Consistency (CSC):** Measures geometric fidelity of tracked bounding boxes
- **Geometric Alignment Score (GAS):** Assesses alignment quality under challenging conditions

**Technical Approach**

- Physics-informed data augmentation based on underwater light propagation models
- Contrastive learning framework tailored for underwater scenarios
- Multi-stage association algorithm for robust tracking
- Generalization across diverse water types and visibility conditions

**Benchmark Performance**

Achieved state-of-the-art results on multiple underwater tracking datasets:
- **WebUOT-1M:** Large-scale underwater object tracking benchmark
- **UOT32:** 32 diverse underwater sequences
- **UTB180:** 180 challenging underwater scenarios
- **UWCOT220:** 220 underwater tracking sequences

**Applications**

- Marine biology research and species monitoring
- Underwater robotics and autonomous vehicles
- Subsea infrastructure inspection
- Ocean exploration and documentation

**Links**
- [Paper (arXiv)](https://arxiv.org/abs/2511.23405)
- Code (to be released upon publication)

**Technologies:** PyTorch, Beer-Lambert Law, Contrastive Learning, Object Tracking (YOLO, DETR), Physics-Informed ML

**Status:** Under review at WACV 2026
