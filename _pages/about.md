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




现在我在学习从机器学习到大模型的基础知识

# 📄 Projects

**[AI聊天chatbot](http://xihuanwanyuanshen.icu/)**

此项目以应用LLM技术，对接DeepSeek、OpenAI等大模型提供生成式服务。项目采用微服务架构设计，部署到云服务器对外提供服务。
* 采用 DDD 架构 API，以及便于不同领域模块的独立设计，使用多种设计模式提高代码的简洁性和维护性。
* 使用异步流式响应减少接口响应时间，使用责任链模式提供登录鉴权、访问次数限制、敏感词过滤等功能。
* 使用GitHub的workflow实现CICD，自动打包并发布镜像，利用LLM实现自动代码评审功能。
* 基于k8s的部署，负载均衡




**项目2**





# 🎓 Education


- **Undergraduate Student of Computer Science and Technology  (2020.9 - 2024.6)**

<div style="display: flex; align-items: center;">
    <img src="../images/nuist.png" alt="fdu" width="100" height="100" style="margin-right: 2ch;">
    <div>
        <blockquote>
            Nanjing University of Information<br>
            Science and Technology
        </blockquote>
    </div>
</div>

在本科阶段，我深入学习了从数字电路到人工智能的各项计算机基础知识，阅读了《Modern Operating System》、《CSAPP》等经典教材，并通过实践逐步探索了“hello, world”背后的深层次原理。四年的学习不仅锤炼了我的计算机应用能力，还扩展了我对计算机技术的理解，使其逐渐成为我兴趣所在与未来发展的基石。在这一过程中，我特别关注计算机的工程应用，尤其是Web开发与系统软件，积累了较为深入的实践经验。通过这些学习和实践，我更加坚定了在计算机领域深耕细作的决心，期望在研究生阶段能够进一步深化专业知识，拓宽技术视野。  
[本科成绩单](http://xihuanwanyuanshen.icu/static/grade.pdf)



# 💼 Employment

- **JAVA开发实习生, 中国电信  (2023.1 - 2023-3)** 
<div style="display: flex; align-items: center;">
    <img src="../images/中国电信.jpg" alt="tplink" width="150" height="100">
        <blockquote>
            参与旗下微信小程序118114聪明生活的开发和维护<br>
            独立开发完成流量提速业务功能的升级改造<br>
            改造登录接口,实现基于JWT的token登录。完善发送短信接口,防止短信爆破<br>
            使用基于Redisson的延时队列处理超时订单
        </blockquote>
</div>

- **云服务工程师, 三星中国研发中心  (2024.6 - 2024-9)** 
<div style="display: flex; align-items: center;">
    <img src="../images/samsung.jpg" alt="tplink" width="150" height="100">
        <blockquote>
            就职于Iot部门，负责[三星物联网(SmartThings)](https://www.samsung.com/us/smartthings/)相关生态的开发<br>
            我所在的DA_Service_Team主要负责如[SamsungFood](https://samsungfood.com/)等服务的开发，为智能设备提供内容支持。<br>
            工作中主要使用的技术栈和文化为JAVA、TypeScript、AWS、DevOps<br>
            任职期间我主要负责和英国团队进行对接，进行SamsungFood的中国区特性开发和部署<br>
            英语工作环境以及和世界各地的同事的对接锻炼了我的英语和团队合作能力<br>
        </blockquote>
</div>


# 🏆 Honors and Awards

<ul>
  <li>蓝桥杯C++江苏省二等奖 2022</li>
  <li>校二等奖学金 2021</li>
  <li>校ACM竞赛三等奖 2020</li>
</ul>

# 🛠️ Skills

- **Programming Languages**: JAVA,C++,SQL,TypeScript,Python

<div class="image-container">
  <img src="../images/JAVA.jpg" alt="C/C++" width="50" height="50">
  <img src="../images/ISO_C++_Logo.svg.png" alt="C/C++" width="50" height="50">
  <img src="../images/sql.png" alt="Go" width="50" height="50">
  <img src="../images/typescript.png" alt="C/C++" width="100" height="50">
  <img src="../images/Python-logo-notext.svg.png" alt="Python" width="50" height="50">
</div>

<div class="skill-container">
    <li>JAVA是我使用最多的语言，熟悉包括从JVM到语言特性到框架，具有大量工程经验</li>
    <li>我会用C++写算法题，熟悉它的STL及部分特性</li>
    <li>SQL几乎成了所有后端工程师的必备技能了，我可以使用SQL写复杂查询</li>
    <li>我使用JS写过页面，工作后发现TS构建服务也很方便，欣赏动态语言的干练，但并不熟练</li>
    <li>使用Python完成一些机器学习方面的任务</li>
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