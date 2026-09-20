---
layout: page
permalink: /projects/
title: projects
description: Research projects I have worked on.
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
  <img src="{{ '/assets/img/projects/proje1.jpg' | relative_url }}" alt="">
  <div>
    <h3>Projenin tam adı</h3>
    <div class="project-meta">
      <span>Horizon Europe</span>
      <span>2024–2027</span>
      <span>Role: Postdoc</span>
    </div>
    <p>İki üç cümlelik amaç ve kapsam. Problem ne, sen ne yapıyorsun,
    çıktı ne olacak.</p>
    <p><a href="https://proje-sitesi.eu/">Project website</a></p>
  </div>
</div>

<div class="project-item">
  ...ikinci proje aynı kalıpla...
</div>
