---
layout: page
permalink: /projects/
title: Research Projects
description: Selected projects I have worked on.
nav: true
nav_order: 1
---

<style>
.project-item {
  display: flex;
  gap: 1.5rem;
  padding: 1.5rem 0;
  border-bottom: 1px solid var(--global-divider-color);
  align-items: flex-start;
}
.project-item:last-child { border-bottom: none; }
.project-item img {
  width: 260px;
  flex-shrink: 0;
  border-radius: 6px;
}
.project-item h3 {
  margin: 0 0 0.4rem 0;
  font-size: 1.15rem;
}
.project-meta {
  font-size: 0.85rem;
  color: var(--global-text-color-light);
  margin-bottom: 0.6rem;
}
.project-meta span::after { content: " · "; }
.project-meta span:last-child::after { content: ""; }
@media (max-width: 700px) {
  .project-item { flex-direction: column; }
  .project-item img { width: 100%; }
}
</style>

<div class="project-item">
  <img src="{{ '/assets/img/projects/OptiFish-logo-hor-1.png' | relative_url }}" alt="">
  <div>
    <h3>Optimisation of digital catch monitoring & reporting in the European Fisheries</h3>
    <div class="project-meta">
      <span>Horizon Europe</span>
      <span>2024–2028</span>
      <span>budget: € 5,438,952.50</span>
      <!-- <span>Role: Researcher </span> -->
    </div>
    <p>OptiFish aims to develop, test, and validate technologies that will improve onboard monitoring of catch volumes and fish health, enabling fishers to improve the sustainability of their operations, and better meet control requirements.</p>
    <p>The DTU team is repsonsible for developing computer vision models to detect, count, and length measure the caught fish in electronic monitoring footage for pelagic pumping and sorting table case studies. We are also involved inthe various steps of the development pipeline including data collection and dataset generation. </p>
    <p><a href="https://optifish.eu/">Project website</a></p>
  </div>
</div>

<div class="project-item">
  ...under construction...
</div>
