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
  <h2>Hi, I am tiangan :)</h2>
</div>

2024年6月毕业于南京信息工程大学计算机科学与技术专业.在大学期间，我系统学习了计算机专业的各项知识，阅读过《Modern Operating System》、《Computer Systems: A Programmer's Perspective》等经典英文教材，打下了坚实的理论基础。熟悉JAVA及其生态、掌握C++和Python，熟悉多种数据库，熟练使用Linux和git。

工程经历：大二下学期我在中国电信实习，担任JAVA后端开发。任职期间开发并上线了其旗下微信小程序一项流量提速业务功能(使用Redis锁阻止恶意短信攻击，使用消息队列处理超时订单)。2024.6.18-2024.9.20期间我在三星中国研发中心(南京)Iot部门担任云服务开发工程师，负责[三星物联网设备](https://www.samsung.com/us/smartthings/?CID=afl-ecomm-rkt-cha-040122-url_Cashback+on+Bing+for+Edge+browser&utm_source=url_Cashback+on+Bing+for+Edge+browser&utm_medium=affiliate&utm_campaign=1&utm_content=3829940&rktevent=Cashback+on+Bing+for+Edge+browser__jZHTpnCvx8-_QtrxnYSwxYlNGQLTH6fWw&ranMID=47773&ranEAID=%2FjZHTpnCvx8&ranSiteID=_jZHTpnCvx8-_QtrxnYSwxYlNGQLTH6fWw)的后端服务开发。任职期间我主要负责和英国同事进行对接，进行[Samsung Food](https://samsungfood.com/)的中国区特性部署和开发，工作中我掌握了AWS(亚马逊云)的常用组件，云服务架构，以及docker、CICD等流行开发技术，英语工作环境写锻炼了我的英语文档阅读能力。

现在我在学习从机器学习到大模型的基础知识

# 📄 Projects

***Sensys 2024 - ACM Conference on Embedded Networked Sensor Systems, Hangzhou, China, 2024***

Demo: CTSim: A Scalable and Flexible Cybertwin Network
Simulator for Internet of Things Scenarios.

**Yuke Ma**, Shihan Lin, Yang Chen*, Jun Wu

---

***ICC 2023 - IEEE International Conference on Communications, Rome, Italy, 2023***

[SocialCache: A Pervasive Social-Aware Caching Strategy for Self-Operated Content Delivery Networks of Online Social Networks.](https://doi.org/10.1109/ICC45041.2023.10279588)

Tiancheng Guo, **Yuke Ma**, Mengying Zhou, Xin Wang, Jun Wu, Yang Chen.

---

***Information, 2022, Volume 13***

[DNS Request Log Analysis of Universities in Shanghai: A CDN Service Provider’s Perspective (mdpi.com)](https://www.mdpi.com/2078-2489/13/11/542)

Zhiyang Sun, Tiancheng Guo, Shiyu Luo, Yingqiu Zhuang, **Yuke Ma**, Yang Chen, Xin Wang.

---

# 🎓 Education


- **Undergraduate Student of Computer Science and Technology  (Sep. 2020 - Jun. 2024)**

<div style="display: flex; align-items: center;">
    <img src="../images/nuist.png" alt="fdu" width="100" height="100" style="margin-right: 2ch;">
    <div>
        <blockquote>
            Dalian University of Technology<br>
            School of Computer Science and technology
        </blockquote>
    </div>
</div>

# 💼 Employment

- **Embedded Software Engineer, TP-Link Technologies Co., Ltd. (Jul.2020 - Jun. 2022)** 
<div style="display: flex; align-items: center;">
    <img src="../images/samsung.jpg" alt="tplink" width="150" height="100">
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

- **Programming Languages**: C/C++, Python, Shell, Go, Verilog

<div class="image-container">
  <img src="../images/The_C_Programming_Language_logo.svg.png" alt="C/C++" width="50" height="50">
  <img src="../images/ISO_C++_Logo.svg.png" alt="C/C++" width="50" height="50">
  <img src="../images/Gnu-bash-logo.svg.png" alt="C/C++" width="100" height="50">
  <img src="../images/Python-logo-notext.svg.png" alt="Python" width="50" height="50">
  <img src="../images/215px-Go_Logo_Blue.svg.png" alt="Go" width="50" height="50">
  <img src="../images/verilog.jpg" alt="Verilog" width="50" height="50">
</div>

<div class="skill-container">
I have more than three years of experience building large software systems using C/C++, so I am proficient in both C/C++ and shell scripting languages. I have also used Python for network measurement and simulation, as well as Go for cloud-native development. Additionally, I have experience with Verilog for FPGA development.
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

I have two years of experience in embedded software engineering, during which I was responsible for Linux system porting and build processes, as well as advanced programming and project construction in the Linux environment. I have also used Docker and Kubernetes for cloud-native development.

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
I am using ns-3 to build a simulation platform for future Internet architectures. As a result, I have more than two years of experience of using ns-3. Since it's design follows the specifications of the Linux network protocol stack, I also have a good understanding of Linux kernel networking subsystems. Additionally, I integrated an MPTCP protocol scanning module into the zmap tool, enabling me to scan and measure the entire IPv4 address space for MPTCP servers. This experience has provided me with a solid understanding of the libpcap library, which is at the core of zmap and tcpdump.<br>
<br>
I am currently very interested in IPFS, particularly its core library, libp2p, and I am conducting research related to it.
</div>

- **Languages**: English (Fluent), Japanese (Intermediate)
<div class="skill-container">
I can speak English (CET-6 score of 555) and Japanese (JLPT N2 level).
</div>