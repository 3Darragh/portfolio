---
layout: page
title: Projects
permalink: /works/
---
<style>
  .page {
    max-width: 100%;
  }
  .content {
    max-width: 100%;
    padding-right: 2rem;
  }
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
  .tag-blender {
    display: inline-block; padding: 2px 10px; border-radius: 20px;
    font-size: 0.75rem; margin-right: 4px;
    border: 1px solid rgb(234, 118, 0); color: rgb(234, 118, 0);
  }
  .tag-unity {
    display: inline-block; padding: 2px 10px; border-radius: 20px;
    font-size: 0.75rem; margin-right: 4px;
    border: 1px solid rgb(0, 0, 0); color: rgb(0, 0, 0);
  }
  .tag-zig {
    display: inline-block; padding: 2px 10px; border-radius: 20px;
    font-size: 0.75rem; margin-right: 4px;
    border: 1px solid rgb(246, 164, 30); color: rgb(246, 164, 30);
  }
  .tag-cpp {
    display: inline-block; padding: 2px 10px; border-radius: 20px;
    font-size: 0.75rem; margin-right: 4px;
    border: 1px solid rgb(0, 84, 159); color: rgb(0, 84, 159);
  }
  .tag-javascript {
    display: inline-block; padding: 2px 10px; border-radius: 20px;
    font-size: 0.75rem; margin-right: 4px;
    border: 1px solid rgb(247, 223, 30); color: rgb(247, 223, 30);
  }
  .tag-model {
    display: inline-block; padding: 2px 10px; border-radius: 20px;
    font-size: 0.75rem; margin-right: 4px;
    border: 1px solid rgb(100, 160, 95); color: rgb(100, 160, 95);
  }
  .tag-interactive {
    display: inline-block; padding: 2px 10px; border-radius: 20px;
    font-size: 0.75rem; margin-right: 4px;
    border: 1px solid rgb(180, 100, 255); color: rgb(180, 100, 255);
  }
  .tag-tool {
    display: inline-block; padding: 2px 10px; border-radius: 20px;
    font-size: 0.75rem; margin-right: 4px;
    border: 1px solid rgb(246, 30, 30); color: rgb(246, 30, 30);
  }
</style>

<div class="project-grid">

  <!-- Build System -->
  <div class="project-card">
    <img src="/portfolio/projects/Portfolio_Zig.png" alt="Build System"/>
    <div class="project-card-body">
      <h3>Build System</h3>
      <p>A modular build library for game engines written in Zig.</p>
      <div>
        <span class="tag-tool">Development Tool</span>
        <span class="tag-zig">Zig</span>
      </div>
    </div>
  </div>

  <!-- Input Handler -->
  <div class="project-card">
    <img src="/portfolio/projects/Portfolio_Zig.png" alt="Input Handler"/>
    <div class="project-card-body">
      <h3>Input Handler</h3>
      <p>An input handler made with SDL3 for mouse, keyboard, and controllers.</p>
      <div>
        <span class="tag-tool">Development Tool</span>
        <span class="tag-zig">Zig</span>
      </div>
    </div>
  </div>

  <!-- Solar System -->
  <div class="project-card">
    <img src="/portfolio/projects/Portfolio_CPP.png" alt="Solar System"/>
    <div class="project-card-body">
      <h3>Interactive Solar System</h3>
      <p>An interactive solar system made in Javascript as an educational tool.</p>
      <div>
        <span class="tag-interactive">Interactive Demo</span>
        <span class="tag-javascript">Javascript</span>
      </div>
    </div>
  </div>

  <!-- Subway Scene -->
  <div class="project-card">
    <img src="/portfolio/projects/Portfolio_Subway_1.png" alt="Subway Scene"/>
    <div class="project-card-body">
      <h3>Subway Scene</h3>
      <p>A custom subway tunnel scene made in Blender.</p>
      <div>
        <span class="tag-model">3D Model</span>
        <span class="tag-blender">Blender</span>
      </div>
    </div>
  </div>

  <!-- Math Library -->
  <div class="project-card">
    <img src="/portfolio/projects/Portfolio_CPP.png" alt="Math Library"/>
    <div class="project-card-body">
      <h3>Math Library</h3>
      <p>A math library built from scratch with vectors, matrices, and quaternions.</p>
      <div>
        <span class="tag-tool">Development Tool</span>
        <span class="tag-cpp">C++</span>
      </div>
    </div>
  </div>

  <!-- Unity Demo -->
  <div class="project-card">
    <img src="/portfolio/projects/Portfolio_CPP.png" alt="Unity Character Demo"/>
    <div class="project-card-body">
      <h3>Unity Character Demo</h3>
      <p>Playable Unity Demo made to show physics applied to the character controller.</p>
      <div>
        <span class="tag-interactive">Interactive Demo</span>
        <span class="tag-unity">Unity</span>
      </div>
    </div>
  </div>

  <!-- AC Unit -->
  <div class="project-card">
    <img src="/portfolio/projects/Portfolio_AC_1.png" alt="AC Unit"/>
    <div class="project-card-body">
      <h3>AC Unit</h3>
      <p>A detailed 3D model of an AC unit made in Blender.</p>
      <div>
        <span class="tag-model">3D Model</span>
        <span class="tag-blender">Blender</span>
      </div>
    </div>
  </div>

  <!-- Locker -->
  <div class="project-card">
    <img src="/portfolio/projects/Portfolio_Locker_1.png" alt="School Locker"/>
    <div class="project-card-body">
      <h3>School Locker</h3>
      <p>A 3D model of a school locker made in Blender.</p>
      <div>
        <span class="tag-model">3D Model</span>
        <span class="tag-blender">Blender</span>
      </div>
    </div>
  </div>

  <!-- PC Case -->
  <div class="project-card">
    <img src="/portfolio/projects/Portfolio_PC_2.png" alt="PC Case"/>
    <div class="project-card-body">
      <h3>PC Case</h3>
      <p>A 3D model of a PC case made in Blender.</p>
      <div>
        <span class="tag-model">3D Model</span>
        <span class="tag-blender">Blender</span>
      </div>
    </div>
  </div>

</div>