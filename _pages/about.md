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
<span style="font-size: 18px;">I am a second-year Master's student in Mechanical Engineering with a foucus on Robotics at Columbia University. Before entering Columbia, I earned B.Eng. from Xi'an Jiaotong University.

<span style="font-size: 18px;">My research interest lies at the intersection of robotics, optimal control, machine learning, and artificial intelligence.



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
      <p>Use random search and genetic algorithm to find the optimal positions of the motors that can satisfy all desired wrenches.</p>
    </div>
  </div>

  <!-- 项目 2 -->
  <div class="research-item">
    <div class="research-image">
      <img src="/images/HVAC.png" alt="Rapidly Customizable HVAC Simulator for Reinforcement Learning">
    </div>
    <div class="research-details">
      <h3><a href="/Research/HVAC-details">Rapidly Customizable HVAC Simulator for Reinforcement Learning</a></h3>
        <!-- 新增的 Flexbox 容器 -->
        <div class="lab-info">
          <p><strong>Creative Machines Lab</strong></p>
          <span class="research-date">2024.09 - now </span>
        </div>
      <p>A Lightweight Calibrated Simulation Enabling Efficient Offline Learning for Optimal Control of Real Buildings, in collaboration with Google.</p>
    </div>
  </div>  
  
</div>

  

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
          <li>Assembled the robot and iteratively refined the design.</li>
          <li>Developed a simulation in PyBullet and utilized PPO to train the robot for stable locomotion.</li>
      </ul>
    </div>
    </div>

  <!-- 项目 2 -->
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

  <!-- 项目 3 -->
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

  <!-- 项目 4 -->
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



# <span id="work-experiences"> 💻 Work Experiences </span>
- *2024.09 - now*, Teaching Assistant: Data Science for Mechanical Systems

# <span id="educations">📖 Educations</span>
- *2023.09 - now*, Master, Columbia University.
- *2019.09 - 2023.06*, Undergraduate, Xi'an Jiaotong University.
- *2016.09 - 2019.06*, NO.1 Middle School Affiliated to Central China Normal University, Wuhan. 
