---
layout: page
title: Analyzing Clinician–System Disagreements
description: Where automated medical evaluation diverges from expert judgment — and why scaling doesn't fix it.
img: assets/img/3.jpg
importance: 3
category: "Evaluation & Safety"
---

Two studies dissecting *why* automated evaluators and clinicians disagree on medical
chatbot outputs.

**LLM-as-a-Judge fails on completeness.** Judges score near chance (**AUC 0.49–0.66**)
across 3 rubrics, 3 models, and 2 clinician datasets. Even when an LLM and a clinician
reach the same verdict, only **24.6%** cite the same omission — verdict-level agreement
hides disagreement on the reasons.
*"Same Verdict, Different Reasons: LLM-as-a-Judge and Clinician Disagreement on Medical
Chatbot Completeness,"* **in preparation for HCOMP 2026**.
[arXiv](https://arxiv.org/abs/2604.16383)

**Retrieval-based factuality evaluation has structural limits.** A taxonomy-driven
analysis across **6 verifier LLMs × 4 retrievers × 3 corpora** shows that scaling,
reasoning effort, medical fine-tuning, and corpus expansion all fail to fix the dominant
failure modes of retrieve-then-verify pipelines in open-ended medical settings.
*"Taxonomy-Driven Performance Analysis of Retrieval-Based Open-ended Factuality
Evaluation: A Medical Case Study,"* **ACL ARR 2026**.
