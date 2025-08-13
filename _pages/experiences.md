---
title: "Research & Project Experiences"
permalink: /experiences/
author_profile: true
---

{% include base_path %}

<style>
.experiences-container {
  max-width: 100%;
  margin: 5px 0;
}

.experience-item {
  margin-bottom: 1.5em;
  padding: 1.2em;
  background: #fdfdfd;
  border-left: 4px solid #667eea;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  border-radius: 0 8px 8px 0;
}

.experience-header {
  margin-bottom: 0.6em;
}

.experience-title {
  font-size: 1.1em;
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 0.4em;
  line-height: 1.3;
}

.experience-title a {
  color: #2c3e50;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: border-bottom 0.2s ease;
}

.experience-title a:hover {
  border-bottom: 1px solid #667eea;
}

.experience-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 1em;
  margin-bottom: 0.5em;
  font-size: 0.9em;
  color: #6c757d;
}

.meta-item {
  display: flex;
  align-items: center;
  gap: 0.3em;
}

.meta-icon {
  font-size: 0.9em;
}

.supervisor-info {
  font-size: 0.85em;
  color: #495057;
  font-style: italic;
}

.supervisor-info a {
  color: #667eea;
  text-decoration: none;
  font-weight: 500;
}

.supervisor-info a:hover {
  text-decoration: underline;
}

.experience-description {
  color: #495057;
  line-height: 1.6;
  margin-top: 0.6em;
}

.experience-highlights {
  margin-top: 0.6em;
}

.highlight-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.highlight-item {
  position: relative;
  padding-left: 1.5em;
  margin-bottom: 0.4em;
  color: #495057;
  line-height: 1.5;
}

.highlight-item:before {
  content: "▸";
  position: absolute;
  left: 0;
  color: #667eea;
  font-weight: 600;
}

.highlight-item:last-child {
  margin-bottom: 0;
}

@media (max-width: 768px) {
  .experience-item {
    padding: 1.2em;
  }
  
  .experience-title {
    font-size: 1.1em;
  }
  
  .experience-meta {
    flex-direction: column;
    gap: 0.5em;
  }
}
</style>

<div class="experiences-container">

  <div class="experience-item">
    <div class="experience-header">
      <h3 class="experience-title">Research on Delay Doppler Communication</h3>
      <div class="experience-meta">
        <div class="meta-item">
          <span class="meta-icon">📅</span>
          <span><strong>June 2025 - Present</strong></span>
        </div>
        <div class="meta-item">
          <span class="meta-icon">🏢</span>
          <span><em>Summer Internship, SJTU</em></span>
        </div>
      </div>
      <div class="supervisor-info">
        Supervisor: <a href="https://ee.sjtu.edu.cn/FacultyDetail.aspx?id=212&infoid=66&flag=66">Assoc. Prof. Shu Sun</a>
      </div>
    </div>
    <div class="experience-description">
      Conducting theoretical study and simulation-based research on <strong>Orthogonal Time Frequency Space (OTFS) modulation</strong> in the <strong>delay-Doppler domain</strong> for <strong>high-mobility wireless communications</strong>.
    </div>
  </div>

  <div class="experience-item">
    <div class="experience-header">
      <h3 class="experience-title">Novel Hybrid Precoder Based on Deep Reinforcement Learning</h3>
      <div class="experience-meta">
        <div class="meta-item">
          <span class="meta-icon">📅</span>
          <span><strong>Feb 2025 - May 2025</strong></span>
        </div>
        <div class="meta-item">
          <span class="meta-icon">🏢</span>
          <span><em>Electronic Engineering Talent Development Program, SJTU</em></span>
        </div>
      </div>
      <div class="supervisor-info">
        Supervisor: <a href="https://wnt.sjtu.edu.cn/qingqingwu/index.html">Assoc. Prof. Qingqing Wu</a>
      </div>
    </div>
    <div class="experience-highlights">
      <ul class="highlight-list">
        <li class="highlight-item">Conducted literature review on related research topics and reproduced several relevant <strong>GitHub projects</strong>.</li>
        <li class="highlight-item">Proposed an innovative <strong>hybrid precoder architecture</strong> with the relief of the constraint of the <strong>phase shifters</strong> to optimize <strong>S(I)NR</strong>.</li>
        <li class="highlight-item">Applied <strong>(MA)DDPG</strong> and <strong>SAC</strong> to design the <strong>MU-SISO</strong> and <strong>MU-MISO</strong> hybrid precoder based on <strong>deep reinforcement learning</strong>.</li>
      </ul>
    </div>
  </div>

  <div class="experience-item">
    <div class="experience-header">
      <h3 class="experience-title">
        <a href="https://github.com/johnnyhank/MIRA-Multimodal-Intelligent-Robotic-Assistant">Multimodal Intelligent Robotic Assistant</a>
      </h3>
      <div class="experience-meta">
        <div class="meta-item">
          <span class="meta-icon">📅</span>
          <span><strong>May 2025</strong></span>
        </div>
        <div class="meta-item">
          <span class="meta-icon">🏢</span>
          <span><em>Course Project for AI1101, SJTU Student Innovation Center</em></span>
        </div>
      </div>
      <div class="supervisor-info">
        Supervisor: <a href="https://www.si.sjtu.edu.cn/content/person-detail?params=69203cf7b7cf4f88bb55c94bd1f47646&menuIds=2,7,12l">Sr. Eng. Pengzhi Chu</a>
      </div>
    </div>
    <div class="experience-highlights">
      <ul class="highlight-list">
        <li class="highlight-item">Built a <strong>Gradio interface</strong> for voice, text, and image input with speech output, context memory, and device control (<strong>robotic arm</strong> & <strong>Micro:bit</strong>).</li>
        <li class="highlight-item">Used <strong>Qwen-Plus</strong> to understand instructions and trigger actions like weather queries, <strong>DB operations</strong>, robot control, and image understanding via <strong>Qwen-VL</strong>.</li>
        <li class="highlight-item">Implemented <strong>Function Calling</strong> and <strong>MCP</strong> in <strong>Qwen Agent</strong> for tool integration.</li>
      </ul>
    </div>
  </div>

  <div class="experience-item">
    <div class="experience-header">
      <h3 class="experience-title">
        <a href="https://github.com/8zym/AIOT_group3">Smart Driver Monitor System Based on IoT</a>
      </h3>
      <div class="experience-meta">
        <div class="meta-item">
          <span class="meta-icon">📅</span>
          <span><strong>July 2024</strong></span>
        </div>
        <div class="meta-item">
          <span class="meta-icon">🏢</span>
          <span><em>Group Project for NUS SoC Summer Workshop</em></span>
        </div>
      </div>
      <div class="supervisor-info">
        Supervisor: <a href="https://www.comp.nus.edu.sg/disa/people/tanwk/">Assoc. Prof. TAN Wee Kek</a>
      </div>
    </div>
    <div class="experience-highlights">
      <ul class="highlight-list">
        <li class="highlight-item">Developed a <strong>sensor network</strong> and processed fatigue-related data using <strong>RPi</strong> and <strong>ESP32</strong> with <strong>MQTT</strong> for data transmission.</li>
        <li class="highlight-item">Built a website for <strong>data visualization</strong> and <strong>video monitoring</strong> with <strong>WebSocket</strong> and <strong>MJPG-Streamer</strong>.</li>
      </ul>
    </div>
  </div>

</div>