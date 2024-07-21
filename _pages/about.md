![image](https://github.com/user-attachments/assets/c205e4dd-74e2-465e-9dfb-0aa509038ebc)![image](https://github.com/user-attachments/assets/66105785-c878-4e2b-ae6a-9c86b2c1895a)---
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

我目前是[清华大学计算机科学与技术系](https://www.cs.tsinghua.edu.cn/)的一名博士生，导师是[张松海](https://www.cs.tsinghua.edu.cn/info/1117/3538.htm)副教授。在这之前，我在[北京科技大学计算机与通信工程学院](https://scce.ustb.edu.cn/)获得了我的学士学位。博士在读期间，曾在腾讯的AI Lab实习过两年的时间，主要从事3D数字人重建/编辑相关的研究工作，指导老师是康𬱖博士。现在蚂蚁集团的蚂蚁研究院实习，研究工作仍然聚焦于3D数字人重建/编辑/生成，指导导师是王璇博士。

<br>

目前我的研究兴趣主要聚焦在<span style="color:red; font-weight: bold;">3D数字人</span>和<span style="color:red; font-weight: bold;">计算机视觉</span>领域，包括3D数字人体/人头的创建和编辑，图像/视频的生成模型，以及新的3D表示方式。

<br>

另外，我正在攻读博士学位的第四年（总共五年），<span style="color:red; font-weight: bold;">将在2025年6月份毕业。</span>如果您正在寻找数字人算法工程师，欢迎联系我（wangcong20@mails.tsinghua.edu.cn），工作地点最好在北京或者周边。

<span class='anchor' id='news'></span>

# 🔥 新闻
- *2024.07*: &nbsp; 作为实习生入职蚂蚁研究院.
- *2023.08*: &nbsp;🎉 Neural Point-based Volumetric Avatars 被 **SIGRRAPH Asia 2023** 接受!
- *2023.07*: &nbsp;🎉 LoLep 被 **ICCV 2023** 接受!
- *2022.07*: &nbsp; 作为日常实习生入职腾讯AI Lab.
- *2022.02*: &nbsp;🎉 MotionHint 被 **ICRA 2022** 接受!


<span class='anchor' id='publications'></span>

# 📝 发表论文

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiV 2024</div><img src='images/mega_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MeGA: Hybrid Mesh-Gaussian Head Avatar for High-Fidelity Rendering and Head Editing](https://arxiv.org/abs/2404.19026)

**Cong Wang**, Di Kang, He-Yi Sun, Shen-Han Qian, Zi-Xuan Wang, Linchao Bao, Song-Hai Zhang

[**Project**](https://conallwang.github.io/MeGA_Pages/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- 提出使用**更加合适的表达方式来表达人头的不同部分**和相应的**混合渲染方法**，我们在保证**高质量** 3D 人头重建的基础上，**首次支持人头编辑**（面部涂鸦和发型替换）。

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia 2023</div><img src='images/npva_teaser.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neural Point-based Volumetric Avatar: Surface-guided Neural Points for Efficient and Photorealistic Volumetric Head Avatar](https://dl.acm.org/doi/10.1145/3610548.3618204)

**Cong Wang**, Di Kang, Yan-Pei Cao, Linchao Bao, Ying Shan, Song-Hai Zhang

[**Project**](https://conallwang.github.io/npva.github.io/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- 主要贡献：提出新的**表面引导的神经点表示**和相应的**渲染加速方法**，极大地改善了 3D 数字人建模中**眼睛和口腔内部**的渲染质量。

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/lolep_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LoLep: Single-View View Synthesis with Locally-Learned Planes and Self-Attention Occlusion Inference](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_LoLep_Single-View_View_Synthesis_with_Locally-Learned_Planes_and_Self-Attention_Occlusion_ICCV_2023_paper.pdf)

**Cong Wang**, Yu-Ping Wang, Dinesh Manocha

[**Project**](None) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:2osOgNQ5qMEC'></span></strong>
- 提出**使用神经网络采样器**，使推理时的 **MPI 平面位置更加确定且合理**，同时**引入重投影损失**来促进采样器的学习；利用 Attention 机制**提升网络对于遮挡部分的推理能力**。

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2022</div><img src='images/motionhint_pipe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MotionHint: Self-Supervised Monocular Visual Odometry with Motion Constraints](https://dl.acm.org/doi/abs/10.1109/ICRA46639.2022.9812288)

**Cong Wang**, Yu-Ping Wang, Dinesh Manocha

[**Project**](https://github.com/conallwang/MotionHint) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:u5HHmVD_uO8C'></span></strong>
- 提出通过预训练的 PPNet **引入相机载具（主要是无人驾驶汽车）的运动先验**，从而可以根据运动先验对网络预测的位姿进行矫正，得到 SOTA 的（理论上总是更好的）结果。

</div>
</div>

- [ORBBuf: A robust buffering method for remote visual SLAM](https://dl.acm.org/doi/abs/10.1109/IROS51168.2021.9635950), Yu-Ping Wang, Zi-xin Zou, **Cong Wang**, et al. **IROS 2021**


<span class='anchor' id='honors-and-awards'></span>

# 🎖 荣誉奖励
- *2024.07* **2023腾讯犀牛鸟精英人才计划 "优秀奖"**
- *2023.10* 清华大学综合奖学金 (5,000元)
- *2023.09* 龙湖奖学金 (5,000元)
- *2023.05* **2023腾讯犀牛鸟精英人才计划**
- *2022.10* 清华大学综合奖学金 (5,000元)
- *2022.09* 龙湖奖学金 (5,000元)
- *2020.06* **北京市优秀毕业生**（前5%）
- *2019.11* **国家奖学金** (8,000元, 1/446)
- *2019.04* 美国大学生数学建模大赛, Meritorious Winner (前4%)
- *2018.11* **国家奖学金** (8,000元, 1/446)
- *2018.04* 美国大学生数学建模大赛, Meritorious Winner (前4%)
- *2017.11* 人民特等奖学金 (5,000元, 1/145)
- *2017.11* 冠之奖学金 (10,000元, 1/446)

<span class='anchor' id='educations'></span>

# 📖 教育背景
- *2020.09 - now*, 博士生, 清华大学计算机科学与技术系, 北京.
- *2016.09 - 2020.06*, 本科生, 北京科技大学计算机科学与技术系, 北京.

<span class='anchor' id='talks'></span>

# 💬 邀请汇报
- *2023.12*, 针对论文"Neural Point-based Volumetric Avatar: Surface-guided Neural Points for Efficient and Photorealistic Volumetric Head Avatar"的口头报告, SIGGRAPH Asia 2023, 悉尼，新南威尔士州, 澳大利亚。
- *2023.11*, 受[中国图像图形学报](http://www.cjig.cn/jig/ch/index.aspx)邀请讲解论文, [bilibili视频](https://www.bilibili.com/video/BV1o64y177Ny/?spm_id_from=333.337.search-card.all.click&vd_source=b4eed9deaadbce01a5a20c7c9374a85e)
- *2022.07*, 受[北鲲云](https://www.bkunyun.com/)平台邀请讲解论文, [bilibili视频](https://www.bilibili.com/video/BV1cB4y1C7Zw/?spm_id_from=333.337.search-card.all.click)
- *2022.05*, 针对论文"MotionHint: Self-Supervised Monocular Visual Odometry with Motion Constraints"的口头报告，ICRA 2022, 费城, 宾夕法尼亚州, 美国。

<span class='anchor' id='internships'></span>

# 💻 实习经历
- *2022.07 - 2024.07*, 腾讯 AI Lab, 北京.
- *2022.07 - now*, 蚂蚁研究院, 杭州.
