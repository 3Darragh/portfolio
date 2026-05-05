---
layout: page
title: AC Unit
permalink: /projects/model_ac/
---

<div class="carousel" id="ac">
  <button class="arrow left-arrow" onclick="slide('ac', -1)">&#8249;</button>
  <img src="/portfolio/projects/Portfolio_locker_1.png" alt="AC Unit 1" class="active" style="border: 2px solid rgb(159, 224, 153);"/>
  <img src="/portfolio/projects/Portfolio_locker_2.png" alt="AC Unit 2" style="border: 2px solid rgb(159, 224, 153);"/>
  <button class="arrow right-arrow" onclick="slide('ac', 1)">&#8250;</button>
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

**Description:** "A 3D model of a school locker created in Blender as part of a class assignment to find and recreate an everyday object found around campus. The goal of this assignment was to practice accuracy in texturing and scaling.