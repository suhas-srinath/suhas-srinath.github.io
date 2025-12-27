---
title: "Source-Free Test-Time Adaptation for Virtual Try-On"
excerpt: "Novel adaptation framework enabling diffusion-based virtual try-on systems to handle domain shifts without source data access."
collection: portfolio
---

## Test-Time Adaptation for Diffusion-Based Virtual Try-On

**Project Overview**

This project addresses a critical challenge in deploying virtual try-on systems: maintaining performance when encountering new clothing styles, body types, or image conditions not present during training, all without access to the original training data.

**Problem Statement**

Virtual try-on systems based on diffusion models often struggle when deployed in real-world scenarios due to:
- Distribution shifts between training and deployment data
- Diverse clothing styles and patterns not seen during training
- Varying body types and poses
- Different image qualities and backgrounds
- Privacy concerns preventing access to source training data

**Key Innovation: Source-Free Adaptation**

**Why Source-Free?**
- Training data often proprietary or privacy-sensitive
- Model deployment environments have different data distributions
- Need for on-the-fly adaptation without retraining
- Enables continuous model improvement in production

**Technical Approach**

**Test-Time Adaptation Framework:**
- Adapts diffusion model parameters during inference
- No requirement for source domain data
- Leverages test-time signals for model adjustment
- Maintains generation quality while adapting to new domains

**Diffusion Model Specialization:**
- Tailored adaptation strategies for diffusion-based generators
- Preserves semantic consistency during try-on
- Handles clothing texture and pattern preservation
- Maintains realistic body-clothing interaction

**Comprehensive Evaluation**

- Extensive baseline comparisons with existing methods
- Novel evaluation framework for virtual try-on quality
- Metrics for both visual fidelity and semantic correctness
- Cross-domain generalization experiments

**Applications**

- **E-commerce:** Robust virtual try-on for diverse product catalogs
- **Fashion Retail:** Personalized visualization across customer segments
- **Mobile Apps:** On-device adaptation to user preferences
- **AR/VR:** Real-time virtual fitting in mixed reality applications

**Impact**

Enables practical deployment of virtual try-on systems that can:
- Adapt to new fashion trends without retraining
- Handle diverse customer body types and preferences
- Maintain performance across varying image conditions
- Respect data privacy by not requiring source data

**Technical Contributions**

- Source-free adaptation methodology for diffusion models
- Test-time optimization strategies for generative virtual try-on
- Comprehensive evaluation framework and metrics
- Analysis of domain shift challenges in virtual try-on

**Links**
- Paper (under review at ICLR 2026)
- Code (to be released upon acceptance)

**Tools:** PyTorch, Diffusion Models, Test-Time Adaptation, Generative AI, Domain Adaptation

**Status:** Under review at ICLR 2026

**Collaborators:** Joint work with researchers from IISc and Flipkart, Bengaluru
