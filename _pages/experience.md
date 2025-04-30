---
layout: page
permalink: /experience/
title: Experience
description: A detailed overview of my professional experience.
nav: true
nav_order: 1
---

<div class="experience-container">
  <!-- Zoox -->
  <div class="experience-entry">
    <div class="experience-logo zoox-logo">
      <img src="/assets/img/zoox-logo.png" alt="Zoox Logo" />
    </div>
    <div class="experience-content">
      <h2 class="experience-title">ML Engineer</h2>
      <h3 class="experience-company"><a href="https://zoox.com/">Zoox</a> | Foster City, USA | June 2024 - Present</h3>
      <ul class="experience-details">
        <li>Productionizing Generative Driving Scenarios to enhance testing and validation of the robot's prediction and planner stack by augmenting & fuzzing vehicle logs for diverse scenarios.</li>
      </ul>
    </div>
  </div>

  <!-- Matic Robots Inc. (Full-time) -->
  <div class="experience-entry">
    <div class="experience-logo" style="background-color: white;">
      <img src="/assets/img/matic-logo.svg" alt="Matic Robots Logo" />
    </div>
    <div class="experience-content">
      <h2 class="experience-title">Research Engineer</h2>
      <h3 class="experience-company"><a href="https://maticrobots.com/">Matic Robots Inc.</a> | Mountain View, USA | Feb 2023 - June 2024</h3>
      <ul class="experience-details">
        <li>Designed and developed a frontier-based autonomous exploration algorithm, transforming the camera-powered robot vacuum from semi-autonomous to fully autonomous exploration.</li>
        <li>Optimized the algorithm to achieve a remarkable 3x increase in speed, enabling exploration of an average 2000 sqft household in ~15 minutes.</li>
        <li>Crafted an end-to-end simulation test framework with Unreal Engine (UE) and Grafana for iterative improvements through user feedback, A/B testing, and hyperparameter optimization.</li>
      </ul>
    </div>
  </div>

  <!-- Matic Robots Inc. (Intern) -->
  <div class="experience-entry">
    <div class="experience-logo" style="background-color: white;">
      <img src="/assets/img/matic-logo.svg" alt="Matic Robots Logo" />
    </div>
    <div class="experience-content">
      <h2 class="experience-title">Perception Intern</h2>
      <h3 class="experience-company"><a href="https://maticrobots.com/">Matic Robots Inc.</a> | Mountain View, USA | May 2022 - Aug 2022</h3>
      <ul class="experience-details">
        <li>Improved depth prediction along the image edges and for low-light conditions through data augmentation.</li>
      </ul>
    </div>
  </div>

  <!-- Oracle -->
  <div class="experience-entry">
    <div class="experience-logo oracle-logo">
      <img src="/assets/img/oracle-logo.png" alt="Oracle Logo" />
    </div>
    <div class="experience-content">
      <h2 class="experience-title">Senior Software Engineer</h2>
      <h3 class="experience-company"><a href="https://www.oracle.com/">Oracle</a> | Bengaluru, India | June 2018 - July 2021</h3>
      <ul class="experience-details">
        <li>Designed and developed key marketing segmentation, data integration, and performance enhancement features for Oracle Marketing Cloud's SaaS products.</li>
        <li>Collaborated and set up an automated testing framework to enable the product's Quality Assurance Team.</li>
      </ul>
    </div>
  </div>

  <!-- IIT Madras -->
  <div class="experience-entry">
    <div class="experience-logo">
      <img src="/assets/img/iitm-logo.png" alt="IIT Madras Logo" />
    </div>
    <div class="experience-content">
      <h2 class="experience-title">Computer Vision Intern</h2>
      <h3 class="experience-company"><a href="https://www.iitm.ac.in/">Indian Institute of Technology Madras</a> | Chennai, India | Aug 2017 - Jan 2018</h3>
      <ul class="experience-details">
        <li>Explored the suitability of Faster R-CNN for the purpose of CBIR under the guidance of Prof. Anurag Mittal.</li>
        <li>Achieved 4.5% increase in mAP with data augmentation, triplet network and self learning classifier.</li>
      </ul>
    </div>
  </div>

  <!-- Goldman Sachs -->
  <div class="experience-entry">
    <div class="experience-logo">
      <img src="/assets/img/goldman-sachs-logo.png" alt="Goldman Sachs Logo" />
    </div>
    <div class="experience-content">
      <h2 class="experience-title">Software Engineer Intern</h2>
      <h3 class="experience-company"><a href="https://www.goldmansachs.com/">Goldman Sachs</a> | Bengaluru, India | May 2017 - July 2017</h3>
      <ul class="experience-details">
        <li>Implemented an AI-based search tool for ticket resolution.</li>
      </ul>
    </div>
  </div>
</div>

<style>
  .experience-container {
    position: relative;
  }
  
  .experience-entry {
    display: flex;
    margin-bottom: 2rem;
    position: relative;
  }
  
  .experience-logo {
    width: 80px;
    height: 80px;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-right: 1.5rem;
    background-color: #f8f9fa;
    flex-shrink: 0;
  }
  
  .experience-logo img {
    max-width: 80%;
    max-height: 80%;
    object-fit: contain;
  }
  
  /* .zoox-logo, .oracle-logo {
    background-color: #000;
  }
   */
  .experience-content {
    flex: 1;
  }
  
  .experience-title {
    margin: 0 0 0.25rem 0;
    font-size: 1.2rem;
    font-weight: 500;
  }
  
  .experience-company {
    margin: 0 0 0.75rem 0;
    font-size: 1rem;
    font-weight: normal;
    color: var(--global-text-color);
  }
  
  .experience-details {
    margin: 0.5rem 0 0 0;
    padding-left: 1.25rem;
  }
  
  .experience-details li {
    margin-bottom: 0.5rem;
  }
</style>