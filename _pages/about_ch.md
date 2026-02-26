---
permalink: /ch/
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /ch-about/
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

我是 **施逸天 (Yitian Shi)**，目前在[卡尔斯鲁厄理工学院 (KIT)](https://www.kit.edu/english/) [物料搬运与物流研究所 (IFL)](https://www.ifl.kit.edu/english/index.php) 攻读博士学位。

我的研究兴趣主要集中在**机器人抓取学习**、**机器人操纵系统**以及**不确定性估计**。

# 🤖 研究亮点
<div style="text-align: center;">
  <img src="/images/icra25.gif" alt="Real world grasping with vMF-Contact from ICRA25" title="vMF-Contact from ICRA25" style="max-width: 90%; height: auto;">
  <p style="margin-top: 10px; font-size: 16px; font-weight: bold;"><a href="https://www.youtube.com/watch?v=mmQ4Ps8b3DI">Uncertainty-aware 6-DoF Grasping (ICRA25)</a></p>
</div>

<div style="text-align: center;">
  <img src="/images/iros25.gif" alt="Real world grasping with vMF-Contact from ICRA25" title="vMF-Contact from ICRA25" style="max-width: 90%; height: auto;">
  <p style="margin-top: 10px; font-size: 16px; font-weight: bold;"><a href="https://www.youtube.com/watch?v=mmQ4Ps8b3DI">Target-oriented Active View for Grasping (IROS25)</a></p>
</div>

<div style="text-align: center;">
  <img src="/images/icra24.gif" alt="Offline-to-online Grasp Learning" title="Offline-to-online Grasp Learning" style="max-width: 45%; height: auto;">
  <p style="margin-top: 10px; font-size: 16px; font-weight: bold;"><a href="https://www.youtube.com/watch?v=Rr2QwIA2J4s">Offline-to-online Grasp Learning (ICRA24)</a></p>
</div>

<div style="text-align: center;">
  <img src="/images/isaac.gif" alt="MetaIsaacGrasp Simulation" title="MetaIsaacGrasp" style="max-width: 45%; height: auto;">
  <p style="margin-top: 10px; font-size: 16px; font-weight: bold;"><a href="https://github.com/YitianShi/MetaIsaacGrasp">MetaIsaacGrasp: Isaac Lab-based Simulation for Grasping</a></p>
</div>

<span class='anchor' id='-news'></span>

# 🔥 新闻动态
- *2026.02*: &nbsp; 1 篇论文获得德国机器人会议(GRC) 口头报告(20/244) 🎉🎉
- *2026.02*: &nbsp; 3 篇论文被 ICRA 录用 🎉🎉
- *2026.02*: &nbsp; 1 篇合作论文被 ICLR 录用 🎉🎉 
- *2025.06*: &nbsp; 1 篇论文被 IROS 录用 🎉🎉

<span class='anchor' id='-education'></span>

# 🎓 教育背景

- **博士研究生**, 卡尔斯鲁厄理工学院 (KIT), 物料搬运与物流研究所 (IFL) (2023.10 - 至今)
- **工学硕士 (电动汽车：自动驾驶与联网方向)**, 斯图加特大学 (2020.10 - 2023.04)
- **工学学士 (机械工程中德合作项目)**, 富特旺根应用技术大学 (2019.10 - 2020.07)
- **工学学士 (机械工程)**, 上海理工大学 (2016.09 - 2020.07) (*荣誉: 2020年上海市优秀毕业生*)


<span class='anchor' id='-professional-experience'></span>
# 💼 职业经历

- **2023.10 - 至今**: 研究助理, 人工智能与机器人组, KIT IFL 研究所
- **2022.11 - 2023.04**: 研究助理, 博世人工智能中心 (BCAI), 伦宁根
  - *硕士论文*: 机器人抓取在线学习中的不确定性驱动探索策略
- **2022.04 - 2022.10**: 研究助理, 斯图加特大学信号处理与系统理论研究所 (ISS)
  - *论文*: 一种用于2D目标检测无监督领域自适应的贝叶斯方法
- **2022.04 - 2022.10**: 研究助理, 斯图加特汽车工程与车辆发动机研究院 (FKFS)


<span class='anchor' id='-teaching'></span>

# 🏫 教学工作

- 机器人系统机器学习 1 & 2
- 实践课：机器人机器学习

<span class='anchor' id='-project'></span>

# ⚙️ 研究项目

- SFB-1574 循环工厂 (Circular Factory) [[项目链接]](https://www.sfb1574.kit.edu/english/355.php) 

<span class='anchor' id='-publications'></span>

# 📖 学术成果

## 精选论文

<div class='paper-box'><div class='paper-box-image'><div><img src='/images/icra26.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

- **HOGraspFlow: Taxonomy-Aware Hand–Object Retargeting for Multi-Modal SE(3) Grasp Generation**
  **Y Shi**, Z Guo, R Wolf, E Welte, R Rayyes
  *2026 IEEE International Conference on Robotics and Automation (ICRA)*
  [[链接]](https://arxiv.org/abs/2509.16871)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='/images/icra25.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
- **vMF-Contact: Uncertainty-aware Evidential Learning for Probabilistic Contact-grasp in Noisy Clutter**
  **Y Shi**, E Welte, M Gilles, R Rayyes
  *2025 IEEE International Conference on Robotics and Automation (ICRA)*
  [[链接]](https://ieeexplore.ieee.org/document/11127888)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='/images/iros25.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
- **VISO-Grasp: Vision-Language Informed Spatial Object-centric 6-DoF Active View Planning and Grasping in Clutter and Invisibility**
  **Y Shi**, D Wen, G Chen, E Welte, S Liu, K Peng, R Stiefelhagen, R Rayyes
  *2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*
  [[链接]](https://ieeexplore.ieee.org/document/11246329)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='/images/icra24.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

- **Uncertainty-driven Exploration Strategies for Online Grasp Learning**
  **Y Shi**, P Schillinger, M Gabriel, A Kuss, Z Feldman, H Ziesche, NA Vien
  *2024 IEEE International Conference on Robotics and Automation (ICRA)*
  [[链接]](https://ieeexplore.ieee.org/document/10610056)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/icra26.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

- **FlowCorrect: Efficient Interactive Correction of Generative Flow Policies for Robotic Manipulation**

  E, Welte, **Y Shi**, R Wolf, M Gilles, R Rayyes

  *under review*
  [[链接]](https://arxiv.org/abs/2602.22056)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/survey.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
- **Diffusion Models for Robotic Manipulation: A Survey**

  R Wolf, **Y Shi**, S Liu, R Rayyes

  *Frontiers in Robotics and AI*
  [[链接]](https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2025.1606247/full)
</div>
</div>

- **Go Beyond Earth: Understanding Human Actions and Scenes in Microgravity Environments**

  D Wen, L Qi, K Peng, K Yang, F Teng, A Luo, J Fu, Y Chen, R Liu, **Y Shi**, et al.

  *2026 International Conference on Learning Representations (ICLR)*
  [[链接]](https://arxiv.org/pdf/2506.02845)

- **Human-Interpretable Uncertainty Explanations for Point Cloud Registration**

  JA Gaus, L Schneider, **Y Shi**, J Lee, R Rayyes, R Triebel

  *2026 IEEE International Conference on Robotics and Automation (ICRA)*
  [[链接]](https://arxiv.org/abs/2509.18786)

- **Mica: Multi-agent industrial coordination assistant**

  D Wen, K Peng, J Zheng, Y Chen, **Y Shi**, J Wei, R Liu, K Yang, et al.

  *2026 IEEE International Conference on Robotics and Automation (ICRA)*
  [[链接]](https://arxiv.org/abs/2509.15237)

- **A Control Architecture for Robust and Resilient Circular Factories under Uncertain Conditions**

  F Bail, J Baumgärtner, F Erlenbusch, A Ernst, M Poyer, E Blum, **Y Shi**, et al.

  *Procedia CIRP*
  [[链接]](https://www.sciencedirect.com/science/article/pii/S221282712500633X)

- **A Knowledge-Based Intralogistic System for a Circular Factory**

  JF Klein, R Wolf, A Ernst, **Y Shi**, P Schumacher, RB Thapa, R Rayyes, et al.

  *Logistics Journal: Proceedings*, 2025
  [[链接]](https://proc.logistics-journal.de/article/view/1194)

## 工作坊 (Workshop) 论文

<div class='paper-box'><div class='paper-box-image'><div><img src='/images/RSS_best_paper_award.jpg' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

- **Enhancing Robotic Grasping with Uncertainty-Aware Exploration for Unseen Objects**
  **Y Shi**, AV Ngo, R Rayyes
  *RSS 2024 Workshop on "Open-Set Robot Perception in the Wild"* (**最佳论文奖**)
  [[链接]](https://www.researchgate.net/profile/Rania-Rayyes/publication/386159923_Enhancing_Robotic_Grasping_with_Uncertainty-Aware_Exploration_for_Unseen_Objects/links/6746d984f309a268c00f195b/Enhancing-Robotic-Grasping-with-Uncertainty-Aware-Exploration-for-Unseen-Objects.pdf)

</div>

</div>
