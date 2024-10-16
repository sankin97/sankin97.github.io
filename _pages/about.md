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
# About Me
I am currently a postdoctoral researcher at the Shanghai Jiao Tong University, working with Prof. [Cewu Lu](https://scholar.google.com/citations?user=QZVQEWAAAAAJ). I received Ph.D. degree in the School of [Computer Science and Technology, East China Normal University](http://www.cs.ecnu.edu.cn/), advised by Prof. [Liang He](https://faculty.ecnu.edu.cn/_s16/hl2/main.psp). My research focuses on 3D Vision, Autonomous Driving, Embodied AI.

I am fortunate to have research attachments and internships at [Shanghai AI Lab](https://www.shlab.org.cn).

**<font color=red> Here is my <a href='works/cv_en.pdf'>CV</a>. Please feel free to drop me an <a href="mailto: sankin0528@gmail.com">email</a> if you have any interests.</font>**
<!-- Here is my <a href="works/lixin_cv.pdf">CV</a> -->

# 🔥 News
- *2024.09*: &nbsp;🔥🔥🔥 One paper (LeapAD) is accepted by NeurIPS 2024.
- *2024.02*: &nbsp;🎉 One paper (M3Net) is accepted by CVPR 2024.
- *2024.01*: &nbsp;🎉  One paper (DiLu) is accepted by ICLR 2024.
- *2023.07*: &nbsp;🎉🎉🎉 Three papers (Robo3D, DetZero and UniSeg) are accepted by ICCV 2023.
- *2023.03*: &nbsp;🎉 Our offline-method DetZero ranked 1st on 85.15 mAPH (L2) on Waymo 3D detection leaderboard.
- *2023.02*: &nbsp;🎉🎉 Two papers (LoGoNet and SCPNet) are accepted by CVPR 2023.
- *2022.10*: &nbsp;🎉 Our LoGoNet ranked 1st on Waymo 3D detection leaderboard. 
- *2022.02*: &nbsp;🎉 One paper (HMFI) is accepted by ECCV 2022. 

# 📝 Recent Publications [\[Google Scholar\]](https://scholar.google.com/citations?user=7atts2cAAAAJ&hl=zh-CN) 
\* *indicates equal contribution*
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/paper/leapad.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Continuously Learning, Adapting, and Improving: A Dual-Process Approach to Autonomous Driving**

Jianbiao Mei Yukai Ma, Xuemeng Yang, Licheng Wen, Xinyu Cai, **Xin Li**, Daocheng Fu, Bo Zhang, Pinlong Cai, Min Dou, Botian Shi, Liang He, Yong Liu1, Yu Qiao

[Neural Information Processing Systems (NeurIPS), 2024](https://neurips.cc/)

[**PDF**](https://arxiv.org/abs/2405.15324) | [**Code**](https://github.com/PJLab-ADG/LeapAD) ｜ [**Home**](https://leapad-2024.github.io/LeapAD/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/paper/m3net.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Multi-Space Alignments Towards Universal LiDAR Segmentation**

Youquan Liu, Lingdong Kong, Xiaoyang Wu, Runnan Chen, **Xin Li**, Liang Pan, Ziwei Liu, Yuexin Ma  

[Computer Vision and Pattern Recognition (CVPR), 2024](https://cvpr.thecvf.com/Conferences/2024)

[**PDF**](https://arxiv.org/pdf/2405.01538) | [**Code**](https://github.com/youquanl/M3Net)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/paper/dilu.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DiLu🐴: A Knowledge-Driven Approach to Autonomous Driving with Large Language Models**

Licheng Wen\*, Daocheng Fu\*, **Xin Li\***, Xinyu Cai, Tao Ma, Pinlong Cai, Min Dou, Botian Shi, Liang He, Yu Qiao

[International Conference on Learning Representations (ICLR), 2024](https://iclr.cc/)

[**PDF**](https://arxiv.org/abs/2309.16292) | [**Code**](https://github.com/PJLab-ADG/DiLu) | [**Home**](https://pjlab-adg.github.io/DiLu) 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/paper/robo3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Robo3D: Towards Robust and Reliable 3D Perception against Corruptions**

Lingdong Kong\*, Youquan Liu\*, **Xin Li\***, Runnan Chen, Wenwei Zhang, Jiawei Ren, Liang Pan, Kai Chen, Ziwei Liu

[International Conference on Computer Vision (ICCV), 2023](https://iccv2023.thecvf.com/)

[**PDF**](https://arxiv.org/abs/2303.17597) | [**Code**](https://github.com/ldkong1205/Robo3D) | [**Home**](https://ldkong.com/Robo3D) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/paper/detzero.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DetZero: Rethinking Offboard 3D Object Detection with Long-term Sequential Point Clouds**

Tao Ma, Xuemeng Yang, Hongbin Zhou, **Xin Li**, Botian Shi, Junjie Liu, Yuchen Yang, Zhizheng Liu, Liang He, Yu Qiao, Yikang Li, Hongsheng Li

[International Conference on Computer Vision (ICCV), 2023](https://iccv2023.thecvf.com/)

[**PDF**](https://arxiv.org/abs/2306.06023) | [**Code**](https://github.com/PJLab-ADG/DetZero) 
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/paper/uniseg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**UniSeg: A Unified Multi-Modal LiDAR Segmentation Network and the OpenPCSeg Codebase**

Youquan Liu, Runnan Chen,  **Xin Li**, Lingdong Kong,  Yuchen Yang, Zhaoyang Xia, Yeqi Bai,Xinge Zhu, Yikang Li, Yuenan Hou, Yu Qiao

[International Conference on Computer Vision (ICCV), 2023](https://iccv2023.thecvf.com/)

[**PDF**](https://sankin97.github.io/) | [**Code**](https://github.com/PJLab-ADG/PCSeg) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/paper/logonet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LoGoNet: Towards Accurate 3D Object Detection with Local-to-Global Cross-Modal Fusion**

**Xin Li**, Tao Ma, Yuenan Hou, Botian Shi, Yuchen Yang, Youquan Liu, Xingjiao Wu, Qin Chen, Yikang Li, Yu Qiao, Liang He

[Computer Vision and Pattern Recognition (CVPR), 2023](https://cvpr.thecvf.com/)

[**PDF**](https://openaccess.thecvf.com/content/CVPR2023/html/Li_LoGoNet_Towards_Accurate_3D_Object_Detection_With_Local-to-Global_Cross-Modal_Fusion_CVPR_2023_paper.html) | [**Code**](https://github.com/PJLab-ADG/LoGoNet) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/paper/scpnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SCPNet: Semantic Scene Completion on Point Cloud**

Zhaoyang Xia, Youquan Liu, **Xin Li**, Xinge Zhu, Yuexin Ma, Yikang Li, Yuenan Hou, Yu Qiao

[Computer Vision and Pattern Recognition (CVPR), 2023](https://cvpr.thecvf.com/)

[**PDF**](https://openaccess.thecvf.com/content/CVPR2023/html/Xia_SCPNet_Semantic_Scene_Completion_on_Point_Cloud_CVPR_2023_paper.html) | [**Code**](https://github.com/SCPNet/Codes-for-SCPNet) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLRW 2023</div><img src='images/paper/iclrw2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Benchmarking 3D Perception Robustness to Common Corruptions and Sensor Failure**

Lingdong Kong\*, Youquan Liu\*, **Xin Li\***, Runnan Chen, Wenwei Zhang, Jiawei Ren, Liang Pan, Kai Chen, Ziwei Liu

[ICLR Workshop on Scene Representations for Autonomous Driving, 2023](https://opendrivelab.com/sr4ad/iclr23)

**<font color=red>Best Workshop Paper Award</font>**

[**PDF**](https://openreview.net/forum?id=pyi73rdeGP) | [**Code**](https://github.com/ldkong1205/Robo3D) | [**Home**](https://ldkong.com/Robo3D) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/paper/hmfi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Homogeneous Multi-modal Feature Fusion and Interaction for 3D Object Detection**

**Xin Li**, Botian Shi, Yuenan Hou, Xingjiao Wu, Tianlong Ma, Yikang Li, Liang He

[European Conference on Computer Vision (ECCV), 2022](https://eccv2022.ecva.net/)

[**PDF**](https://link.springer.com/chapter/10.1007/978-3-031-19839-7_40) | [**Code**](https://github.com/sankin97/HMFI) 
</div>
</div>



# 📖 Educations
- *2019.09 - 2024.06*, East China Normal University, Computer Science and technology. 
- *2015.09 - 2019.06*, China University of Petroleum (East China), Computer Science and technology. 

# 💬 Acadamic Services
- Conference Reviewer:
  - IEEE/CVF Computer Vision and Pattern Recognition Conference (CVPR)
  - IEEE/CVF International Conference on Computer Vision (ICCV)
  - European Conference on Computer Vision (ECCV)
  - Conference on Neural Information Processing Systems (NeurIPS)
  - Association for the Advancement of Artificial Intelligence (AAAI)

# 💻 Internships
- *2021.06 - 2024.06*, [Shanghai AI Lab](https://www.shlab.org.cn), Shanghai.
  - Mentor: [Botian Shi](https://scholar.google.com.hk/citations?user=K0PpvLkAAAAJ)

© Last Updated: Oct. 2024
