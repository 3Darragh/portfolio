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

  <div style="margin-bottom: 40px;">
    <h3>AC Unit</h3>
    <img src="/portfolio/projects/Portfolio_AC_1.png" width="100%" alt="AC Unit Main" style="border: 3px solid rgb(159, 224, 153); display: block; margin-bottom: 10px;"/>
    <img src="/portfolio/projects/Portfolio_AC_2.png" width="50%" alt="AC Unit Detail" style="border: 3px solid rgb(159, 224, 153); display: block;"/>
  </div>

  <div style="margin-bottom: 40px;">
    <h3>School Locker</h3>
    <img src="/portfolio/projects/Portfolio_Locker_1.png" width="100%" alt="Locker Main" style="border: 3px solid rgb(159, 224, 153); display: block; margin-bottom: 10px;"/>
    <img src="/portfolio/projects/Portfolio_Locker_2.png" width="50%" alt="Locker Detail" style="border: 3px solid rgb(159, 224, 153); display: block;"/>
  </div>

  <div style="margin-bottom: 40px;">
    <h3>PC Case</h3>
    <img src="/portfolio/projects/Portfolio_PC_1.png" width="100%" alt="PC Case Main" style="border: 3px solid rgb(159, 224, 153); display: block; margin-bottom: 10px;"/>
    <img src="/portfolio/projects/Portfolio_PC_2.png" width="50%" alt="PC Case Detail" style="border: 3px solid rgb(159, 224, 153); display: block;"/>
  </div>

  <div style="margin-bottom: 40px;">
    <h3>Subway Scene</h3>
    <img src="/portfolio/projects/Portfolio_Subway_1.png" width="100%" alt="Subway Main" style="border: 3px solid rgb(159, 224, 153); display: block; margin-bottom: 10px;"/>
    <img src="/portfolio/projects/Portfolio_Subway_2.png" width="50%" alt="Subway Detail" style="border: 3px solid rgb(159, 224, 153); display: block;"/>
  </div>

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