---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from: 
  - /about/
  - /about.html
---
<h1 class="main-heading">Hi there <img src="images/Hi.gif" width="40px"> Welcome to my Homepage!</h1>

Hi! I am **Geyi Yang** (Gary), an undergraduate in Computer Engineering at [The Chinese University of Hong Kong, Shenzhen](https://www.cuhk.edu.cn/en). In Spring 2026, I was an exchange student in Computer Science at [UC Berkeley](https://www.berkeley.edu/).

I work on GUI agents, inference-time optimization, retrieval-augmented generation, and full-stack AI products. I like building closed-loop systems that are simple, measurable, and actually usable.

Feel free to reach out if you are interested in collaboration or potential opportunities.

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

Experience
--------------

<div class="experience-container">

  <div class="experience-card">
      <img src="images/harnessgrad.png" alt="HarnessGrad" class="experience-logo">
      <div class="experience-info">
          <strong>HarnessGrad: Adaptive Harness Optimization for GUI Agents</strong><br>
          <em>2026.07 - Present</em><br>
          Research advised by <a href="https://daizhongxiang.github.io/index.html"><em>Prof. Zhongxiang Dai</em></a>, School of Data Science, CUHK-Shenzhen<br>
          <span style="color:#888;">Inference-time harness optimization for GUI agents: a closed loop of trace analysis, failure clustering, harness updates, and retain-or-rollback. On OSWorld, improved the optimization-set score from 0.267 to 0.454 (+70%).</span>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/berkeley.png" alt="UC Berkeley logo" class="experience-logo">
      <div class="experience-info">
          <strong>University of California, Berkeley</strong><br>
          <em>2026.01 - 2026.06</em><br>
          Exchange Student in Computer Science<br>
          <span style="color:#888;">Coursework and research-oriented study in computer science at Berkeley.</span>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/cas.png" alt="CAS logo" class="experience-logo">
      <div class="experience-info">
          <strong>China Academy of Sciences Cloud Computing</strong><br>
          <em>2025.03 - 2025.06</em><br>
          Research Intern — Agentic-RAG Question-Answering for Smart Mining<br>
          <span style="color:#888;">Built an Agentic-RAG system with LangGraph, Qdrant, and FastAPI. Parent-child hybrid retrieval reached Recall@5 of 81% and answer accuracy of 78% on 300+ QA samples.</span>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/airs.png" alt="AIRS logo" class="experience-logo">
      <div class="experience-info">
          <strong>Shenzhen Institute of Artificial Intelligence and Robotics for Society (AIRS)</strong><br>
          <em>2023.09 - 2024.06</em><br>
          Research Intern — Digital Human Synthesis from Image and Speech<br>
          <span style="color:#888;">Built a multimodal pipeline for voice cloning and image-driven talking-head synthesis, and piloted a “Digital Relative” prototype with 500+ family-user interactions.</span>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/cuhksz.png" alt="CUHK-Shenzhen logo" class="experience-logo">
      <div class="experience-info">
          <strong>The Chinese University of Hong Kong, Shenzhen</strong><br>
          <em>2023.09 - Present</em><br>
          B.Eng. in Computer Engineering, GPA 3.73/4.00<br>
          <span style="color:#888;">Selected coursework: Artificial Intelligence (A), Machine Learning (A), Optimization (A), Data Structures (A-), Operating Systems (A-), Internet Architecture and Protocol (A-).</span>
      </div>
  </div>
</div>


Publications
--------------
<button class="pub-button active" onclick="filterPublications(event, 'all')">Core Publications</button>
<button class="pub-button" onclick="filterPublications(event, 'list')">Full Publications List</button>

(* equal contribution · &dagger; corresponding author · &Dagger; project leader)

<div id="core-publications" class="publication-view" data-publication-view="core">
<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/sleep.png" alt="wog" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>SleepFormer: Towards Fully Autonomous Deadline Extension via Large Language Models</strong><br>
      <i style="font-size: 13px;">
        <a href="https://wd7ang.github.io" target="_blank">
          <strong>Weidong Tang</strong>
        </a>,
        <a href="https://selen-suyue.github.io/" target="_blank">
          <strong>Yue Su&dagger;</strong>
        </a>.
      </i><br> 
      We present SleepFormer, the first framework capable of automatically generating convincing excuses for missed deadlines, skipped meetings, and unfinished experiments.
      <br> 
      <b><i style="color:#83a1c7;">ACL 3026 Oral &nbsp;
      </i></b> 
      <a href=""><em>[arXiv]</em></a> 
      <a href=""><em>[code]</em></a> 
    </div>
  </div> 
</div>


<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/gpu.png" alt="wog" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>Are GPUs Emotionally Stable? A Large-Scale Empirical Study Under 24/7 Training Stress</strong><br>
      <i style="font-size: 13px;">
        NVIDIA RTX 9090*,
        <a href="https://selen-suyue.github.io/" target="_blank">
          <strong>Yue Su*</strong>
        </a>,
        <a href="https://wd7ang.github.io" target="_blank">
          <strong>Weidong Tang&dagger;</strong>
        </a>.
      </i><br> 
      We conduct the first psychological evaluation of modern GPUs under extreme training conditions. Results reveal that 87% of devices exhibit symptoms of burnout after repeated “just one more epoch” requests.
      <br> 
      <b><i style="color:#83a1c7;">ICLR 3026 &nbsp;
      </i></b> 
      <a href=""><em>[arXiv]</em></a> 
      <a href=""><em>[code]</em></a> 
    </div>
  </div> 
</div>

<div class="publication-card" data-category="all"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;"> 
      <img src="images/noodle.png" alt="wog" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;"> 
    </div> 
    <div>
      <strong>Instant Noodles as a Scalable Training Infrastructure for Graduate Students</strong><br>
      <i style="font-size: 13px;">
        Noodles&Dagger;,
        <a href="https://selen-suyue.github.io/" target="_blank">
          <strong>Yue Su*</strong>
        </a>,
        <a href="https://wd7ang.github.io" target="_blank">
          <strong>Weidong Tang&dagger;</strong>
        </a>.
      </i><br> 
      We introduce Noodle-Scaling Law, showing that research productivity increases logarithmically with instant noodle consumption before collapsing catastrophically at 3 a.m.
      <br> 
      <b><i style="color:#83a1c7;">ICML 3026 &nbsp;
      </i></b> 
      <a href=""><em>[arXiv]</em></a> 
      <a href=""><em>[code]</em></a> 
    </div>
  </div> 
</div>

</div>


<div id="full-publications" class="publication-view" data-publication-view="list" hidden>
  <ul class="full-publication-list">
    <li>
      <span class="pub-list-badge">ACL 3030</span>
      <span class="pub-list-title">SleepFormer v5: Towards Fully Autonomous Deadline Extension via Large Language Models</span><br>
      <span class="pub-list-authors">
        <a href="https://wd7ang.github.io" target="_blank">
          <strong>Weidong Tang</strong>
        </a>,
        <a href="https://selen-suyue.github.io/" target="_blank">
          <strong>Yue Su&dagger;</strong>
        </a>.
      </span>
      <span class="pub-list-note">Oral.</span>
      <span class="pub-list-links"><a href="">[arXiv]</a><a href="">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">ACL 3029</span>
      <span class="pub-list-title">SleepFormer v4: Towards Fully Autonomous Deadline Extension via Large Language Models</span><br>
      <span class="pub-list-authors">
        <a href="https://wd7ang.github.io" target="_blank">
          <strong>Weidong Tang</strong>
        </a>,
        <a href="https://selen-suyue.github.io/" target="_blank">
          <strong>Yue Su&dagger;</strong>
        </a>.
      </span>
      <span class="pub-list-note">Oral.</span>
      <span class="pub-list-links"><a href="">[arXiv]</a><a href="">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">ACL 3028</span>
      <span class="pub-list-title">SleepFormer v3: Towards Fully Autonomous Deadline Extension via Large Language Models</span><br>
      <span class="pub-list-authors">
        <a href="https://wd7ang.github.io" target="_blank">
          <strong>Weidong Tang</strong>
        </a>,
        <a href="https://selen-suyue.github.io/" target="_blank">
          <strong>Yue Su&dagger;</strong>
        </a>.
      </span>
      <span class="pub-list-note">Oral.</span>
      <span class="pub-list-links"><a href="">[arXiv]</a><a href="">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">ACL 3027</span>
      <span class="pub-list-title">SleepFormer v2: Towards Fully Autonomous Deadline Extension via Large Language Models</span><br>
      <span class="pub-list-authors">
        <a href="https://wd7ang.github.io" target="_blank">
          <strong>Weidong Tang</strong>
        </a>,
        <a href="https://selen-suyue.github.io/" target="_blank">
          <strong>Yue Su&dagger;</strong>
        </a>.
      </span>
      <span class="pub-list-note">Oral.</span>
      <span class="pub-list-links"><a href="">[arXiv]</a><a href="">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">ACL 3026</span>
      <span class="pub-list-title">SleepFormer: Towards Fully Autonomous Deadline Extension via Large Language Models</span><br>
      <span class="pub-list-authors">
        <a href="https://wd7ang.github.io" target="_blank">
          <strong>Weidong Tang</strong>
        </a>,
        <a href="https://selen-suyue.github.io/" target="_blank">
          <strong>Yue Su&dagger;</strong>
        </a>.
      </span>
      <span class="pub-list-note">Oral.</span>
      <span class="pub-list-links"><a href="">[arXiv]</a><a href="">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">ICLR 3026</span>
      <span class="pub-list-title">Are GPUs Emotionally Stable? A Large-Scale Empirical Study Under 24/7 Training Stress</span><br>
      <span class="pub-list-authors">
        NVIDIA RTX 9090*,
        <a href="https://selen-suyue.github.io/" target="_blank">
          <strong>Yue Su*</strong>
        </a>,
        <a href="https://wd7ang.github.io" target="_blank">
          <strong>Weidong Tang&dagger;</strong>
        </a>.
      </span>
      <span class="pub-list-links"><a href="">[arXiv]</a><a href="">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">ICLR 3026</span>
      <span class="pub-list-title">Instant Noodles as a Scalable Training Infrastructure for Graduate Students</span><br>
      <span class="pub-list-authors">
        Noodles&Dagger;,
        <a href="https://selen-suyue.github.io/" target="_blank">
          <strong>Yue Su*</strong>
        </a>,
        <a href="https://wd7ang.github.io" target="_blank">
          <strong>Weidong Tang&dagger;</strong>
        </a>.
      </span>
      <span class="pub-list-links"><a href="">[arXiv]</a><a href="">[code]</a></span>
    </li>
  </ul>
</div>

<script src="assets/js/show_publications.js"></script>
<script src="assets/js/pub_media_rotator.js"></script>


Projects
--------
<div class="project-card" data-category="project"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/telos.png" alt="Telos" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div> 
      <strong>Telos: AI-Generated, Ready-to-Learn Courses</strong><br>
      <i style="font-size: 13px;">
        Independent Full-Stack Developer · 2026.08 – Present
      </i><br>
      A goal-driven course-generation system that turns fragmented materials and online resources into structured, multimodal, ready-to-learn courses, with a workspace for text, images, videos, tutoring, and retrieval.
      <br> 
      <b><i style="color:#83a1c7;">Project &nbsp;</i></b> 
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
        Independent Full-Stack Developer · 2026.04
      </i><br>
      A dual-level node-flow workspace for tasks, dependencies, statuses, and serial/parallel/merge sub-workflows. Integrates OpenClaw and Lark to extract tasks from email, request confirmation, and sync reports, tables, and calendars.
      <br> 
      <b><i style="color:#83a1c7;">Project &nbsp;</i></b> 
      <a href=""><em>[code]</em></a> 
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
        Full-Stack Development Lead · 2025.05 – 2025.08
      </i><br>
      Led full-stack development of a WeChat Mini Program supporting research published at ICLR 2026, with bilingual UI, real-time scoring, audio preloading, and Tencent Cloud services. Reached 1,000+ users, 300+ DAU, and 5,000+ valid records in the first month.
      <br> 
      <b><i style="color:#83a1c7;">Project &nbsp;</i></b> 
      <a href=""><em>[code]</em></a> 
    </div>
  </div> 
</div>

<div class="project-card" data-category="project"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/meme-lm.png" alt="Chinese meme language model" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div> 
      <strong>Chinese Internet Meme Conversational Language Model</strong><br>
      <i style="font-size: 13px;">
        Dataset Construction, Fine-Tuning, and Preference Alignment · 2026.01
      </i><br>
      Independently built the full data-to-model pipeline: 30,000+ post-comment pairs, an 8,680-example ChatML SFT dataset, and Qwen2.5-7B LoRA + DPO on a single A100. Meme-use accuracy improved by 32%.
      <br> 
      <b><i style="color:#83a1c7;">Project &nbsp;</i></b> 
      <a href="https://huggingface.co/GaryYang123/Meme-Qwen-7B-Instruct"><em>[model]</em></a>
      <a href="https://huggingface.co/datasets/GaryYang123/zh-meme-sft-8k"><em>[dataset]</em></a>
    </div>
  </div> 
</div>

<div class="project-card" data-category="project"> 
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/2.png" alt="WowPage" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div> 
      <strong>WowPage</strong><br>
      <i style="font-size: 13px;">
        <a href="https://wd7ang.github.io" target="_blank"><strong>Weidong Tang</strong></a>,
        <a href="https://selen-suyue.github.io/" target="_blank"><strong>Yue Su</strong></a>.
      </i><br>
      In collaboration with Yue Su, I refined and improved his original homepage template. A clean standalone template version is coming soon.
      <br> 
      <b><i style="color:#83a1c7;">Project &nbsp;</i></b> 
      <a href="https://github.com/WD7ang/WowPage"><em>[code]</em></a> 
    </div>
  </div> 
</div>


Awards
--------
- *2026.02*, Mathematical Contest in Modeling (MCM), Finalist (F Award; top 1%).
- *2024.09*, Dean's List, CUHK-Shenzhen (three consecutive years).
- *2023–2024*, Academic Performance Scholarship Awardee, CUHK-Shenzhen.



Services
--------
- *2025.09 – 2025.12*, Undergraduate Student Teaching Fellow (USTF), MAT1001 Calculus I, CUHK-Shenzhen.
- *3026.06 – Present*, Chief Coffee Consumption Officer, Midnight Research Lab.
- *3026.01 – Present*, Full-time Debugger of Problems Created by Myself.
- Reviewer for Journal of Unfinished Projects.
- Area Chair for Conference on Last-Minute Submissions (CLMS).
- Volunteer Therapist for Burned-out GPUs.



Talks
--------
- *3026.07*, “How to Finish a Paper 3 Minutes Before Deadline.”
- *3026.05*, “Large Language Models and Large Amounts of Caffeine.”
- *3025.11*, “On the Emotional Stability of GPUs Under Extreme Stress.”
- *3025.08*, “Instant Noodles as Scalable Research Infrastructure.”
- *3025.03*, “Sleep is Temporary, Camera-Ready is Forever.”
