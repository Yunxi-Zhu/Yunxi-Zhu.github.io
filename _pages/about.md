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

# <span class='anchor' id='about-me'></span> About Me  /•᷅•᷄\୭
<span style="font-size: 18px;">
  I am a student researcher at 
  <a href="https://www.columbia.edu/" target="_blank" style="text-decoration: none;">Columbia University</a>, 
  advised by Prof. 
  <a href="https://yunzhuli.github.io/" target="_blank" style="text-decoration: none;">Yunzhu Li</a>. 
  I am also fortunate to receive mentorship from Prof. 
  <a href="https://www.me.columbia.edu/faculty/sunil-agrawal" target="_blank" style="text-decoration: none;">Sunil Agrawal</a>. 
  I received my M.S. in Mechanical Engineering (Robotics) from 
  <a href="https://www.me.columbia.edu/" target="_blank" style="text-decoration: none;">Columbia University</a>, 
  and my B.Eng. from 
  <a href="https://www.xjtu.edu.cn/" target="_blank" style="text-decoration: none;">Xi’an Jiaotong University</a>.

<span style="font-size: 18px;">
  I am currently seeking full-time opportunities as a mechanical engineer or interdisciplinary R&D engineer, where I can apply my skills in mechanical design, system integration, rapid prototyping, and intelligent system development to build impactful and innovative products.



<div style="margin-top: 40px;"></div>

# 🤖 Research 
<!-- 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='/images/roar.png' alt="mTPAD" width="250" height="auto"></div></div>
<div class='paper-box-text' markdown="1">

<span style="font-size: 18px;text-decoration: none;color: #0000EE;">[Mobile Tethered Pelvic Assist Device (mTPAD) Motor Positions Optimization](/Research/mTPAD-details)</span>

**Robotics And Rehabilitation (RoAR) Lab** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *2024.01 - 2024.09*
- Use random search and genetic algorithm to find the optimal positions of the motors that can satisfy all desired wrenches.
</div>
</div>
-->

<div class="research-container">
  <!-- 项目 2 -->
  <div class="research-item">
    <div class="research-image">
      <img src="/images/robopil.png" alt="Bimanual Teleoperation with Vision-Tactile Sensing">
    </div>
    <div class="research-details">
      <h3>
        <a href="javascript:void(0);" style="text-decoration: none; color: #0056b3;">
          Bimanual Teleoperation with Vision-Tactile Sensing
        </a>
      </h3>
        <!-- 新增的 Flexbox 容器 -->
        <div class="lab-info">
          <p><strong>Robotic Perception, Interaction, and Learning Lab (RoboPIL)</strong></p>
          <span class="research-date">2025.01 - now </span>
        </div>
      <ul>
          <li>Built and calibrated a low-cost, flexible tactile sensor integrated into robotic grippers.</li>
          <li>Engineered a bimanual teleoperation system (ALOHA robot) incorporating vision and tactile information, collected multimodal
data, processed and aligned point clouds, and trained a diffusion policy for imitation learning.</li>
          <li>Assembled LEAP Hand and used Meta gloves for teleoperation.</li>
          <li>Simulated a bimanual human-size robot in Isaac Lab and teleoperated it using a keyboard interface.</li>
      </ul>
    </div>
  </div>  

  <!-- 项目 1 -->
  <div class="research-item">
    <div class="research-image">
      <img src="/images/roar.png" alt="mTPAD">
    </div>
    <div class="research-details">
        <h3><a href="/Research/mTPAD-details" >Mobile Tethered Pelvic Assist Device (mTPAD) Motor Positions Optimization</a></h3>
          <!-- 新增的 Flexbox 容器 -->
          <div class="lab-info">
            <p><strong>Robotics And Rehabilitation (RoAR) Lab</strong></p>
            <span class="research-date">2024.01 - 2024.09</span>
          </div>
      <ul>
          <li>Managed the optimization project for the mobile Tethered Pelvic Assist Device, addressing the Z-axis torque limitation and expanding the workspace of the end-effector by integrating an 8th motor.</li>
          <li>Developed a simulator to optimize cable exit point positions, utilizing a tournament selection method and convex hull representation to ensure desired wrenches and maximize the end-effector range.</li>
          <li>Designed, iterated, and built validation prototypes using SolidWorks.</li>
          <li>Improved alignment between simulation results and real-world implementation by integrating practical constraints into the simulator.</li>
          <li>Assisted in conducting experiments on subjects to validate the system.</li>
          <li>Processed data from VICON using MATLAB.</li>
      </ul>
    </div>
  </div>
  
</div>

<div style="margin-top: 40px;"></div>

