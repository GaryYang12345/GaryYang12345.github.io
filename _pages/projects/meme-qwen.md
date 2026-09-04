---
permalink: /projects/meme-qwen/
title: "Meme-Qwen-7B-Instruct"
author_profile: true
comments: false
share: false
related: false
read_time: false
stylesheets:
  - /assets/css/home.css
---

<div class="project-detail">
  <p class="section-kicker">Language modeling · Jan. 2026</p>
  <p class="paper-meta">Independent work · dataset construction, fine-tuning, and preference alignment</p>
  <div class="paper-actions">
    <a class="brand-link brand-link--hf" href="https://huggingface.co/GaryYang123/Meme-Qwen-7B-Instruct"><img src="{{ '/images/hf-logo.png' | relative_url }}" alt="">Model</a>
    <a class="brand-link brand-link--hf" href="https://huggingface.co/datasets/GaryYang123/zh-meme-sft-8k"><img src="{{ '/images/hf-logo.png' | relative_url }}" alt="">Dataset</a>
    <a class="brand-link" href="{{ '/' | relative_url }}#research">Back</a>
  </div>
  <p>I built the full data-to-model pipeline for a Chinese meme conversational model. The work started with 30,000+ post-comment pairs collected with Playwright, then an 8,680-example SFT dataset released in ChatML format.</p>
  <p>Qwen2.5-7B was fine-tuned on one A100 (40GB) with LoRA and DPO. Meme-use accuracy improved by 32%. Human and LLM preference rates were 82% / 91% / 68% for humor, accuracy, and naturalness.</p>
</div>
