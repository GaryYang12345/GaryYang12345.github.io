---
permalink: /projects/harnessgrad/
title: "HarnessGrad"
author_profile: true
comments: false
share: false
related: false
read_time: false
stylesheets:
  - /assets/css/home.css
---

<div class="project-detail">
  <p class="section-kicker">GUI agents · Jul. 2026 – Present</p>
  <p class="paper-meta">Research Assistant at CUHK-Shenzhen · advised by Prof. Zhongxiang Dai</p>
  <div class="paper-actions">
    <a class="brand-link" href="https://github.com/GaryYang12345/HarnessGrad"><i class="fab fa-github" aria-hidden="true"></i>GitHub</a>
    <a class="brand-link" href="{{ '/' | relative_url }}#research">Back</a>
  </div>
  <p>HarnessGrad is an inference-time method for improving GUI-agent harnesses without retraining the underlying agent model. A stronger model acts as a meta-controller: it reads rollouts, screenshots, and execution feedback, clusters systematic failures, attributes them to editable harness components, and proposes updates that are kept or rolled back after paired retesting.</p>
  <p>On OSWorld, with fixed Qwen3-VL-32B, UI-TARS-1.5-7B, and Agent-S3 components, the optimization-set score rose from 0.267 to 0.454 (+70%). An independent rerun reached 0.464.</p>
</div>
