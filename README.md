# Awesome Efficient Video Generation

<p>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg)](https://github.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Last Commit](https://img.shields.io/github/last-commit/xuyang-liu16/Awesome-Diffusion-Acceleration.svg?style=flat&color=orange)](https://github.com/xuyang-liu16/Awesome-Diffusion-Acceleration)
[![GitHub](https://img.shields.io/github/stars/NUS-HPC-AI-Lab/Awesome-Efficient-Video-Generation.svg?style=social)](https://github.com/NUS-HPC-AI-Lab/Awesome-Efficient-Video-Generation.git)  

</p>

A curated list of recent efficient video generation methods.

## 🗂️ Table of Contents
- [Scheduler](#scheduler)
- [Distillation](#distillation)
- [Quantization](#quantization)
- [Caching](#caching)
- [Pruning](#pruning)
- [Parallelism](#parallelism)
- [Others](#others)

## 📄 Papers

### Scheduler

* [Pyramidal Flow Matching for Efficient Video Generative Modeling](https://arxiv.org/abs/2410.05954) \
arXiv 2024 | [Paper](https://arxiv.org/abs/2410.05954) | [Code](https://github.com/jy0205/Pyramid-Flow) | ![GitHub stars](https://img.shields.io/github/stars/jy0205/Pyramid-Flow?style=social)

* [AdaDiff: Adaptive Step Selection for Fast Diffusion Models](https://arxiv.org/pdf/2311.14768) \
arXiv 2023 | [Paper](https://arxiv.org/pdf/2311.14768)

* [Latent Consistency Models: Synthesizing High-Resolution Images with Few-Step Inference](https://arxiv.org/abs/2310.04378) \
ICLR 2024 | [Paper](https://arxiv.org/abs/2310.04378) | [Code](https://github.com/luosiallen/latent-consistency-model) | ![GitHub stars](https://img.shields.io/github/stars/luosiallen/latent-consistency-model?style=social)

* [DPM-Solver++: Fast Solver for Guided Sampling of Diffusion Probabilistic Models](https://arxiv.org/abs/2211.01095) \
arXiv 2022 | [Paper](https://arxiv.org/abs/2211.01095) | [Code](https://github.com/LuChengTHU/dpm-solver) | ![GitHub stars](https://img.shields.io/github/stars/LuChengTHU/dpm-solver?style=social)

* [Flow Matching for Generative Modeling](https://arxiv.org/abs/2210.02747) \
ICLR 2023 (Spotlight) | [Paper](https://arxiv.org/abs/2210.02747)

* [Flow Straight and Fast: Learning to Generate and Transfer Data with Rectified Flow](https://arxiv.org/abs/2209.03003) \
ICLR 2023 (Spotlight) | [Paper](https://arxiv.org/abs/2209.03003) | [Code](https://github.com/gnobitab/RectifiedFlow) | ![GitHub stars](https://img.shields.io/github/stars/gnobitab/RectifiedFlow?style=social)

* [DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps](https://arxiv.org/abs/2206.00927) \
NeurIPS 2022 | [Paper](https://arxiv.org/abs/2206.00927) | [Code](https://github.com/LuChengTHU/dpm-solver) | ![GitHub stars](https://img.shields.io/github/stars/LuChengTHU/dpm-solver?style=social)

* [Denoising Diffusion Implicit Models](https://arxiv.org/pdf/2010.02502) \
ICLR 2021 | [Paper](https://arxiv.org/pdf/2010.02502) | [Code](https://github.com/ermongroup/ddim) | ![GitHub stars](https://img.shields.io/github/stars/ermongroup/ddim?style=social)

### Distillation

* [Distilling Diffusion Models into Conditional GANs](https://arxiv.org/abs/2405.05967) \
ECCV 2024 | [Paper](https://arxiv.org/abs/2405.05967)

* [Improved Distribution Matching Distillation for Fast Image Synthesis](https://arxiv.org/abs/2405.14867) \
NeurIPS 2024 (Oral) | [Paper](https://arxiv.org/abs/2405.14867) | [Code](https://github.com/tianweiy/DMD2) | ![GitHub stars](https://img.shields.io/github/stars/tianweiy/DMD2?style=social)

* [Fast High-Resolution Image Synthesis with Latent Adversarial Diffusion Distillation](https://arxiv.org/abs/2403.12015) \
arXiv 2024 | [Paper](https://arxiv.org/abs/2403.12015)

* [LCM-LoRA: A Universal Stable-Diffusion Acceleration Module](https://arxiv.org/abs/2311.05556) \
arXiv 2023 | [Paper](https://arxiv.org/abs/2311.05556) | [Code](https://github.com/luosiallen/latent-consistency-model) | ![GitHub stars](https://img.shields.io/github/stars/luosiallen/latent-consistency-model?style=social)

* [One-step Diffusion with Distribution Matching Distillation
](https://arxiv.org/abs/2311.18828) \
CVPR 2024 | [Paper](https://arxiv.org/abs/2311.18828)

* [Adversarial Diffusion Distillation](https://arxiv.org/abs/2311.17042) \
ECCV 2024 | [Paper](https://arxiv.org/abs/2311.17042)


### Quantization


### Caching

* [Adaptive Caching for Faster Video Generation with Diffusion Transformers](https://arxiv.org/abs/2411.02397) \
arXiv 2024 | [Paper](https://arxiv.org/abs/2411.02397) | [Code](https://github.com/Shenyi-Z/ToCa) | ![GitHub stars](https://img.shields.io/github/stars/Shenyi-Z/ToCa?style=social)

* [FasterCache: Training-Free Video Diffusion Model Acceleration with High Quality](https://arxiv.org/abs/2410.19355) \
arXiv 2024 | [Paper](https://arxiv.org/abs/2410.19355) | [Code](https://github.com/Vchitect/FasterCache) | ![GitHub stars](https://img.shields.io/github/stars/Vchitect/FasterCache?style=social)

* [Accelerating Diffusion Transformers with Token-wise Feature Caching](https://arxiv.org/abs/2410.05317) \
arXiv 2024 | [Paper](https://arxiv.org/abs/2410.05317) | [Code](https://github.com/AdaCache-DiT/AdaCache) | ![GitHub stars](https://img.shields.io/github/stars/AdaCache-DiT/AdaCache?style=social)

* [Real-Time Video Generation with Pyramid Attention Broadcast](https://arxiv.org/abs/2408.12588) \
arXiv 2024 | [Paper](https://arxiv.org/abs/2408.12588) | [Code](https://github.com/NUS-HPC-AI-Lab/VideoSys) | ![GitHub stars](https://img.shields.io/github/stars/NUS-HPC-AI-Lab/VideoSys?style=social)

* [∆-DiT: A Training-Free Acceleration Method Tailored for Diffusion Transformers](https://arxiv.org/abs/2406.01125) \
arXiv 2024 | [Paper](https://arxiv.org/abs/2406.01125)

* [DiTFastAttn: Attention Compression for Diffusion Transformer Models](https://arxiv.org/abs/2406.08552) \
arXiv 2024 | [Paper](https://arxiv.org/abs/2406.08552) | [Code](https://github.com/thu-nics/DiTFastAttn) | ![GitHub stars](https://img.shields.io/github/stars/thu-nics/DiTFastAttn?style=social)

* [Faster Diffusion via Temporal Attention Decomposition](https://arxiv.org/abs/2404.02747v2) \
arXiv 2024 | [Paper](https://arxiv.org/abs/2404.02747v2) | [Code](https://github.com/HaozheLiu-ST/T-GATE) | ![GitHub stars](https://img.shields.io/github/stars/HaozheLiu-ST/T-GATE?style=social)

* [Cross-Attention Makes Inference Cumbersome in Text-to-Image Diffusion Models](https://arxiv.org/abs/2404.02747v1) \
arXiv 2024 | [Paper](https://arxiv.org/abs/2404.02747v1) | [Code](https://github.com/HaozheLiu-ST/T-GATE) | ![GitHub stars](https://img.shields.io/github/stars/HaozheLiu-ST/T-GATE?style=social)


### Pruning


### Parallelism

* [xDiT: an Inference Engine for Diffusion Transformers (DiTs) with Massive Parallelism](https://arxiv.org/abs/2405.14430) \
arXiv 2024 | [Paper](https://arxiv.org/abs/2405.14430) | [Code](https://github.com/xdit-project/xDiT) | ![GitHub stars](https://img.shields.io/github/stars/xdit-project/xDiT?style=social)

* [PipeFusion: Patch-level Pipeline Parallelism for Diffusion Transformers Inference](https://arxiv.org/abs/2405.14430) \
arXiv 2024 | [Paper](https://arxiv.org/abs/2405.14430) | [Code](https://github.com/xdit-project/xDiT) | ![GitHub stars](https://img.shields.io/github/stars/xdit-project/xDiT?style=social)

* [DSP: Dynamic Sequence Parallelism for Multi-Dimensional Transformers](https://arxiv.org/abs/2403.10266) \
arXiv 2024 | [Paper](https://arxiv.org/abs/2403.10266) | [Code](https://github.com/NUS-HPC-AI-Lab/VideoSys) | ![GitHub stars](https://img.shields.io/github/stars/NUS-HPC-AI-Lab/VideoSys?style=social)

* [DistriFusion: Distributed Parallel Inference for High-Resolution Diffusion Models](https://arxiv.org/abs/2402.19481) \
CVPR 2024 (Highlight) | [Paper](https://arxiv.org/abs/2402.19481) | [Code](https://github.com/mit-han-lab/distrifuser) | ![GitHub stars](https://img.shields.io/github/stars/mit-han-lab/distrifuser?style=social)



### Others
