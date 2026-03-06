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

I am a M.S. student in Computer Science and Technology at the School of Software Engineering, [Xi'an Jiaotong University (XJTU)](https://www.xjtu.edu.cn/), advised by Prof. [Yihong Gong](https://scholar.google.com/citations?user=GDHsOtIAAAAJ). I received my B.S. in Mathematics from the School of Mathematics and Statistics, XJTU in 2024. I am a recipient of the **National Scholarship for Graduate Students (Top 1%)** and the **Outstanding Student Award** at XJTU.

My research interests include **Embodied Intelligence & Spatial Reasoning** (VLA, temporal-spatial understanding, reinforcement learning), **Generative AI** (unified visual generation, video/3D generation), and **Vision-Language Models** (multimodal large models, spatial perception).

I am currently a Research Intern at **ByteDance Seed** (Seed-Robotics), working on VLM spatial-temporal reasoning and unified embodied VLA systems.


# 🔥 News
- *2026.02*: &nbsp;🎉 One paper (**ReMoT**) accepted by **CVPR 2026**!
- *2025.11*: &nbsp;Started research internship at **ByteDance Seed** (Seed-Robotics).
- *2025.06*: &nbsp;Started research internship at **Microsoft Research Asia (MSRA)**.
- *2024.12*: &nbsp;Started research internship at **Alibaba DAMO Academy**.
- *2024.09*: &nbsp;🎉 One paper (**PAP**) accepted by **NeurIPS 2024**!


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

- Constructs the **ReMoT-16K** motion contrast triplet dataset via a multi-expert collaborative pipeline, overcoming the 55% format error rate of direct VLM generation.
- Designs a **SFT↔GRPO hybrid** training paradigm with logical consistency rewards; the 4B model achieves **25.1% improvement** in spatial-temporal reasoning on VLM2/VSI benchmarks, surpassing models 7.5× larger (e.g., Qwen3-VL-30B), while maintaining performance on general benchmarks.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review</div>
      <img src='images/gridshow_teaser.png' alt="GRID" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**GRID: Omni Visual Generation**

**Cong Wan**, et al.

[**Code**](https://github.com/vancyland/GRID)

- Proposes a unified visual generation framework that reframes temporal sequences as **spatial grid layout problems** by repurposing the FLUX architecture, achieving up to **1000× training efficiency** improvement over conventional video generation pipelines.
- Constructs **35k high-quality video-text pairs** and supports full-stack visual generation tasks including Text-to-Video (T2V), Text-to-Multi-View (T2MV), and video editing.

  </div>
</div>

- **Prompt-Agnostic Adversarial Perturbation for Customized Diffusion Models**, **Cong Wan**, et al. *NeurIPS 2024*. \[[Project Page](https://vancyland.github.io/Prompt-Agnostic-Adversarial-Perturbation-for-Customized-Diffusion-Models.github.io/)\] \[[Code](https://github.com/vancyland/Prompt-Agnostic-Adversarial-Perturbation-for-Customized-Diffusion-Models.github.io)\]
  - Proposes a **prompt-agnostic adversarial evaluation protocol** for AIGC image protection, modeling the prompt distribution via Laplace Approximation and maximizing expected perturbation to address the failure of existing prompt-specific methods under unknown-prompt scenarios.
  - Achieves **SOTA** on both face privacy protection and artistic style protection benchmarks.


# 💼 Internships

- *2025.11 - 2026.03* &nbsp;<img src="images/bytedance_logo.png" alt="ByteDance" height="20" style="vertical-align:middle;"> &nbsp;**Multimodal Algorithm Research Intern**, Seed-Robotics, ByteDance Seed
  - **ReMoT** *(CVPR 2026)*: Developed the full ReMoT pipeline; built motion contrast triplet datasets through multi-expert collaboration to enhance VLM spatial-temporal reasoning; the 4B model achieves SOTA on spatial-temporal and multiple general benchmarks.
  - **Unified VLA World Model**: Developed an interleaved image-text reasoning architecture enabling autonomous visual generation and planning for robot manipulation; integrated datasets including Bridge, RT-1, Ego4D, Fourier ActionNet, RoboMind, OpenVid-1M, FineVision, and Zebro-COT; constructed interleaved reasoning scenario data and the corresponding evaluation benchmarks.

- *2025.06 - 2025.10* &nbsp;<img src="images/msra_logo.png" alt="MSRA" height="20" style="vertical-align:middle;"> &nbsp;**World Model Algorithm Research Intern**, Machine Learning Group, Microsoft Research Asia (MSRA)
  - Constructed **10k Minetest simulation videos** (2,000 frames each) with **64³ voxel annotations**; designed **23 action combination evaluation scenarios**; supported voxel-pixel joint training, achieving a **23% consistency improvement** over SOTA.

- *2024.12 - 2025.06* &nbsp;<img src="images/alibaba_logo.png" alt="Alibaba" height="20" style="vertical-align:middle;"> &nbsp;**AIGC Algorithm Research Intern**, Basic Vision Lab, Alibaba DAMO Academy
  - **GRID**: Proposed the GRID unified visual generation method, converting video sequences into grid images and repurposing FLUX for image-based training; achieved **1000× training efficiency** improvement; constructed 35k high-quality video-text pairs supporting full-stack visual generation (T2V, T2MV, editing).
  - **LuminaData / 寻光Edit**: Co-built a tens-of-millions-scale editing dataset covering grounding, local editing, style transfer, and watermark removal; integrated **80M inpainting samples**, **21,000 indoor 3D renderings**, and **4,730 real-capture data** samples.
  - **VLM Spatial Evaluation**: Constructed a four-dimensional VLM spatial evaluation system covering geometric scale, Ego-centric orientation, scene viewpoint, and embodied operation, based on ScanNet/NuScenes/AgiBot/OmniWorld data; evaluated generation models including Banana, GPT-4o, Bagel, and Qwen-Image.

- *2023.12 - 2024.05* &nbsp;<img src="images/xjtu_logo.png" alt="XJTU" height="20" style="vertical-align:middle;"> &nbsp;**Undergraduate Researcher**, Yihong Gong Lab, Xi'an Jiaotong University
  - Proposed **PAP**, a prompt-agnostic adversarial perturbation method for personalized diffusion models; modeled the prompt distribution via Laplace Approximation and maximized expected perturbation to solve the weak image protection problem under unknown-prompt scenarios.
  - Achieved **SOTA** on face privacy protection and artistic style protection benchmarks *(NeurIPS 2024)*.


# 🎓 Education

- *2024.09 - 2027.06 (expected)* &nbsp;M.S. in Computer Science and Technology, School of Software Engineering, **Xi'an Jiaotong University**
  - Advisor: Prof. Yihong Gong
  - 🏆 National Scholarship for Graduate Students (Top 1%) \| Outstanding Student Award

- *2020.09 - 2024.06* &nbsp;B.S. in Mathematics, School of Mathematics and Statistics, **Xi'an Jiaotong University**
