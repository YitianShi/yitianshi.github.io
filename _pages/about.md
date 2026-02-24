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

I am **Yitian Shi** (施逸天), PhD candidate at the [Institute for Material Handling and Logistics (IFL)](https://www.ifl.kit.edu/english/index.php), [Karlsruhe Institute of Technology (KIT)](https://www.kit.edu/english/).

My research interests include robotic grasp learning, robotic manipulation systems and uncertainty estimation.

# 🤖 Highlights
<div style="text-align: center;">
  <img src="/images/icra25.gif" alt="Real world grasping with vMF-Contact from ICRA25" title="vMF-Contact from ICRA25" style="max-width: 90%; height: auto;">
  <p style="margin-top: 10px; font-size: 16px; font-weight: bold;"><a href="https://www.youtube.com/watch?v=mmQ4Ps8b3DI">Uncertainty-aware 6-DoF Grasping (ICRA25)</a></p>
</div>

<div style="text-align: center;">
  <img src="/images/icra24.gif" alt="Offline-to-online Grasp Learning" title="Offline-to-online Grasp Learning" style="max-width: 50%; height: auto;">
  <p style="margin-top: 10px; font-size: 16px; font-weight: bold;"><a href="https://www.youtube.com/watch?v=Rr2QwIA2J4s">Offline-to-online Grasp Learning (ICRA24)</a></p>
</div>

<div style="text-align: center;">
  <img src="/images/isaac.gif" alt="MetaIsaacGrasp Simulation" title="MetaIsaacGrasp" style="max-width: 40%; height: auto;">
  <p style="margin-top: 10px; font-size: 16px; font-weight: bold;"><a href="https://github.com/YitianShi/MetaIsaacGrasp">MetaIsaacGrasp: Isaac Lab-based Simulation for Grasping</a></p>
</div>

<span class='anchor' id='-news'></span>

# 🔥 News
- *2026.02*: &nbsp; 3 papers accepted by ICRA 🎉🎉
- *2026.02*: &nbsp; 1 co-authored paper accepted by ICLR 🎉🎉 
- *2025.06*: &nbsp; 1 paper accepted by IROS 🎉🎉

<span class='anchor' id='-education'></span>

# 🎓 Education

- **Ph.D. Candidate**, Institute for Material Handling and Logistics (IFL), Karlsruhe Institute of Technology (KIT) (10/2023 - Present)
- **M. Sc. Electromobility (Autonomous and Connected Driving)**, University of Stuttgart (10/2020 - 04/2023)
- **B. Sc. Mechanical Engineering (Sino-German Program)**, Hochschule Furtwangen, Villingen-Schwenningen (10/2019 - 07/2020)
- **B. Sc. Mechanical Engineering**, University of Shanghai for Science and Technology (USST) (09/2016 - 07/2020) (*Award: College Graduate Excellence Award of Shanghai, 2020*)


<span class='anchor' id='-professional-experience'></span>
# 💼 Professional Experience

- **10/2023 - Present**: Research Associate, Artificial Intelligence & Robotics, Institute for Material Handling and Logistics (IFL), KIT
- **11/2022 - 04/2023**: Research Assistant, Bosch Center for Artificial Intelligence (BCAI), Renningen
  - *Thesis title*: Uncertainty-driven exploration strategies for online learning in robotic grasping
- **04/2022 - 10/2022**: Research Assistant, Institute for Signal Processing and System Theory (ISS), University of Stuttgart
  - *Thesis title*: A Bayesian Approach for Unsupervised Domain Adaptation in 2D Object Detection
- **04/2022 - 10/2022**: Research Assistant, Research Institute for Automotive Engineering and Vehicle Engines Stuttgart (FKFS)


<span class='anchor' id='-teaching'></span>

# 🏫 Teaching

- Machine Learning for Robotic Systems 1&2
- Praktikum: Machine Learning for Robotics


<span class='anchor' id='-project'></span>

# ⚙️ Project

- SFB-1574 Circular Factory [[Link]](https://www.sfb1574.kit.edu/english/355.php) 

<span class='anchor' id='-publications'></span>


# 📖 Publications

## Selected publications

<div class='paper-box'><div class='paper-box-image'><div><img src='images/icra26.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

- **HOGraspFlow: Taxonomy-Aware Hand–Object Retargeting for Multi-Modal SE(3) Grasp Generation**

  **Y Shi**, Z Guo, R Wolf, E Welte, R Rayyes

  *2026 IEEE International Conference on Robotics and Automation (ICRA)*
  [[Link]](https://arxiv.org/abs/2509.16871)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/icra25.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
- **vMF-Contact: Uncertainty-aware Evidential Learning for Probabilistic Contact-grasp in Noisy Clutter**

  **Y Shi**, E Welte, M Gilles, R Rayyes

  *2025 IEEE International Conference on Robotics and Automation (ICRA)*
  [[Link]](https://ieeexplore.ieee.org/document/11127888)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/iros25.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
- **VISO-Grasp: Vision-Language Informed Spatial Object-centric 6-DoF Active View Planning and Grasping in Clutter and Invisibility**

  **Y Shi**, D Wen, G Chen, E Welte, S Liu, K Peng, R Stiefelhagen, R Rayyes

  *2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*
  [[Link]](https://ieeexplore.ieee.org/document/11246329)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/icra24.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

- **Uncertainty-driven Exploration Strategies for Online Grasp Learning**

  **Y Shi**, P Schillinger, M Gabriel, A Kuss, Z Feldman, H Ziesche, NA Vien

  *2024 IEEE International Conference on Robotics and Automation (ICRA)*
  [[Link]](https://ieeexplore.ieee.org/document/10610056)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/survey.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
- **Diffusion Models for Robotic Manipulation: A Survey**

  R Wolf, **Y Shi**, S Liu, R Rayyes

  *Frontiers in Robotics and AI*
  [[Link]](https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2025.1606247/full)
</div>
</div>

- **Human-Interpretable Uncertainty Explanations for Point Cloud Registration**

  JA Gaus, L Schneider, **Y Shi**, J Lee, R Rayyes, R Triebel

  *2026 IEEE International Conference on Robotics and Automation (ICRA)*
  [[Link]](https://arxiv.org/abs/2509.18786)

- **Mica: Multi-agent industrial coordination assistant**

  D Wen, K Peng, J Zheng, Y Chen, **Y Shi**, J Wei, R Liu, K Yang, et al.

  *2026 IEEE International Conference on Robotics and Automation (ICRA)*
  [[Link]](https://arxiv.org/abs/2509.15237)

- **A Control Architecture for Robust and Resilient Circular Factories under Uncertain Conditions**

  F Bail, J Baumgärtner, F Erlenbusch, A Ernst, M Poyer, E Blum, **Y Shi**, et al.

  *Procedia CIRP*
  [[Link]](https://www.sciencedirect.com/science/article/pii/S221282712500633X)

- **A Knowledge-Based Intralogistic System for a Circular Factory**

  JF Klein, R Wolf, A Ernst, **Y Shi**, P Schumacher, RB Thapa, R Rayyes, et al.

  *Logistics Journal: Proceedings*, 2025
  [[Link]](https://proc.logistics-journal.de/article/view/1194)

## Workshop papers

<div class='paper-box'><div class='paper-box-image'><div><img src='images/RSS_best_paper_award.jpg' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

- **Enhancing Robotic Grasping with Uncertainty-Aware Exploration for Unseen Objects**

  **Y Shi**, AV Ngo, R Rayyes

  *RSS 2024 Workshop on "Open-Set Robot Perception in the Wild"* (**Best Paper Award**)
  [[Link]](https://www.researchgate.net/profile/Rania-Rayyes/publication/386159923_Enhancing_Robotic_Grasping_with_Uncertainty-Aware_Exploration_for_Unseen_Objects/links/6746d984f309a268c00f195b/Enhancing-Robotic-Grasping-with-Uncertainty-Aware-Exploration-for-Unseen-Objects.pdf)


</div>
</div>

- **Grasp the Invisibility by Vision-Language guided Active View Planning**

  **Y Shi**, D Wen, E Welte, K Peng, R Stiefelhagen, R Rayyes

  *ICRA 2025 Workshop on "Language and Semantics of Task and Motion Planning"*
  [[Link]](https://dyalab.mines.edu/2025/icra-workshop/2.pdf)



