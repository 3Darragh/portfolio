---
layout: page
title: Projects
permalink: /works/
---

<style>
  .project-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 24px;
    margin-top: 24px;
  }
  @media (max-width: 900px) {
    .project-grid { grid-template-columns: repeat(2, 1fr); }
  }
  @media (max-width: 550px) {
    .project-grid { grid-template-columns: 1fr; }
  }
  .project-card {
    border: 2px solid rgb(159, 224, 153);
    border-radius: 6px;
    overflow: hidden;
    background: #fff;
    display: flex;
    flex-direction: column;
  }
  .project-card img {
    width: 100%;
    aspect-ratio: 16/9;
    object-fit: cover;
    display: block;
  }
  .project-card-body {
    padding: 14px;
    flex: 1;
    display: flex;
    flex-direction: column;
  }
  .project-card h3 {
    margin: 0 0 8px 0;
    font-size: 1rem;
  }
  .project-card p {
    font-size: 0.875rem;
    color: #555;
    flex: 1;
    margin: 0 0 10px 0;
  }
  .project-tag {
    display: inline-block;
    padding: 2px 10px;
    border-radius: 20px;
    border: 1px solid rgb(159, 224, 153);
    font-size: 0.75rem;
    color: rgb(100, 160, 95);
    margin-right: 4px;
  }
</style>

<div class="project-grid">

<!-- AC Unit -->
<div class="project-card">
    <img src="/portfolio/projects/Portfolio_AC_1.png" alt="AC Unit"/>
    <div class="project-card-body">
      <h3>AC Unit</h3>
      <div>
        <span class="project-tag">3D Model</span>
        <span class="project-tag">Blender</span>
      </div>
    </div>
  </div>

<!-- Locker -->
  <div class="project-card">
    <img src="/portfolio/projects/Portfolio_Locker_1.png" alt="School Locker"/>
    <div class="project-card-body">
      <h3>School Locker</h3>
      <div>
        <span class="project-tag">3D Model</span>
        <span class="project-tag">Blender</span>
      </div>
    </div>
  </div>

<!-- PC Case -->
  <div class="project-card">
    <img src="/portfolio/projects/Portfolio_PC_2.png" alt="PC Case"/>
    <div class="project-card-body">
      <h3>PC Case</h3>
      <div>
        <span class="project-tag">3D Model</span>
        <span class="project-tag">Blender</span>
      </div>
    </div>
  </div>

<!-- Subway Scene -->
<div class="project-card">
  <img src="/portfolio/projects/Portfolio_Subway_1.png" alt="Subway Scene"/>
  <div class="project-card-body">
    <h3>Subway Scene</h3>
    <div>
      <span class="project-tag">3D Model</span>
      <span class="project-tag">Blender</span>
    </div>
  </div>
</div>

<!-- Build System -->
<div class="project-card">
  <img src="/portfolio/projects/Portfolio_Zig.png" alt="Build System"/>
  <div class="project-card-body">
    <h3>Build System</h3>
    <div>
      <span class="project-tag">Programming</span>
      <span class="project-tag">Zig</span>
    </div>
  </div>
</div>

<!-- Input Handler -->
<div class="project-card">
  <img src="/portfolio/projects/Portfolio_Zig.png" alt="Build System"/>
  <div class="project-card-body">
    <h3>Input Handler</h3>
    <div>
      <span class="project-tag">Programming</span>
      <span class="project-tag">Zig</span>
    </div>
  </div>
</div>

<!-- Math Library -->
<div class="project-card">
  <img src="/portfolio/projects/Portfolio_CPP.png" alt="Build System"/>
  <div class="project-card-body">
    <h3>Math Library</h3>
    <div>
      <span class="project-tag">Programming</span>
      <span class="project-tag">C++</span>
    </div>
  </div>
</div>

</div>