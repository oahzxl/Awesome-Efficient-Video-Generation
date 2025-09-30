# Awesome Efficient Video Generation

<p>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg)](https://github.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Last Commit](https://img.shields.io/github/last-commit/oahzxl/Awesome-Efficient-Video-Generation.svg?style=flat&color=orange)](https://github.com/oahzxl/Awesome-Efficient-Video-Generation)
[![GitHub](https://img.shields.io/github/stars/oahzxl/Awesome-Efficient-Video-Generation.svg?style=social)](https://github.com/oahzxl/Awesome-Efficient-Video-Generation.git)  

</p>

A curated list of recent efficient video generation methods.


## 🗂️ Table of Contents
- [Long Context](#long-context)
- [Auto-Regressive](#auto-regressive)
- [Attention](#attention)
- [Caching](#caching)
- [VAE](#vae)
- [Hierarchical](#hierarchical)
- [Pruning](#pruning)
- [Architecture](#architecture)
- [Distillation](#distillation)
- [Quantization](#quantization)
- [Parallelism](#parallelism)
- [Scheduler](#scheduler)


## 📄 Papers

### Long Context
* LongLive: Real-time Interactive Long Video Generation \
2025.09 | [Paper](https://arxiv.org/abs/2509.22622) | [Code](https://github.com/NVlabs/LongLive) | [GitHub stars](https://img.shields.io/github/stars/NVlabs/LongLive?style=social)

* Longscape: Advancing Long-horizon Embodied World Models with Context-aware MoE \
2025.09 | [Paper](https://arxiv.org/abs/2509.21790) | [Code](https://github.com/tsinghua-fib-lab/Longscape) | [GitHub stars](https://img.shields.io/github/stars/tsinghua-fib-lab/Longscape?style=social)

* KeyWorld: Key Frame Reasoning Enables Effective and Efficient World Models \
2025.09 | [paper](https://arxiv.org/abs/2509.21027) | [code](https://anonymous.4open.science/r/Keyworld-E43D)

* Kling-Avatar: Grounding Multimodal Instructions for Cascaded Long-Duration Avatar Animation Synthesis \
2025.09 | [Paper](https://arxiv.org/abs/2509.09595)

* HunyuanWorld-Voyager: Technical Report \
2025.08 | [Paper](https://3d-models.hunyuan.tencent.com/voyager/voyager_en/assets/HYWorld_Voyager.pdf) | [Code](https://github.com/Tencent-Hunyuan/HunyuanWorld-Voyager) | ![GitHub stars](https://img.shields.io/github/stars/Tencent-Hunyuan/HunyuanWorld-Voyager?style=social)

* Mixture of Contexts for Long Video Generation \
2025.08 | [Paper](https://arxiv.org/abs/2508.21058)

* Macro-from-Micro Planning for High-Quality and Parallelized Autoregressive Long Video Generation \
2025.08 | [Paper](https://arxiv.org/abs/2508.03334) | [Code](https://github.com/Tele-AI/MMPL) | ![GitHub stars](https://img.shields.io/github/stars/Tele-AI/MMPL?style=social)

* LoViC: Efficient Long Video Generation with Context Compression \
2025.07 | [Paper](https://arxiv.org/abs/2507.12952)

* Video World Models with Long-term Spatial Memory \
2025.06 | [Paper](https://arxiv.org/abs/2506.05284)

* Context as Memory: Scene-Consistent Interactive Long Video Generation with Memory Retrieval \
2025.06 | [Paper](https://arxiv.org/abs/2506.03141)

* Memory-Efficient Visual Autoregressive Modeling with Scale-Aware KV Cache Compression \
2025.05 | [Paper](https://arxiv.org/abs/2505.19602) | [Code](https://github.com/StargazerX0/ScaleKV) | ![GitHub stars](https://img.shields.io/github/stars/StargazerX0/ScaleKV?style=social)

* Packing Input Frame Context in Next-Frame Prediction Models for Video Generation \
2025.04 | [Paper](https://arxiv.org/abs/2504.12626) | [Code](https://github.com/lllyasviel/FramePack) | ![GitHub stars](https://img.shields.io/github/stars/lllyasviel/FramePack?style=social)

* Long-Context Autoregressive Video Modeling with Next-Frame Prediction \
2025.03 | [Paper](https://arxiv.org/abs/2503.19325) | [Code](https://github.com/showlab/FAR) | ![GitHub stars](https://img.shields.io/github/stars/showlab/FAR?style=social)



### Auto-Regressive
* Longscape: Advancing Long-horizon Embodied World Models with Context-aware MoE \
2025.09 | [Paper](https://arxiv.org/abs/2509.21790) | [Code](https://github.com/tsinghua-fib-lab/Longscape) | [GitHub stars](https://img.shields.io/github/stars/tsinghua-fib-lab/Longscape?style=social)

* Macro-from-Micro Planning for High-Quality and Parallelized Autoregressive Long Video Generation \
2025.08 | [Paper](https://arxiv.org/abs/2508.03334) | [Code](https://github.com/Tele-AI/MMPL) | ![GitHub stars](https://img.shields.io/github/stars/Tele-AI/MMPL?style=social)

* Autoregressive Adversarial Post-Training for Real-Time Interactive Video Generation \
2025.06 | [Paper](https://arxiv.org/abs/2506.09350)

* Self Forcing: Bridging the Train-Test Gap in Autoregressive Video Diffusion \
2025.06 | [Paper](https://arxiv.org/abs/2506.08009) | [Code](https://github.com/guandeh17/Self-Forcing) | ![GitHub stars](https://img.shields.io/github/stars/guandeh17/Self-Forcing?style=social)

* Memory-Efficient Visual Autoregressive Modeling with Scale-Aware KV Cache Compression \
2025.05 | [Paper](https://arxiv.org/abs/2505.19602) | [Code](https://github.com/StargazerX0/ScaleKV) | ![GitHub stars](https://img.shields.io/github/stars/StargazerX0/ScaleKV?style=social)

* Packing Input Frame Context in Next-Frame Prediction Models for Video Generation \
2025.04 | [Paper](https://arxiv.org/abs/2504.12626) | [Code](https://github.com/lllyasviel/FramePack) | ![GitHub stars](https://img.shields.io/github/stars/lllyasviel/FramePack?style=social)

* From Slow Bidirectional to Fast Autoregressive Video Diffusion Models \
2024.12 | [Paper](https://arxiv.org/abs/2412.07772) | [Code](https://github.com/tianweiy/CausVid) | ![GitHub stars](https://img.shields.io/github/stars/tianweiy/CausVid?style=social)



### Attention
* LongLive: Real-time Interactive Long Video Generation \
2025.09 | [Paper](https://arxiv.org/abs/2509.22622) | [Code](https://github.com/NVlabs/LongLive) | [GitHub stars](https://img.shields.io/github/stars/NVlabs/LongLive?style=social)

* RAPID^3: Tri-Level Reinforced Acceleration Policies for Diffusion Transformer \
2025.09 | [Paper](https://arxiv.org/abs/2509.22323)

* Towards Interpretable and Efficient Attention: Compressing All by Contracting a Few \
2025.09 | [Paper](https://arxiv.org/abs/2509.16875)

* FG-Attn: Leveraging Fine-Grained Sparsity In Diffusion Transformers \
2025.09 | [Paper](https://arxiv.org/abs/2509.16518)

* Bidirectional Sparse Attention for Faster Video Diffusion Training \
2025.09 | [Paper](https://arxiv.org/abs/2509.01085)

* Compact Attention: Exploiting Structured Spatio-Temporal Sparsity for Fast Video Generation \
2025.08 | [Paper](https://arxiv.org/abs/2508.12969)

* Video-BLADE: Block-Sparse Attention Meets Step Distillation for Efficient Video Generation \
2025.08 | [Paper](https://arxiv.org/abs/2508.10774) | [Code](https://github.com/ziplab/VIDEO-BLADE) | ![GitHub stars](https://img.shields.io/github/stars/ziplab/VIDEO-BLADE?style=social)

* VMoBA: Mixture-of-Block Attention for Video Diffusion Models \
2025.06 | [Paper](https://arxiv.org/abs/2506.23858) | [Code](https://github.com/KwaiVGI/VMoBA) | ![GitHub stars](https://img.shields.io/github/stars/KwaiVGI/VMoBA?style=social)

* Radial Attention: O(nlogn) Sparse Attention with Energy Decay for Long Video Generation \
2025.06 | [Paper](https://arxiv.org/abs/2506.19852) | [Code](https://github.com/mit-han-lab/radial-attention) | ![GitHub stars](https://img.shields.io/github/stars/mit-han-lab/radial-attention?style=social)

* Astraea: A GPU-Oriented Token-wise Acceleration Framework for Video Diffusion Transformers \
2025.06 | [Paper](https://arxiv.org/abs/2506.05096)

* FPSAttention: Training-Aware FP8 and Sparsity Co-Design for Fast Video Diffusion \
2025.06 | [Paper](https://arxiv.org/abs/2506.04648)

* Sparse-vDiT: Unleashing the Power of Sparse Attention to Accelerate Video Diffusion Transformers \
2025.06 | [Paper](https://arxiv.org/abs/2506.03065)

* Sparse VideoGen2: Accelerate Video Generation with Sparse Attention via Semantic-Aware Permutation \
2025.05 | [Paper](https://arxiv.org/abs/2505.18875)

* VORTA: Efficient Video Diffusion via Routing Sparse Attention \
2025.05 | [Paper](https://arxiv.org/abs/2505.18809) | [Code](https://github.com/wenhao728/VORTA) | ![GitHub stars](https://img.shields.io/github/stars/wenhao728/VORTA?style=social)

* Faster Video Diffusion with Trainable Sparse Attention \
2025.05 | [Paper](https://arxiv.org/abs/2505.13389) | [Code](https://github.com/hao-ai-lab/FastVideo) | ![GitHub stars](https://img.shields.io/github/stars/hao-ai-lab/FastVideo?style=social)

* Training-free and Adaptive Sparse Attention for Efficient Long Video Generation \
2025.02 | [Paper](https://arxiv.org/abs/2502.21079)

* MoBA: Mixture of Block Attention for Long-Context LLMs \
2025.02 | [Paper](https://arxiv.org/abs/2502.13189) | [Code](https://github.com/MoonshotAI/MoBA) | ![GitHub stars](https://img.shields.io/github/stars/MoonshotAI/MoBA?style=social)

* Native Sparse Attention: Hardware-Aligned and Natively Trainable Sparse Attention \
2025.02 | [Paper](https://arxiv.org/abs/2502.11089)

* Fast Video Generation with Sliding Tile Attention \
2025.02 | [Paper](https://arxiv.org/abs/2502.04507) | [Code](https://github.com/hao-ai-lab/FastVideo) | ![GitHub stars](https://img.shields.io/github/stars/hao-ai-lab/FastVideo?style=social)

* Sparse VideoGen: Accelerating Video Diffusion Transformers with Spatial-Temporal Sparsity \
2025.02 | [Paper](https://arxiv.org/abs/2502.01776) | [Code](https://github.com/svg-project/Sparse-VideoGen) | ![GitHub stars](https://img.shields.io/github/stars/svg-project/Sparse-VideoGen?style=social)

* AsymRnR: Video Diffusion Transformers Acceleration with Asymmetric Reduction and Restoration \
2024.12 | [Paper](https://arxiv.org/abs/2412.11706) | [Code](https://github.com/wenhao728/AsymRnR) | ![GitHub stars](https://img.shields.io/github/stars/wenhao728/AsymRnR?style=social)



### Caching
* RAPID^3: Tri-Level Reinforced Acceleration Policies for Diffusion Transformer \
2025.09 | [Paper](https://arxiv.org/abs/2509.22323)

* SpecDiff: Accelerating Diffusion Model Inference with Self-Speculation \
2025.09 | [Paper](https://arxiv.org/abs/2509.13848)

* BWCache: Accelerating Video Diffusion Transformers through Block-Wise Caching \
2025.09 | [Paper](https://arxiv.org/abs/2509.13789)

* SpeCa: Accelerating Diffusion Transformers with Speculative Feature Caching \
2025.09 | [Paper](https://www.arxiv.org/abs/2509.11628) | [Code](https://github.com/Shenyi-Z/Cache4Diffusion) | ![GitHub stars](https://img.shields.io/github/stars/Shenyi-Z/Cache4Diffusion?style=social)

* Compute Only 16 Tokens in One Timestep: Accelerating Diffusion Transformers with Cluster-Driven Feature Caching \
2025.09 | [Paper](https://arxiv.org/abs/2509.10312) | [Code](https://github.com/Shenyi-Z/Cache4Diffusion) | ![GitHub stars](https://img.shields.io/github/stars/Shenyi-Z/Cache4Diffusion?style=social)

* ERTACache: Error Rectification and Timesteps Adjustment for Efficient Diffusion \
2025.08 | [Paper](https://arxiv.org/abs/2508.21091)

* Reusing Computation in Text-to-Image Diffusion for Efficient Generation of Image Sets \
2025.08 | [Paper](https://arxiv.org/abs/2508.21032)

* DiCache: Let Diffusion Model Determine Its Own Cache \
2025.08 | [Paper](https://arxiv.org/abs/2508.17356) | [Code](https://github.com/Bujiazi/DiCache) | ![GitHub stars](https://img.shields.io/github/stars/Bujiazi/DiCache?style=social)

* HiCache: Training-free Acceleration of Diffusion Models via Hermite Polynomial-based Feature Caching \
2025.08 | [Paper](https://arxiv.org/abs/2508.16984)

* OmniCache: A Trajectory-Oriented Global Perspective on Training-Free Cache Reuse for Diffusion Transformer Models \
2025.08 | [Paper](https://arxiv.org/abs/2508.16212)

* Forecast then Calibrate: Feature Caching as ODE for Efficient Diffusion Transformers \
2025.08 | [Paper](https://arxiv.org/abs/2508.16211)

* MixCache: Mixture-of-Cache for Video Diffusion Transformer Acceleration \
2025.08 | [Paper](https://arxiv.org/abs/2508.12691)

* TaoCache: Structure-Maintained Video Generation Acceleration \
2025.08 | [Paper](https://arxiv.org/abs/2508.08978)

* Sortblock: Similarity-Aware Feature Reuse for Diffusion Model \
2025.08 | [Paper](https://arxiv.org/abs/2508.00412) | [Code](https://github.com/PaddlePaddle/PaddleMIX/tree/develop/ppdiffusers/examples/Fast-Diffusers/Training-Free/sortblock) | ![GitHub stars](https://img.shields.io/github/stars/PaddlePaddle/PaddleMIX?style=social)

* PromptTea: Let Prompts Tell TeaCache the Optimal Threshold \
2025.07 | [Paper](https://arxiv.org/abs/2507.06739) | [Code](https://github.com/zishen-ucap/PromptTea) | ![GitHub stars](https://img.shields.io/github/stars/zishen-ucap/PromptTea?style=social)

* Less is Enough: Training-Free Video Diffusion Acceleration via Runtime-Adaptive Caching \
2024.07 | [Paper](https://arxiv.org/abs/2507.02860) | [Code](https://github.com/H-EmbodVis/EasyCache) | ![GitHub stars](https://img.shields.io/github/stars/H-EmbodVis/EasyCache?style=social)

* MagCache: Fast Video Generation with Magnitude-Aware Cache \
2025.06 | [Paper](https://arxiv.org/abs/2506.09045) | [Code](https://github.com/Zehong-Ma/MagCache) | ![GitHub stars](https://img.shields.io/github/stars/Zehong-Ma/MagCache?style=social)

* FastCache: Fast Caching for Diffusion Transformer Through Learnable Linear Approximation \
2025.05 | [Paper](https://arxiv.org/abs/2505.20353) | [Code](https://github.com/NoakLiu/FastCache-xDiT) | ![GitHub stars](https://img.shields.io/github/stars/NoakLiu/FastCache-xDiT?style=social)

* AB-Cache: Training-Free Acceleration of Diffusion Models via Adams-Bashforth Cached Feature Reuse \
2025.04 | [Paper](https://arxiv.org/abs/2504.10540)

* Model Reveals What to Cache: Profiling-Based Feature Reuse for Video Diffusion Models \
2025.04 | [Paper](https://arxiv.org/abs/2504.03140) | [Code](https://github.com/GeekGuru123/ProfilingDiT) | ![GitHub stars](https://img.shields.io/github/stars/GeekGuru123/ProfilingDiT?style=social)

* FEB-Cache: Frequency-Guided Exposure Bias Reduction for Enhancing Diffusion Transformer Caching \
2025.03 | [Paper](https://arxiv.org/abs/2503.07120)

* From Reusing to Forecasting: Accelerating Diffusion Models with TaylorSeers \
2025.03 | [Paper](https://arxiv.org/abs/2503.06923) | [Code](https://github.com/Shenyi-Z/TaylorSeer) | ![GitHub stars](https://img.shields.io/github/stars/Shenyi-Z/TaylorSeer?style=social)

* QuantCache: Adaptive Importance-Guided Quantization with Hierarchical Latent and Layer Caching for Video Generation \
2025.03 | [Paper](https://arxiv.org/abs/2503.06545) | [Code](https://github.com/JunyiWuCode/QuantCache) | ![GitHub stars](https://img.shields.io/github/stars/JunyiWuCode/QuantCache?style=social)

* UniCP: A Unified Caching and Pruning Framework for Efficient Video Generation \
2025.02 | [Paper](https://arxiv.org/abs/2502.04393)

* Accelerating Diffusion Transformer via Error-Optimized Cache \
2025.01 | [Paper](https://arxiv.org/abs/2501.19243)

* Accelerating Diffusion Transformers with Dual Feature Caching \
2024.12 | [Paper](https://arxiv.org/abs/2412.18911) | [Code](https://github.com/Shenyi-Z/DuCa) | ![GitHub stars](https://img.shields.io/github/stars/Shenyi-Z/DuCa?style=social)

* Timestep Embedding Tells: It's Time to Cache for Video Diffusion Model \
2024.11 | [Paper](https://arxiv.org/abs/2411.19108) | [Code](https://liewfeng.github.io/TeaCache) | ![GitHub stars](https://img.shields.io/github/stars/liewfeng/TeaCache?style=social)

* SmoothCache: A Universal Inference Acceleration Technique for Diffusion Transformers \
2024.11 | [Paper](https://arxiv.org/abs/2411.10510)

* Adaptive Caching for Faster Video Generation with Diffusion Transformers \
2024.11 | [Paper](https://arxiv.org/abs/2411.02397) | [Code](https://github.com/Shenyi-Z/ToCa) | ![GitHub stars](https://img.shields.io/github/stars/Shenyi-Z/ToCa?style=social)

* FasterCache: Training-Free Video Diffusion Model Acceleration with High Quality \
2024.10 | [Paper](https://arxiv.org/abs/2410.19355) | [Code](https://github.com/Vchitect/FasterCache) | ![GitHub stars](https://img.shields.io/github/stars/Vchitect/FasterCache?style=social)

* Accelerating Diffusion Transformers with Token-wise Feature Caching \
2024.10 | [Paper](https://arxiv.org/abs/2410.05317) | [Code](https://github.com/AdaCache-DiT/AdaCache) | ![GitHub stars](https://img.shields.io/github/stars/AdaCache-DiT/AdaCache?style=social)

* Real-Time Video Generation with Pyramid Attention Broadcast \
2024.08 | [Paper](https://arxiv.org/abs/2408.12588) | [Code](https://github.com/NUS-HPC-AI-Lab/VideoSys) | ![GitHub stars](https://img.shields.io/github/stars/NUS-HPC-AI-Lab/VideoSys?style=social)

* ∆-DiT: A Training-Free Acceleration Method Tailored for Diffusion Transformers \
2024.06 | [Paper](https://arxiv.org/abs/2406.01125)

* DiTFastAttn: Attention Compression for Diffusion Transformer Models \
2024.06 | [Paper](https://arxiv.org/abs/2406.08552) | [Code](https://github.com/thu-nics/DiTFastAttn) | ![GitHub stars](https://img.shields.io/github/stars/thu-nics/DiTFastAttn?style=social)

* Faster Diffusion via Temporal Attention Decomposition \
2024.04 | [Paper](https://arxiv.org/abs/2404.02747) | [Code](https://github.com/HaozheLiu-ST/T-GATE) | ![GitHub stars](https://img.shields.io/github/stars/HaozheLiu-ST/T-GATE?style=social)



### VAE
* REGEN: Learning Compact Video Embedding with (Re-)Generative Decoder \
2025.03 | [Paper](https://arxiv.org/abs/2503.08665)



### Hierarchical
* Waver: Wave Your Way to Lifelike Video Generation \
2025.08 | [Paper](https://arxiv.org/abs/2508.15761) | [Code](https://github.com/FoundationVision/Waver) | ![GitHub stars](https://img.shields.io/github/stars/FoundationVision/Waver?style=social)

* SRDiffusion: Accelerate Video Diffusion Inference via Sketching-Rendering Cooperation \
2025.05 | [Paper](https://arxiv.org/abs/2505.19151)

* VGDFR: Diffusion-based Video Generation with Dynamic Latent Frame Rate \
2025.04 | [Paper](https://arxiv.org/abs/2504.12259) | [Code](https://github.com/thu-nics/VGDFR) | ![GitHub stars](https://img.shields.io/github/stars/thu-nics/VGDFR?style=social)

* Training-free Diffusion Acceleration with Bottleneck Sampling \
2025.03 | [Paper](https://arxiv.org/abs/2503.18940)

* TPDiff: Temporal Pyramid Video Diffusion Model \
2025.03 | [Paper](https://arxiv.org/abs/2503.09566) | [Code](https://github.com/showlab/TPDiff) | ![GitHub stars](https://img.shields.io/github/stars/showlab/TPDiff?style=social)

* DLFR-VAE: Dynamic Latent Frame Rate VAE for Video Generation \
2025.02 | [Paper](https://arxiv.org/abs/2502.11897)

* Collaborative Decoding Makes Visual Auto-Regressive Modeling Efficient \
2024.11 | [Paper](https://arxiv.org/abs/2411.17787) | [Code](https://github.com/czg1225/CoDe) | ![GitHub stars](https://img.shields.io/github/stars/czg1225/CoDe?style=social)

* Pyramidal Flow Matching for Efficient Video Generative Modeling \
2024.10 | [Paper](https://arxiv.org/abs/2410.05954) | [Code](https://github.com/jy0205/Pyramid-Flow) | ![GitHub stars](https://img.shields.io/github/stars/jy0205/Pyramid-Flow?style=social)



### Pruning
* SlimDiff: Training-Free, Activation-Guided Hands-free Slimming of Diffusion Models \
2025.09 | [Paper](https://arxiv.org/abs/2509.21498)

* Do Sparse Subnetworks Exhibit Cognitively Aligned Attention? Effects of Pruning on Saliency Map Fidelity, Sparsity, and Concept Coherence \
2025.09 | [Paper](https://arxiv.org/abs/2509.21387)

* HERO: Hierarchical Extrapolation and Refresh for Efficient World Models \
2025.08 | [Paper](https://arxiv.org/abs/2508.17588)

* TokensGen: Harnessing Condensed Tokens for Long Video Generation \
2025.07 | [Paper](https://arxiv.org/abs/2507.15728) | [Code](https://github.com/Vicky0522/TokensGen) | ![GitHub stars](https://img.shields.io/github/stars/Vicky0522/TokensGen?style=social)

* Astraea: A GPU-Oriented Token-wise Acceleration Framework for Video Diffusion Transformers \
2025.06 | [Paper](https://arxiv.org/abs/2506.05096)

* D2iT: Dynamic Diffusion Transformer for Accurate Image Generation \
2025.04 | [Paper](https://arxiv.org/abs/2504.09454)

* FlexiDiT: Your Diffusion Transformer Can Easily Generate High-Quality Samples with Less Compute \
2025.02 | [Paper](https://arxiv.org/abs/2502.20126)

* UniCP: A Unified Caching and Pruning Framework for Efficient Video Generation \
2025.02 | [Paper](https://arxiv.org/abs/2502.04393)

* AsymRnR: Video Diffusion Transformers Acceleration with Asymmetric Reduction and Restoration \
2024.12 | [Paper](https://arxiv.org/abs/2412.11706) | [Code](https://github.com/wenhao728/AsymRnR) | ![GitHub stars](https://img.shields.io/github/stars/wenhao728/AsymRnR?style=social)

* TinyFusion: Diffusion Transformers Learned Shallow \
2024.12 | [Paper](https://arxiv.org/abs/2412.01199) | [Code](https://github.com/VainF/TinyFusion) | ![GitHub stars](https://img.shields.io/github/stars/VainF/TinyFusion?style=social)

* Importance-Based Token Merging for Efficient Image and Video Generation \
2024.11 | [Paper](https://arxiv.org/abs/2411.16720)

* Token Merging for Fast Stable Diffusion \
2023.03 | [Paper](https://arxiv.org/abs/2303.17604) | [Code](https://github.com/dbolya/tomesd) | ![GitHub stars](https://img.shields.io/github/stars/dbolya/tomesd?style=social)



### Architecture
* Improving Video Diffusion Transformer Training by Multi-Feature Fusion and Alignment from Self-Supervised Vision Encoders \
2025.09 | [Paper](https://arxiv.org/abs/2509.09547)

* Test-Time Training Done Right \
2025.05 | [Paper](https://arxiv.org/abs/2505.23884) | [Code](https://github.com/a1600012888/LaCT) | ![GitHub stars](https://img.shields.io/github/stars/a1600012888/LaCT?style=social)

* One-Minute Video Generation with Test-Time Training \
2025.04 | [Paper](https://arxiv.org/abs/2504.05298) | [Code](https://github.com/test-time-training/ttt-video-dit) | ![GitHub stars](https://img.shields.io/github/stars/test-time-training/ttt-video-dit?style=social)



### Distillation
* DistillKac: Few-Step Image Generation via Damped Wave Equations \
2025.09 | [Paper](https://arxiv.org/abs/2509.21513)

* SD3.5-Flash: Distribution-Guided Distillation of Generative Flows \
2025.09 | [Paper](https://arxiv.org/abs/2509.21318)

* Q-Sched: Pushing the Boundaries of Few-Step Diffusion Models with Quantization-Aware Scheduling \
2025.09 | [Paper](https://arxiv.org/abs/2509.01624)

* POSE: Phased One-Step Adversarial Equilibrium for Video Diffusion Models \
2025.08 | [Paper](https://arxiv.org/abs/2508.21019)

* Ouroboros: Single-step Diffusion Models for Cycle-consistent Forward and Inverse Rendering \
2025.08 | [Paper](https://arxiv.org/abs/2508.14461)

* Dual-Expert Consistency Model for Efficient and High-Quality Video Generation \
2025.06 | [Paper](https://arxiv.org/abs/2506.03123) | [Code](https://github.com/Vchitect/DCM) | ![GitHub stars](https://img.shields.io/github/stars/Vchitect/DCM?style=social)

* QuantCache: Adaptive Importance-Guided Quantization with Hierarchical Latent and Layer Caching for Video Generation \
2025.03 | [Paper](https://arxiv.org/abs/2503.06545) | [Code](https://github.com/JunyiWuCode/QuantCache) | ![GitHub stars](https://img.shields.io/github/stars/JunyiWuCode/QuantCache?style=social)

* Distilling Diffusion Models into Conditional GANs \
2024.05 | [Paper](https://arxiv.org/abs/2405.05967)

* Improved Distribution Matching Distillation for Fast Image Synthesis \
2024.05 | [Paper](https://arxiv.org/abs/2405.14867) | [Code](https://github.com/tianweiy/DMD2) | ![GitHub stars](https://img.shields.io/github/stars/tianweiy/DMD2?style=social)

* Fast High-Resolution Image Synthesis with Latent Adversarial Diffusion Distillation \
2024.03 | [Paper](https://arxiv.org/abs/2403.12015)

* LCM-LoRA: A Universal Stable-Diffusion Acceleration Module \
2023.11 | [Paper](https://arxiv.org/abs/2311.05556) | [Code](https://github.com/luosiallen/latent-consistency-model) | ![GitHub stars](https://img.shields.io/github/stars/luosiallen/latent-consistency-model?style=social)

* One-step Diffusion with Distribution Matching Distillation \
2023.11 | [Paper](https://arxiv.org/abs/2311.18828)

* Adversarial Diffusion Distillation \
2023.11 | [Paper](https://arxiv.org/abs/2311.17042)



### Quantization
* Q-Sched: Pushing the Boundaries of Few-Step Diffusion Models with Quantization-Aware Scheduling \
2025.09 | [Paper](https://arxiv.org/abs/2509.01624)

* FPSAttention: Training-Aware FP8 and Sparsity Co-Design for Fast Video Diffusion \
2025.06 | [Paper](https://arxiv.org/abs/2506.04648)

* SVDQuant: Absorbing Outliers by Low-Rank Components for 4-Bit Diffusion Models \
2024.11 | [Paper](https://arxiv.org/abs/2411.05007) | [Code](https://github.com/nunchaku-tech/nunchaku) | ![GitHub stars](https://img.shields.io/github/stars/nunchaku-tech/nunchaku?style=social)

* ViDiT-Q: Efficient and Accurate Quantization of Diffusion Transformers for Image and Video Generation \
2024.06 | [Paper](https://arxiv.org/abs/2406.02540) | [Code](https://github.com/thu-nics/ViDiT-Q) | ![GitHub stars](https://img.shields.io/github/stars/thu-nics/ViDiT-Q?style=social)



### Parallelism
* STADI: Fine-Grained Step-Patch Diffusion Parallelism for Heterogeneous GPUs \
2025.09 | [Paper](https://arxiv.org/abs/2509.04719)

* KnapFormer: An Online Load Balancer for Efficient Diffusion Transformers Training \
2025.08 | [Paper](https://arxiv.org/abs/2508.06001) | [Code](https://github.com/Kai-46/KnapFormer/) | ![GitHub stars](https://img.shields.io/github/stars/Kai-46/KnapFormer?style=social)

* DDiT: Dynamic Resource Allocation for Diffusion Transformer Model Serving \
2025.06 | [Paper](https://arxiv.org/abs/2506.13497)

* xDiT: an Inference Engine for Diffusion Transformers (DiTs) with Massive Parallelism \
2024.05 | [Paper](https://arxiv.org/abs/2411.01738) | [Code](https://github.com/xdit-project/xDiT) | ![GitHub stars](https://img.shields.io/github/stars/xdit-project/xDiT?style=social)

* PipeFusion: Patch-level Pipeline Parallelism for Diffusion Transformers Inference \
2024.05 | [Paper](https://arxiv.org/abs/2405.14430) | [Code](https://github.com/xdit-project/xDiT) | ![GitHub stars](https://img.shields.io/github/stars/xdit-project/xDiT?style=social)

* DSP: Dynamic Sequence Parallelism for Multi-Dimensional Transformers \
2024.03 | [Paper](https://arxiv.org/abs/2403.10266) | [Code](https://github.com/NUS-HPC-AI-Lab/VideoSys) | ![GitHub stars](https://img.shields.io/github/stars/NUS-HPC-AI-Lab/VideoSys?style=social)

* DistriFusion: Distributed Parallel Inference for High-Resolution Diffusion Models \
2024.02 | [Paper](https://arxiv.org/abs/2402.19481) | [Code](https://github.com/mit-han-lab/distrifuser) | ![GitHub stars](https://img.shields.io/github/stars/mit-han-lab/distrifuser?style=social)



### Scheduler
* ContextFlow: Training-Free Video Object Editing via Adaptive Context Enrichment \
2025.09 | [Paper](https://arxiv.org/abs/2509.17818)

* A-FloPS: Accelerating Diffusion Sampling with Adaptive Flow Path Sampler \
2025.09 | [Paper](https://arxiv.org/abs/2509.00036)

* Pretrained Diffusion Models Are Inherently Skipped-Step Samplers \
2025.08 | [Paper](https://arxiv.org/abs/2508.15233)

* Disentanglement in T-space for Faster and Distributed Training of Diffusion Models with Fewer Latent-states \
2025.08 | [Paper](https://arxiv.org/abs/2508.14413)

* Pyramidal Flow Matching for Efficient Video Generative Modeling \
2024.10 | [Paper](https://arxiv.org/abs/2410.05954) | [Code](https://github.com/jy0205/Pyramid-Flow) | ![GitHub stars](https://img.shields.io/github/stars/jy0205/Pyramid-Flow?style=social)

* AsyncDiff: Parallelizing Diffusion Models by Asynchronous Denoising \
2024.06 | [Paper](https://arxiv.org/abs/2406.06911) | [Code](https://github.com/czg1225/AsyncDiff) | ![GitHub stars](https://img.shields.io/github/stars/czg1225/AsyncDiff?style=social)

* AdaDiff: Adaptive Step Selection for Fast Diffusion Models \
2023.11 | [Paper](https://arxiv.org/abs/2311.14768)

* Latent Consistency Models: Synthesizing High-Resolution Images with Few-Step Inference \
2023.10 | [Paper](https://arxiv.org/abs/2310.04378) | [Code](https://github.com/luosiallen/latent-consistency-model) | ![GitHub stars](https://img.shields.io/github/stars/luosiallen/latent-consistency-model?style=social)

* DPM-Solver++: Fast Solver for Guided Sampling of Diffusion Probabilistic Models \
2022.11 | [Paper](https://arxiv.org/abs/2211.01095) | [Code](https://github.com/LuChengTHU/dpm-solver) | ![GitHub stars](https://img.shields.io/github/stars/LuChengTHU/dpm-solver?style=social)

* Flow Matching for Generative Modeling \
2022.10 | [Paper](https://arxiv.org/abs/2210.02747)

* Flow Straight and Fast: Learning to Generate and Transfer Data with Rectified Flow \
2022.09 | [Paper](https://arxiv.org/abs/2209.03003) | [Code](https://github.com/gnobitab/RectifiedFlow) | ![GitHub stars](https://img.shields.io/github/stars/gnobitab/RectifiedFlow?style=social)

* DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps \
2022.06 | [Paper](https://arxiv.org/abs/2206.00927) | [Code](https://github.com/LuChengTHU/dpm-solver) | ![GitHub stars](https://img.shields.io/github/stars/LuChengTHU/dpm-solver?style=social)

* Denoising Diffusion Implicit Models \
2020.10 | [Paper](https://arxiv.org/abs/2010.02502) | [Code](https://github.com/ermongroup/ddim) | ![GitHub stars](https://img.shields.io/github/stars/ermongroup/ddim?style=social)
