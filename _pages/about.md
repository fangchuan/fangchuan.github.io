---
permalink: /
title: ""
excerpt: ""
author_profile: false
layout_class: home-page
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

<div class="home-hero anchor" id="about-me">
  <div class="home-hero__text">
    <h1><a href="https://fangchuan.github.io/">Chuan FANG</a></h1>
    <h3>Ph.D. Candidate</h3>
    <p class="home-hero__affiliation">Electronic and Computer Engineering</p>
    <p class="home-hero__affiliation">Hong Kong University of Science and Technology</p>
    <p class="home-hero__affiliation">Hong Kong SAR, China</p>
    <p class="home-hero__email">Email: <code>cfangac@connect.ust.hk</code> / <code>fang1457737815@gmail.com</code></p>
    <p class="home-hero__links"><a href="https://scholar.google.com/citations?user=cBUlGS8AAAAJ">[Google Scholar]</a> &nbsp; <a href="https://github.com/fangchuan">[GitHub]</a></p>
  </div>
  <div class="home-hero__avatar">
    <img src="images/android-chrome-512x512.png" alt="Chuan FANG">
  </div>
</div>

## 👤 Biography

Hi there👋, my name is Chuan FANG (in Chinese: 方川). I am a fourth-year Ph.D. candidate of Electronic and Computer Engineering at [Hong Kong University of Science and Technology](https://hkust.edu.hk/), supervised by Prof. [Ping Tan](https://ece.hkust.edu.hk/pingtan).

My research focuses on advancing the frontier of **Multi-modal World Models**: AI systems that 👀perceive, 🎨generate, and 🦾interact within the physical world. I pursue this vision through four tightly connected directions: (1) **Multi-modality LLMs for Spatial Reasoning**, (2) **Generative Models for Controllable Video/3D Scenes**, (3) **Geometry-grounded Perception for Spatial Intelligence**, and (4) **Agentic Frameworks that unify understanding and generation**—where perception, reasoning, and content creation form a closed loop. By weaving these directions together, my overarching goal is to build general-purpose intelligent systems: AI that can understand, generate, and interact with complex physical environments.

I've spent wonderful time as a research intern at [ManyCore Tech](https://www.manycoretech.com/) for controllable video generation, 3D scene generation and perception, working with [Dr. Zihan Zhou](https://zihan-zhou.github.io/). Before joining HKUST, I worked as a senior algorithm engineer at DAMO Academy XR-Lab, Alibaba Group from 2019 to 2023, led by Prof. [Ping Tan](https://ece.hkust.edu.hk/pingtan).

I'm always open to research discussions and collaborations. Feel free to 📲contact me if you are interested.

📌 I am going to graduate in spring 2027 and am actively seeking full-time opportunities! Please feel free to reach out for more information if you think my background could be a good fit.

<span class="anchor" id="news"></span>

## 📢 News

<ul class="compact-list news-list">
  <!-- <li><span>[2026-07]</span> One paper about single-image world generation (<a href="https://arxiv.org/pdf/2406.01467">SpatialCrafter</a>) was accepted to <strong>SIGGRAPH Asia</strong> 2026.</li> -->
  <li><span>[2026-06]</span> One paper about structured indoor modeling with LLMs (<a href="https://github.com/JIANG-CX/H-OmniStereo">SceneSpinner</a>) was accepted to <strong>ECCV</strong> 2026.</li>
  <li><span>[2025-11]</span> One paper about layout-guided 3D indoor scene generation (<a href="https://manycore-research.github.io/SpatialGen/">SpatialGen</a>) was accepted to <strong>3DV</strong> 2026.</li>
  <li><span>[2025-09]</span> One paper about structured indoor modeling with LLMs (<a href="https://manycore-research.github.io/SpatialLM/">SpatialLM</a>) was accepted to <strong>NeurIPS</strong> 2025.</li>
  <li><span>[2025-06]</span> One paper about geometry surface reconstruction in Gaussian Splatting (<a href="https://baowenz.github.io/radegs/">RaDeGS</a>) was accepted to <strong>TOG</strong> 2025.</li>
  <li><span>[2024-11]</span> One paper about text-to-3D scene mesh generation (<a href="https://fangchuan.github.io/ctrl-room.github.io/">CtrlRoom</a>) was accepted to <strong>3DV</strong> 2025.</li>
  <li><span>[2024-02]</span> One paper about panoramic total scene understanding (<a href="https://fangchuan.github.io/PanoContext-Former/">PanoContext-Former</a>) was accepted to <strong>CVPR</strong> 2024.</li>
  <li><span>[2021-07]</span> One paper about multi-sensor calibration was accepted to <strong>IROS</strong> 2021.</li>
</ul>

<span class="anchor" id="publications"></span>

## 📑 Selected Publications [[Google Scholar](https://scholar.google.com/citations?user=cBUlGS8AAAAJ)]

<p><em>*: equal contribution</em></p>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">SIGGRAPH Asia 2026</div><img src="images/spatialcrafter-teaser.jpg" alt="SpatialCrafter teaser"></div></div>
<div class="paper-box-text" markdown="1">

■ [SpatialCrafter: Single-Image World Modeling via Generative 3D Proxies](https://arxiv.org/pdf/2406.01467)

**Chuan Fang**, Lingteng Qiu, Yixun Liang, Rui Chen, Yuantong Bai, Zhaohua Zheng, Feipeng Tian, Zilong Dong, Zihan Zhou, Ping Tan

*ACM SIGGRAPH Asia 2026*, submitted
<p class="paper-links"><a href="https://arxiv.org/pdf/2406.01467">[arXiv]</a> <a class="github-repo-link" href="https://github.com/fangchuan/SpatialCrafter" data-repo="fangchuan/SpatialCrafter"><i class="fab fa-github" aria-hidden="true"></i> GitHub <span class="github-stars" data-repo="fangchuan/SpatialCrafter">-- stars</span></a></p>

TL;DR: SpatialCrafter builds generative 3D proxies from a single image to enable consistent, controllable video generation.

</div></div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">Submitted to RAL</div><img src="images/oministereo-teaser.png" alt="H-OmniStereo teaser"></div></div>
<div class="paper-box-text" markdown="1">

■ [H-OmniStereo: Zero-Shot Omnidirectional Stereo Matching with Heading-Aligned Normal Priors](https://arxiv.org/abs/2605.14963)

Chenxing Jiang, Zhe Tong, Pusen Gao, Peize Liu, Yang Xu, **Chuan Fang**, Ping Tan, Shaojie Shen

*IEEE Robotics and Automation Letters*, submitted
<p class="paper-links"><a href="https://github.com/JIANG-CX/H-OmniStereo">[Project Page]</a> <a class="github-repo-link" href="https://github.com/JIANG-CX/H-OmniStereo" data-repo="JIANG-CX/H-OmniStereo"><i class="fab fa-github" aria-hidden="true"></i> GitHub <span class="github-stars" data-repo="JIANG-CX/H-OmniStereo">-- stars</span></a></p>

TL;DR: H-OmniStereo performs zero-shot omnidirectional stereo matching guided by heading-aligned normal priors.

</div></div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">3DV 2026</div><img src="images/spatialgen-teaser.png" alt="SpatialGen teaser"></div></div>
<div class="paper-box-text" markdown="1">

■ [SpatialGen: Layout-guided 3D Indoor Scene Generation](https://arxiv.org/pdf/2406.01467)

**Chuan Fang**, Heng Li, Yixun Liang, Jia Zheng, Yongsen Mao, Yuan Liu, Rui Tang, Zihan Zhou, Ping Tan

*International Conference on 3D Vision* (**3DV**), 2026

<p class="paper-links"><a href="https://manycore-research.github.io/SpatialGen/">[Project Page]</a> <a class="github-repo-link" href="https://github.com/manycore-research/SpatialGen" data-repo="manycore-research/SpatialGen"><i class="fab fa-github" aria-hidden="true"></i> GitHub <span class="github-stars" data-repo="manycore-research/SpatialGen">-- stars</span></a></p>

TL;DR: SpatialGen generates realistic, layout-consistent 3D indoor scenes conditioned on structured room layouts.

</div></div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">NeurIPS 2025</div><img src="images/spatiallm-teaser.jpg" alt="SpatialLM teaser"></div></div>
<div class="paper-box-text" markdown="1">

■ [SpatialLM: Training Large Language Models for Structured Indoor Modeling](https://arxiv.org/pdf/2406.01467)

Yongsen Mao, Junhao Zhong, **Chuan Fang**, Jia Zheng, Rui Tang, Hao Zhu, Ping Tan, Zihan Zhou

*Neural Information Processing Systems* (**NeurIPS**), 2025

<p class="paper-links"><a href="https://manycore-research.github.io/SpatialLM/">[Project Page]</a> <a class="github-repo-link" href="https://github.com/manycore-research/SpatialLM" data-repo="manycore-research/SpatialLM"><i class="fab fa-github" aria-hidden="true"></i> GitHub <span class="github-stars" data-repo="manycore-research/SpatialLM">-- stars</span></a></p>

TL;DR: SpatialLM trains large language models to directly predict structured 3D indoor scene representations.

</div></div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">TOG 2025</div><img src="images/radegs-teaser.png" alt="RaDeGS teaser"></div></div>
<div class="paper-box-text" markdown="1">

■ [RaDeGS: Rasterizing Depth in Gaussian Splatting](https://arxiv.org/pdf/2406.01467)

Baowen Zhang, **Chuan Fang**, Rakesh Shrestha, Yixun Liang, Xiaoxiao Long, Ping Tan

*ACM Transactions on Graphics* (**TOG**), 2025

<p class="paper-links"><a href="https://baowenz.github.io/radegs/">[Project Page]</a> <a class="github-repo-link" href="https://github.com/BaowenZ/RaDe-GS" data-repo="BaowenZ/RaDe-GS"><i class="fab fa-github" aria-hidden="true"></i> GitHub <span class="github-stars" data-repo="BaowenZ/RaDe-GS">-- stars</span></a></p>

TL;DR: RaDeGS improves geometric fidelity of Gaussian Splatting by directly rasterizing depth during optimization.

</div></div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">3DV 2025</div><img src="images/ctrlroom-teaser.png" alt="CtrlRoom teaser"></div></div>
<div class="paper-box-text" markdown="1">

■ [CtrlRoom: Controllable Text-to-3D Room Meshes Generation with Layout Constraints](https://arxiv.org/abs/2310.03602)

**Chuan Fang**, Yuan Dong, Kunming Luo, Xiaotao Hu, Rakesh Shrestha, Ping Tan

*International Conference on 3D Vision* (**3DV**), 2025

<p class="paper-links"><a href="https://fangchuan.github.io/ctrl-room.github.io/">[Project Page]</a> <a class="github-repo-link" href="https://github.com/fangchuan/Ctrl-Room" data-repo="fangchuan/Ctrl-Room"><i class="fab fa-github" aria-hidden="true"></i> GitHub <span class="github-stars" data-repo="fangchuan/Ctrl-Room">-- stars</span></a></p>

TL;DR: CtrlRoom generates controllable, layout-constrained 3D room meshes directly from text descriptions.

</div></div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">CVPR 2024</div><img src="images/panocontext-former-teaser.png" alt="PanoContext-Former teaser"></div></div>
<div class="paper-box-text" markdown="1">

■ [PanoContext-Former: Panoramic Total Scene Understanding with a Transformer](https://arxiv.org/pdf/2305.12497.pdf)

Yuan Dong\*, **Chuan Fang\***, Liefeng Bo, Zilong Dong, Ping Tan

*Computer Vision and Pattern Recognition* (**CVPR**), 2024

<p class="paper-links"><a href="https://fangchuan.github.io/PanoContext-Former/">[Project Page]</a> <a class="github-repo-link" href="https://github.com/fangchuan/PanoContext-Former" data-repo="fangchuan/PanoContext-Former"><i class="fab fa-github" aria-hidden="true"></i> GitHub <span class="github-stars" data-repo="fangchuan/PanoContext-Former">-- stars</span></a></p>

TL;DR: PanoContext-Former jointly reasons about layout, objects, and semantics in panoramic scenes with a transformer.

</div></div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">IROS 2021</div><img src="images/single-shot-teaser.png" alt="Single-Shot calibration teaser"></div></div>
<div class="paper-box-text" markdown="1">

■ [Single-Shot is Enough: Panoramic Infrastructure Based Calibration of Multiple Cameras and 3D LiDARs](https://arxiv.org/pdf/2103.12941.pdf)

**Chuan Fang**, Shuai Ding, Zilong Dong, Honghua Li, Siyu Zhu, Ping Tan

*International Conference on Intelligent Robots and Systems* (**IROS**), 2021

<p class="paper-links"><a href="https://github.com/alibaba/multiple-cameras-and-3D-LiDARs-extrinsic-calibration">[Code]</a> <a class="github-repo-link" href="https://github.com/alibaba/multiple-cameras-and-3D-LiDARs-extrinsic-calibration" data-repo="alibaba/multiple-cameras-and-3D-LiDARs-extrinsic-calibration"><i class="fab fa-github" aria-hidden="true"></i> GitHub <span class="github-stars" data-repo="alibaba/multiple-cameras-and-3D-LiDARs-extrinsic-calibration">-- stars</span></a></p>

TL;DR: A single-shot calibration method for multiple cameras and 3D LiDARs using panoramic infrastructure cues.

</div></div>

<ul class="compact-list publication-list">
  <li>■ <a href="https://arxiv.org/abs/2103.14846">RenderNet: Visual Relocalization Using Virtual Viewpoints in Large-Scale Indoor Environments</a><br>
  Rui Huang, <strong>Chuan Fang</strong>, Kejie Qiu, Le Cui, Zilong Dong, Siyu Zhu, Ping Tan, arXiv 2022.</li>
  <li>■ <a href="https://arxiv.org/abs/2310.03602">AR Mapping: Accurate and Efficient Mapping for Augmented Reality</a><br>
  Jiahui Zhang, Shitao Tang, Kejie Qiu, Rui Huang, <strong>Chuan Fang</strong>, Le Cui, Zilong Dong, Siyu Zhu, Ping Tan, arXiv 2021.</li>
</ul>

<span class="anchor" id="educations"></span>

## 🎓 Educations

<ul class="compact-list edu-list">
  <li>
    <strong>Ph.D. student</strong>, Electronic and Computer Engineering, Hong Kong University of Science and Technology
    <span class="date-right">2023.02 – now</span>
  </li>
  <li>
    <strong>M.Sc.</strong>, Electronic Science and Engineering School, Nanjing University
    <span class="date-right">2016.09 – 2019.06</span>
  </li>
  <li>
    <strong>B.E.</strong>, Automation School, Nanjing University of Posts and Telecommunications
    <span class="date-right">2012.09 – 2016.06</span>
  </li>
</ul>

<!-- <span class="anchor" id="honors"></span> -->

<!-- ## 🏆 Honors & Awards

<ul class="compact-list honor-list">
  <li>
    <strong>Jiangsu Outstanding Master's Thesis Award</strong>, Jiangsu Provincial Education Department
    <span class="date-right">2019.10</span>
  </li>
  <li>
    National Second Prize, National Undergraduate Electronic Design Contest
    <span class="date-right">2015.10</span>
  </li>
  <li>
    National First Prize, RoboCup China
    <span class="date-right">2014.08</span>
  </li>
</ul> -->

<span class="anchor" id="services"></span>

## 📝 Services & Talks

<ul class="compact-list">
  <li>■ Conference Reviewer:
    <ul>
      <li>Computer Vision: ICCV 2024–2025, CVPR 2024–2026, ECCV 2025–2026</li>
      <li>Graphics: SIGGRAPH Asia 2026, Eurographics 2025, 3DV 2025–2026</li>
      <li>Robotics: IROS 2026</li>
    </ul>
  </li>
  <li>■ Journal Reviewer: TVCG</li>
  <li>■ Invited talk: <em>Indoor Scene Understanding and Generation</em>, AI Center, Beike Inc., 2024.01. [[<a href="https://github.com/">Slides</a>]]</li>
  <li>■ Invited talk: <em>Multiple Sensor Calibration</em>, 3D Vision Online WeChat Account, 2021.06. [[<a href="https://github.com/">Video</a>]]</li>
</ul>

<span class="anchor" id="experiences"></span>

## 💻 Experiences

<ul class="compact-list exp-list">
  <li>
    <strong>Research Intern</strong>, <a href="https://www.manycoretech.com/">ManyCore Tech</a>, China
    <span class="date-right">2024.06 – now</span>
  </li>
  <li>
    LightIllusion, China
    <span class="date-right">2023.06 – 2024.06</span>
  </li>
  <li>
    <strong>Senior Algorithm Engineer</strong>, DAMO Academy XR-Lab, Alibaba Group
    <span class="date-right">2019.06 – 2023.01</span>
  </li>
</ul>

<footer class="site-footer">
  © Chuan FANG
</footer>