---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.publication-container {
  display: flex;
  align-items: flex-start;
  gap: 20px;
  margin: 20px 0;
}

.publication-content {
  flex: 1;
}

.publication-video {
  flex: 0 0 300px;
}

.publication-video video {
  width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

@media (max-width: 768px) {
  .publication-container {
    flex-direction: column;
  }
  
  .publication-video {
    flex: none;
    width: 100%;
    max-width: 400px;
    margin: 0 auto;
  }
}
</style>

# About me

I am currently a PhD student at [HKUST(GZ)](https://www.hkust-gz.edu.cn/), under the supervision of Prof. [Jie Song]("https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/SONG-Jie/jsongroas"). My research focuses on multi-fingered dexterous hands, Reinforcement Learning, Vision-Language-Action model for manipulation. Previously, I worked for four years at [TAPO](https://www.tapo.com/en/) and [DREAME](https://www.dreametech.com/?srsltid=AfmBOopjTLrnPBuzvDYJRBLCjDf-zoXCgxdxI4_0B7PR0jSNGym5bSyC) as an embedded software and robotics algorithm engineer, where I contributed to the development of [smart security cameras](https://www.tp-link.com/us/home-networking/cloud-camera/tapo-c320ws/) and [robotic vacuum cleaners](https://www.tp-link.com/us/smart-home/robot-vacuum/tapo-rv30c-plus/).

I have a strong interest in technology, especially robotics. I will devote myself to the research and development of robots to serve human.

# Education

* M.S./PhD in [HKUST(GZ)](https://www.hkust-gz.edu.cn/), 2023-now
* B.S. in [SCUT](https://www.scut.edu.cn/en/), 2015-2019

# Publications

## \* Robust Dexterous Grasping of General Objects from Single-view Perception [[Project Page](https://zdchan.github.io/Robust_DexGrasp/)] [[Paper](https://arxiv.org/pdf/2504.05287)]

<div class="publication-container">
  <div class="publication-content">
    <p><strong>Authors:</strong> [Hui Zhang\*](https://zdchan.github.io/), **[Zijian Wu\*](https://zijianwu1121.github.io/)**, [Linyi Huang](https://hly-123.github.io/FunGrasp/), [Sammy Christen](https://ait.ethz.ch/people/sammyc), [Jie Song](https://ait.ethz.ch/people/song)</p>
  </div>
  <div class="publication-video">
    <video id="RDG" width="300" height="225" controls="controls" autoplay="autoplay" loop="loop">
      <source id="mp4" src="images/robustdexgrasp.mp4" type="video/mp4">
      <p>Your user agent does not support the HTML5 Video element.</p>
    </video>
  </div>
</div>

## \* FunGrasp: Functional Grasping for Diverse Dexterous Hands [[Project Page](https://hly-123.github.io/FunGrasp/)] [[Paper](https://arxiv.org/pdf/2411.16755)]

<div class="publication-container">
  <div class="publication-content">
    <p><strong>Authors:</strong> [Linyi Huang\*](https://hly-123.github.io/FunGrasp/), [Hui Zhang\*](https://zdchan.github.io/), **[Zijian Wu](https://zijianwu1121.github.io/)**, [Sammy Christen](https://ait.ethz.ch/people/sammyc), [Jie Song](https://ait.ethz.ch/people/song)</p>
    <p><em>Robotics and Automation Letters (RA-L), 2025</em></p>
  </div>
  <div class="publication-video">
    <video id="fungrasp" width="300" height="225" controls="controls" autoplay="autoplay" loop="loop">
      <source id="mp4" src="images/fungrasp.mp4" type="video/mp4">
      <p>Your user agent does not support the HTML5 Video element.</p>
    </video>
  </div>
</div>

# Awards
* 2024, Second Prize, ICRA [AgileX Sim2Real Challenge](http://www.sim2real.net/track/track/?nav=AXS2024)
* 3rd & 4th, Champion, [RoboMaster](https://www.robomaster.com/en-US)
* 16th, Second Prize, [ABU RoboCon](http://aburobocon2019.mnb.mn/en/gallery/show/50)
* 2018, Second Prize, ICRA [DJI Robomaster AI Challenge](https://ewh.ieee.org/soc/ras/conf/fullysponsored/icra/2018/ICRA2018/icra2018.org/wp-content/uploads/2017/10/Overview-ICRA-2018-DJI-RoboMaster-AI-Challenge-.pdf)
* 2017, First Prize, National Innovation Practice Project
* 2017, Third Prize, National Engineering Training Competition
* 2017, Second Prize, National Robot Entrepreneurship Competition
* 2016, Scholarship, SCUT scholarship.
#### [Authorized Invention Patents](http://epub.cnipa.gov.cn/Dxb/IndexQuery)
* An operating method, terminal equipment and storage medium for IOT equipment and intelligent gateway (CN113727336B)
* A manual projectile head (CN109157821B)
* A small manual medicine dispensing device (CN107399454B)
* A steerable waist structure for quadruped robots (CN106892016B)
* A counter-rotating cutter wheel fruit picking device with controllable drop point collection (CN107409625B)

# Engineering Technology Stack

* **Robotics Algorithm Develop:** Navigation, 2D-SLAM, Decision, Vision Measurement
* **Operating System Develop:** FreeRTOS, RTX, OpenWRT, ROS/ROS2, Each layer of LINUX Architecture
* **Protocol Stack Application:** TCP/IP, LWIP, 802.11, SPI, I2C, UART, CAN
* **Simulator Application:** Raisim, IsaacSim, Gazebo, CoppeliaSim
* **Coding Languages:** Assembly, C/C++, Python
