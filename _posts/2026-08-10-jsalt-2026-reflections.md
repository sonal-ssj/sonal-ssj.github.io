---
layout: post
title: JSALT Wrapped — Reflections on Evaluating AI
date: 2026-08-10 09:00:00-0400
description: Takeaways from the 12th Frederick Jelinek Memorial Summer Workshop on measuring, judging, and Goodhart's Law.
tags: research AI evaluation
categories: thoughtpiece
---

{% include figure.liquid path="/assets/img/jsalt-2026-group.jpeg" alt="JSALT 2026 participants at Johns Hopkins University" caption="A group of JSALT 2026 participants gathers during the workshop at Johns Hopkins University." %}

JSALT wrapped up today. For me, it was a reminder of just how rapidly the AI world is moving, and how it matters more than ever that we build the right thing, the right way. Here are some of the reflections and takeaways from the workshop.

- **The term "good" isn't a single attribute**: A reply from AI can be accurate but cold, safe but slow, fluent but off-topic. Accuracy, tone, safety, latency, relevance — all of it matters at once. Anyone measuring only a single number is hiding behind the other N. A single metric often tells a very incomplete story.

- **The easy things to measure are rarely the things that matter**: Latency, F1, WER are simple to monitor. Whether or not it is actually helpful to the user and solved the problem is a different game. An AI can pass all benchmarks and yet still fail. To detect these silent failures, a deep dive into data & traces is needed.

- **Today's AI has no answer key**: Ask the same question twice and a non-deterministic LLM means you get two good answers, similar but worded differently. And if you phrase the question a bit differently, you get more answers! Match scoring was suitable for classical machine learning but breaks down as soon as there are 100s of ways of being correct in different ways. Getting "ground truth" answers is also very hard with annotation budgets and time to get them right.

- **Rigor vs. speed**: A thorough eval adds cost and delay. And if logging and tracing are not built in from the start, you are signing up to just hope for the best.

- **LLM-as-judge is harder than the simple prompt you might think it is**: The judge has the same blind spots (hallucinations, implicit learnt reasoning from training) as the model it grades. A good judge needs calibration with domain experts and real conversations with actual users.

My mind kept going back to **Goodhart's Law**: "When a measure becomes a target, it stops being a good measure." A golden dataset/benchmark starts as a proxy for quality. The moment you optimize for the score, the score and the quality drift apart… and gives you a false sense of hope!

Cross-posted from [LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7491596730665316352/).
