---
permalink: /
author_profile: false
stylesheets:
  - /assets/css/home.css
redirect_from:
  - /about/
  - /about.html
---

<header class="profile-intro">
  <img class="profile-intro__photo" src="{{ '/images/avatar1.jpg' | relative_url }}" alt="Portrait of Geyi Yang">
  <div class="profile-intro__copy">
    <h1>Geyi Yang <span>杨戈易</span></h1>
    <p>Hi, I am Geyi Yang, also known as Gary. I am an undergraduate researcher in Computer Engineering at <a href="https://www.cuhk.edu.cn/en">The Chinese University of Hong Kong, Shenzhen</a> (CUHK-Shenzhen), and was a GLOBE Program visiting student in Computer Science at <a href="https://www.berkeley.edu/">UC Berkeley</a> in Spring 2026. I am currently advised by <a href="https://daizhongxiang.github.io/index.html">Prof. Zhongxiang Dai</a>.</p>
    <p>I am broadly interested in <strong>LLM-based agents, GUI agents, self-improving agentic systems, harness optimization, and retrieval-augmented generation (RAG)</strong>. My previous work also covers LLM post-training and dataset construction.</p>
    <nav class="profile-links" aria-label="Profile links">
      <a href="mailto:123090721@link.cuhk.edu.cn"><i class="fas fa-envelope" aria-hidden="true"></i>Email</a>
      <a href="https://github.com/GaryYang12345"><i class="fab fa-github" aria-hidden="true"></i>GitHub</a>
      <a href="https://huggingface.co/GaryYang123"><img src="{{ '/images/hf-icon.svg' | relative_url }}" alt="">Hugging Face</a>
      <a href="{{ '/files/GeyiYang_CV.pdf' | relative_url }}"><i class="fas fa-file-alt" aria-hidden="true"></i>CV</a>
    </nav>
  </div>
</header>

<section id="research" class="home-section">
  <h2>Research</h2>
  <p>More recently, I have become particularly interested in <strong>self-improving agentic systems and recursive self-improvement (RSI)</strong>, especially how agents can turn their own execution traces, failures, and feedback into reliable improvements in future behavior. My current work, <a href="{{ '/projects/gui-harvest/' | relative_url }}">GUI-HARVEST</a>, studies how repeated multimodal execution evidence can drive systematic, validated changes to a GUI agent's inference-time harness.</p>
</section>

<section class="home-section publications-section">
  <h2>Preprints</h2>
  <article class="publication-row">
    <a class="publication-row__preview" href="{{ '/projects/gui-harvest/' | relative_url }}">
      <img src="{{ '/images/projects/gui-harvest/workflow.png' | relative_url }}" alt="GUI-HARVEST workflow">
    </a>
    <div class="publication-row__body">
      <h3><a href="{{ '/projects/gui-harvest/' | relative_url }}">GUI-HARVEST: Self-Improving GUI Agents through Evidence-Driven Harness Evolution</a></h3>
      <p class="publication-authors"><strong>Geyi Yang</strong>, Zikun Qu, Xiang Li, Zhiyong Wang, Min Zhang, Shipei Zeng, and Zhongxiang Dai</p>
      <p class="publication-venue"><em>Under review at ICLR 2027</em> · arXiv, 2026</p>
      <div class="publication-links">
        <a href="https://arxiv.org/abs/2610.00948v1">Paper</a>
        <a href="https://github.com/GaryYang12345/GUI-HARVEST">Code</a>
        <a href="{{ '/projects/gui-harvest/' | relative_url }}">Project Page</a>
      </div>
    </div>
  </article>
</section>

<section class="home-section publications-section">
  <h2>Selected Research</h2>
  <article class="publication-row publication-row--compact">
    <a class="publication-row__preview" href="{{ '/projects/meme-qwen/' | relative_url }}">
      <img src="{{ '/images/Meme-Qwen.png' | relative_url }}" alt="Meme-Qwen project preview">
    </a>
    <div class="publication-row__body">
      <h3><a href="{{ '/projects/meme-qwen/' | relative_url }}">Meme-Qwen-7B-Instruct</a></h3>
      <p>Built the full data-to-model pipeline for a Chinese internet-meme conversational model, including 30,000+ collected pairs, an 8,680-example open SFT dataset, and LoRA plus DPO training.</p>
      <div class="publication-links">
        <a href="https://huggingface.co/GaryYang123/Meme-Qwen-7B-Instruct">Model</a>
        <a href="https://huggingface.co/datasets/GaryYang123/zh-meme-sft-8k">Dataset</a>
        <a href="{{ '/projects/meme-qwen/' | relative_url }}">Project Page</a>
      </div>
    </div>
  </article>

  <article class="publication-row publication-row--compact">
    <a class="publication-row__preview" href="{{ '/projects/mcm-2026/' | relative_url }}">
      <img src="{{ '/images/MCM-flowchart.png' | relative_url }}" alt="MCM lunar logistics workflow">
    </a>
    <div class="publication-row__body">
      <h3><a href="{{ '/projects/mcm-2026/' | relative_url }}">Dynamic Hybrid Lunar Logistics Optimization</a></h3>
      <p>Led modeling and programming for an MCM 2026 Finalist team (top 1%), combining dynamic logistics simulation, Differential Evolution, Monte Carlo analysis, and sensitivity analysis.</p>
      <div class="publication-links">
        <a href="{{ '/files/Paper.pdf' | relative_url }}">Paper</a>
        <a href="{{ '/projects/mcm-2026/' | relative_url }}">Project Page</a>
      </div>
    </div>
  </article>
</section>

