---
permalink: /
title: ""
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

I am currently a 3rd-Year Master student at [Tsinghua University](https://www.tsinghua.edu.cn/en/), under the guidance of [Prof. Haoqian Wang](https://www.sigs.tsinghua.edu.cn/whq/). I got B.Eng. degree in College of Electronic and Information Engineering at [Tongji University](https://en.tongji.edu.cn/). 

Currently, my research topic is 3D computer vision, with a particular focus on 3D object detection for autonomous driving and robot manipulation. (e.g. BEV, OCC)

[github](https://github.com/xingyoujun) / [google scholar](https://scholar.google.com.hk/citations?hl=zh-CN&user=sBYo2zQAAAAJ) / [cv](cv.pdf)

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024 Highlight</div><img src='images/langsplat.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LangSplat: 3D Language Gaussian Splatting](https://arxiv.org/pdf/2312.16084.pdf)

<b>Minghan Qin\*</b>, [Wanhua Li\*†](https://li-wanhua.github.io/), [Jiawei Zhou\*](https://latitudezhou.github.io/), [Haoqian Wang†](https://www.sigs.tsinghua.edu.cn/whq_en/main.htm), [Hanspeter Pfister](https://seas.harvard.edu/person/hanspeter-pfister)

[**WEBSITE**](https://langsplat.github.io/) [![](https://img.shields.io/github/stars/minghanqin/Langsplat?style=flat-square&label=GitHub%20Star)](https://github.com/minghanqin/LangSplat) <strong><span class='show_paper_citations' data=''></span></strong>
- We introduces LangSplat, which constructs a 3D language field that enables precise and efficient open-vocabulary querying within 3D spaces.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/avatarsve.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[High-Fidelity 3D Head Avatars Reconstruction through Spatially-Varying Expression Conditioned Neural Radiance Field](https://arxiv.org/abs/2310.06275)

<b>Minghan Qin\*</b>, Yifan Liu\*, Yuelang Xu, Xiaochen Zhao, [Yebin Liu†](https://www.liuyebin.com/), [Haoqian Wang†](https://www.sigs.tsinghua.edu.cn/whq_en/main.htm)

[**WEBSITE**](https://minghanqin.github.io/AvatarSVE/) <strong><span class='show_paper_citations' data=''></span></strong>
-  We introduce a novel Spatially-Varying Expression (SVE) conditioning, encompassing both spatial positional features and global expression information.
</div>
</div>
