---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from: 
  - /about/
  - /about.html
---

I am **Geyi Yang** (Gary), an undergraduate in Computer Engineering at [The Chinese University of Hong Kong, Shenzhen](https://www.cuhk.edu.cn/en). In Spring 2026, I was an exchange student in Computer Science at [UC Berkeley](https://www.berkeley.edu/).

I work on GUI agents, inference-time optimization, retrieval-augmented generation, and full-stack AI products. I like building closed-loop systems that are simple, measurable, and actually usable.

Feel free to reach out if you are interested in collaboration or potential opportunities.

<h2 id="education" class="section-heading">Education</h2>

<div class="edu-list">
  <div class="edu-item">
    <img src="images/cuhksz.png" alt="CUHK-Shenzhen logo" class="profile-logo">
    <div class="profile-text">
      <div class="profile-org">The Chinese University of Hong Kong, Shenzhen</div>
      <div class="profile-role">B.Eng. in Computer Engineering · GPA 3.73/4.00</div>
      <div class="profile-date">Sep. 2023 – Present</div>
    </div>
  </div>

  <div class="edu-item">
    <img src="images/berkeley.png" alt="UC Berkeley logo" class="profile-logo">
    <div class="profile-text">
      <div class="profile-org">University of California, Berkeley</div>
      <div class="profile-role">Exchange Student in Computer Science</div>
      <div class="profile-date">Jan. 2026 – Jun. 2026</div>
    </div>
  </div>
</div>

<h2 id="experience" class="section-heading">Experience</h2>

<div class="timeline">
  <div class="timeline-item">
    <img src="images/cuhksz.png" alt="CUHK-Shenzhen logo" class="profile-logo">
    <div class="profile-text">
      <div class="profile-org">The Chinese University of Hong Kong, Shenzhen</div>
      <div class="profile-role">Undergraduate Research Assistant, advised by <a href="https://daizhongxiang.github.io/index.html">Prof. Zhongxiang Dai</a></div>
      <div class="profile-date">Jul. 2026 – Present</div>
    </div>
  </div>

  <div class="timeline-item">
    <img src="images/zhongke.jpg" alt="Dongguan Zhongke Institute of Cloud Computing logo" class="profile-logo">
    <div class="profile-text">
      <div class="profile-org">Dongguan Zhongke Institute of Cloud Computing</div>
      <div class="profile-role">Research Intern</div>
      <div class="profile-date">Mar. 2025 – Jun. 2025</div>
    </div>
  </div>

  <div class="timeline-item">
    <img src="images/airs.png" alt="AIRS logo" class="profile-logo">
    <div class="profile-text">
      <div class="profile-org">Shenzhen Institute of Artificial Intelligence and Robotics for Society (AIRS)</div>
      <div class="profile-role">Research Intern</div>
      <div class="profile-date">Sep. 2023 – Jun. 2024</div>
    </div>
  </div>
</div>

{% comment %}
News
---------------
<div class="news-box">
  <ul class="news-list">

<li><span class="news-date"><em>2026.08</em></span> Started building <a href="https://github.com/GaryYang12345/Telos">Telos</a>, a goal-driven system for generating ready-to-learn courses.</li>
<li><span class="news-date"><em>2026.07</em></span> Started research on <a href="https://github.com/GaryYang12345/HarnessGrad">HarnessGrad</a> with <a href="https://daizhongxiang.github.io/index.html">Prof. Zhongxiang Dai</a> at SDS, CUHK-Shenzhen.</li>
<li><span class="news-date"><em>2026.06</em></span> Completed a Computer Science exchange at UC Berkeley.</li>
<li><span class="news-date"><em>2026.04</em></span> Built TaskFlow AI, a visual workspace for task orchestration and automation.</li>
<li><span class="news-date"><em>2026.02</em></span> Named Finalist (F Award, top 1%) in the Mathematical Contest in Modeling (MCM).</li>
<li><span class="news-date"><em>2026.01</em></span> Open-sourced a <a href="https://huggingface.co/GaryYang123/Meme-Qwen-7B-Instruct">Chinese meme conversational model</a> and an <a href="https://huggingface.co/datasets/GaryYang123/zh-meme-sft-8k">8.6k SFT dataset</a>.</li>
<li><span class="news-date"><em>2025.09</em></span> Served as Undergraduate Student Teaching Fellow for MAT1001 Calculus I at CUHK-Shenzhen.</li>
<li><span class="news-date"><em>2025.05</em></span> Led full-stack development of a Voice Turing Test data platform supporting research published at ICLR 2026.</li>
<li><span class="news-date"><em>2025.03</em></span> Started a research internship at China Academy of Sciences Cloud Computing on Agentic-RAG for smart mining.</li>
<li><span class="news-date"><em>2024.09</em></span> Named to the Dean's List at CUHK-Shenzhen (three consecutive years).</li>
<li><span class="news-date"><em>2023.09</em></span> Began B.Eng. in Computer Engineering at CUHK-Shenzhen, and joined AIRS as a research intern.</li>
  </ul>
</div>
{% endcomment %}

{% comment %}
Publications
--------------
<button class="pub-button active" onclick="filterPublications(event, 'all')">Core Publications</button>
<button class="pub-button" onclick="filterPublications(event, 'list')">Full Publications List</button>

(* equal contribution · &dagger; corresponding author · &Dagger; project leader)

<div id="core-publications" class="publication-view" data-publication-view="core">
</div>
{% endcomment %}

<h2 id="research" class="section-heading">Research Projects</h2>

<div class="project-card" data-category="project">
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/harnessgrad.png" alt="HarnessGrad" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div>
      <strong>HarnessGrad: Adaptive Harness Optimization for GUI Agents</strong><br>
      <i style="font-size: 13px;">
        Undergraduate Research Assistant · advised by <a href="https://daizhongxiang.github.io/index.html">Prof. Zhongxiang Dai</a> · Jul. 2026 – Present
      </i><br>
      Inference-time harness optimization for GUI agents, targeting accuracy-cost-latency trade-offs without changing the underlying models. Built a closed loop of trace analysis, failure clustering, harness attribution, paired retesting, and retain-or-rollback. On OSWorld, improved the optimization-set score from 0.267 to 0.454 (+70%).
      <br>
      <b><i class="project-tag">Research &nbsp;</i></b>
      <a href="https://github.com/GaryYang12345/HarnessGrad"><em>[code]</em></a>
    </div>
  </div>
</div>

<div class="project-card" data-category="project">
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/meme-lm.png" alt="Meme-Qwen-7B-Instruct" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div>
      <strong>Meme-Qwen-7B-Instruct</strong><br>
      <i style="font-size: 13px;">
        Dataset Construction, Fine-Tuning, and Preference Alignment · Jan. 2026
      </i><br>
      Independently built the full data-to-model pipeline: collected 30,000+ post-comment pairs, released an 8,680-example Chinese meme SFT dataset in ChatML format, and fine-tuned Qwen2.5-7B with LoRA and DPO on a single A100. Meme-use accuracy improved by 32%.
      <br>
      <b><i class="project-tag">Research &nbsp;</i></b>
      <a href="https://huggingface.co/GaryYang123/Meme-Qwen-7B-Instruct"><em>[model]</em></a>
      <a href="https://huggingface.co/datasets/GaryYang123/zh-meme-sft-8k"><em>[dataset]</em></a>
    </div>
  </div>
</div>

<h2 id="development" class="section-heading">Development Projects</h2>

<div class="project-card" data-category="project">
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/telos.png" alt="Telos" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div>
      <strong>Telos: AI-Generated, Ready-to-Learn Courses</strong><br>
      <i style="font-size: 13px;">
        Independent Full-Stack Developer · Aug. 2026 – Present
      </i><br>
      A goal-driven course-generation system that turns fragmented materials and online resources into structured, multimodal, ready-to-learn courses, with a workspace for text, images, videos, tutoring, and retrieval.
      <br>
      <b><i class="project-tag">Project &nbsp;</i></b>
      <a href="https://github.com/GaryYang12345/Telos"><em>[code]</em></a>
    </div>
  </div>
</div>

<div class="project-card" data-category="project">
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/taskflow.png" alt="TaskFlow AI" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div>
      <strong>TaskFlow AI: Visual Task Orchestration and Automation</strong><br>
      <i style="font-size: 13px;">
        Independent Full-Stack Developer · Apr. 2026
      </i><br>
      A dual-level node-flow workspace for tasks, dependencies, statuses, and serial/parallel/merge sub-workflows. Integrates OpenClaw and Lark to extract tasks from email, request confirmation, and sync reports, tables, and calendars.
      <br>
      <b><i class="project-tag">Project &nbsp;</i></b>
    </div>
  </div>
</div>

<div class="project-card" data-category="project">
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/voice-turing.png" alt="Voice Turing Test" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div>
      <strong>Voice Turing Test Data Collection Platform</strong><br>
      <i style="font-size: 13px;">
        Full-Stack Development Lead · May 2025 – Aug. 2025
      </i><br>
      Led full-stack development of a WeChat Mini Program supporting research published at ICLR 2026, with bilingual UI, real-time scoring, audio preloading, and Tencent Cloud services. Reached 1,000+ users, 300+ DAU, and 5,000+ valid records in the first month.
      <br>
      <b><i class="project-tag">Project &nbsp;</i></b>
    </div>
  </div>
</div>

<h2 id="awards" class="section-heading">Awards</h2>

- *2026.02*, Mathematical Contest in Modeling (MCM), Finalist (F Award; top 1%).
- *2024.09*, Dean's List, CUHK-Shenzhen (three consecutive years).
- *2023–2024*, Academic Performance Scholarship Awardee, CUHK-Shenzhen.

<h2 id="services" class="section-heading">Services</h2>

- *2025.09 – 2025.12*, Undergraduate Student Teaching Fellow (USTF), MAT1001 Calculus I, CUHK-Shenzhen.

{% comment %}
Talks
--------
{% endcomment %}
