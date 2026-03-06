---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am a M.S. student in Software Engineering at [Xi'an Jiaotong University (XJTU)](https://www.xjtu.edu.cn/), advised by Prof. [Yihong Gong](https://scholar.google.com/citations?user=GDHsOtIAAAAJ). I received my B.Eng. in Mathematics and Statistics from XJTU in 2024.

My research interests include **Embodied Intelligence & Spatial Reasoning** (VLA, temporal-spatial understanding, reinforcement learning), **Generative AI** (unified visual generation, video/3D generation), and **Vision-Language Models** (multimodal large models, spatial perception).

I am currently a Research Intern at **ByteDance Seed**, working on unified video generation and embodied planning (VLA).


# 🔥 News
- *2026.02*: &nbsp; 🎉 One paper (**ReMoT**) accepted by **CVPR 2026**!
- *2025.11*: &nbsp; Started research internship at **ByteDance Seed**.
- *2025.06*: &nbsp; Started research internship at **Microsoft Research Asia (MSRA)**.
- *2025.01*: &nbsp; Started research internship at **Alibaba DAMO Academy**.
- *2024.09*: &nbsp; 🎉 One paper (**PAP**) accepted by **NeurIPS 2024**!


# 📝 Publications

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVPR 2026</div>
      <img src='images/remot_teaser.png' alt="ReMoT" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**ReMoT: Reinforcement Learning with Motion Contrast Triplets**

**Cong Wan**, et al.

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026*

[**Paper**](#) \| [**Code**](#)

- Proposes a multi-expert collaborative framework that automatically constructs the ReMoT-16K motion contrast triplet dataset (16.5k samples), avoiding the 55% format error rate of direct VLM generation.
- Designs a SFT↔GRPO hybrid training paradigm with logical consistency rewards; achieves **25.1%** improvement in spatial-temporal reasoning, with a 4B model surpassing Qwen3-VL-30B (7.5× larger) on VLM2/VSI benchmarks.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVPR 2025 Under Review</div>
      <img src='images/voxel_teaser.png' alt="Voxel World Model" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**Voxel-based World Model for Dynamic Scene Consistency**

**Cong Wan**, et al.

*Under Review at CVPR 2025*

- Constructs 10k simulation videos (2000 frames each) with 64³ voxel annotations on Minetest; designs 23 action combination evaluation scenarios.
- Supports voxel-pixel joint training, achieving **23%** consistency improvement over SOTA.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICLR 2025 Under Review</div>
      <img src='images/gridshow_teaser.png' alt="GridShow" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**GridShow: Omni Visual Generation**

**Cong Wan**, et al.

*Under Review at ICLR 2025*

[**Code**](https://github.com/vancyland/GRID)

- Presents a unified framework for omni visual generation tasks, built on 35k high-quality video-text pairs.

  </div>
</div>

- **Prompt-Agnostic Adversarial Perturbation for Customized Diffusion Models**, **Cong Wan**, et al. *NeurIPS 2024*. \[[Project Page](https://vancyland.github.io/Prompt-Agnostic-Adversarial-Perturbation-for-Customized-Diffusion-Models.github.io/)\] \[[Code](https://github.com/vancyland/Prompt-Agnostic-Adversarial-Perturbation-for-Customized-Diffusion-Models.github.io)\]


# 💼 Internships

- *2025.11 - 2026.03* &nbsp; <img src="images/bytedance_logo.png" alt="ByteDance" height="20" style="vertical-align:middle;"> &nbsp; **Research Intern**, Multimodal Research, ByteDance Seed
  - **Unified VLA**: Built a unified video generation and embodied planning framework based on the StarVLA architecture, training Wan VAE, DiT, and Action Head from scratch. Integrated 10+ robot and video datasets (Bridge, RT-1, IOAI, Bytemini PPAA, AGIBot, Ego4D, Fourier ActionNet, RoboCoin, RoboMind, OpenVid-1M) to enable joint modeling of embodied manipulation and natural video, improving cross-task generalization.
  - **ReMoT** *(CVPR 2026)*: Designed and led the full pipeline from dataset construction to reinforcement learning training; see Publications above.

- *2025.01 - 2025.10* &nbsp; <img src="images/alibaba_logo.png" alt="Alibaba" height="20" style="vertical-align:middle;"> &nbsp; **Research Intern**, Basic Vision Lab, Alibaba DAMO Academy
  - **Spatial Perception Evaluation & Generation**: Built a four-dimensional evaluation system (geometric scale, centric orientation, scene viewpoint, embodied operation) based on ScanNet/NuScenes/AgiBot; trained a Geometry-Aligned VAE for improved 3D-aware generation.
  - **LuminaEdit Dataset**: Constructed a tens-of-millions-scale editing dataset covering grounding, local editing, style transfer, and watermark removal; integrated 80M inpainting samples, achieving **19%** realism improvement over IC-Light.

- *2025.06 - 2025.09* &nbsp; <img src="images/msra_logo.png" alt="MSRA" height="20" style="vertical-align:middle;"> &nbsp; **Research Intern**, Machine Learning Group, Microsoft Research Asia (MSRA)
  - Built 10k Minetest simulation videos (2000 frames each) with 64³ voxel annotations; designed 23 action combination evaluation scenarios; supported voxel-pixel joint training, achieving **23%** consistency improvement over SOTA *(corresponding to CVPR 2025 submission)*.

- *2024.05 - 2025.01* &nbsp; <img src="images/xjtu_logo.png" alt="XJTU" height="20" style="vertical-align:middle;"> &nbsp; **Graduate Researcher**, Yihong Gong Lab, Xi'an Jiaotong University — Led GRID unified visual generation project (ICLR 2025 under review), constructing 35k high-quality video-text pairs.


# 🎓 Education

- *2024 - 2027 (expected)* &nbsp; M.Eng. in Software Engineering, **Xi'an Jiaotong University**
  - Advisor: Prof. Yihong Gong

- *2020 - 2024* &nbsp; B.Eng. in Mathematics and Statistics, **Xi'an Jiaotong University**
