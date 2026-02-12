---
layout: post
title: MedExpert presented at ML4H
date: 2025-12-02 16:11:00-0400
inline: false
related_posts: false
---

𝗚𝗮𝗽: Most medical benchmarks test knowledge (e.g., multiple-choice QA), but not safety in open-ended patient-chatbot interactions.
𝗥𝗶𝘀𝗸: LLMs generate plausible but dangerous hallucinations or omit life-critical warnings. Patients cannot verify medical accuracy, so we need expert clinicians.
𝗡𝗲𝗲𝗱: Fine-grained, expert-level evaluation of Factuality and Completeness of LLMs.

𝗜𝗻𝘁𝗿𝗼𝗱𝘂𝗰𝗶𝗻𝗴 𝗠𝗲𝗱𝗘𝘅𝗽𝗲𝗿𝘁, 𝗱𝗮𝘁𝗮𝘀𝗲𝘁 𝗳𝗼𝗿 𝗺𝗲𝗱𝗶𝗰𝗮𝗹 𝗰𝗵𝗮𝘁𝗯𝗼𝘁 𝗲𝘃𝗮𝗹𝘂𝗮𝘁𝗶𝗼𝗻, 𝗽𝗿𝗲𝘀𝗲𝗻𝘁𝗲𝗱 𝗮𝘁 𝗠𝗟𝟰𝗛! 🎓🤖

𝗠𝗲𝗱𝗘𝘅𝗽𝗲𝗿𝘁-𝗕𝗲𝗻𝗰𝗵𝗺𝗮𝗿𝗸: 540 clinician-annotated Question-Response pairs from the high-risk medical specialties of Prenatal Care and Young Adult Mental Health. Additional 32 dual-annotated pairs. Subtasks: factuality and omission detection.

𝗤𝘂𝗲𝘀𝘁𝗶𝗼𝗻-𝗥𝗲𝘀𝗽𝗼𝗻𝘀𝗲𝘀: 100+ unique questions were authored by clinicians based on focus groups & clinical experience. Each question was answered by 5 open-source LLMs: Llama-2 7B, Llama-3.3 70B, OLMo-2 13B, Gemma-2 27B, and OpenBioLLM-70B

𝗔𝗻𝗻𝗼𝘁𝗮𝘁𝗶𝗼𝗻𝘀: 8 practicing clinicians (MDs, Residents, LCSW)

MedExpert includes detailed annotations for factuality & omissions with severity ratings to help keep evaluation systems rigorous and accountable.

Big thanks to the team at JHU, RTX-BBN, and our clinical collaborators! 🙏 Alexandra DeLucia, Lillian Chen, Leslie Miller, Heyuan Huang, Sonal Joshi, Jonathan Lasko, Sarah Collica, Ryan Moore, Haoling Qiu, Peter Zandi, Damianos Karakos, Mark Dredze. 

We have open-sourced the code and data to support the community’s drive for safer medical AI. 🚀
[𝗣𝗮𝗽𝗲𝗿](https://openreview.net/forum?id=rkLAzDPlqL)
[𝗚𝗶𝘁𝗛𝘂𝗯](https://github.com/JHU-CLSP/MedExpert)
[𝗗𝗮𝘁𝗮𝘀𝗲𝘁](https://huggingface.co/datasets/sonal-ssj/MedExpert)
