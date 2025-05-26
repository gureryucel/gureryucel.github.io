---
layout: page
title: Projects
permalink: /projects/
---

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  margin-top: 30px;
}
.project-card {
  border: 1px solid #ddd;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 2px 2px 10px rgba(0,0,0,0.05);
  transition: transform 0.3s ease;
}
.project-card:hover {
  transform: translateY(-5px);
}
.project-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
}
.project-content {
  padding: 15px;
}
.project-title {
  font-size: 1.1rem;
  font-weight: bold;
  margin-bottom: 0.5rem;
}
</style>

<div class="project-grid">

  <a href="/projects/euroleague-analysis" class="project-card">
    <img src="/assets/images/euroleague.jpg" alt="Euroleague Analysis">
    <div class="project-content">
      <div class="project-title">Data Analysis on Performance of Euroleague Teams</div>
    </div>
  </a>

  <a href="/projects/block-copolymers" class="project-card">
    <img src="/assets/images/copolymers.jpg" alt="Block-Co-Polymers">
    <div class="project-content">
      <div class="project-title">Behavior of Block-Co-Polymers in Different Solvents</div>
    </div>
  </a>

  <a href="/projects/trc-parking" class="project-card">
    <img src="/assets/images/trc-parking.jpg" alt="Textile Concrete">
    <div class="project-content">
      <div class="project-title">Design of Textile Reinforced Concrete Parking Station</div>
    </div>
  </a>

  <a href="/projects/earthquake-analysis" class="project-card">
    <img src="/assets/images/earthquake.jpg" alt="Earthquake Building Analysis">
    <div class="project-content">
      <div class="project-title">Earthquake Analysis of 3 Storey Reinforced Concrete Building</div>
    </div>
  </a>

</div>
