---
layout: page
title: Securing Speech Systems Against Adversarial & Poisoning Attacks
description: PhD dissertation work — top-ranked DARPA GARD/RED blue-team defenses for speech and speaker recognition.
img: assets/img/7.jpg
importance: 1
category: "Speech & Robustness"
related_publications: true
---

My PhD thesis built defenses for speech systems under worst-case threat models
(full attacker knowledge, zero defender knowledge), as the lead of JHU's top-ranked
blue team across the **DARPA GARD** and **RED** programs.

- **Adversarial ASR:** tandem adversarial fine-tuning + denoiser defense cut WER
  degradation **45%** against PGD-500 attacks {% cite joshi2022defense %}
  *(Interspeech 2022, Oral)*.
- **Data poisoning:** an unsupervised KMeans defense over DINO embeddings dropped attack
  success from **99% → 0.25%** {% cite thebaud2023clustering %} *(ASRU 2023)*.
- **Speaker recognition:** ParallelWaveGAN vocoder preprocessing gave **~41%** average
  absolute robustness gain {% cite joshi2021study %} *(IEEE TIFS, IF 7.2)*.
- **Attack forensics:** ~90% accuracy classifying known attacks and victim models
  {% cite joshi2024unraveling %} *(Odyssey 2024, Oral)*.

Dissertation: *Securing Speech Systems Against Adversarial and Poisoning Attacks*
(JHU, 2025).
