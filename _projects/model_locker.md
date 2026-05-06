---
layout: page
title: Blender Locker
permalink: /projects/model_locker/
---

<a href="/portfolio/works/" style="display: inline-block; margin-bottom: 20px; padding: 6px 16px; border: 2px solid rgb(159, 224, 153); color: var(--body-color); text-decoration: none; border-radius: 4px; font-size: 0.875rem; font-weight: bold;">← Back to Projects</a>

<div class="carousel" id="locker">
  <button class="arrow left-arrow" onclick="slide('locker', -1)">&#8249;</button>
  <img src="/portfolio/projects/Portfolio_Locker_1.png" alt="Locker 1" class="active" style="border: 2px solid rgb(159, 224, 153);"/>
  <img src="/portfolio/projects/Portfolio_Locker_2.png" alt="Locker 2" style="border: 2px solid rgb(159, 224, 153);"/>
  <button class="arrow right-arrow" onclick="slide('locker', 1)">&#8250;</button>
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

**Tags:** 3D Model, Blender

**Description:** "A 3D model of a school locker created in Blender as part of a class assignment to find and recreate an everyday object found around campus. The goal of this assignment was to practice accuracy in texturing and scaling. Uses basic textures with toned down metalic maps and I made a basic black and white texture for the handle.