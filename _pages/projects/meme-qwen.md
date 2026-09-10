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

<article class="project-detail">
  <p class="section-kicker">Language modeling · Jan. 2026</p>
  <p class="paper-meta">Independent work · dataset construction, fine-tuning, and preference alignment</p>
  <div class="paper-actions">
    <a class="brand-link brand-link--hf" href="https://huggingface.co/GaryYang123/Meme-Qwen-7B-Instruct"><img src="{{ '/images/hf-logo.png' | relative_url }}" alt="">Model</a>
    <a class="brand-link brand-link--hf" href="https://huggingface.co/datasets/GaryYang123/zh-meme-sft-8k"><img src="{{ '/images/hf-logo.png' | relative_url }}" alt="">Dataset</a>
    <a class="brand-link" href="{{ '/' | relative_url }}#research">Back to projects</a>
  </div>

  <p class="article-deck">Meme-Qwen is an experiment in teaching a compact language model the timing, references, and conversational rhythm of Chinese internet memes rather than simply adding meme vocabulary to otherwise generic responses.</p>

  <figure class="article-hero">
    <img src="{{ '/images/projects/meme-qwen/dataset-viewer.webp' | relative_url }}" alt="Hugging Face viewer for the Meme-Qwen conversation dataset">
    <figcaption>The open dataset contains 8,680 ChatML conversations derived from a larger collection of public post-comment pairs.</figcaption>
  </figure>

  <div class="metric-strip" aria-label="Meme-Qwen results">
    <div><strong>30,000+</strong><span>raw pairs collected</span></div>
    <div><strong>8,680</strong><span>released examples</span></div>
    <div><strong>+32%</strong><span>meme-use accuracy</span></div>
  </div>

  <h2>Data-to-model pipeline</h2>
  <p>I collected public Chinese post-comment pairs with Playwright, filtered and normalized the data, and released the selected conversations in ChatML format. To our knowledge, it is the first open conversational SFT dataset and model centered on Chinese internet-meme usage.</p>

  <h2>Training and evaluation</h2>
  <p>Qwen2.5-7B was trained on a single A100 40GB GPU using LoRA followed by DPO preference alignment. Human and LLM preference evaluations reached 82%, 91%, and 68% for humor, meme accuracy, and conversational naturalness, respectively.</p>

  <blockquote class="article-quote">The objective was not to maximize meme frequency. It was to make references appear naturally, at the right moment, without overwhelming the conversation.</blockquote>
</article>
