---
layout: page
title: life
permalink: /life/
nav: true
nav_order: 5
---

## Travel

I love traveling. The maps below show where I've been: 18 states across India and 25 states across the US.

<div class="sar-pass-photo">
  <img src="{{ '/assets/img/life/sar_pass.jpg' | relative_url }}" alt="Sar Pass Trek, Himachal Pradesh, 13,800 ft" />
  <p class="photo-caption">Sar Pass Trek, Himachal Pradesh (13,800 ft)</p>
</div>

One summer, I completed the **Sar Pass Trek** in the Himalayas. Food and photography are my other interests.

### India

<div class="travel-map">
  <img src="https://douwe.com/projects/visited/india.png?selected=AN,TG,AP,DL,GA,GJ,HP,JK,KL,MP,MH,OR,PB,RJ,SK,TN,UP,WB" width="720" height="400" alt="Map of India, 18 states visited" />
</div>

### United States

<div class="travel-map">
  <img src="https://douwe.com/projects/visited/usa.png?selected=AL,AR,CA,DE,FL,GA,IL,IN,KS,LA,MD,MA,MS,MO,NH,NJ,NY,NC,OH,OK,PA,SC,TX,VA,WV" width="720" height="400" alt="Map of USA, 25 states visited" />
</div>

---

## Photos

<div class="life-gallery">
  <!-- More photos coming soon -->
  <p class="placeholder-text">More photos coming soon.</p>
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

.sar-pass-photo {
  margin: 1.5rem 0;
}

.sar-pass-photo img {
  width: 100%;
  max-width: 800px;
  height: auto;
  border-radius: 4px;
  display: block;
}

.photo-caption {
  margin-top: 0.4rem;
  font-size: 0.85rem;
  color: var(--global-text-color-light);
  font-style: italic;
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
