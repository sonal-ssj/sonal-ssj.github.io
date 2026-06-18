---
layout: post
title: What Breaks This System, and Why, and How Can I Fix It?
date: 2026-06-16 09:00:00-0400
description: Ten years, four domains, one question.
tags: research AI safety speech
categories: thoughtpiece
---

For the last ten years, I kept asking the same question: _What breaks this system — and why — and how can I fix it?_ It connects everything I have worked on: speaker identification, ASR, adversarial speech, clinical AI safety, LLM-as-a-Judge, clinician–AI misalignment.

---

## The Question, Version 1

I did my undergrad in Electronics & Telecommunication. During my master's at IIT Jodhpur, I became fascinated by audio — not because of the spectrogram, but because you could _hear_ the data. One day, while choosing my thesis topic, an ISRO scientist visited the lab and asked something that sent my brain into overdrive:

> _When criminals cross a border and switch languages, can you still identify the speaker?_

I knew nothing about speech, language, or speaker identity. I knew almost nothing about machine learning. I said yes anyway. That yes was the first instance of a decision I would keep making: take the problem you cannot yet solve.

It also planted the question I have been asking ever since, in one form or another: **what breaks this system, and why, and how can I fix it?**

The domains changed. The question did not.

It cost something. I cold-emailed professors across IITs for guidance when my own advisor had no background in the area. My first thesis proposal was rejected. I rewrote it and landed on multilingual, multi-environment speaker identification. None of it was handed to me.

---

## Robustness, One Messy Problem at a Time

At TCS Research I joined the speech and NLP lab and built a low-resource Hindi ASR system, bootstrapped from English acoustic models, for the mKRISHI platform serving over 400,000 Indian farmers. The question underneath was the same one from my master's: what happens to your system when the input looks nothing like the clean case you trained on?

My supervisor saw the pattern before I named it. He pushed me toward a PhD. I applied broadly and got into Johns Hopkins.

---

## When the Noise Starts Fighting Back

At Hopkins, a DARPA project reframed the question in a way I did not expect. Noise is passive. An adversary adapts. In the worst-case scenario that defined my dissertation, the attacker has complete knowledge of your defense and you have none of their attack. You cannot assume the threat away. You have to build something that holds anyway.

I led the blue team across DARPA GARD and RED evaluations, and our defenses ranked at the top. One result I am proud of: dropping a poisoning attack's success rate from 99% to under 1%.

The curiosity from speaker ID had not gone anywhere. It had found a harder version of itself: when someone is actively and intelligently trying to fool your system, what actually holds?

---

## The Same Question, in Text

When the DARPA work wound down, I moved into LLM safety — specifically, catching when a medical chatbot's answer is incomplete or factually wrong. On paper this looked like a hard pivot: waveforms to clinical text, spectrograms to annotation rubrics.

It was not a pivot. The question was identical.

Can your system stay reliable when conditions — or an adversary, or its own overconfidence — are working against it? We showed that LLM-as-a-Judge frameworks cannot reliably tell when a medical answer leaves something critical out. Models agree on the verdict while pointing at entirely different reasons. Only 24.6% of model–clinician pairs cite the same omission even when they land on the same score.

The adversary this time was not a person. It was the gap between what a model is confident about and what a clinician actually knows.

---

## What Carried Over

Eighteen papers, two patents, and a path through speaker ID, noise-robust ASR, adversarial defense, keyword spotting at Microsoft, and clinical AI safety. People call it a varied career. To me it is one question asked in four rooms.

Three things held the whole way:

**I am comfortable starting at zero.** From that first yes to the ISRO question, to entering AI safety mid-PhD, the willingness to begin knowing nothing is what made each jump possible.

**I go toward the failure modes, and give it everything to fix them.** The interesting part of any system is where it breaks and why.

**I think end-to-end.** A speech pipeline, a poisoning defense, a clinical annotation workflow — I want to know what fails, where, and why it matters to the person on the other end of the system.

I used to say curiosity chose this path for me. That is not quite right. At every fork, I chose the unmapped problem on purpose. And at every fork I asked the same three things: what breaks this, why, and how do I fix it.

The thread did not connect itself. I kept tying it.

_Onward._
