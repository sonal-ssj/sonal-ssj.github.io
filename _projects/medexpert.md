---
layout: page
title: MedExpert
description: A clinician-annotated benchmark for evaluating the factuality and completeness of medical chatbots.
img: assets/img/1.jpg
importance: 1
category: "Evaluation & Safety"
related_publications: true
---

**MedExpert** is an expert-annotated dataset for evaluating medical chatbots on two
safety-critical axes: **factuality** and **completeness** (omission detection).

- **540+** clinician-annotated question–response pairs from high-risk specialties —
  prenatal care and young-adult mental health — plus 32 dual-annotated pairs.
- **100+** unique questions authored by clinicians, each answered by 5 open-source LLMs
  (Llama-2 7B, Llama-3.3 70B, OLMo-2 13B, Gemma-2 27B, OpenBioLLM-70B).
- Annotated by **8 practicing clinicians** (MDs, residents, LCSW), with severity ratings
  for every factuality error and omission.

[Paper](https://openreview.net/forum?id=rkLAzDPlqL) ·
[GitHub](https://github.com/JHU-CLSP/MedExpert) ·
[Dataset](https://huggingface.co/datasets/sonal-ssj/MedExpert) — presented at **ML4H 2025**.

{% cite yarmohammadi2025medexpert %}