# 🦾 Projects 
<div class="research-container">

  <!-- 项目 1 -->
  <div class="research-item">
    <div class="research-image">
      <img src="/images/RS_robo.jpg" alt="Robotics Studio">
    </div>
    <div class="research-details">
      <h3><a href="/Research/RS-details">Bipedal Robot</a></h3>
      <p>MECE4611 ROBOTICS STUDIO, Fall 2024.</p>
      <ul>
          <li>Designed an 8-DOF bipedal robot and 3D-printed all components.</li>
          <li>Assembled the robot and refined its structure through multiple iterations to enhance stability and performance.</li>
          <li>Developed a simulation in PyBullet and utilized PPO to train the robot for stable locomotion.</li>
          <li>Achieved stable and smooth movement by designing a control mode with sine functions.</li>
      </ul>
    </div>
    </div>

  <!-- 项目 2 -->
  <div class="research-item">
    <div class="research-image">
      <img src="/images/RH-1.jpg" alt="Robot Eye">
    </div>
    <div class="research-details">
      <h3><a href="/Research/RH-details">Robot Eye</a></h3>
      <p>Robotics Hackathon 2024 (Third Prize)</p>
      <ul>
          <li>Designed and developed a robotic eye system capable of tracking human movement using a camera and OpenCV.</li>
          <li>Programmed synchronized LED lighting on the eyelid to dynamically respond to musical beats, enhancing the interactive experience.</li>
      </ul>
    </div>
    </div>

  <!-- 项目 3 -->
  <div class="research-item">
    <div class="research-image">
      <video src="/images/RL.mp4" autoplay loop muted width="250"></video>
    </div>
    <div class="research-details">
      <h3><a href="/Research/RL-details" >Robot Learning</a></h3>
      <p>MECS6616 Robot Learning, Spring 2024</p>
      <ul>
          <li>Applied deep learning to train a two-link robot arm to learn the forward dynamics from a teacher arm.</li>
          <li>Implemented Model Predictive Control (MPC) to control the robot arm, enabling it to reach arbitrary goals by learning from collected data and applying the learned dynamics model.</li>
          <li>Used reinforcement learning algorithms (DQN and PPO) to optimize the robot arm’s ability to efficiently reach specified targets.</li>
      </ul>
    </div>
  </div>  

  <!-- 项目 4 -->
  <div class="research-item">
    <div class="research-image">
      <video src="/images/evo.mp4" autoplay loop muted width="250"></video>
    </div>
    <div class="research-details">
      <h3><a href="/Research/evo-details" >Evolving Soft Robot</a></h3>
      <p>MECS4510 Evolutionary Computation and Design Automation, Fall 2023.</p>
      <ul>
          <li>Simulated a breathing and bouncing spring-mass cube, and generated the plots for potential energy, kinetic energy and total energy.</li>
          <li>Created a robot body using connected cubes and utilized genetic algorithm to optimize its locomotion pattern by selecting, crossovering, and mutating spring parameters.</li>
          <li>Developed a robot with a variable morphology, enabling addition and removal of springs and masse during the evolution process. Implemented genetic algorithm to iteratively refine the robot's design, resulting in the fastest possible robotic configuration by optimizing both its physical structure and movement dynamics.</li>
      </ul>
    </div>
  </div>  

  <!-- 项目 5 -->
  <div class="research-item">
    <div class="research-image">
      <img src="/images/turbine.png" alt="Numerical Simulation Study of Methane and Ammonia Blending in Gas Turbine">
    </div>
    <div class="research-details">
      <h3>Numerical Simulation Study of Methane and Ammonia Blending in Gas Turbine</h3>
      <p>Graduation Project at Xi'an Jiaotong University, Spring 2023.</p>
      <ul>
          <li>Modeled a gas turbine in SolidWorks and meshed it using ANSYS Meshing.</li>
          <li>Simulated combustion under various boundary conditions in ANSYS Fluent to study the impact of ammonia doping ratio on the flow field, temperature field, and NOx emission in the combustion chamber.</li>
          <li>Processed and analyzed the simulation data using ANSYS CFD-Post.</li>
      </ul>
    </div>
  </div>
 

</div>

<div style="margin-top: 40px;"></div>

# <span id="work-experiences"> 💻 Work Experiences </span>
- *2024.09 - 2024.12*, Teaching Assistant: Data Science for Mechanical Systems
- *2025.02 - 2025.05*, Teaching Assistant: Advanced Kinematics, Dynamics, and Control in Robotics
<div style="margin-top: 40px;"></div>
# <span id="educations">📖 Educations</span>
- *2023.09 - 2024.12*, Master, Columbia University.
- *2019.09 - 2023.06*, Undergraduate, Xi'an Jiaotong University.
- *2016.09 - 2019.06*, NO.1 Middle School Affiliated to Central China Normal University, Wuhan. 
