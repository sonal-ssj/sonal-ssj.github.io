---
layout: post
title: What Breaks This System & Why & How Can I Fix It?
date: 2026-06-16 09:00:00-0400
description: 10 years, 1 question.
tags: research AI safety speech
categories: thoughtpiece
---

For the last ten years, I kept asking the same question:

> _What breaks this system — & why — & how can I fix it?_

It connects everything I have worked on: speaker identification, speech recognition, adversarial speech, poisoning attacks and defenses, clinical AI safety, LLM-as-a-Judge, clinician–AI misalignment & diagnosing failure modes

---

## The Question, Version 1

I did my undergrad in Electronics & Telecommunication. During my master's at IIT Jodhpur, I became fascinated by audio — not because of the spectrogram, but because you could _hear_ the data. One day, while choosing my thesis topic, an ISRO scientist visited the lab and asked something that sent my brain into overdrive:

> _When criminals cross a border and switch languages, can you still identify the speaker?_

I knew nothing about speech, language, or speaker identity. I knew almost nothing about machine learning. I said yes anyway. That yes was the first instance of a decision I would keep making: **take the problem you cannot yet solve**.

It also planted the question I have been asking ever since, in one form or another:

> What breaks this system & why & how can I fix it?\_

---

## Robustness, One Messy Problem at a Time

At TCS Research I joined the speech and NLP lab and we built a low-resource Hindi ASR system, bootstrapped from English acoustic models, for the mKRISHI platform (which later i got to know serves over 400,000 Indian farmers [link](https://www.tatatrusts.org/our-work/livelihood/agriculture-practices/mkrishi)). The question underneath was the same one from my master's: what happens to your system when the input looks nothing like the clean case you trained on? My supervisors might have seen something in me and encouraged me to pursue a PhD. I applied broadly and got into Johns Hopkins.

---

## When the Noise Starts Fighting Back

At Hopkins, a DARPA project reframed the question in a way I did not expect. Noise is passive. An adversary adapts. In the worst-case scenario that defined my dissertation, the attacker has complete knowledge of your defense and you have no kowledge of their attack. You cannot assume the threat. You have to build something that holds.

We led the blue team from JHU across DARPA GARD and RED evaluations, and our defenses ranked at the top.

The curiosity from speaker ID had not gone anywhere. It had found a harder version of itself: when someone is actively and intelligently trying to fool your system, what defense actually holds? The answer to that carried roots in the speech signal itself.

---

## The Same Question, in Text

When the DARPA work wound down, I moved into LLM safety — specifically, catching when a medical chatbot's answer is incomplete or factually wrong.

On paper, this looked like a hard pivot: waveforms to clinical text, spectrograms to annotation rubrics. But it was not a pivot. The question was identical.

Can your system stay reliable when conditions — or an adversary, or its own overconfidence — are working against it? We showed that LLM-as-a-Judge frameworks cannot reliably tell when a medical answer leaves something critical out. Models agree on the verdict while pointing at entirely different reasons.

---

## What Carried Over

18 papers, 2 patents & a winding path through speaker ID, noise-robust ASR, adversarial defense, keyword spotting at Microsoft, and clinical AI safety. One question carries the thread of all my work:

> _What breaks this system — & why — & how can I fix it?_

Reflecting, I am connecting the dots about what defines my work:

- **I am comfortable starting at zero.**
  From that first yes to the ISRO question, to entering AI safety mid-PhD, the willingness to begin knowing nothing is what made each jump possible.

- **I go toward the failure modes & give it my best inorder to fix.**
  The interesting part of any system is where it breaks and why. The more interesting part is actually fixing it and seeign the impact!

- **I think about the end-to-end system**
  A speech pipeline, a poisoning defense, a clinical annotation workflow — I want to know what fails, where, & why it matters to the person on the other end of the system.

I used to say curiosity chose this path for me. That is not quite right. At every fork, I chose the unmapped problem on purpose. And at every fork I asked the same three things:

> _What breaks this system — & why — & how can I fix it?_

_Onward._

With gratitude to all mentors over the years:

- Mark Dredze (JHU CLSP)
- Najim Dehak (JHU), Jesus Villaba, Piotr Zelasko, Thomas Thebaud, Laureano Moro-Velazquez (JHU), Sanjeev Khudanpur (JHU)
- Odette Scharenborg (TU Delft) for mentoring during PhD applications
- Ashish Panda & Sunil Kumar Kopparapu (TCS Research & Innovation)
- Sandeep Yadav (IIT Jodhpur) & Padmanabhan Rajan (IIT Mandi) for graduate thesis
- Prashant Upadhay (undergrad)
- my family!
