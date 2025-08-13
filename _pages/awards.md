---
title: "Awards"
permalink: /awards/
author_profile: true

---

{% include base_path %}

<style>
.awards-container {
  max-width: 100%;
  margin: 20px 0;
}

.award-item {
  display: grid;
  grid-template-columns: 2fr 3fr 1fr;
  gap: 20px;
  padding: 15px 0;
  border-bottom: 1px solid #e0e0e0;
  align-items: center;
}

.award-item:last-child {
  border-bottom: none;
}

.award-name {
  font-weight: 600;
  color: #2c3e50;
  text-align: left;
  font-size: 0.9em;
}

.award-organization {
  color: #2E86AB;
  font-style: italic;
  text-align: center;
  font-size: 0.9em;
}

.award-date {
  color: #1B4F72;
  font-weight: 500;
  text-align: right;
  white-space: nowrap;
  font-size: 0.9em;
}

@media (max-width: 768px) {
  .award-item {
    grid-template-columns: 1fr;
    gap: 8px;
    text-align: left;
  }
  
  .award-organization,
  .award-date {
    text-align: left;
  }
}
</style>

<div class="awards-container">
  <div class="award-item">
    <div class="award-name">National Scholarship</div>
    <div class="award-organization">Ministry of Education, PRC</div>
    <div class="award-date">Dec 2024</div>
  </div>

  <div class="award-item">
    <div class="award-name">The Second Prize Scholarship</div>
    <div class="award-organization">Shanghai Jiao Tong University</div>
    <div class="award-date">Dec 2024</div>
  </div>

  <div class="award-item">
    <div class="award-name">The Third Prize Scholarship</div>
    <div class="award-organization">Shanghai Jiao Tong University</div>
    <div class="award-date">Dec 2023</div>
  </div>

  <div class="award-item">
    <div class="award-name">Three Good Student</div>
    <div class="award-organization">Shanghai Jiao Tong University</div>
    <div class="award-date">Oct 2023</div>
  </div>

  <div class="award-item">
    <div class="award-name">Excellent League Member</div>
    <div class="award-organization">Shanghai Jiao Tong University</div>
    <div class="award-date">May 2023</div>
  </div>

  <div class="award-item">
    <div class="award-name">The Third Prize of National Mathematical Modeling Contest</div>
    <div class="award-organization">Shanghai Municipal Education Commission</div>
    <div class="award-date">Nov 2023</div>
  </div>

  <div class="award-item">
    <div class="award-name">Successful Participant of Mathematical Contest In Modeling</div>
    <div class="award-organization">Consortium for Mathematics and its Applications</div>
    <div class="award-date">May 2025</div>
  </div>
</div>