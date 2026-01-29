---
title: "Experiences"
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
  border-left: 4px solid #023b53;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  border-radius: 0 8px 8px 0;
}

.experience-header {
  margin-bottom: 0.6em;
  margin-top: 0;
}

.experience-title {
  font-size: 1.1em;
  font-weight: 600;
  color: #000000;
  margin-bottom: 0.4em;
  margin-top: 0;
  line-height: 1.3;
}

/* 重置h3标签的默认边距 */
.experience-title h3 {
  margin: 0;
  padding: 0;
}

.experience-title a {
  color: #2c3e50;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: border-bottom 0.2s ease;
}

.experience-title a:hover {
  border-bottom: 1px solid #1B4F72;
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
  color: #000000;
  font-style: italic;
}

.supervisor-info a {
  color: #023b53;
  text-decoration: none;
  font-weight: 500;
}

.supervisor-info a:hover {
  text-decoration: underline;
}

.experience-description {
  color: #000000;
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
  color: #000000;
  line-height: 1.5;
}

.highlight-item:before {
  content: "▸";
  position: absolute;
  left: 0;
  color: #023b53;
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
          <span>June 2025 - Present</span>
        </div>
        <div class="meta-item">
          <span><em>Summer Internship and Undergraduate Thesis, SJTU</em></span>
        </div>
      </div>
      <div class="supervisor-info">
        Supervisor: <a href="https://ee.sjtu.edu.cn/FacultyDetail.aspx?id=212&infoid=66&flag=66">Assoc. Prof. Shu Sun</a>
      </div>
    </div>
    <div class="experience-description">
      Conducting theoretical study and simulation-based research on Orthogonal Time Frequency Space (OTFS) modulation in the delay-Doppler domain for high-mobility wireless communications.
    </div>
  </div>

  <div class="experience-item">
    <div class="experience-header">
      <h3 class="experience-title">Novel Hybrid Precoder Based on Deep Reinforcement Learning</h3>
      <div class="experience-meta">
        <div class="meta-item">
          <span>February 2025 - May 2025</span>
        </div>
        <div class="meta-item">
          <span><em>Electronic Engineering Talent Development Program, SJTU</em></span>
        </div>
      </div>
      <div class="supervisor-info">
        Supervisor: Assoc. Prof. <a href="https://wnt.sjtu.edu.cn/qingqingwu/index.html">Qingqing Wu</a>
      </div>
    </div>
    <div class="experience-highlights">
      <ul class="highlight-list">
        <li class="highlight-item">Conducted literature review on related research topics and reproduced several relevant GitHub projects.</li>
        <li class="highlight-item">Proposed an innovative hybrid precoder architecture with the relief of the constraint of the phase shifters to optimize S(I)NR.</li>
        <li class="highlight-item">Applied (MA)DDPG and SAC to design the MU-SISO and MU-MISO hybrid precoder based on deep reinforcement learning.</li>
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
          <span>May 2025</span>
        </div>
        <div class="meta-item">
          <span><em>Course Project for AI1101, SJTU Student Innovation Center</em></span>
        </div>
      </div>
      <div class="supervisor-info">
        Supervisor: Sr. Eng. <a href="https://www.si.sjtu.edu.cn/content/person-detail?params=69203cf7b7cf4f88bb55c94bd1f47646&menuIds=2,7,12l">Pengzhi Chu</a>
      </div>
    </div>
    <div class="experience-highlights">
      <ul class="highlight-list">
        <li class="highlight-item">Built a Gradio interface for voice, text, and image input with speech output, context memory, and device control (robotic arm & Micro:bit).</li>
        <li class="highlight-item">Used Qwen-Plus to understand instructions and trigger actions like weather queries, database operations, robot control, and image understanding via Qwen-VL.</li>
        <li class="highlight-item">Implemented function calling and MCP in Qwen Agent for tool integration.</li>
      </ul>
    </div>
    <div class="experience-highlights">
      <h4 style="color: #000000; font-size: 0.95em; margin: 0.8em 0 0.4em 0; font-weight: 600;">Awards</h4>
      <ul class="highlight-list">
        <li class="highlight-item">First Prize(only one) of the OrangePi Campus Development Competition</li>
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
          <span>July 2024</span>
        </div>
        <div class="meta-item">
          <span><em>Group Project for NUS SoC Summer Workshop</em></span>
        </div>
      </div>
      <div class="supervisor-info">
        Supervisor: Assoc. Prof. <a href="https://www.comp.nus.edu.sg/disa/people/tanwk/">TAN Wee Kek</a>
      </div>
    </div>
    <div class="experience-highlights">
      <ul class="highlight-list">
        <li class="highlight-item">Developed a sensor network and processed fatigue-related data using RPi and ESP32 with MQTT for data transmission.</li>
        <li class="highlight-item">Built a website for data visualization and video monitoring with WebSocket and MJPG-Streamer.</li>
      </ul>
    </div>
    <div class="experience-highlights">
      <h4 style="color: #000000; font-size: 0.95em; margin: 0.8em 0 0.4em 0; font-weight: 600;">Awards</h4>
      <ul class="highlight-list">
        <li class="highlight-item">Third Prize(3rd in 12 groups) of the AIoT Group Project</li>
        <li class="highlight-item">Personal A+ Performance in the AIoT Course</li>
      </ul>
    </div>
  </div>

</div>