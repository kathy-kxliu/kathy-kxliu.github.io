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

Hi, I am Kexin Liu（刘柯鑫）. I am now a research engineer at Huawei, focusing on building and improving the performance of scale-up/scale-out network systems for AI, including network protocol stacks, supernode network topologies, and collective communication libraries. 

I received my Ph.D. degree in computer science and engineering from Nanjing University in 2023, supervised by Prof. <a href='https://cs.nju.edu.cn/tianchen/index.htm'>Chen Tian</a>. My research interests include datacenter network systems and congestion management. My work has been published at top-tier conferences and transactions such as NSDI, CoNEXT, TON, and TPDS, etc.

Before that, I received my bachelor’s degree from Sun-Yat Sen University.

# 🔥 News
- *2024.07*: &nbsp;🎉🎉 Paper: Pyrrha accepted by NSDI 2025. Pyrrha is a flow control that controls transient congestion at a fine granularity without HOL blocking, requiring only a minimal number of queues.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NSDI 2025</div></div></div>
<div class='paper-box-text' markdown="1">

[Pyrrha: Congestion-Root-Based Flow Control to Eliminate Head-of-Line Blocking in Datacenter](/docs/paper/nsdi25-liukexin.pdf)

**Kexin Liu***, Zhaochen Zhang*, Chang Liu, Yizhi Wang, Vamsi Addanki, Stefan Schmid,
Qingyue Wang, Wei Chen, Xiaoliang Wang, Jiaqi Zheng, Wenhao Sun, Tao Wu, Ke Meng,
Fei Chen, Weiguang Wang, Bingyang Liu, Wanchun Dou, Guihai Chen, Chen Tian


# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Work Experience
- *2023.07 - *, Huawei, China.
