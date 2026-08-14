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

我目前是腾讯混元世界模型团队的算法研究员，主要研究方向为视频世界模型。在此之前，我在腾讯混元应用模型中心工作，主要研究身份一致的视频生成模型。

我于[清华大学计算机科学与技术系](https://www.cs.tsinghua.edu.cn/)获得博士学位，导师为[张松海教授](https://www.cs.tsinghua.edu.cn/info/1117/3538.htm)和[王瑀屏教授](https://scholar.google.com/citations?hl=en&user=QqdDO64AAAAJ)。我所在的实验室是由[胡事民教授](https://scholar.google.com/citations?user=LDb4tb0AAAAJ&hl=en)创建的 CSCG 实验室。在攻读博士学位期间，我有三段精彩的实习经历：我在腾讯 AI Lab 实习了两年，与[康頔博士](https://scholar.google.com/citations?user=2ztThPwAAAAJ&hl=en)和[暴林超博士](https://linchaobao.github.io/)共同研究 3D 数字人表示与动画；我在蚂蚁研究院交互智能实验室实习了一年，与[王璇博士](https://xuanwangvc.github.io/)共同探索 3D 数字人生成与动画；我还作为阿里星实习生在淘天集团实习，研究数字人表情动画。在攻读博士学位之前，我在[北京科技大学计算机与通信工程学院](https://scce.ustb.edu.cn/)获得了学士学位。

我目前的研究兴趣集中在<span style="color:red; font-weight: bold;">视频世界模型、多模态生成和数字人 AI</span>。

# 🔥 新闻
- *2026.07*: &nbsp;🎉 **Goku** 被接收为 **ECCV 2026 Spotlight**！
- *2026.06*: &nbsp;🎉 **HarmoView** 在 arXiv 上发布！
- *2026.05*: &nbsp;🎉 **SpongeBob** 在 arXiv 上发布！
- *2025.07*: &nbsp; 我作为算法研究员加入**腾讯混元**。
- *2025.07*: &nbsp;🎉 两篇论文被 **ICCV 2025** 接收！
- *2025.03*: &nbsp;🎉 **MeGA** 被 **CVPR 2025** 接收！
- *2024.07*: &nbsp; 我作为实习生加入**蚂蚁集团**。
- *2023.08*: &nbsp;🎉 **Neural Point-based Volumetric Avatars** 被 **SIGGRAPH Asia 2023** 接收！
- *2023.07*: &nbsp;🎉 **LoLep** 被 **ICCV 2023** 接收！

# 📝 发表论文 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026 (Spotlight)</div><img src='images/goku_teaser.jpg' alt="sym" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Goku: A Million-Scale Universal Dataset and Benchmark for Instruction-Based Video Editing](https://arxiv.org/abs/2606.30599)

Sen Liang*, **Cong Wang***, Zhentao Yu, Fengbin Guan, Zhengguang Zhou, Teng Hu, Youliang Zhang, Yuan Zhou, Xin Li, Qinglin Lu, Zhibo Chen (* 共同一作)

[**Project**](http://flying-sky999.github.io/Goku.github.io/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- 我们介绍了 **Goku**，这是一个包含 200 万高质量视频编辑对的大规模数据集，将任务边界扩展到了多任务和结构性操作，同时还提出了 **Goku-Edit**（基于 MLLM 的双分支模型）和 **Goku-Bench** 以进行全面评估。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/harmoview_teaser.jpg' alt="sym" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[HarmoView: Harmonizing Multi-View Constraints for Identity-Consistent Video Generation](https://arxiv.org/abs/2606.10839)

**Cong Wang**, Zhentao Yu, Hongmei Wang, Weicong Liang, Zixiang Zhou, Zilin Yang, Jiarong Ou, Rui Chen, Yezhou Liu, Shiyu An, Yue Lu, Yuan Zhou, Qinglin Lu

[**Project**](https://conallwang.github.io/HarmoView_Pages/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- 我们提出了 **HarmoView**，这是一个用于**身份一致视频生成**的鲁棒框架，它通过三种架构改进（**多级特征注入**、**可学习的代理 token** 和 **Jump-RoPE**）有效地整合了**多视角线索**，并结合**渐进式视角课程**，在预训练的 T2V 模型上实现了稳定的多视角训练。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/spongebob_teaser.jpg' alt="sym" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[SpongeBob: Sync-Aware Harmonious Audio-Visual Generative Editing](https://arxiv.org/abs/2605.25193)

Sen Liang, **Cong Wang**, Fengbin Guan, Zhentao Yu, Yiting Lu, Yuanzhi Wang, Yuan Zhou, Xin Li, Zhibo Chen

[**Project**](https://hy-spongebob.github.io/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- SpongeBob 是**首个端到端的音视频联合编辑框架**，基于双流 DiT 构建，具有用于时空对齐的**同步感知编辑机制**和用于保持内容一致性的**上下文感知模块**，实现了和谐的视频-音频协同编辑。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/pipeline.png' alt="sym" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[SVG-Head: Hybrid Surface-Volumetric Gaussians for High-Fidelity Head Reconstruction and Real-Time Editing](https://arxiv.org/pdf/2508.09597)

He-Yi Sun, **Cong Wang**, Tian-Xing Xu, Jingwei Huang, Di Kang, Chunchao Guo, Song-Hai Zhang

[**Project**](https://heyy-sun.github.io/SVG-Head/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- 通过提出 **surf-GS 用于将全局外观建模为纹理图像**，以及 **vol-GS 用于非朗伯区域的高保真渲染**，SVG-Head 不仅支持高质量渲染，还支持实时、细粒度的纹理编辑。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/finegrained_teaser.jpg' alt="sym" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-Grained 3D Gaussian Head Avatars Modeling from Static Captures via Joint Reconstruction and Registration](https://openaccess.thecvf.com/content/ICCV2025/papers/Sun_Fine-Grained_3D_Gaussian_Head_Avatars_Modeling_from_Static_Captures_via_ICCV_2025_paper.pdf)

Yuan Sun, Xuan Wang, **Cong Wang**, WeiLi Zhang, Yanbo Fan, Yu Guo, Fei Wang

[**Paper**](https://openaccess.thecvf.com/content/ICCV2025/html/Sun_Fine-Grained_3D_Gaussian_Head_Avatars_Modeling_from_Static_Captures_via_ICCV_2025_paper.html) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- 我们将从静态采集中进行 3D 高斯头部数字人建模转化为一个**联合重建和配准**问题，优化了**基于先验**和**无先验**的两组高斯，并通过**非刚性 ICP** 将它们绑定，生成了高分辨率的细粒度可驱动数字人。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/mega_teaser.jpg' alt="sym" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[MeGA: Hybrid Mesh-Gaussian Head Avatar for High-Fidelity Rendering and Head Editing](https://arxiv.org/abs/2404.19026)

**Cong Wang**, Di Kang, He-Yi Sun, Shen-Han Qian, Zi-Xuan Wang, Linchao Bao, Song-Hai Zhang

[**Project**](https://conallwang.github.io/MeGA_Pages/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- 通过提出**为人类头部的不同部分使用更合适的表示方法**以及相应的**混合渲染方法**，我们生成了**高质量**的 3D 人头数字人，并首次**支持人头编辑**（即纹理编辑和头发更改）。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia 2023</div><img src='images/npva_teaser.jpg' alt="sym" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[Neural Point-based Volumetric Avatar: Surface-guided Neural Points for Efficient and Photorealistic Volumetric Head Avatar](https://dl.acm.org/doi/10.1145/3610548.3618204)

**Cong Wang**, Di Kang, Yan-Pei Cao, Linchao Bao, Ying Shan, Song-Hai Zhang

[**Project**](https://conallwang.github.io/npva.github.io/) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:9yKSN-GCB0IC'></span></strong>
- 我们提出了一种新的**表面引导的神经点表示方法**以及相应的**渲染加速方法**，大大提高了 3D 数字人头建模中**眼睛和口腔内部**的渲染质量。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/lolep_teaser.jpg' alt="sym" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[LoLep: Single-View View Synthesis with Locally-Learned Planes and Self-Attention Occlusion Inference](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_LoLep_Single-View_View_Synthesis_with_Locally-Learned_Planes_and_Self-Attention_Occlusion_ICCV_2023_paper.pdf)

**Cong Wang**, Yu-Ping Wang, Dinesh Manocha

[**Project**](None) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:2osOgNQ5qMEC'></span></strong>
- 我们提出使用 **NN 采样器**来获得**更确定和合理的 MPI 平面位置**，并引入了重投影损失来促进采样器的学习。此外，我们提出了**块自注意力机制**来增强网络对遮挡区域的推理能力。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2022</div><img src='images/motionhint_pipe.png' alt="sym" width="100%" loading="lazy"></div></div>
<div class='paper-box-text' markdown="1">

[MotionHint: Self-Supervised Monocular Visual Odometry with Motion Constraints](https://dl.acm.org/doi/abs/10.1109/ICRA46639.2022.9812288)

**Cong Wang**, Yu-Ping Wang, Dinesh Manocha

[**Project**](https://github.com/conallwang/MotionHint) <strong><span class='show_paper_citations' data='0gSn6sgAAAAJ:u5HHmVD_uO8C'></span></strong>
- 我们通过**预训练的 PPNet** 引入了相机载体（主要是无人车）的**运动先验**，从而可以根据运动先验校正预测的相机姿态，取得了最先进的结果。
</div>
</div>

- [ORBBuf: A robust buffering method for remote visual SLAM](https://dl.acm.org/doi/abs/10.1109/IROS51168.2021.9635950), Yu-Ping Wang, Zi-xin Zou, **Cong Wang**, et al. **IROS 2021**


# 🎖 荣誉奖项
- *2024.11* **华为奖学金** (¥20,000) 
- *2024.07* **2023 腾讯 AI Lab 犀牛鸟精英人才，卓越奖**
- *2023.10* 二等奖学金 (¥5,000)
- *2023.09* 龙湖奖学金 (¥5,000)
- *2023.05* **2023 腾讯 AI Lab 犀牛鸟精英人才**
- *2022.10* 二等奖学金 (¥5,000)
- *2022.09* 龙湖奖学金 (¥5,000)
- *2020.06* **北京市优秀毕业生** (Top 5%)
- *2019.11* **国家奖学金** (¥8,000, 1/446)
- *2019.04* 美国大学生数学建模竞赛，一等奖 (Top 4%)
- *2018.11* **国家奖学金** (¥8,000, 1/446)
- *2018.04* 美国大学生数学建模竞赛，一等奖 (Top 4%)
- *2017.11* 人民特等奖学金 (¥5,000, 1/145)
- *2017.11* “冠之”奖学金 (¥10,000, 1/446)

# 📖 教育背景
- *2020.09 - 2025.06*，博士生，清华大学计算机科学与技术系，北京。
- *2016.09 - 2020.06*，本科生，北京科技大学计算机与通信工程学院，北京。

# 💬 邀请报告
- *2023.12*，"Neural Point-based Volumetric Avatar: Surface-guided Neural Points for Efficient and Photorealistic Volumetric Head Avatar" 口头报告，SIGGRAPH Asia 2023，澳大利亚新南威尔士州悉尼。
- *2023.11*，展示我的论文，受[中国图象图形学报](http://www.cjig.cn/jig/ch/index.aspx)邀请，[bilibili 视频](https://www.bilibili.com/video/BV1o64y177Ny/?spm_id_from=333.337.search-card.all.click&vd_source=b4eed9deaadbce01a5a20c7c9374a85e)
- *2022.07*，展示我的论文，受[将门创投](https://www.bkunyun.com/)邀请，[bilibili 视频](https://www.bilibili.com/video/BV1cB4y1C7Zw/?spm_id_from=333.337.search-card.all.click)
- *2022.05*，"MotionHint: Self-Supervised Monocular Visual Odometry with Motion Constraints" 口头报告，ICRA 2022，美国宾夕法尼亚州费城。

# 💻 工作经历
- *2025.07 - 至今*，腾讯混元，北京。
- *2025.05 - 2025.07*，淘天集团，杭州。
- *2024.07 - 2025.05*，蚂蚁集团，杭州。
- *2022.07 - 2024.07*，腾讯 AI Lab，北京。
