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

# Profile

I have been a postdoctoral researcher at Hangzhou Dianzi University since September 2025, supervised by Prof. Chongyang Deng. I obtained my Ph.D. degree from Hangzhou Dianzi University, advised by Prof. Chongyang Deng. Before that, I received my B.S. degree from Southwest University of Science and Technology in 2020. 

My research interests focus on computer aided geometric design (CAGD), particularly the construction and applications of polygonal domain surfaces and polyhedral domain volumes.

Although I majored in mathematics, I'm not particularly good at it. X_X So I prefer using simple math in my research...

# 🔥 News

- *2026.08*: I have been awarded a grant under the NSFC Young Scientists Fund (Category C)! &nbsp;🎉
- *2026.08*: 1 paper (journal track) is conditionally accepted to PG 2026! &nbsp;🎉
- *2026.07*: My poster on C^0 generalized Coons volumes won the Best Poster Award at CSIAM GDC 2026. &nbsp;🎉


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PG 2026 (CGF)</div><img src='images/IVGCP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Image Vectorization with Generalized Coons Patches](https://kaikai-qin.github.io/)         
Yan Jing, [Kai Hormann](https://www.inf.usi.ch/hormann/), **Kaikai Qin**, Chongyang Deng\*                                             
[**Paper**](https://github.com/kaikai-qin/kaikai-qin.github.io/blob/main/images/2026-CGF-Image%20Vectorization%20with%20Generalized%20Coons%20Patches.pdf)
- In this paper, we presented an image vectorization method based on C0 generalized Coons patches.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH 2026</div><img src='images/papers_464s3.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[C^0 Generalized Coons Volumes over Arbitrary Polyhedra](https://dl.acm.org/doi/10.1145/3799902.3811087)         
**Kaikai Qin**#, [Zeqi Ge](https://gezeqi.github.io/)#, [Péter Salvi](https://www.iit.bme.hu/users/dr-salvi-p%C3%A9ter?language=en), Chenhao Ying, [Huibiao Wen](https://huibiaowen.github.io/), [Kepeng Xu](https://kepengxu.github.io/), [Shiqing Xin](https://irc.cs.sdu.edu.cn/~shiqing/index.html), Chongyang Deng\*                                             
[**Paper**](https://github.com/kaikai-qin/kaikai-qin.github.io/blob/main/images/2026-SIGGRAPH-C^0 Generalized Coons Volumes over Arbitrary Polyhedra.pdf)
- In this paper, we generalize the Coons volume from hexahedral topology to arbitrary polyhedral topologies via generalized barycentric coordinates. We prove that the proposed generalized Coons volume possesses several desirable geometric properties and demonstrate its applications in computer graphics.
- Thanks also to Dr. [Dong Xiao](https://submanifold.github.io/), [Shibo Liu](https://liu43.github.io/) and Qi Zhang from University of Science and Technology of China, for their generous sharing of models and high-order cages!
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH 2026 (TOG)</div><img src='images/papers_255s3.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PR-Cage: Progressive Feasibility Relaxation for Tight Bounding Cage Generation](https://dl.acm.org/doi/10.1145/3811300)         
[Huibiao Wen](https://huibiaowen.github.io/), **Kaikai Qin**, Xinxin Su, Jingcheng Mei, Shuangmin Chen, Chongyang Deng, [Changhe Tu](https://irc.cs.sdu.edu.cn/~chtu/index.html), [Shiqing Xin](https://irc.cs.sdu.edu.cn/~shiqing/index.html)\*, [Wenping Wang](https://engineering.tamu.edu/cse/profiles/Wang-Wenping.html)          
[**Paper**](https://github.com/kaikai-qin/kaikai-qin.github.io/blob/main/images/2026-TOG-PR-Cage%3D%20Progressive%20Feasibility%20Relaxation%20for%20Tight%20Bounding%20Cage%20Generation.pdf)
- PR-Cage is an automated framework for generating high-quality cages—simplified mesh proxies that tightly enclose complex geometry. Using a staircase relaxation of a thickness parameter and constrained QEM optimization, it achieves extreme simplification while preserving shape fidelity, enabling efficient contact simulation, deformation, and other graphics applications.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CAD/Graphics 2025 (CSIAM-AM)</div><img src='images/2D high-order cbd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[2D High-order Cage-based Deformation by Polygonal Surface Patches]( https://doi.org/10.4208/csiam-am.SO-2025-0069)         
[Zeqi Ge](https://gezeqi.github.io/), **Kaikai Qin\***, Chongyang Deng, and [Li-yong Shen](https://people.ucas.ac.cn/~shenly)                                                                                                         
[**Paper**](https://github.com/kaikai-qin/kaikai-qin.github.io/blob/main/images/2026-CSIAM AM-2D High-order Cage-based Deformation by Polygonal Surface Patches.pdf)
- A unified framework of 2D high-order cage-based deformation by using polygonal surface patches.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia 2024 (TOG)</div><img src='images/c0deformation.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ C^0 Generalized Coons Patches for High-order Cage-based Deformation](https://dl.acm.org/doi/10.1145/3687972)   
[**Paper**](https://github.com/kaikai-qin/kaikai-qin.github.io/blob/main/images/2024-TOG-C0 Generalized Coons Patches for High-order Cage-based Deformation.pdf)  
**Kaikai Qin**, Yunhao Zhou, Chenhao Ying, Yajuan Li, and Chongyang Deng*
- A generalization of the Coons patch via generalized barycentric coordinates.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CAGD 2024</div><img src='images/gbv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ Generalized Bézier volumes over simple convex polyhedra](https://www.sciencedirect.com/science/article/abs/pii/S0167839624000724)   
[**Paper**](https://github.com/kaikai-qin/kaikai-qin.github.io/blob/main/images/2024-CAGD-Generalized Bezier Volume over Simple Convex Polyhedra.pdf)   
 **Kaikai Qin**, Yajuan Li, and Chongyang Deng*
- A 3D extension of the [Generalized Bézier \(GB\) patch](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.12833).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CAGD 2023</div><img src='images/bbp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ Blending Bézier patch for multisided surface modeling](https://www.sciencedirect.com/science/article/abs/pii/S0167839623000547)   
[**Paper**](https://github.com/kaikai-qin/kaikai-qin.github.io/blob/main/images/2023-CAGD-Blending Bézier patch for multi-sided surface modeling.pdf)   
 **Kaikai Qin**, Yajuan Li, and Chongyang Deng*
- A multi-sided Bézier patch by Gregory corner blending.
</div>
</div>


# 📝 Acknowledgements 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CAGD</div><img src='images/salvi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ Genuine multi-sided parametric surface patches – A survey](https://www.sciencedirect.com/science/article/pii/S0167839624000207)        
 Tamás Várady, Péter Salvi, Márton Vaitkus
- A very comprehensive survey on multi-sided surfaces. If you are interested in multi-sided surfaces, this would be a great starting point.
</div>
</div>

# 🎖 Honors and Awards and Grants
- *2026.08*: NSFC Young Scientists Fund (Category C), CNY 300000, *2027.01-2029.12*
- *2026.07*: Best Poster Award of CSIAM GDC 2026
- *2026.05*: Excellent Doctoral Dissertation Award of Hangzhou Dianzi University
- *2025.08*: Best Poster Award of the union conference of CCF CAD&CG and CSIAM GDC 2025
- *2025.01*: Second Prize of the Graduate Innovation Scholarship of the "Qiu Junping and Yan Jinlian Graduate Education Award Fund"
- *2024.07*: First Prize in the 2024 Excellent Paper Selection of Zhejiang Applied Mathematics Research Association
- *2024.07*: Hangzhou Dianzi University 2024 Excellent Doctoral Dissertation Cultivation Project Approved 

# 📖 Educations and Experiences
- *2025.09 - Now*, Postdoctoral researcher, Hangzhou Dianzi University, Hangzhou, China.
- *2022.09 - 2025.06*, Ph.D., Applied Mathematics, Hangzhou Dianzi University, Hangzhou, China.
- *2020.09 - 2022.06*, M.S., Applied Mathematics, Hangzhou Dianzi University, Hangzhou, China. 
- *2016.09 - 2020.06*, B.S., Information and Computing Science, Southwest University of Science and Technology, Mianyang, China.  

# 💬 Invited Talks
- *2025.08*, I attended CAD/Graphics 2025 in Yantai, China, and gave a talk titled "2D High-order Cage-based Deformation by Polygonal Surface Patches".
- *2025.06*, Invited by Dr. [Márton Vaitkus](https://www.iit.bme.hu/users/dr-vaitkus-m%C3%A1rton), I have presented our work "C^0 Generalized Coons Patches for High-order Cage-based Deformation" at CGTA (Conference on Geometry: Theory and Applications) 2025 held in Sopron, Hungary. \(better than my last CGTA talk~~ ^-^ \)
- *2024.12*, I attended SIGGRAPH Asia 2024 in Tokyo, Japan, and gave a talk titled "C^0 Generalized Coons Patches for High-order Cage-based Deformation". \(It really is an amazing experience!!! :D \)
- *2023.06*, Invited by Dr. [Péter Salvi](https://www.iit.bme.hu/users/dr-salvi-p%C3%A9ter?language=en) to attend the CGTA (Conference on Geometry: Theory and Applications) 2023 held in Linz, Austria, and gave a talk entitled "Blending Bézier patch for multisided surface modeling" at the conference. \(A really really bad talk... T_T \)

