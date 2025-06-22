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

My research interests include:

Building scale-up/scale-out network systems for AI,
Datacenter Network architectures and protocols,
Congestion Management

# 🔥 News
- *2024.07*: &nbsp;🎉🎉 Paper: Pyrrha accepted by NSDI 2025. Pyrrha is a flow control that controls transient congestion at a fine granularity without HOL blocking, requiring only a minimal number of queues.

# 📝 Publications 

<div class='paper-box-text' markdown="1">
- <span style="background-color: blue; color: white; font-size: 0.85em;">&nbsp;
  **NSDI'25** &nbsp;</span>
  *Pyrrha: Congestion-Root-Based Flow Control to Eliminate Head-of-Line Blocking in Datacenter*. 📄 [**Paper**](docs/paper/nsdi25-liukexin.pdf) 🌐 [**Code**](https://github.com/NASA-NJU/Pyrrha-NS3)

  - **Kexin Liu**\*, Zhaochen Zhang\*, Chang Liu, Yizhi Wang, Vamsi Addanki, Stefan Schmid, Qingyue Wang, Wei Chen, Xiaoliang Wang, Jiaqi Zheng, Wenhao Sun, Tao Wu, Ke Meng, Fei Chen, Weiguang Wang, Bingyang Liu, Wanchun Dou, Guihai Chen, Chen Tian
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: blue; color: white; font-size: 0.85em;">&nbsp;
  **CoNEXT'21** &nbsp;</span>
  *Floodgate: Taming Incast in Datacenter Networks*. 📄 [**Paper**](docs/paper/conext21-kexin.pdf) 🌐 [**Code**](https://github.com/NASA-NJU/Floodgate-NS3)

  - **Kexin Liu**, Chen Tian, Qingyue Wang, Hao Zheng, Peiwen Yu, Wenhao Sun, Yonghui Xu, Ke Meng, Lei Han, Jie Fu, Wanchun Dou, and Guihai Chen
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: green; color: white; font-size: 0.85em;">&nbsp;
  TON'25 &nbsp;</span>
  *An Anatomy of Token-based Congestion Control*. 📄 [**Paper**](docs/paper/ton25-kexin.pdf)

- **Kexin Liu**, Chang Liu, Qingyue Wang, Zhiqiang Li, Lu Lu, Xiaoliang Wang, Fu Xiao, Ying Zhang, Wanchun Dou, Guihai Chen, Chen Tian.
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: blue; color: white; font-size: 0.85em;">&nbsp;
  APNet'23 &nbsp;</span>
  *Dilemma of Proactive Congestion Control Protocols*. 📄 [**Paper**](docs/paper/apnet25-kexin.pdf) 

  - **Kexin Liu**, Chen Tian, Xiaoliang Wang, Wanchun Dou, Guihai Chen. 
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: green; color: white; font-size: 0.85em;">&nbsp;
  TPDS'22 &nbsp;</span>
  *PayDebt: Reduce Buffer Occupancy Under Bursty Traffic on Large Clusters*. 📄 [**Paper**](docs/paper/tpds22-kexin.pdf) 

  - **Kexin Liu**, Chen Tian, Qingyue Wang, Yanqing Chen, Bingchuan Tian, Wenhao Sun, Ke Meng, Long Yan, Lei Han, Jie Fu, Wanchun Dou, and Guihai Chen.
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: green; color: white; font-size: 0.85em;">&nbsp;
  TPDS'20 &nbsp;</span>
  *Exploring Token-oriented In-network Prioritization in Datacenter Networks*. 📄 [**Paper**](docs/paper/tpds20-kexin.pdf) 

  - **Kexin Liu**, Bingchuan Tian, Chen Tian, Bo Li, Qingyue Wang, Jiaqi Zheng, Jiajun Sun, Yixiao Gao, Wei Wang, Guihai Chen, Wanchun Dou, Yanan Jiang, Huaping Zhou, Jingjie Jiang, Fan Zhang, and Gong Zhang
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: blue; color: white; font-size: 0.85em;">&nbsp;
  ICCCN'19 &nbsp;</span>
  *Error Recovery of RDMA Packets in Data Center Networks*. 📄 [**Paper**](docs/paper/icccn19-kexin.pdf) 

  - Yi Wang, **Kexin Liu**, Chen Tian, Bo Bai and Gong Zhang
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: green; color: white; font-size: 0.85em;">&nbsp;
  JPDC'21 &nbsp;</span>
  *Django: Bilateral Coflow Scheduling with Predictive Concurrent Connect*. 📄 [**Paper**](docs/paper/jpdc21-zheng.pdf) 

  - Jiaqi Zheng, Liulan Qin, **Kexin Liu**, Bingchuan Tian, Chen Tian, Bo Li, and Guihai Chen
</div>

<div class='paper-box-text' markdown="1">
- <span style="background-color: green; color: white; font-size: 0.85em;">&nbsp;
  CN'19 &nbsp;</span>
  *Scheduling Dependent Coflows to Minimize the Total Weighted Job Completion Time in Datacenters*. 📄 [**Paper**](docs/paper/bingchuan-cn.pdf) 

  - Bingchuan Tian, Chen Tian, Bingquan Wang, Bo Li, Zehao He, Haipeng Dai, **Kexin Liu**, Wanchun Dou, and Guihai Chen
</div>

# 📖 Educations
- *2017.09 - 2023.03*, Nanjing University, China. Ph.D. 
- *2013.07 - 2017.06*, Sun-yat Sen University, China. Bachelor.

# 💻 Work Experience
- *2023.07 - (Now)*, Huawei, China.
