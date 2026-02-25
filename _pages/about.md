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

I am a first-year Ph.D student of ***R&L Group*** at ***Nanjing University (NJU)***, under the supervision of Prof. ***Qi Fan*** [-- homepage](https://fanq15.github.io/). I obtained my M.S. in Computer Science at ***the University of Chinese Academy of Sciences (UCAS)*** in 2024 and B.S at ***Shanghai Jiao Tong University (SJTU)*** in 2021. I was also fortunate to be an internship at 01AI <img src="./images/01AI.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">, Huawei <img src="./huawei_icon.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">, TeleAI <img src="./teleai_icon.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">, Kuaishou-Kling <img src="./Kuaishou_icon.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;"><img src="./Kling_icon.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">, Tecent-Hunyuan.

My research interests lie in the intersection of ***Computer Vision and Machine Learning***. From 2021, I started to do some research on Neural architecture search and image caption. Now, I focus on designing novel applications for ***image/video generation, World model, 3D autoregressive-generation*** and other downstream AIGC tasks. Welcome to the [Zhihu homepage](https://zhuanlan.zhihu.com/p/10593629023) for academic discussions in the field of image/video generation.

# 📖 Educations
- *2024.10 - up-to-now, Phd, School of Intelligence Science and Technology,*  ***Nanjing University.*** <img src="./images/nju_1em.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">
- *2021.09 - 2024.06, M.S.  degree, School of Computer Science and Technology,* ***University of Chinese Academy of Sciences.*** <img src="./images/ucas_1em.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">
- *2017.09 - 2021.06, B.S.  degree, School of Electronic Information and Electrical Engineering,* ***Shanghai Jiao Tong University.*** <img src="./images/sjtu_1em.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">

# 📝 Publications/Preprints - main contribution

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2026</div><img src='images/TTO.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Pathwise Test-Time Correction for Autoregressive Long Video Generation](https://arxiv.org/abs/2602.05871)

**Xunzhi Xiang**, Zixuan Duan, Guiyu Zhang, Haiyu Zhang, Zhe Gao, Junta Wu, Shaofeng Zhang, Tengfei Wang, Qi Fan, Chunchao Guo.

[**Paper**](https://arxiv.org/abs/2511.12633) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report 2025</div><img src='images/TeleWorld.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[TeleWorld: Towards Dynamic Multimodal Synthesis with a 4D World Mode](https://arxiv.org/abs/2601.00051)

TeleWorld Team.

[**Paper**](https://arxiv.org/abs/2601.00051) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2025</div><img src='images/DenoisingVAE.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Denoising Vision Transformer Autoencoder with Spectral Regularization](https://arxiv.org/abs/2511.12633)

**Xunzhi Xiang**, Xingye Tian, Guiyu Zhang, Yabo Chen, Shaofeng Zhang, Xuebo Wang, Xin Tao, Qi Fan.

[**Paper**](https://arxiv.org/abs/2511.12633) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2025</div><img src='images/MMPL.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Macro-from-Micro Planning for High-Quality and Parallelized Autoregressive Long Video Generation](https://nju-xunzhixiang.github.io/Anchor-Forcing-Page/)

**Xunzhi Xiang**, Yabo Chen, Guiyu Zhang, Zhongyu Wang, Zhe Gao, Quanming Xiang, Gonghu Shang, Junqi Liu, Haibin Huang, Yang Gao, Chi Zhang, Qi Fan, et al. 

[**Paper**](https://arxiv.org/abs/2508.03334) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'>
[**Project**](https://nju-xunzhixiang.github.io/Anchor-Forcing-Page/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2025</div><img src='images/makeit.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Make It Efficient: Dynamic Sparse Attention for Autoregressive Image Generation](https://arxiv.org/abs/2506.18226)

**Xunzhi Xiang**, Qi Fan.

[**Paper**](https://arxiv.org/abs/2506.18226) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/remask.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[ReMask-Animate: Refined Character Image Animation Using Mask-Guided Adapters](https://ojs.aaai.org/index.php/AAAI/article/view/32932)

**Xunzhi Xiang**, Haiwei Xue, Zonghong Dai, Di Wang, Minglei Li, Ye Yue, Fei Ma, Weijiang Yu, Heng Chang, Fei Richard Yu.

[**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/32932) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AISTATS 2025</div><img src='images/gnet.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[A Neural Architecture Predictor based on GNN-Enhanced Transformer](https://proceedings.mlr.press/v238/xiang24a.html)

**Xunzhi Xiang**, Kun Jing, Jungang Xu.

[**Paper**](https://proceedings.mlr.press/v238/xiang24a.html) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>


# 🔥 Publications/Preprints - participating contribution
<ul class="paper-list">

  <li>
    <span class="badge-arxiv">CVPR 2026</span>
    <a href="https://xbxsxp9.github.io/" class="paper-title">
    HERA: Efficient Test-Time Adaptation for Cross-Domain Few-Shot Segmentation with Vision Foundation Models</a>.
    Junyuan Ma, <strong>Xunzhi Xiang</strong>, Wenbin Li, Yang Gao, Qi Fan.
    [<a href="https://xbxsxp9.github.io/">paper</a>]
  </li>

  <li>
    <span class="badge-arxiv">CVPR 2026</span>
    <a href="https://xbxsxp9.github.io/" class="paper-title">
    SymphoMotion: Joint Control of Camera Motion and Object Dynamics for Coherent Video Generation</a>.
    Guiyu Zhang, Yabo Chen, <strong>Xunzhi Xiang</strong>, Junchao Huang, Zhongyu Wang, Li Jiang.
    [<a href="https://xbxsxp9.github.io/">paper</a>]
  </li>

  <li>
    <span class="badge-arxiv">ICLR 2026</span>
    <a href="#" class="paper-title">
    Retain and Adapt: Auto-Balanced Model Editing for Open-Vocabulary Object Detection under Domain Shifts</a>.
    Zixuan Duan, Fengyuan Lu, <strong>Xunzhi Xiang</strong>, Wenbin Li, Yang Gao, Qi Fan.
    [<a href="#">paper</a>]
  </li>

  <li>
    <span class="badge-arxiv">ICLR 2026</span>
    <a href="#" class="paper-title">
    QPrompt-R1: Real-Time Reasoning for Domain-Generalized Semantic Segmentation via Group-Relative Query Alignment</a>.
    Fengyuan Lu, Zixuan Duan, <strong>Xunzhi Xiang</strong>, Zhicheng Zhang, Wenbin Li, Yang Gao, Qi Fan.
    [<a href="#">paper</a>]
  </li>

  <li>
    <span class="badge-arxiv">NeurIPS 2025</span>
    <a href="https://neurips.cc/virtual/2025/poster/119868" class="paper-title">
    DON’T NEED RETRAINING: A Mixture of DETR and Vision Foundation Models for Cross-Domain Few-Shot Object Detection</a>.
    Chang-han Liu, <strong>Xunzhi Xiang</strong>, Zixuan Duan, Wenbin Li, Yang Gao, Qi Fan.
    [<a href="https://neurips.cc/virtual/2025/poster/119868">paper</a>]
  </li>

  <li>
    <span class="badge-arxiv">SIGGRAPH 2025</span>
    <a href="https://arxiv.org/abs/2506.23729" class="paper-title">
    Proteus-ID: ID-Consistent and Motion-Enhanced Video Customization</a>.
    Guiyu Zhang, Chen Shi, Zijian Jiang, <strong>Xunzhi Xiang</strong>, Jingjing Qian, Shaoshuai Shi, Li Jiang.
    [<a href="https://arxiv.org/abs/2506.23729">paper</a>]
    [<a href="https://grenoble-zhang.github.io/Proteus-ID/">project</a>]
  </li>

  <li>
    <span class="badge-arxiv">TPAMI 2025</span>
    <a href="https://arxiv.org/pdf/2509.03883" class="paper-title">
    Human Motion Video Generation: A Survey</a>.
    Haiwei Xue, Xiangyang Luo, Zhanghao Hu, Xin Zhang, <strong>Xunzhi Xiang</strong>, Yuqing Dai, Jianzhuang Liu, Zhensong Zhang, Minglei Li, Jian Yang, Fei Ma, Changpeng Yang, Zonghong Dai, Fei Richard Yu.
    [<a href="https://arxiv.org/pdf/2509.03883">paper</a>]
  </li>

  <li>
    <span class="badge-arxiv">ArXiv 2025</span>
    <a href="https://xbxsxp9.github.io/" class="paper-title">
    SmartSAM: Segment Ambiguous Objects like Smart Annotators</a>.
    Zhe Gao, Shiyu Shen, <strong>Xunzhi Xiang</strong>, Wenbin Li, Yang Gao, Qi Fan.
    [<a href="https://xbxsxp9.github.io/">paper</a>]
  </li>

</ul>

# 🎖 Honors and Awards
- *2021.10* CCF-BDCI award. 

