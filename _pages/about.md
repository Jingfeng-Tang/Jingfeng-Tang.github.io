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


I am a Ph.D. student in Computer Science and Technology at Northeastern University. Before that, I received my M.Sc. degree from the School of Computer Science and Communication Engineering, Jiangsu University. My research interests include brain disorder analysis and weakly supervised learning.

# 🔥 News

<style>
.news-scroll {
  max-height: 120px; 
  overflow-y: auto; 
  padding-right: 10px; 
}

.news-scroll::-webkit-scrollbar {
  width: 5px;
}

.news-scroll::-webkit-scrollbar-track {
  background: transparent;
}

.news-scroll::-webkit-scrollbar-thumb {
  background: #ccc; 
  border-radius: 4px;
}
</style>

<div class="news-scroll" markdown="1">
- *2025.09*: &nbsp; One paper accepted by JVCIR.
- *2025.06*: &nbsp; Received the M.Sc. (Eng.) degree from Jiangsu University.
- *2024.08*: &nbsp; One paper accepted by IEEE TCSVT.
</div>

# 📝 Publications 
\* denotes corresponding author.

# 2025

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JVCIR</div><img src='images/jvcir_2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Inter-image Token Relation Learning for weakly supervised semantic segmentation<br> 
**Jingfeng Tang**, Keyang Cheng\*, Liutao Wei, Yongzhao Zhan<br>
*Journal of Visual Communication and Image Representation (JVCIR)*

[[**Paper**]](https://www.sciencedirect.com/science/article/pii/S1047320325001907) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

# 2024

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TCSVT</div><img src='images/tcsvt_2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Cross-block Sparse Class Token Contrast for Weakly Supervised Semantic Segmentation<br> 
Keyang Cheng\*, **Jingfeng Tang**, Hongjian Gu, Hao Wan, Maozhen Li<br>
*IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)*

[[**Paper**]](https://ieeexplore.ieee.org/document/10634191) [[**Code**]](https://github.com/Jingfeng-Tang/CB-SCTC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>



# 🎖 Selected Honors and Awards
- *2025.06* Outstanding Graduate
- *2024.11* National Scholarship
- *2024.11* Jiangsu University 'Boxue' President Medal (Top 0.19%)


# 📖 Education
- *2025.09 - Present*, Ph.D. in Computer Science and Technology, College of Computer Science and Engineering, Northeastern University, Shenyang, China.
- *2022.09 - 2025.06*, M.Sc. in Computer Science and Technology, School of Computer Science and Communication Engineering, Jiangsu University, Zhenjiang, China.
- *2016.09 - 2020.06*, B.Eng. in Internet of Things Engineering, School of Computer Science and Technology, Huaiyin Normal University, Huai’an, China.

<!--# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo >dapibus sit amet. -->

# 💻 Work Experience
- *2020.04 - 2021.02*, Software Engineer, Changzhou Mingseal Robot Technology Co., Ltd..

# 🧱 Projects
- *2024.08*, Developed [Image-Doodler](https://github.com/Jingfeng-Tang/Image-Doodler), a tool for generating masks to occlude arbitrary semantic regions and analyze class activation map variations.
- *2022.05*, Developed a [serial port communication tool](https://github.com/Jingfeng-Tang/ComMonitor).

## Acknowledgments
This homepage is based on [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io). Many thanks to the authors!
