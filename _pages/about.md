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
    justify-content: flex-start; /* 左对齐 */
    align-items: center; /* 垂直居中 */
    margin-bottom: 20px; /* 可选：设置下方间距 */
  }
  .image-container img {
    margin: 30px; /* 可选：设置图片之间的间距 */
  }
    .skill-container {
    max-width: 800px;
    margin: 10 auto;
    background-color: #ddd;
    padding: 20px; /* 设置内边距 */
    border-radius: 10px; /* 圆角 */
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* 阴影 */
}
</style>
<div class="centered">
  <h2>Hi, I am yuke :)</h2>
</div>

I am currently pursuing my graduate studies at [Fudan University](https://www.fudan.edu.cn/en/) under the guidance of Professor [Yang Chen](https://chenyang03.wordpress.com/). Prior to this, I earned my Bachelor's degree from the School of Computer Science and Technology at [Dalian University of Technology](https://www.dlut.edu.cn/) in 2020.

Following my graduation, from June 2020 to June 2022, I served as an embedded software development engineer in [TP-LINK](https://www.tp-link.com/en/)'s Consumer Electronics R&D Department. During my time there, I was responsible for the development and maintenance of the TP-LINK NVR-1008H (Network Video Recorder) device, as well as the establishment of the TP-LINK robot operating system platform.

Since September 2022, I have been involved in research at the School of Computer Science at Fudan University, with a focus on network systems. My research interests encompass network measurement, network simulation, network protocols and architecture design and implementation, as well as network security.

Recently, I am particularly interested in cloud-native networking (including network virtualization and containerized networking), distributed storage and network systems (including content delivery networks and InterPlanetary File System), and data center networks. I have read numerous papers on these research topics and hope to engage in related research work in the future.

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

- **Programming Languages**: C/C++, Python, Shell, Go

<div class="image-container">
  <img src="../images/The_C_Programming_Language_logo.svg.png" alt="C/C++" width="50" height="50">
  <img src="../images/ISO_C++_Logo.svg.png" alt="C/C++" width="50" height="50">
  <img src="../images/Gnu-bash-logo.svg.png" alt="C/C++" width="100" height="50">
  <img src="../images/Python-logo-notext.svg.png" alt="Python" width="50" height="50">
  <img src="../images/215px-Go_Logo_Blue.svg.png" alt="Go" width="50" height="50">
</div>

<div class="skill-container">
I have three years of experience building large software projects using C/C++, so I am proficient in both C/C++ and shell scripting languages. Additionally, I am currently very interested in the features of the Go language, so I am also studying related projects in Go (such as go-libp2p, kubo).
</div>
   

- **Operating Systems**: Linux, Docker, Kubernetes
<div class="image-container">
  <img src="../images/Tux.svg.png" alt="Tux" width="50" height="50">
  <img src="../images/180px-Heckert_GNU_white.svg.png" alt="ZMap" width="50" height="50">
  <img src="../images/Cmake.svg.png" alt="ZMap" width="50" height="50">
  <img src="../images/Docker_logo.svg.png" alt="Docker" width="100" height="50">
  <img src="../images/Kubernetes_logo_without_workmark.svg.png" alt="k8s" width="50" height="50">
  <img src="../images/Yocto_Project_logo.svg.png" alt="yocoto" width="100" height="50">
</div>

<div class="skill-container">
While working at TPLINK, I was responsible for porting and building the operating system for robot vacuum cleaners. Therefore, I am proficient in Linux system building, Linux environment programming, and using Yocto tools for the creation of Linux distributions for embedded and IoT software. Additionally, I am very interested in cloud-native and containerization technologies.
</div>

- **Network Tools and Projects**:  network simulator-3 (ns-3), zmap, tcpdump, libp2p, IPFS

<div class="image-container">
  <img src="../images/ns-3-notext.png" alt="ns-3" width="100" height="50">
  <img src="../images/ZMap_logo_from_GitHub.png" alt="ZMap" width="100" height="50">
  <img src="../images/Tcpdump&libpcap.svg.png" alt="tcpdump" width="200" height="100">
  <img src="../images/logo_small.png" alt="libp2p" width="50" height="50">
  <img src="../images/Ipfs-logo-1024-ice-text.png" alt="ipfs" width="50" height="50">
</div>

<div class="skill-container">
I am using ns-3 to build a simulation platform for future Internet architectures. As a result, I have over a year of experience reading and utilizing ns-3 source code. Since ns-3's design follows the specifications of the Linux network protocol stack, I also have a good understanding of Linux kernel networking subsystems. Additionally, I integrated an MPTCP protocol scanning module into the zmap tool, enabling me to scan and measure the entire IPv4 address space for MPTCP servers. This experience has provided me with a solid understanding of the libpcap library, which is at the core of zmap and tcpdump.<br>
<br>
I am currently very interested in IPFS, particularly its core library, libp2p, and I am conducting research related to it.
</div>

- **Languages**: English (Fluent), Japanese (Intermediate)
<div class="skill-container">
I can speak English (CET-6 score of 555) and Japanese (JLPT N2 level).
</div>