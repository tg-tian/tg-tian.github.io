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

<style>
  .centered {
    text-align: center;
    font-size: 24px;
    background: linear-gradient(to right, #81c784, #ff6b6b); /* 西瓜绿到西瓜红的渐变色 */
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
    .intro {
    margin-top: 50px; /* 调整分割线顶部间距 */
    padding-top: 50px; /* 调整分割线底部间距 */
    border-top: 2px solid #ccc; /* 分割线样式 */
  }
   .image-container {
    display: flex;
    justify-content: space-around; /* 水平分散排列 */
    align-items: center; /* 垂直居中 */
    margin-bottom: 20px; /* 可选：设置下方间距 */
  }

  .image-container img {
    margin: 0 5px; /* 可选：设置图片之间的间距 */
  }
</style>
<div class="centered">
  <h2>Hi, I am yuke :)</h2>
</div>

<div class="intro">
I am currently pursuing my graduate studies at <a href="https://www.fudan.edu.cn/en/">Fudan University</a> under the guidance of Professor <a href="https://chenyang03.wordpress.com/">Yang Chen</a>. Prior to this, I earned my Bachelor's degree from the School of Computer Science and Technology at <a href="https://www.dlut.edu.cn/">Dalian University of Technology</a> in 2020.<br>
<br>
Following my graduation, from June 2020 to June 2022, I served as an embedded software development engineer in <a href="https://www.tp-link.com/en/">TP-LINK</a>'s Consumer Electronics R&D Department. During my time there, I was responsible for the development and maintenance of the TP-LINK network video record (NVR) device, as well as the establishment of the TP-LINK robot operating system platform.<br>
<br>
Since September 2022, I have been actively involved in research at the School of Computer Science at Fudan University, with a focus on network systems. My research interests encompass network measurement, network simulation, network protocols and architecture design and implementation, as well as network security.<br>
<br>
Recently, I am particularly intrigued by cloud-native networking (such as network virtualization and containerized networking), distributed storage and network systems (such as content delivery networks and InterPlanetary File System), and data center networks. I have read many papers on these research topics and hope to engage in related research work in the future.
</div>


# 📄 Publications

***ICC 2023 - IEEE International Conference on Communications, Rome, Italy, 2023***

[SocialCache: A Pervasive Social-Aware Caching Strategy for Self-Operated Content Delivery Networks of Online Social Networks.](https://doi.org/10.1109/ICC45041.2023.10279588)

Tiancheng Guo, **Yuke Ma**, Mengying Zhou, Xin Wang, Jun Wu, Yang Chen.

---

***Information, 2022, Volume 13***

[DNS Request Log Analysis of Universities in Shanghai: A CDN Service Provider’s Perspective (mdpi.com)](https://www.mdpi.com/2078-2489/13/11/542)

Zhiyang Sun, Tiancheng Guo, Shiyu Luo, Yingqiu Zhuang, **Yuke Ma**, Yang Chen, Xin Wang.

---


# 🎓 Education

- **Graduate Student of Computer Science (Sep.2022 - now)**

<div style="display: flex; align-items: center;">
    <img src="../images/Fudan_University_Logo.svg.png" alt="fdu" width="100" height="100" style="margin-right: 2ch;">
    <div>
        <blockquote>
             Fudan University<br>
             School of Computer Science Fudan University
        </blockquote>
    </div>
</div>

- **Undergraduate Student of Computer Science and Technology (Japanese Intensive) (Sep. 2015 - Jun. 2020)**

<div style="display: flex; align-items: center;">
    <img src="../images/Dalian_University_of_Technology_logo.svg.png" alt="fdu" width="100" height="100" style="margin-right: 2ch;">
    <div>
        <blockquote>
            Dalian University of Technology<br>
            School of Computer Science and technology
        </blockquote>
    </div>
</div>

# 💼 Work Experience 

- **Embedded Software Engineer, TP-Link Technologies Co., Ltd. (Jul.2020 - Jun. 2022)** 
<div style="display: flex; align-items: center;">
    <img src="../images/tplink.png" alt="tplink" width="150" height="100">
        <blockquote>
            Consumer Electronics R&D Department, Intelligent Security Equipment Group (2020-2021)<br>
            Consumer Electronics R&D Department, Robotics Group (2021-2022)
        </blockquote>
</div>


# 🏆 Honors and Awards

<ul>
  <li>Fudan University Academic Excellence Scholarship, First Class, 2023</li>
  <li>Fudan University Graduate Freshman Scholarship, 2022</li>
  <li>National Inspirational Scholarship, 2019</li>
  <li>Dalian University of Technology Excellent Scholarship, 2018</li>
</ul>

# 🛠️ Skills

<div class="image-container">
  <img src="../images/ISO_C++_Logo.svg.png" alt="C/C++" width="50" height="50">
  <img src="../images/Python-logo-notext.svg.png" alt="Python" width="50" height="50">
  <img src="../images/215px-Go_Logo_Blue.svg.png" alt="Go" width="50" height="50">
</div>

- **Programming Languages**: C/C++, Python, Shell, Go
    I have two years of experience working on large-scale projects using C/C++, so I am proficient in both C/C++ and shell scripting. Additionally, I am currently very interested in the features of the Go language, so I am actively learning Go as well

<div class="image-container">
  <img src="../images/Tux.svg.png" alt="Tux" width="50" height="50">
  <img src="../images/180px-Heckert_GNU_white.svg.png" alt="ZMap" width="100" height="100">
  <img src="../images/Cmake.svg.png" alt="ZMap" width="100" height="100">
</div>

- **Operating Systems**: Linux, Windows
    I was responsible for porting the embedded Linux operating system for TPLINK's robotic vacuum cleaner, which has made me proficient in Linux systems.

<div class="image-container">
  <img src="../images/ns-3-notext.png" alt="ns-3" width="100" height="50">
  <img src="../images/ZMap_logo_from_GitHub.png" alt="ZMap" width="100" height="50">
</div>

- **Network Tools**:  network simulator-3 (ns-3), zmap, tcpdump
    I am currently utilizing ns-3 to build a simulation platform for future network architectures. As a result, I have over a year of experience with ns-3 and am proficient in the source code of various modules within ns-3, including TCP, UDP, IP, and others. I have previously contributed to ZMap by integrating a module for scanning MPTCP servers and successfully conducted scans of MPTCP servers across the IPv4 address space

- **Software Development and Maintainence Tools**: Git, Makefile, CMake, Docker, Kubernetes
    As an embedded software development engineer, I am proficient in using Makefile, CMake, and Git to build and maintain large-scale projects. Additionally, I excel in utilizing Docker containers for system development.

- **Languages**: English (Fluent), Japanese (Intermediate)
