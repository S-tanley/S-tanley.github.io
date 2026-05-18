---
title: "Real-Time Language Model Jamming: A Case Study for Live Music Accompaniment Generation"
collection: publications
category: conferences
permalink: /publication/2025-11-01-real-time-language-model-jamming
excerpt: 'A case study on live music accompaniment generation with real-time language models.'
date: 2026-01-01
venue: 'IEEE Real-Time and Embedded Technology and Applications Symposium (RTAS)'
citation: '<strong>Bowen Zheng</strong><sup>*</sup>, Andrew Yang<sup>*</sup>, Jiaqi Ruan, He Jia, Xinyue Li, Yuanxin Chen, Ziyu Wang<sup>&dagger;</sup>, and Xiaosong Ma<sup>&dagger;</sup>. (2026). &quot;Real-Time Language Model Jamming: A Case Study for Live Music Accompaniment Generation.&quot; <i>RTAS 2026</i>.'
# paperurl: '/files/你的论文.pdf'
# slidesurl: '/files/你的slides.pdf'
---

Language models (LMs) have become one of the
most prominent paradigms in modern generative modeling.
While making them faster has been the main focus of real-time
deployment, speed alone is not enough. Many real-world applications, such as synchronized translation and voice synthesis,
also require precise alignment between generation and external
signals, both in terms of generation content and timing. We
refer to this problem as frame-synchronous streaming inference.
To address it, we present StreamMUSE, an inference system
that performs LM generation in response to an external signal
stream within a client-server architecture. The client continuously
sends high-frequency inference requests based on the most recent
inputs and receives outputs synchronized to the external clock,
while the server executes model inference. We demonstrate the
framework through a live music accompaniment task, showing
how real-time synchronization can be achieved across different
deployment environments with varying round-trip latencies. We
further model the relationship between system hyperparameters
and round-trip latency, and evaluate how different environments
affect optimal configurations to achieve real-time performance.
Experimental results show a consistent correspondence between
system real-time performance and music quality, demonstrating
the effectiveness of the proposed framework. The code is open-sourced at [https://github.com/StreamMUSE/AE](https://github.com/StreamMUSE/AE).
