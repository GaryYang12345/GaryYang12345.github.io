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
  <p>Hi, my name is <strong>Geyi Yang</strong> (杨戈易). I am an undergraduate student in Computer Engineering at <a href="https://www.cuhk.edu.cn/en">The Chinese University of Hong Kong, Shenzhen</a> (CUHK-Shenzhen). In Spring 2026, I was a GLOBE Program visiting student in Computer Science at <a href="https://www.berkeley.edu/">UC Berkeley</a>.</p>
  <p>My research interests focus on <strong>Agents and LLMs</strong>, especially <strong>self-improving agent systems</strong>: agents that inspect their own traces, diagnose failure modes, and revise their harness, tools, or policies without retraining the underlying model. My current work on HarnessGrad, inference-time optimization of GUI-agent harnesses, is one instance of this self-evolution loop. I also work on retrieval-augmented generation and full-stack AI products.</p>
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
        <p>Undergraduate Research Assistant · advised by <a href="https://daizhongxiang.github.io/index.html">Prof. Zhongxiang Dai</a></p>
        <time>Jul. 2026 – Present</time>
      </div>
    </article>
    <article class="experience-row">
      <span class="experience-marker" aria-hidden="true"></span>
      <img src="images/cloud-computing-center.png" alt="Cloud Computing Center, China Academy of Sciences emblem" class="institution-logo institution-logo--round">
      <div class="experience-row__copy">
        <h3>Cloud Computing Center, China Academy of Sciences</h3>
        <p>Research Intern · Agentic-RAG Question-Answering for Smart Mining</p>
        <time>Mar. 2025 – Jun. 2025</time>
      </div>
    </article>
    <article class="experience-row">
      <span class="experience-marker" aria-hidden="true"></span>
      <img src="images/logo-airs.png" alt="AIRS logo" class="institution-logo institution-logo--airs">
      <div class="experience-row__copy">
        <h3>Shenzhen Institute of Artificial Intelligence and Robotics for Society</h3>
        <p>Research Intern · Digital Human Synthesis from Image and Speech</p>
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
      <a class="project-art" href="https://github.com/GaryYang12345/HarnessGrad">
        <img src="images/harnessgrad.png" alt="HarnessGrad preview">
      </a>
      <div class="project-entry__body">
        <div class="project-entry__meta">Self-improving agents · Jul. 2026 – Present</div>
        <h3>HarnessGrad: Adaptive Harness Optimization for GUI Agents</h3>
        <p>Built a recursive self-improving loop for GUI-agent harnesses: collect traces, cluster failures, attribute them to editable harness components, and retain or roll back updates. This is a self-evolution system at the harness level, without changing the underlying models. On OSWorld, improved the optimization-set score from 0.267 to 0.454 (+70%).</p>
        <div class="project-actions">
          <a class="brand-link" href="https://github.com/GaryYang12345/HarnessGrad" aria-label="Open HarnessGrad on GitHub">
            <i class="fab fa-github" aria-hidden="true"></i>GitHub
          </a>
        </div>
      </div>
    </article>

    <article class="project-entry">
      <a class="project-art" href="https://huggingface.co/GaryYang123/Meme-Qwen-7B-Instruct">
        <img src="images/meme-lm.png" alt="Meme Language Model preview">
      </a>
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
      <a class="project-art" href="{{ '/files/Paper.pdf' | relative_url }}">
        <img src="images/mcm.png" alt="MCM 2026 lunar logistics paper preview">
      </a>
      <div class="project-entry__body">
        <div class="project-entry__meta">MCM 2026 · Modeling and programming lead</div>
        <h3>Dynamic Hybrid Lunar Logistics Optimization</h3>
        <p>Developed an Earth-to-Moon logistics model integrating space elevators, reusable rockets, and ISRU maturation. Used Differential Evolution (1,301 evaluations), 5,000-run Monte Carlo robustness analysis, and sensitivity analysis to derive a three-phase transition strategy.</p>
        <div class="project-facts" aria-label="MCM project recognition">
          <span>Finalist · top 1%</span>
        </div>
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
      <a class="project-art" href="https://github.com/GaryYang12345/Telos">
        <img src="images/telos.png" alt="Telos preview">
      </a>
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
      <div class="project-art">
        <img src="images/taskflow.png" alt="TaskFlow AI preview">
      </div>
      <div class="project-entry__body">
        <div class="project-entry__meta">Independent full-stack developer · Apr. 2026</div>
        <h3>TaskFlow AI: Visual Task Orchestration and Automation</h3>
        <p>A dual-level node-flow workspace for tasks, dependencies, statuses, deadlines, and serial/parallel/merge sub-workflows. Integrates OpenClaw and Lark to extract tasks from email and synchronize reports, tables, and calendars.</p>
      </div>
    </article>

    <article class="project-entry">
      <div class="project-art">
        <img src="images/voice-turing.png" alt="Voice Turing Test preview">
      </div>
      <div class="project-entry__body">
        <div class="project-entry__meta">Full-stack development lead · May 2025 – Aug. 2025</div>
        <h3>Voice Turing Test Data Collection Platform</h3>
        <p>Led full-stack development of a WeChat Mini Program supporting research published at ICLR 2026. Built experiment flow, bilingual UI, real-time scoring, audio preloading, and caching; reached 1,000+ users, 300+ DAU, and 5,000+ valid records in its first month.</p>
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
