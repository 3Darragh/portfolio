---
layout: page
title: Blender Computer
permalink: /projects/model_pc/
---

<a href="/portfolio/works/" style="display: inline-block; margin-bottom: 20px; padding: 6px 16px; border: 2px solid rgb(159, 224, 153); color: var(--body-color); text-decoration: none; border-radius: 4px; font-size: 0.875rem; font-weight: bold;">← Back to Projects</a>

<div class="carousel" id="pc">
  <button class="arrow left-arrow" onclick="slide('pc', -1)">&#8249;</button>
  <img src="/portfolio/projects/Portfolio_PC_2.png" alt="Computer 1" class="active" style="border: 2px solid rgb(159, 224, 153);"/>
  <img src="/portfolio/projects/Portfolio_PC_1.png" alt="Computer 2" style="border: 2px solid rgb(159, 224, 153);"/>
  <button class="arrow right-arrow" onclick="slide('pc', 1)">&#8250;</button>
</div>

<script>
  function slide(id, dir) {
    const imgs = document.querySelectorAll('#' + id + ' img');
    let active = Array.from(imgs).findIndex(i => i.classList.contains('active'));
    imgs[active].classList.remove('active');
    active = (active + dir + imgs.length) % imgs.length;
    imgs[active].classList.add('active');
  }
</script>

<div style="margin-top: 16px;">
  <span class="tag-model">3D Model</span>
  <span class="tag-blender">Blender</span>
</div>

<div style="margin-top: 20px; padding: 16px; border: 2px solid rgb(159, 224, 153); border-radius: 6px; background: rgba(159, 224, 153, 0.05);">
  <strong>Description</strong>
  <p style="margin: 8px 0 10px 0;">A 3D model of my personal computer case created in Blender as part of an assignment to recreate an object from our homes.</p>
  <p style="margin: 0;">The goal of this assignment was to experiment with more complex shapes and textures, 
  which is why I chose this as while rigid the front panel has triangular holes which were created with a boolean modifier to make the first hole and an array modifier to repeat it.</p>
  <p style="margin: 0;"> The model also has reflective and emmisive textures on the glass side panel and the power button, better shown by the second image which has a basic wall and floor. </p>
</div>