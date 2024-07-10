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

Shuai

My research interests are centered around three-dimensional vision in robotics, encompassing areas such as image matching, equivariant representation learning, visual localization, and extrinsic calibration.
I have been invited to serve as a reviewer for conferences such as ICME, ICPR, ICRA, ICASSP, ICCVW and ECCVW.


# 🔥 News
- *2023.11*: &nbsp;🎉🎉 One paper accepted by IEEE Transactions on Intelligent Transportation Systems.
- *2023.11*: &nbsp;🎉🎉 One paper accepted by Neurocomputing.
- *2023.09*: &nbsp;🎉🎉 One paper accepted by IEEE Transactions on Instrumentation & Measurement
- *2023.09*: &nbsp;🎉🎉 One paper accepted by Neurocomputing.
- *2023.07*: &nbsp;🎉🎉 One paper accepted by ICCV-2023.
- *2023.01*: &nbsp;🎉🎉 One paper accepted by ICRA-2023.
- *2022.08*: &nbsp;🎉🎉 One paper accepted by ECCVW-2022.




# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurocomputing</div><img src='images/dream.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Rotation-equivariant correspondence matching based on a dual-activation mixer](https://www.sciencedirect.com/science/article/abs/pii/S0925231223011761)
**Shuai Su**, Ronghao Dang, Rui Fan, Chengju Liu, Qijun Chen
Learning-based correspondence matching methods have become the mainstream techniques in many computer vision and robotics applications due to their robustness to large illumination and viewpoint changes. However, it is difficult for conventional convolutional neural networks (CNNs) to extract rotation-equivariant local features. Recent work has shown that CNNs combined with group-equivariant architectures are surprisingly effective at matching correspondences even when the images are rotated to a dramatic extent. However, the inherent shape (square) of convolution kernels causes the performance bottleneck of such rotation-equivariant CNNs. To address this issue, we propose an adaptive dual rotation-equivariant correspondence matching algorithm, which performs stably at all angles. We mathematically analyze the effectiveness of our proposed rotation-equivariant correspondence matching approach and its performance with respect to different convolution kernels. Extensive experiments on the Rotated-HPatches, SIM2E, and MegaDepth datasets demonstrate the effectiveness of our proposed algorithm.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCVW</div><img src='images/sim2e.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[SIM2E: Benchmarking the Group Equivariant Capability of Correspondence Matching Algorithms](https://link.springer.com/chapter/10.1007/978-3-031-25056-9_47)
**Shuai Su**, Zhongkai Zhao, Yixin Fei, Shuda Li, Qijun Chen, Rui Fan
Correspondence matching is a fundamental problem in computer vision and robotics applications. Solving correspondence matching problems using neural networks has been on the rise recently. Rotation-equivariance and scale-equivariance are both critical in correspondence matching applications. Classical correspondence matching approaches are designed to withstand scaling and rotation transformations. However, the features extracted using convolutional neural networks (CNNs) are only translation-equivariant to a certain extent. Recently, researchers have strived to improve the rotation-equivariance of CNNs based on group theories. Sim(2) is the group of similarity transformations in the 2D plane. This paper presents a specialized dataset dedicated to evaluating sim(2)-equivariant correspondence matching algorithms. We compare the performance of 16 state-of-the-art (SoTA) correspondence matching approaches. The experimental results demonstrate the importance of group equivariant algorithms for correspondence matching on various sim(2) transformation conditions. Since the subpixel accuracy achieved by CNN-based correspondence matching approaches is unsatisfactory, this specific area requires more attention in future works.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA23</div><img src='images/transparentstereo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Transparent Objects: A Corner Case in Stereo Matching](https://ieeexplore.ieee.org/abstract/document/10161385)
Zhiyuan Wu; **Shuai Su**; Qijun Chen; Rui Fan
Stereo matching is a common technique used in 3D perception, but transparent objects such as reflective and penetrable glass pose a challenge as their disparities are often estimated inaccurately. In this paper, we propose transparency-aware stereo (TA-Stereo), an effective solution to tackle this issue. TA-Stereo first utilizes a semantic segmentation or salient object detection network to identify transparent objects, and then homogenizes them to enable stereo matching algorithms to handle them as non-transparent objects. To validate the effectiveness of our proposed TA-Stereo strategy, we collect 260 images containing transparent objects from the KITTI Stereo 2012 and 2015 datasets and manually label pixel-level ground truth. We evaluate our strategy with six deep stereo networks and two types of transparent object detection methods. Our experiments demonstrate that TA-Stereo significantly improves the disparity accuracy of transparent objects. Our project webpage can be accessed at mias.group/TA-Stereo.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurocomputing</div><img src='images/e3cm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[E3CM: Epipolar-constrained cascade correspondence matching](https://www.sciencedirect.com/science/article/pii/S0925231223009116)
Chenbo Zhou; **Shuai Su**; Qijun Chen; Rui Fan
Accurate and robust correspondence matching is of utmost importance for various 3D computer vision tasks. However, traditional explicit programming-based methods often struggle to handle challenging scenarios, and deep learning-based methods require large well-labeled datasets for network training. In this article, we introduce Epipolar-Constrained Cascade Correspondence (E3CM), a novel approach that addresses these limitations. Unlike traditional methods, E3CM leverages pre-trained convolutional neural networks to match correspondence, without requiring annotated data for any network training or fine-tuning. Our method utilizes epipolar constraints to guide the matching process and incorporates a cascade structure for progressive refinement of matches. We extensively evaluate the performance of E3CM through comprehensive experiments and demonstrate its superiority over existing methods.
</div>
</div>


# 📝 Projects
- Rotation-equivariant correspondence matching.
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Open</div><img src='images/repedesc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[RE]
**Shuai Su**, Qijun Chen
.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Open</div><img src='images/sdk.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
SDK
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Open</div><img src='images/predfm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
PREDFM
</div>
</div>

- Continous-time based Lidar-camera calibration.
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Project</div><img src='images/ctcalib.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Continous-time based Lidar-camera calibration.
</div></div>


- Visual localization system for human-computer interaction under heterogeneous cameras.
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Project</div><img src='images/UPVLoc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Visual Localization System for autonomous Parking in Underground garages.
</div></div>


# 📖 Educations
- *2020.09 - 2025.03*, Control Science and Engineering.
- *2016.09 - 2020.06*, Electronic and Information Engineering.


# 💻 Internships
- *2021.07 - 2021.10*, NIO Autonomous Driving Algorithm Department, Shanghai, China.
- *2023.04 - 2023.12*, Industrial robot production line, Machine Vision Department, Jiangsu, China.


