---
layout: page
permalink: /experience/
---

<!-- 引入FontAwesome（GitHub Pages默认支持的话可用） -->
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
/>

<style>
  /* 时间线容器 */
  .timeline {
    border-left: 3px solid #3498db; /* 蓝色时间线 */
    margin-left: 15px;
    padding-left: 25px;
  }

  /* 时间节点 */
  .timeline-item {
    position: relative;
    margin-bottom: 30px;
  }
  .timeline-item:last-child {
    margin-bottom: 0;
  }

  /* 时间圆点 */
  .timeline-item::before {
    content: '';
    position: absolute;
    left: -15px;
    top: 5px;
    width: 12px;
    height: 12px;
    background: #3498db;
    border-radius: 50%;
    border: 2px solid white;
  }

  /* 时间文本（右侧内容左边） */
  .time-label {
    float: left;
    width: 110px;
    color: #666;
    font-size: 0.9em;
    font-family: monospace;
    text-align: right;
    margin-right: 20px;
  }

  /* 内容部分 */
  .timeline-content {
    overflow: hidden; /* 清除float影响 */
  }

  /* 标题小一点 */
  h3.timeline-title {
    font-size: 1.1em;
    color: #2c3e50;
    margin: 0 0 6px 0;
  }

  /* 超链接颜色 */
  a {
    color: #2980b9;
    text-decoration: underline;
    font-weight: normal;
  }

  /* 段落 */
  p {
    margin: 4px 0;
    color: #34495e;
  }

  /* icon样式 */
  .icon {
    color: #2980b9;
    margin-right: 8px;
  }
</style>

<h3 style="margin-top: 20px; margin-bottom: 15px;">Academic Experience</h3>
<div class="timeline">
  <div class="timeline-item">
    <div class="time-label">2025 – Present</div>
    <div class="timeline-content">
      <h3 class="timeline-title"><i class="fas fa-user-graduate icon"></i>Ph.D. in Chemistry</h3>
      <p>The Chinese University of Hong Kong</p>
      <p>Supervisor: <a href="https://xinglong-zhang.github.io" target="_blank">Prof. Xinglong Zhang</a></p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="time-label">2022 – 2025</div>
    <div class="timeline-content">
      <h3 class="timeline-title"><i class="fas fa-user-graduate icon"></i>M.S. in Chemistry</h3>
      <p>Wuhan University of Technology</p>
      <p>Supervisor: Prof. Yiyong Huang</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="time-label">2018 – 2022</div>
    <div class="timeline-content">
      <h3 class="timeline-title"><i class="fas fa-user-graduate icon"></i>B.S. in Chemistry</h3>
      <p>Wuhan University of Technology</p>
    </div>
  </div>
</div>

<hr style="margin: 40px 0; border-color: #ccc;"/>

<h3 style="margin-top: 20px; margin-bottom: 15px;">Other Experience</h3>
<div class="timeline">
  <div class="timeline-item">
    <div class="time-label">2024 – 2025</div>
    <div class="timeline-content">
      <h3 class="timeline-title"><i class="fas fa-flask icon"></i>Research Assistant</h3>
      <p>XYZ Lab, CUHK</p>
      <p>Worked on machine learning applications for chemical reactivity prediction.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="time-label">Summer 2021</div>
    <div class="timeline-content">
      <h3 class="timeline-title"><i class="fas fa-industry icon"></i>Internship</h3>
      <p>ABC Chemical Co.</p>
      <p>Assisted with synthetic route design, lab optimization, and analytical method development.</p>
    </div>
  </div>
</div>
