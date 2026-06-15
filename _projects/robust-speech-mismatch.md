---
layout: page
title: Robust Speech Under Train–Test Distribution Mismatch
description: Keeping ASR accurate when test-time audio doesn't match training data: noise, channel, and far-field shift.
img: assets/img/8.jpg
importance: 3
category: "Speech & Robustness"
related_publications: true
---

Real-world speech rarely matches clean training data. This work targets the train–test
distribution mismatch that degrades ASR in the field: background noise, channel
artifacts, and far-field/reverberant capture.

- Cut WER **9.21%** (LibriSpeech) and PER **5.92%** (TIMIT) via residual-noise artifact
  removal, and improved far-field ASR on CHiME-5 with a TDNN denoising autoencoder
  {% cite joshi2018enhanced %}.
