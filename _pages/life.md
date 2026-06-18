---
layout: page
title: life
permalink: /life/
nav: true
nav_order: 5
---

## Travel

### India

I've visited **18 states** across India.

<div class="travel-map">
  <img src="https://douwe.com/projects/visited/india.png?selected=AN,TG,AP,DL,GA,GJ,HP,JK,KL,MP,MH,OR,PB,RJ,SK,TN,UP,WB" width="720" height="400" alt="Map of India showing visited states" />
</div>

---

## Photos

<div class="life-gallery">
  <!-- Photos go here — drop images into assets/img/life/ and add them below. -->

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

.travel-map {
  margin: 1rem 0 1.5rem;
  overflow-x: auto;
}

.travel-map img {
  max-width: 100%;
  height: auto;
  border-radius: 4px;
}

.placeholder-text {
  color: var(--global-text-color-light);
  font-style: italic;
}
</style>
