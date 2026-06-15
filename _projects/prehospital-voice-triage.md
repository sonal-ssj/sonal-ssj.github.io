---
layout: page
title: ASR for Noisy Radio Speech, TTS for Fine-Tuning
description: Turning noisy EMS radio into structured clinical data before the patient arrives.
img: assets/img/9.jpg
importance: 2
category: "Speech & Robustness"
---

A current project (Harvard collaboration, PI: Gabriel Brat, MD) building an
**agentic voice interface** for pre-hospital neurological emergency triage (NEI-6).

The pipeline converts noisy EMS radio audio into structured clinical markers
_before the patient arrives_:

- **Synthetic data generation** via TTS+LLM to overcome scarce, sensitive real-world audio,
- **fine-tuned ASR** on a synthetic–real mix,
- **LLM-based transcript correction** to recover clinically meaningful content from
  degraded transmissions.

The evaluation target is downstream clinical-marker accuracy, not just transcript
word-error-rate.
