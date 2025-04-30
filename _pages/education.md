---
layout: page
permalink: /education/
title: Education
description: My academic background and achievements.
nav: true
nav_order: 2
---

<div class="education-container">
  <!-- Carnegie Mellon University -->
  <div class="education-entry">
    <div class="education-logo">
      <img src="/assets/img/cmu-logo.png" alt="Carnegie Mellon University Logo" />
    </div>
    <div class="education-content">
      <h2 class="education-title"><a href="https://www.cmu.edu/">Carnegie Mellon University (CMU)</a></h2>
      <h3 class="education-degree">Master of Science in Computer Vision | Robotics Institute | Pittsburgh, PA | Aug 2021 - Dec 2022</h3>
      <div class="education-details">
        <h4>Achievements</h4>
        <ul>
          <li><a href="https://jntataendowment.org/">JN Tata Scholar</a> 2021</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- National Institute of Technology Karnataka -->
  <div class="education-entry">
    <div class="education-logo">
      <img src="/assets/img/nitk-logo.png" alt="NITK Logo" />
    </div>
    <div class="education-content">
      <h2 class="education-title"><a href="https://www.nitk.ac.in/">National Institute of Technology Karnataka (NITK)</a></h2>
      <h3 class="education-degree">Bachelor of Technology in Information Technology | Surathkal, India | Aug 2014 - May 2018</h3>
      <div class="education-details">
        <h4>Achievements</h4>
        <ul>
          <li>Awarded the Best Outgoing Student, Batch of 2018</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<style>
  .education-container {
    position: relative;
  }
  
  .education-entry {
    display: flex;
    margin-bottom: 2rem;
    position: relative;
  }
  
  .education-logo {
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
  
  .education-logo img {
    max-width: 80%;
    max-height: 80%;
    object-fit: contain;
  }
  
  .education-content {
    flex: 1;
  }
  
  .education-title {
    margin: 0 0 0.25rem 0;
    font-size: 1.2rem;
    font-weight: 500;
  }
  
  .education-degree {
    margin: 0 0 0.75rem 0;
    font-size: 1rem;
    font-weight: normal;
    color: var(--global-text-color);
  }
  
  .education-details h4 {
    font-size: 1rem;
    font-weight: 500;
    margin: 1rem 0 0.5rem 0;
  }
  
  .education-details ul {
    margin: 0.5rem 0 0 0;
    padding-left: 1.25rem;
  }
  
  .education-details li {
    margin-bottom: 0.3rem;
  }
</style>