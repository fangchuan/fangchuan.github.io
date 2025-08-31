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

I am a PhD student of HKUST, supervised by Prof [PingTan](https://ece.hkust.edu.hk/pingtan). I received my Master degree at Nanjing University (NJU), supervised by Prof. YunGe in 2019, and received my Bachelor degree in Nanjing University of Post and Telecommunications (NUPT) in 2016. I worked as a senior algorithm engineer at DAMO academy XR-Lab, Alibaba group from 2019 to 2023.

My research interest includes 3D computer vision and robotics. 
<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 RaDeGS is accepted by TOG. 
- *2024.11*: &nbsp;🎉🎉 CtrlRoom is accepted by 3DV2025. 
- *2024.02*: &nbsp;🎉🎉 PanoContext-Former is accepted by CVPR2024. 
- *2021.07*: &nbsp;🎉🎉 Single-Shot Multiple-Lidar-and-Camera Calibration is accepted by IROS 2021. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2025</div><img src='images/spatialgen-teaser.png' alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

[SpatialGen: Layout-guided 3D Indoor Scene Generation](https://arxiv.org/pdf/2406.01467)

**Chuan Fang**, Heng Li, Yixun Liang, Jia Zheng, Yongsen Mao,
Yuan Liu, Rui Tang, Zihan Zhou, Ping Tan

[**Project**](https://manycore-research.github.io/SpatialGen/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2025</div><img src='images/spatiallm-teaser.jpg' alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

[SpatialLM: Training Large Language Models for Structured Indoor Modeling](https://arxiv.org/pdf/2406.01467)

Yongsen Mao, Junhao Zhong, **Chuan Fang**, Jia Zheng, Rui Tang, Hao Zhu, Ping Tan, Zihan Zhou 

[**Project**](https://manycore-research.github.io/SpatialLM/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TOG 2025</div><img src='images/radegs-teaser.png' alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

[RaDeGS: Rasterizing Depth in Gaussian Splatting](https://arxiv.org/pdf/2406.01467)

Baowen Zhang, **Chuan Fang**, Rakesh Shrestha, Yixun Liang, Xiaoxiao Long, and Ping Tan

[**Project**](https://baowenz.github.io/radegs/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">3DV 2025</div><img src='images/ctrlroom-teaser.png' alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

[CtrlRoom: Controllable Text-to-3D Room Meshes Generation with Layout Constraints](https://arxiv.org/abs/2310.03602)

**Chuan Fang**, Yuan Dong, Kunming Luo, Xiaotao Hu, Rakesh Shrestha, and Ping Tan

[**Project**](https://fangchuan.github.io/ctrl-room.github.io/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/panocontext-former-teaser.png' alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

[PanoContext-Former: Panoramic Total Scene Understanding with a Transformer](https://arxiv.org/pdf/2305.12497.pdf)

Yuan Dong, **Chuan Fang**, Liefeng Bo, Zilong Dong, Ping Tan

[**Project**](https://fangchuan.github.io/PanoContext-Former/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2021</div><img src='images/single-shot-teaser.png' alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

[Single-Shot is Enough: Panoramic Infrastructure Based Calibration of Multiple Cameras and 3D LiDARs](https://arxiv.org/pdf/2103.12941.pdf)

**Chuan Fang**, Shuai Ding, Zilong Dong, Honghua Li, Siyu Zhu, Ping Tan

[**Project**](https://github.com/alibaba/multiple-cameras-and-3D-LiDARs-extrinsic-calibration) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

- [RenderNet: Visual Relocalization Using Virtual Viewpoints in Large-Scale Indoor Environments](https://arxiv.org/abs/2103.14846), Rui Huang, **Chuan Fang**, Kejie Qiu, Le Cui, Zilong Dong, Siyu Zhu, Ping Tan, **axiv 2022**

- [AR Mapping: Accurate and Efficient Mapping for Augmented Reality](https://arxiv.org/abs/2310.03602), Jiahui Zhang, Shitao Tang, Kejie Qiu, Rui Huang, **Chuan Fang**, Le Cui, Zilong Dong, Siyu Zhu, and Ping Tan, **axiv 2021**



# 🎖 Honors and Awards
- *20019.10* 江苏省优秀研究生毕业论文-基于深度强化学习的无人驾驶车道保持决策的研究.
- *2015.10* 全国大学生电子设计竞赛-全国二等奖. 
- *2014.08* RoboCup中国赛-全国一等奖. 

# 📖 Educations
- *2023.02 - now*, PhD, Electronic and Computing Engineering, Hong Kong University of Science and Technology. 
- *2016.09 - 2019.06*, M.Sc, Electronic Science and Engineering School, Nanjing University. 
- *2012.09 - 2016.06*, B.E, Automation School, Nanjing Univeristy of Post and Telecommunication. 

# 💬 Invited Talks
- *2024.01*, Indoor Scene Understanding and Generation. AI center, Beike Inc. [\[slides\]](https://github.com/)
- *2021.06*, Multiple Sensor Calibration. 3D Vision Online Wechat Account \| [\[video\]](https://github.com/)

# 💻 Work Experiences
- *2023.06 - now*, [LightIllusion](https://github.com/), China.
- *2019.06 - 2023.01*, Senior Algorithm Engineer, DAMO Academy XR-Lab, Alibaba Group. 