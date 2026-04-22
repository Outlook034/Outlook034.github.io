---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a junior undergraduate student at **Xi'an Jiaotong-Liverpool University (XJTLU)**, where I am pursuing a degree in Computer Science/Data Science. Currently, I am working as a **Research Assistant** under the supervision of **Prof. Jieming Ma**. My research interests lie in **3D/4D Reconstruction**, **3D Computer Vision**, **Depth Estimation**, **Medical Computer Vision**, and **Generative AI**.

Feel free to reach out if you are interested in my research or want to collaborate!

<div style="margin: 20px 0;">
  <a href="https://github.com/Outlook034" style="margin-right: 20px;"><i class="fab fa-github fa-lg"></i> GitHub</a>
  <a href="https://scholar.google.com/citations?user=nBCZTpQAAAAJ" style="margin-right: 20px;"><i class="fas fa-graduation-cap fa-lg"></i> Google Scholar</a>
  <a href="mailto:Kan.Liu23@student.xjtlu.edu.cn"><i class="fas fa-envelope fa-lg"></i> Email</a>
</div>


# Research Interests

- 3D/4D Reconstruction
- Neural Rendering (NeRF, 3D Gaussian Splatting)
- Medical Computer Vision
- Depth Estimation
- Generative AI


# News
- *2026.02*: Submitted our first-authored paper "See-Through 4D Endoscopy via Semantic-Guided Geometry Assimilation and Occlusion-Aware Tissue Completion for Dynamic Gaussian Splatting" to **MICCAI 2026**.
- *2026.01*: My collaborative paper will be presented as an Poster Presentation at ICASSP 2026![Paper](https://arxiv.org/abs/2511.21367)
- *2025.04*: My first-author paper was accepted by IJCNN ![Paper](https://ieeexplore.ieee.org/document/11229220)


# Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCNN 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MTLP-MDG: Multi-Task Learning Framework using Probabilistic Distribution Perception for Missing Data Generation](https://ieeexplore.ieee.org/document/11229220)

Jiahao Qin, **Kan Liu**, Yizhuo Cai, Tianyi Ji, and Fangyu Liu

*IEEE International Joint Conference on Neural Networks (IJCNN), Rome, Italy, 2025*
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2026</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Endo-G²T: Geometry-Guided and Temporally Aware Training for 4D Gaussian Splatting in Endoscopy](https://arxiv.org/abs/2511.21367)

Yizhuo Liu, Fei Li, **Kan Liu**, and Jiayuan Ma

*IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2026* — Accepted
</div>
</div>


# Research Experience

## See-Through 4D Endoscopy
*Research Assistant | XJTLU | Advisor: Prof. Jieming Ma* | 2025.12 - Present

- Developed a semantic-aware and geometry-prior gated fusion mechanism, dynamically integrating semantic labels and depth information, significantly improving reconstruction accuracy of 4D Gaussian Splatting in complex dynamic scenarios
- Enhanced surgical instrument removal and tissue completion algorithms for endoscopic scenes, leveraging geometric constraints to mitigate rendering artifacts caused by occlusions and preserving anatomical topology consistency
- Reconstructed the neural rendering pipeline tailored for endoscopic datasets, optimizing view synthesis and hole-filling strategies, and successfully improving rendering frame rates while maintaining perceptual fidelity
- Achieved efficient decoupling of surgical instruments and biological tissues, providing a more robust geometric foundation for 4D visualization in surgical navigation systems


## LatentFlowNet
*Project Member | Collaboration with Georgia Institute of Technology (GT)* | 2025.12 - 2026.02

- Utilized intermediate PET imaging data at 6, 12, and 18 time points for longitudinal analysis
- Modeled temporal progression trends using Neural ODE-based linear trajectory fitting
- Encoded PET scans into a latent representation space for autoencoding and downstream model training


## Endo-G2T
*Research Assistant | XJTLU | Advisor: Prof. Jieming Ma* | 2025.06 - 2025.09

- Proposed an innovative training framework, Endo-G2T, integrating Geometry-Prior Distillation (GPD), Temporal-Embedded Gaussian Fields (TEGF), and Keyframe-Constrained Streaming Optimization (KCS), enabling high-precision and high-frame-rate 4D reconstruction of endoscopic dynamic scenes under a monocular setting
- Developed an adaptive filtering mechanism based on VGCT depth maps and confidence maps, leveraging masking strategies to decouple regions affected by instrument occlusions
- Designed a frame-wise normalization strategy that constrains log-depth comparisons (valid pixel ratio >= 10%), effectively mitigating geometric drift caused by inconsistent depth scales across frames
- Implemented effective pixel sampling and confidence threshold optimization, anchoring early-stage geometric structures in challenging dynamic scenarios (strong specular highlights, wet reflections, and occlusions), significantly improving temporal consistency and geometric stability in 3D reconstruction


## EAST
*Research Assistant | XJTLU | Advisor: Prof. Jieming Ma* | 2024.09 - 2025.02

- Designed and implemented a PC-streaming-based optimized rendering pipeline for head-mounted displays (HMDs), integrating stylized game datasets with high-performance transmission protocols to enhance visual realism and interaction responsiveness in virtual environments
- Developed a 3D Gaussian Splatting (3DGS) style transfer algorithm based on VGG feature extraction, incorporating content loss and multi-scale Gram matrix style loss to improve perceptual fidelity and address inconsistencies between geometry and texture
- Built a coherent transition framework across the Reality-Virtuality Continuum (RVC), reducing geometric distortion and visual artifacts during stylization, and enabling high-fidelity, visually consistent game-style rendering in complex scenes


# Skills

**Programming Languages:** Python, Java

**Deep Learning Frameworks:** PyTorch, TensorFlow

**3D Vision & Rendering:** 3D Gaussian Splatting, NeRF, Open3D, COLMAP, OpenCV

**Scientific Computing:** NumPy, SciPy, Matplotlib

**Tools:** Git, LaTeX, Linux


# Honors and Awards

- *2024*: First Prize (Jiangsu Province), China Undergraduate Mathematical Contest in Modeling
- *2025*: Honorable Mention, Mathematical Contest in Modeling (MCM)
- *2024*: Scholarship Award, Xi'an Jiaotong-Liverpool University


# Education

- *2023.09 - Present*, B.Eng. in Computer Science/Data Science, Xi'an Jiaotong-Liverpool University, Suzhou, China

**GPA:** 3.89/4.00 | **IELTS:** 6.5

**Related Courses:** Computer System (97), Data Structures (91), Calculus (90), Artificial Intelligence (82)


# Connect with Me

Feel free to reach out via [email](mailto:Kan.Liu23@student.xjtlu.edu.cn) or check out my [GitHub](https://github.com/Outlook034) profile!
