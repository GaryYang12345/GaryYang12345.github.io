---
permalink: /projects/voice-turing/
title: "Voice Turing Test"
author_profile: true
comments: false
share: false
related: false
read_time: false
stylesheets:
  - /assets/css/home.css
---

<article class="project-detail">
  <p class="section-kicker">Full-stack development lead · May 2025 – Aug. 2025</p>
  <p class="paper-meta">WeChat Mini Program · public game, product, and ICLR 2026 data platform</p>
  <div class="paper-actions">
    <a class="brand-link" href="https://openreview.net/forum?id=Pv5l6cvfno">ICLR 2026 paper</a>
    <a class="brand-link" href="{{ '/' | relative_url }}#development">Back to projects</a>
  </div>

  <p class="article-deck">Voice Turing Test is a public WeChat Mini Program that asks players to listen to multi-speaker conversations and decide whether a responder is human or AI. It turns a research evaluation into a compact game that people can understand in seconds.</p>

  <figure class="article-hero article-hero--compact">
    <img src="{{ '/images/Turing-cover.png' | relative_url }}" alt="Voice Turing Test illustrated project cover">
    <figcaption>A public-facing game and the data-collection platform for an ICLR 2026 study.</figcaption>
  </figure>

  <div class="metric-strip" aria-label="Voice Turing Test adoption">
    <div><strong>1,000+</strong><span>users in month one</span></div>
    <div><strong>300+</strong><span>daily active users</span></div>
    <div><strong>5,000+</strong><span>valid research records</span></div>
  </div>

  <h2>From research question to a playable product</h2>
  <p>Players hear a conversation, inspect the dialogue context, and judge whether the target voice belongs to a human or an AI system. Levels, achievements, combo rewards, referrals, leaderboards, and Chinese-English localization make repeated evaluation feel like a challenge rather than a survey. The experience also builds awareness of increasingly realistic synthetic speech.</p>

  <h2>Research platform</h2>
  <p>The product served as the data-collection platform for <a href="https://openreview.net/forum?id=Pv5l6cvfno"><em>Human or Machine? A Preliminary Turing Test for Speech-to-Speech Interaction</em></a>, published at ICLR 2026. I was not a paper author; my role was to lead the platform's product design and full-stack implementation.</p>

  <h2>My contribution</h2>
  <p>I independently owned the workflow from Mini Program registration and compliance through UI/UX design, front-end and back-end development, testing, deployment, and operations. The native WeChat front end controls the listening and judgment flow, while Tencent Cloud functions, database, and storage support user accounts, audio resources, scoring, and research-data collection.</p>

  <div class="article-gallery article-gallery--phones">
    <figure><img src="{{ '/images/turing.png' | relative_url }}" alt="Voice Turing Test start screen"><figcaption>Entry</figcaption></figure>
    <figure><img src="{{ '/images/turing2.png' | relative_url }}" alt="Voice Turing Test home and challenge modes"><figcaption>Modes</figcaption></figure>
    <figure><img src="{{ '/images/turing3.png' | relative_url }}" alt="Voice Turing Test campus rewards"><figcaption>Retention</figcaption></figure>
    <figure><img src="{{ '/images/turing4.png' | relative_url }}" alt="Voice Turing Test dialogue judgment screen"><figcaption>Judgment</figcaption></figure>
    <figure><img src="{{ '/images/turing5.png' | relative_url }}" alt="Voice Turing Test results screen"><figcaption>Feedback</figcaption></figure>
  </div>
</article>
