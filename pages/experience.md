---
layout: page
permalink: /experience/
---

<!-- 引入 FontAwesome -->
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
/>

<style>
  .timeline {
    border-left: 2px solid #bbb;
    margin-left: 30px;
    padding-left: 25px;
    position: relative;
  }

  .timeline-item {
    position: relative;
    margin-bottom: 30px;
  }

  .timeline-item::before {
    display: none;
  }

  /* 只修改这里，让时间标签靠右贴近竖线 */
  .time-label {
    position: absolute;
    right: 50px;          /* 靠右对齐 */
    top: 2px;
    color: #666;
    font-size: 0.9em;
    font-family: monospace;
    white-space: nowrap;
    width: 120px;      /* 固定宽度 */
    text-align: right; /* 文字右对齐 */
  }

  /* 内容和时间线贴紧对齐 */
  .timeline-content {
    margin-left: 0;
  }

  h3.timeline-title {
    font-size: 1.1em;
    color: #2c3e50;
    margin: 0 0 6px 0;
    padding-left: 10px;
    display: flex;
    align-items: center;
  }

  h3.timeline-title i {
    margin-right: 6px; /* 让图标和文字略微分开 */
    color: #3498db;
  }

  .timeline-content p {
    margin: 4px 0;
    color: #34495e;
    padding-left: 10px;
  }

  a {
    color: #2980b9;
    text-decoration: underline;
    font-weight: normal;
  }
</style>

<h3 style="margin-top: 20px; margin-bottom: 15px;">Education</h3>
<div class="timeline">
  <div class="timeline-item">
    <div class="time-label">Aug 2025 – Present</div>
    <div class="timeline-content">
      <h3 class="timeline-title"><i class="fas fa-user-graduate"></i>Ph.D. in Chemistry</h3>
      <p>The Chinese University of Hong Kong</p>
      <p>Supervisor: Prof. Xinglong Zhang</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="time-label">Sep 2022 – Jun 2025</div>
    <div class="timeline-content">
      <h3 class="timeline-title"><i class="fas fa-user-graduate"></i>M.S. in Chemistry</h3>
      <p>Wuhan University of Technology</p>
      <p>Supervisor: Prof. Yiyong Huang</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="time-label">Sep 2018 – Jun 2022</div>
    <div class="timeline-content">
      <h3 class="timeline-title"><i class="fas fa-user-graduate"></i>B.S. in Chemistry</h3>
      <p>Wuhan University of Technology</p>
    </div>
  </div>
</div>

<hr style="margin: 40px 0; border-color: #ccc;" />

<h3 style="margin-top: 20px; margin-bottom: 15px;">Experience</h3>
<div class="timeline">
  <div class="timeline-item">
    <div class="time-label">Sep 2022 – Feb 2023</div>
    <div class="timeline-content">
      <h3 class="timeline-title"><i class="fas fa-briefcase"></i>Teaching Assistant</h3>
      <p>Wuhan University of Technology</p>
      <p>Teaching assistant for the undergraduate course <i>Chemoinformatics</i>.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="time-label">Jun 2022 – Aug 2022</div>
    <div class="timeline-content">
      <h3 class="timeline-title"><i class="fas fa-briefcase"></i>Internship</h3>
      <p>Hubei Space Focus company</p>
      <p>Participate in the R&D of heat-resistant resin processes.</p>
    </div>
  </div>
</div>
