---
layout: page
title: Subway Scene
permalink: /projects/model_subway/
---

<a href="/portfolio/works/" style="display: inline-block; margin-bottom: 20px; padding: 6px 16px; border: 2px solid rgb(159, 224, 153); color: var(--body-color); text-decoration: none; border-radius: 4px; font-size: 0.875rem; font-weight: bold;">← Back to Projects</a>

<div class="carousel" id="subway">
  <button class="arrow left-arrow" onclick="slide('subway', -1)">&#8249;</button>
  <img src="/portfolio/projects/Portfolio_Subway_1.png" alt="Subway Scene 1" class="active" style="border: 2px solid rgb(159, 224, 153);"/>
  <img src="/portfolio/projects/Portfolio_Subway_2.png" alt="Subway Scene 2" style="border: 2px solid rgb(159, 224, 153);"/>
  <button class="arrow right-arrow" onclick="slide('subway', 1)">&#8250;</button>
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
  <p style="margin: 8px 0 10px 0;">A full 3D subway tunnel scene created in Blender, built as a complete environment rather than a single object.</p>
  <p style="margin: 0;">The models are fully modular and tilable, so if I were to extend the tunel the models
  can be seemlessly connected at tunnel ends to double its length.</p>
  <p style="margin: 0;">I plan to expand this scene with textures, ceiling details, and a train that I will
  animate going down the track, which would bring this scene to life.</p>
</div>