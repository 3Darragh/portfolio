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
  <h2>Models</h2>
  <!-- projects go here -->
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