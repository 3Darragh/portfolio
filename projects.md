---
layout: page
title: Projects
permalink: /projects/
---

<div style="text-align: center; margin-bottom: 30px;">
  <button onclick="showTab('3D Models')">Models</button>
  <button onclick="showTab('Programs and Tools')">Programs</button>
  <button onclick="showTab('Interactive Projects')">Interactive</button>
</div>

<div id="models">

  <style>
    .model { margin-bottom: 40px; position: relative; }
    .model h3 { margin-bottom: 10px; }
    .carousel { position: relative; overflow: hidden; }
    .carousel img { width: 100%; display: none; border: 3px solid rgb(159, 224, 153); }
    .carousel img.active { display: block; }
    .arrow {
      position: absolute; top: 50%; transform: translateY(-50%);
      background: rgba(0,0,0,0.3); color: white; border: none;
      font-size: 24px; padding: 10px 16px; cursor: pointer;
      z-index: 10; transition: background 0.2s;
    }
    .arrow:hover { background: rgba(0,0,0,0.6); }
    .left-arrow { left: 10px; }
    .right-arrow { right: 10px; }
  </style>

  <script>
    function slide(id, dir) {
      const imgs = document.querySelectorAll('#' + id + ' img');
      let active = Array.from(imgs).findIndex(i => i.classList.contains('active'));
      imgs[active].classList.remove('active');
      active = (active + dir + imgs.length) % imgs.length;
      imgs[active].classList.add('active');
    }
  </script>

  <div class="model">
    <h3>AC Unit</h3>
    <div class="carousel" id="ac">
      <button class="arrow left-arrow" onclick="slide('ac', -1)">&#8249;</button>
      <img src="/portfolio/projects/Portfolio_AC_1.png" alt="AC Unit 1" class="active"/>
      <img src="/portfolio/projects/Portfolio_AC_2.png" alt="AC Unit 2"/>
      <button class="arrow right-arrow" onclick="slide('ac', 1)">&#8250;</button>
    </div>
  </div>

  <div class="model">
    <h3>School Locker</h3>
    <div class="carousel" id="locker">
      <button class="arrow left-arrow" onclick="slide('locker', -1)">&#8249;

</div>

<div id="programs" style="display:none;">
  <h2>Programs</h2>
  <!-- projects go here -->
</div>

<div id="interactive" style="display:none;">
  <h2>Interactive</h2>
  <!-- projects go here -->
</div>

<script>
  function showTab(tab) {
    document.getElementById('3D Models').style.display = 'none';
    document.getElementById('Programs and Tools').style.display = 'none';
    document.getElementById('Interactive Projects').style.display = 'none';
    document.getElementById(tab).style.display = 'block';
  }
</script>