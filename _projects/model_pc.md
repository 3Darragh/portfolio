---
layout: page
title: Blender Computer
permalink: /projects/model_pc/
---

<div class="carousel" id="pc">
  <button class="arrow left-arrow" onclick="slide('pc', -1)">&#8249;</button>
  <img src="/portfolio/projects/Portfolio_PC_1.png" alt="Computer 2" class="active" style="border: 2px solid rgb(159, 224, 153);"/>
  <img src="/portfolio/projects/Portfolio_PC_2.png" alt="Computer 1" style="border: 2px solid rgb(159, 224, 153);"/>
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

**Tags:** 3D Model, Blender

**Description:** "A 3D model of my computer in Blender as part of an assignment to create an object with intricate shape and texture. 