<section id="experience" class="home-section">
  <h2>Experience</h2>
  <div class="resume-list">
    <article class="resume-row">
      <img src="{{ '/images/bigdata.png' | relative_url }}" alt="Shenzhen Research Institute of Big Data logo" class="institution-logo institution-logo--sribd">
      <div><h3>Shenzhen Research Institute of Big Data</h3><p>Research Assistant · Advisor: <a href="https://daizhongxiang.github.io/index.html">Prof. Zhongxiang Dai</a></p><time>Jul. 2026 – Present</time></div>
    </article>
    <article class="resume-row">
      <img src="{{ '/images/cloud-computing-center.png' | relative_url }}" alt="Cloud Computing Center, Chinese Academy of Sciences logo" class="institution-logo">
      <div><h3>Cloud Computing Center, Chinese Academy of Sciences</h3><p>Domain-specific Agentic RAG for mining-blasting QA</p><time>Mar. 2025 – Jun. 2025</time></div>
    </article>
    <article class="resume-row">
      <img src="{{ '/images/logo-airs.png' | relative_url }}" alt="AIRS logo" class="institution-logo institution-logo--airs">
      <div><h3>Shenzhen Institute of Artificial Intelligence and Robotics for Society</h3><p>Multimodal digital human synthesis for emotional interaction</p><time>Sep. 2023 – Jun. 2024</time></div>
    </article>
  </div>
</section>

<section id="education" class="home-section">
  <h2>Education</h2>
  <div class="resume-list">
    <article class="resume-row">
      <img src="{{ '/images/cuhksz.png' | relative_url }}" alt="CUHK-Shenzhen logo" class="institution-logo">
      <div><h3>The Chinese University of Hong Kong, Shenzhen</h3><p>B.Eng. in Computer Engineering · GPA 3.73/4.00</p><time>Sep. 2023 – Present</time></div>
    </article>
    <article class="resume-row">
      <img src="{{ '/images/berkeley.svg' | relative_url }}" alt="UC Berkeley logo" class="institution-logo">
      <div><h3>University of California, Berkeley</h3><p>GLOBE Program Visiting Student in Computer Science</p><time>Jan. 2026 – Jun. 2026</time></div>
    </article>
  </div>
</section>

<section id="development" class="home-section">
  <h2>Development Projects</h2>
  <article class="publication-row publication-row--compact">
    <a class="publication-row__preview publication-row__preview--phones" href="{{ '/projects/voice-turing/' | relative_url }}">
      <img src="{{ '/images/turing2.png' | relative_url }}" alt="Voice Turing Test home screen">
      <img src="{{ '/images/turing4.png' | relative_url }}" alt="Voice Turing Test judgment screen">
      <img src="{{ '/images/turing5.png' | relative_url }}" alt="Voice Turing Test result screen">
    </a>
    <div class="publication-row__body">
      <h3><a href="{{ '/projects/voice-turing/' | relative_url }}">Voice Turing Test</a></h3>
      <p>A public WeChat Mini Program game and the data-collection platform for an ICLR 2026 study. I led product design and full-stack development; it reached 1,000+ users and collected 5,000+ valid records in its first month.</p>
      <p class="publication-venue">Full-stack development lead · 2025</p>
      <div class="publication-links">
        <a href="https://openreview.net/forum?id=Pv5l6cvfno">ICLR 2026 Paper</a>
        <a href="{{ '/projects/voice-turing/' | relative_url }}">Project Page</a>
      </div>
    </div>
  </article>

  <article class="publication-row publication-row--compact">
    <a class="publication-row__preview" href="{{ '/projects/telos/' | relative_url }}">
      <img src="{{ '/images/telos.png' | relative_url }}" alt="Telos learning workspace preview">
    </a>
    <div class="publication-row__body">
      <h3><a href="{{ '/projects/telos/' | relative_url }}">Telos: AI-Generated, Ready-to-Learn Courses</a></h3>
      <p>A goal-conditioned education product that turns fragmented sources into structured, multimodal, ready-to-learn courses.</p>
      <p class="publication-venue">Independent full-stack project · 2026 – Present</p>
      <div class="publication-links">
        <a href="https://github.com/GaryYang12345/Telos">Code</a>
        <a href="{{ '/projects/telos/' | relative_url }}">Project Page</a>
      </div>
    </div>
  </article>

  <article class="publication-row publication-row--compact">
    <a class="publication-row__preview" href="{{ '/projects/taskflow/' | relative_url }}">
      <img src="{{ '/images/taskflowai.png' | relative_url }}" alt="TaskFlow AI workspace preview">
    </a>
    <div class="publication-row__body">
      <h3><a href="{{ '/projects/taskflow/' | relative_url }}">TaskFlow AI: Visual Task Orchestration</a></h3>
      <p>A visual workspace for tasks, dependencies, deadlines, and human-in-the-loop agent workflows.</p>
      <p class="publication-venue">Independent full-stack project · 2026</p>
      <div class="publication-links">
        <a href="https://github.com/GaryYang12345/TaskFlowAI">Code</a>
        <a href="{{ '/projects/taskflow/' | relative_url }}">Project Page</a>
      </div>
    </div>
  </article>
</section>

<section id="awards" class="home-section simple-list">
  <h2>Selected Awards</h2>
  <ul>
    <li><span>COMAP Mathematical Contest in Modeling, Finalist (top 1%)</span><time>2026</time></li>
    <li><span>China International College Students' Innovation Competition, Bronze Award</span><time>2025</time></li>
    <li><span>Dean's List, CUHK-Shenzhen</span><time>2023–2026</time></li>
    <li><span>Academic Performance Scholarship, CUHK-Shenzhen</span><time>2023–2024</time></li>
  </ul>
</section>

<section id="services" class="home-section simple-list">
  <h2>Services</h2>
  <ul>
    <li><span>Teaching Assistant, MAT1001 Calculus I, CUHK-Shenzhen</span><time>2025</time></li>
  </ul>
</section>
