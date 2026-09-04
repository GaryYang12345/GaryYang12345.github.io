---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from: 
  - /about/
  - /about.html
---

<header class="intro">
  <p>Hi, my name is <strong>Geyi Yang</strong> (杨戈易), also known as <strong>Gary</strong>. I am an undergraduate student in Computer Engineering at <a href="https://www.cuhk.edu.cn/en">The Chinese University of Hong Kong, Shenzhen</a> (CUHK-Shenzhen). In Spring 2026, I was a GLOBE Program visiting student in Computer Science at <a href="https://www.berkeley.edu/">UC Berkeley</a>.</p>
  <p>My research interests lie in <strong>Agents</strong> and <strong>Large Language Models</strong>, with a growing focus on <strong>recursive self-improvement (RSI)</strong> for agentic systems. I am interested in how agents can learn from execution feedback, diagnose recurring failures, and improve through iterative adaptation. My recent research project, <strong>HarnessGrad</strong>, is an iterative system for GUI-agent harness optimization that identifies a harness framework best suited to a given model. I also have experience in <strong>retrieval-augmented generation (RAG)</strong>, <strong>LLM post-training</strong>, and <strong>dataset construction</strong>.</p>
  <p>Beyond research, I was the modeling and programming lead for a team in the <strong>Mathematical Contest in Modeling (MCM) 2026</strong>, receiving the <strong>Finalist (F Award, top 1%)</strong> distinction. I have also served as an <strong>Undergraduate Student Teaching Fellow</strong> for Calculus I at CUHK-Shenzhen. Outside work, I enjoy <strong>photography</strong>, <strong>piano</strong>, <strong>drawing</strong>, and <strong>hiking</strong>.</p>
  <p class="intro__actions">
    <a class="cv-download" href="{{ '/files/GeyiYang_CV.pdf' | relative_url }}">Download CV</a>
  </p>
</header>

<section id="education" class="resume-section">
  <div class="section-kicker">Academic background</div>
  <h2>Education</h2>
  <div class="education-list">
    <article class="education-row">
      <img src="images/cuhksz.png" alt="CUHK-Shenzhen emblem" class="institution-logo institution-logo--cuhk">
      <div class="education-row__copy">
        <h3>The Chinese University of Hong Kong, Shenzhen</h3>
        <p>B.Eng. in Computer Engineering · GPA 3.73/4.00</p>
        <time>Sep. 2023 – Present</time>
      </div>
    </article>
    <article class="education-row">
      <img src="images/berkeley.svg" alt="UC Berkeley emblem" class="institution-logo institution-logo--berkeley">
      <div class="education-row__copy">
        <h3>University of California, Berkeley</h3>
        <p>GLOBE Program Visiting Student in Computer Science</p>
        <time>Jan. 2026 – Jun. 2026</time>
      </div>
    </article>
  </div>
</section>

<section id="experience" class="resume-section">
  <div class="section-kicker">Research and internships</div>
  <h2>Experience</h2>
  <div class="experience-timeline">
    <article class="experience-row">
      <span class="experience-marker" aria-hidden="true"></span>
      <img src="images/cuhksz.png" alt="CUHK-Shenzhen emblem" class="institution-logo institution-logo--cuhk">
      <div class="experience-row__copy">
        <h3>The Chinese University of Hong Kong, Shenzhen</h3>
        <p>Research Assistant · advised by <a href="https://daizhongxiang.github.io/index.html">Prof. Zhongxiang Dai</a></p>
        <time>Jul. 2026 – Present</time>
      </div>
    </article>
    <article class="experience-row">
      <span class="experience-marker" aria-hidden="true"></span>
      <img src="images/cloud-computing-center.png" alt="Cloud Computing Center, China Academy of Sciences emblem" class="institution-logo institution-logo--round">
      <div class="experience-row__copy">
        <h3>Cloud Computing Center, China Academy of Sciences</h3>
        <p>Research Intern · Agentic-RAG chatbot for smart mining</p>
        <time>Mar. 2025 – Jun. 2025</time>
      </div>
    </article>
    <article class="experience-row">
      <span class="experience-marker" aria-hidden="true"></span>
      <img src="images/logo-airs.png" alt="AIRS logo" class="institution-logo institution-logo--airs">
      <div class="experience-row__copy">
        <h3>Shenzhen Institute of Artificial Intelligence and Robotics for Society</h3>
        <p>Research Intern · Digital human reconstruction</p>
        <time>Sep. 2023 – Jun. 2024</time>
      </div>
    </article>
  </div>
</section>

