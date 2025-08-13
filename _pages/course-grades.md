---
title: "Course Grades"
permalink: /course-grades/
author_profile: true

---

{% include base_path %}

<style>
.grades-container {
  max-width: 100%;
  margin: 15px 0;
}

.grade-item {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 8px 0;
  border-bottom: 1px solid #eee;
}

.grade-item:last-child {
  border-bottom: none;
}

.course-name {
  font-weight: 500;
  color: #2c3e50;
  font-size: 0.95em;
  line-height: 1.3;
  flex: 1;
}

.grade-score {
  font-weight: 600;
  text-align: center;
  font-size: 0.9em;
  padding: 4px 12px;
  border-radius: 15px;
  min-width: 40px;
}

.grade-score.excellent {
  background-color: #667eea;
  color: white;
}

.grade-score.great {
  background-color: #f093fb;
  color: white;
}

.grade-score.good {
  background-color: #4facfe;
  color: white;
}

@media (max-width: 768px) {
  .course-name {
    font-size: 0.9em;
  }
  
  .grade-score {
    font-size: 0.85em;
    padding: 3px 10px;
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
    <div class="grade-score good">94</div>
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
