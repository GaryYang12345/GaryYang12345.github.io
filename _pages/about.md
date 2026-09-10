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
  <p>Hi, I am <strong>Geyi Yang</strong> (杨戈易), also known as <strong>Gary</strong>. I am an undergraduate researcher in Computer Engineering at <a href="https://www.cuhk.edu.cn/en">The Chinese University of Hong Kong, Shenzhen</a> (CUHK-Shenzhen), and was a GLOBE Program visiting student in Computer Science at <a href="https://www.berkeley.edu/">UC Berkeley</a> in Spring 2026.</p>
  <p>My research interests include <strong>GUI agents</strong>, <strong>self-improving agentic systems</strong>, <strong>harness optimization</strong>, and <strong>retrieval-augmented generation (RAG)</strong>. My current project, <a class="intro-jump" href="{{ '/projects/harnessgrad/' | relative_url }}"><strong>GUI-HarnessGrad</strong></a>, develops an automated, failure-driven algorithm that learns from execution feedback to improve the harness around a fixed GUI-agent model.</p>
  <p>I also enjoy turning technical ideas into usable systems. My work includes the <a class="intro-jump" href="{{ '/projects/voice-turing/' | relative_url }}"><strong>Voice Turing Test</strong></a>, a public WeChat game and ICLR 2026 research data platform, and <a class="intro-jump" href="{{ '/projects/telos/' | relative_url }}"><strong>Telos</strong></a>, a goal-driven product for converting fragmented resources into ready-to-learn courses. Beyond computing, I enjoy photography, piano, drawing, and hiking.</p>
  <p class="intro__actions">
    <a class="cv-download" href="{{ '/files/GeyiYang_CV.pdf' | relative_url }}">Download CV</a>
  </p>
</header>

<section id="research" class="project-section">
  <div class="section-kicker">Modeling, systems, and machine learning</div>
  <h2>Research Projects</h2>
  <div class="project-list">
    <article class="project-entry">
      <a class="project-card-link" href="{{ '/projects/harnessgrad/' | relative_url }}" aria-label="Open GUI-HarnessGrad details"></a>
      <div class="project-art">
        <img src="images/harnessgrad.png" alt="">
      </div>
      <div class="project-entry__body">
        <div class="project-entry__meta">GUI agents · Jul. 2026 – Present</div>
        <h3>GUI-HarnessGrad: Automated Harness Optimization for GUI Agents</h3>
        <p>Develops a failure-driven optimization algorithm for improving the inference-time harness around a fixed GUI-agent model. On OSWorld (361 tasks, 15-step budget), the optimized harness raised Qwen3-VL-32B-Instruct from 37.67% to 50.95% (+13.28 points).</p>
      </div>
    </article>

    <article class="project-entry">
      <a class="project-card-link" href="{{ '/projects/meme-qwen/' | relative_url }}" aria-label="Open Meme-Qwen details"></a>
      <div class="project-art">
        <img src="images/Meme-Qwen.png" alt="">
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
        <img src="images/MCM-flowchart.png" alt="">
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
      <img src="images/cloud-computing-center.png" alt="Cloud Computing Center, Chinese Academy of Sciences emblem" class="institution-logo institution-logo--round">
      <div class="experience-row__copy">
        <h3>Cloud Computing Center, Chinese Academy of Sciences</h3>
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

<section id="development" class="project-section">
  <div class="section-kicker">Products and platforms</div>
  <h2>Development Projects</h2>
  <div class="project-list">
    <article class="project-entry">
      <a class="project-card-link" href="{{ '/projects/voice-turing/' | relative_url }}" aria-label="Open Voice Turing Test details"></a>
      <div class="project-art">
        <img src="images/Turing-cover.png" alt="">
      </div>
      <div class="project-entry__body">
        <div class="project-entry__meta">Full-stack development lead · May 2025 – Aug. 2025</div>
        <h3>Voice Turing Test</h3>
        <p>A public WeChat Mini Program game for judging Human-vs-AI speech, with bilingual challenges, scoring, achievements, referrals, and leaderboards. I led the product's full-stack development; it also served as the data-collection platform for an ICLR 2026 paper.</p>
        <div class="project-actions">
          <a class="brand-link" href="https://openreview.net/forum?id=Pv5l6cvfno">ICLR 2026 paper</a>
        </div>
      </div>
    </article>

    <article class="project-entry">
      <a class="project-card-link" href="{{ '/projects/telos/' | relative_url }}" aria-label="Open Telos details"></a>
      <div class="project-art">
        <img src="images/telos.png" alt="">
      </div>
      <div class="project-entry__body">
        <div class="project-entry__meta">Independent full-stack developer · Aug. 2026 – Present</div>
        <h3>Telos: AI-Generated, Ready-to-Learn Courses</h3>
        <p>A goal-conditioned education product that retrieves, evaluates, deduplicates, and sequences user materials and cross-platform resources into a structured, multimodal course that is ready to learn inside one workspace.</p>
        <div class="project-actions">
          <a class="brand-link" href="https://github.com/GaryYang12345/Telos" aria-label="Open Telos on GitHub"><i class="fab fa-github" aria-hidden="true"></i>GitHub</a>
        </div>
      </div>
    </article>

    <article class="project-entry">
      <a class="project-card-link" href="{{ '/projects/taskflow/' | relative_url }}" aria-label="Open TaskFlow AI details"></a>
      <div class="project-art">
        <img src="images/taskflowai.png" alt="">
      </div>
      <div class="project-entry__body">
        <div class="project-entry__meta">Independent full-stack developer · Apr. 2026</div>
        <h3>TaskFlow AI: Visual Task Orchestration and Automation</h3>
        <p>A dual-level node-flow workspace for tasks, dependencies, statuses, deadlines, and serial/parallel/merge sub-workflows. Integrates OpenClaw and Lark to extract tasks from email and synchronize reports, tables, and calendars.</p>
        <div class="project-actions">
          <a class="brand-link" href="https://github.com/GaryYang12345/TaskFlowAI" aria-label="Open TaskFlow AI on GitHub"><i class="fab fa-github" aria-hidden="true"></i>GitHub</a>
        </div>
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
    <li><time>2025</time> Teaching Assistant, MAT1001 Calculus I, CUHK-Shenzhen.</li>
  </ul>
</section>