<section id="research" class="project-section">
  <div class="section-kicker">Modeling, systems, and machine learning</div>
  <h2>Research Projects</h2>
  <div class="project-list">
    <article class="project-entry">
      <a class="project-card-link" href="{{ '/projects/harnessgrad/' | relative_url }}" aria-label="Open HarnessGrad details"></a>
      <div class="project-art">
        <img src="images/harnessgrad.png" alt="">
      </div>
      <div class="project-entry__body">
        <div class="project-entry__meta">GUI agents · Jul. 2026 – Present</div>
        <h3>HarnessGrad: Adaptive Harness Optimization for GUI Agents</h3>
        <p>Used a stronger model as a meta-controller to optimize GUI-agent harnesses at inference time: read traces, cluster failures, attribute them to editable harness components, and retain or roll back updates. On OSWorld, improved the optimization-set score from 0.267 to 0.454 (+70%).</p>
        <div class="project-actions">
          <a class="brand-link" href="https://github.com/GaryYang12345/HarnessGrad" aria-label="Open HarnessGrad on GitHub">
            <i class="fab fa-github" aria-hidden="true"></i>GitHub
          </a>
        </div>
      </div>
    </article>

    <article class="project-entry">
      <a class="project-card-link" href="{{ '/projects/meme-qwen/' | relative_url }}" aria-label="Open Meme-Qwen details"></a>
      <div class="project-art">
        <img src="images/meme-lm.png" alt="">
      </div>
      <div class="project-entry__body">
        <div class="project-entry__meta">Language modeling · Jan. 2026</div>
        <h3>Meme-Qwen-7B-Instruct</h3>
        <p>Independently built the full data-to-model pipeline: 30,000+ post-comment pairs, an 8,680-example Chinese meme SFT dataset, and Qwen2.5-7B LoRA + DPO training on one A100. Meme-use accuracy improved by 32%.</p>
        <div class="project-actions">
          <a class="brand-link brand-link--hf" href="https://huggingface.co/GaryYang123/Meme-Qwen-7B-Instruct" aria-label="Open Meme-Qwen model on Hugging Face">
            <img src="images/hf-logo.png" alt="">Model
          </a>
          <a class="brand-link brand-link--hf" href="https://huggingface.co/datasets/GaryYang123/zh-meme-sft-8k" aria-label="Open meme dataset on Hugging Face">
            <img src="images/hf-logo.png" alt="">Dataset
          </a>
        </div>
      </div>
    </article>

    <article class="project-entry">
      <a class="project-card-link" href="{{ '/projects/mcm-2026/' | relative_url }}" aria-label="Open MCM 2026 details"></a>
      <div class="project-art">
        <img src="images/mcm.png" alt="">
      </div>
      <div class="project-entry__body">
        <div class="project-entry__meta">MCM 2026 · Modeling and programming lead</div>
        <h3>Dynamic Hybrid Lunar Logistics Optimization <span class="title-tag">Finalist</span></h3>
        <p>Developed an Earth-to-Moon logistics model integrating space elevators, reusable rockets, and ISRU maturation. Used Differential Evolution (1,301 evaluations), 5,000-run Monte Carlo robustness analysis, and sensitivity analysis to derive a three-phase transition strategy.</p>
        <div class="project-actions">
          <a class="brand-link" href="{{ '/files/Paper.pdf' | relative_url }}">Paper</a>
        </div>
      </div>
    </article>
  </div>
</section>

<section id="development" class="project-section">
  <div class="section-kicker">Products and platforms</div>
  <h2>Development Projects</h2>
  <div class="project-list">
    <article class="project-entry">
      <a class="project-card-link" href="{{ '/projects/telos/' | relative_url }}" aria-label="Open Telos details"></a>
      <div class="project-art">
        <img src="images/telos.png" alt="">
      </div>
      <div class="project-entry__body">
        <div class="project-entry__meta">Independent full-stack developer · Aug. 2026 – Present</div>
        <h3>Telos: AI-Generated, Ready-to-Learn Courses</h3>
        <p>A goal-driven course-generation system that turns fragmented materials and online resources into structured, multimodal, ready-to-learn courses, with a workspace for text, media, tutoring, and retrieval.</p>
        <div class="project-actions">
          <a class="brand-link" href="https://github.com/GaryYang12345/Telos" aria-label="Open Telos on GitHub">
            <i class="fab fa-github" aria-hidden="true"></i>GitHub
          </a>
        </div>
      </div>
    </article>

    <article class="project-entry">
      <a class="project-card-link" href="{{ '/projects/taskflow/' | relative_url }}" aria-label="Open TaskFlow AI details"></a>
      <div class="project-art">
        <img src="images/taskflow.png" alt="">
      </div>
      <div class="project-entry__body">
        <div class="project-entry__meta">Independent full-stack developer · Apr. 2026</div>
        <h3>TaskFlow AI: Visual Task Orchestration and Automation</h3>
        <p>A dual-level node-flow workspace for tasks, dependencies, statuses, deadlines, and serial/parallel/merge sub-workflows. Integrates OpenClaw and Lark to extract tasks from email and synchronize reports, tables, and calendars.</p>
      </div>
    </article>

    <article class="project-entry">
      <a class="project-card-link" href="{{ '/projects/voice-turing/' | relative_url }}" aria-label="Open Voice Turing Test details"></a>
      <div class="project-art">
        <img src="images/voice-turing.png" alt="">
      </div>
      <div class="project-entry__body">
        <div class="project-entry__meta">Full-stack development lead · May 2025 – Aug. 2025</div>
        <h3>Voice Turing Test</h3>
        <p>A WeChat Mini Program game in which players listen to multi-speaker conversations and decide who is human and who is AI. Built as a product first, with scoring, combos, bilingual UI, and gamified retention; the same platform also collected data for an ICLR 2026 paper.</p>
      </div>
    </article>
  </div>
</section>

<section id="awards" class="compact-section">
  <div class="section-kicker">Recognition</div>
  <h2>Awards</h2>
  <ul>
    <li><time>2026</time> Mathematical Contest in Modeling (MCM), Finalist (top 1%).</li>
    <li><time>2025</time> China International College Students’ Innovation Competition (CICSIC), Bronze Award.</li>
    <li><time>2023–2026</time> Dean’s List, CUHK-Shenzhen.</li>
    <li><time>2023–2024</time> Academic Performance Scholarship Awardee, CUHK-Shenzhen.</li>
  </ul>
</section>

<section id="services" class="compact-section">
  <div class="section-kicker">Teaching</div>
  <h2>Services</h2>
  <ul>
    <li><time>2025</time> Undergraduate Student Teaching Fellow (USTF), MAT1001 Calculus I, CUHK-Shenzhen.</li>
  </ul>
</section>
