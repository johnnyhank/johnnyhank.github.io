---
title: "Course Grades"
permalink: /course-grades/
author_profile: true

---

{% include base_path %}

<style>
.grades-container {
  max-width: 100%;
  margin: 20px 0;
}

.grade-item {
  display: grid;
  grid-template-columns: 4fr 1fr;
  gap: 20px;
  padding: 15px 0;
  border-bottom: 1px solid #e0e0e0;
  align-items: center;
}

.grade-item:last-child {
  border-bottom: none;
}

.course-name {
  font-weight: 500;
  color: #2c3e50;
  text-align: left;
  font-size: 1em;
  line-height: 1.4;
}

.grade-score {
  color: #2c3e50;
  font-weight: 700;
  text-align: right;
  font-size: 1.1em;
  padding: 8px 16px;
  background-color: #f8f9fa;
  border-radius: 20px;
  border: 2px solid transparent;
}

.grade-score.excellent {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  border-color: #667eea;
}

.grade-score.great {
  background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
  color: white;
  border-color: #f093fb;
}

.grade-score.good {
  background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
  color: white;
  border-color: #4facfe;
}

@media (max-width: 768px) {
  .grade-item {
    grid-template-columns: 1fr;
    gap: 12px;
    text-align: left;
  }
  
  .grade-score {
    text-align: center;
    margin: 0 auto;
    max-width: 80px;
  }
  
  .course-name {
    font-size: 0.9em;
  }
}
</style>

<div class="grades-container">
  <div class="grade-item">
    <div class="course-name">Analog Electronic Technology</div>
    <div class="grade-score excellent">100</div>
  </div>

  <div class="grade-item">
    <div class="course-name">University Physics III</div>
    <div class="grade-score excellent">100</div>
  </div>

  <div class="grade-item">
    <div class="course-name">The Practice Course of Artificial Intelligence</div>
    <div class="grade-score excellent">100</div>
  </div>

  <div class="grade-item">
    <div class="course-name">Mathematical Physics Method in Electronic</div>
    <div class="grade-score great">97</div>
  </div>

  <div class="grade-item">
    <div class="course-name">Hardware Description Language and System Simulation</div>
    <div class="grade-score great">97</div>
  </div>

  <div class="grade-item">
    <div class="course-name">Principle of Communications</div>
    <div class="grade-score great">96</div>
  </div>

  <div class="grade-item">
    <div class="course-name">Calculus II</div>
    <div class="grade-score great">96</div>
  </div>

  <div class="grade-item">
    <div class="course-name">Video Coding and Communication</div>
    <div class="grade-score great">96</div>
  </div>

  <div class="grade-item">
    <div class="course-name">Digital Signal Processing</div>
    <div class="grade-score great">95</div>
  </div>

  <div class="grade-item">
    <div class="course-name">Principles Wireless Communication and Mobile Networks</div>
    <div class="grade-score great">94</div>
  </div>

  <div class="grade-item">
    <div class="course-name">Microwave Technology</div>
    <div class="grade-score good">93</div>
  </div>

  <div class="grade-item">
    <div class="course-name">Machine Learning</div>
    <div class="grade-score good">93</div>
  </div>

  <div class="grade-item">
    <div class="course-name">Discrete Mathematics</div>
    <div class="grade-score good">93</div>
  </div>

  <div class="grade-item">
    <div class="course-name">Electromagnetic Field</div>
    <div class="grade-score good">92</div>
  </div>

  <div class="grade-item">
    <div class="course-name">Probability and Statistics</div>
    <div class="grade-score good">92</div>
  </div>

  <div class="grade-item">
    <div class="course-name">Reinforcement Learning</div>
    <div class="grade-score good">92</div>
  </div>
</div>
