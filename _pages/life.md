---
layout: page
title: life
permalink: /life/
nav: true
nav_order: 5
---

<div class="life-gallery">
  <!-- Photos go here — drop images into assets/img/life/ and add them below.
       Format: ![alt text](path){:.life-photo} -->

  <p class="placeholder-text">Photos coming soon.</p>
</div>

<style>
.life-gallery {
  columns: 3;
  column-gap: 1rem;
}

.life-gallery img {
  width: 100%;
  margin-bottom: 1rem;
  break-inside: avoid;
  border-radius: 4px;
}

@media (max-width: 768px) {
  .life-gallery {
    columns: 2;
  }
}

@media (max-width: 480px) {
  .life-gallery {
    columns: 1;
  }
}

.placeholder-text {
  color: var(--global-text-color-light);
  font-style: italic;
}
</style>
