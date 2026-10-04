---
permalink: /projects/gui-harvest/
title: "GUI-HARVEST"
redirect_from:
  - /projects/harnessgrad/
---

<article class="project-detail">
  <p class="section-kicker">Self-improving GUI agents · Under review at ICLR 2027 · arXiv preprint</p>
  <p class="publication-authors"><strong>Geyi Yang</strong>, Zikun Qu, Xiang Li, Zhiyong Wang, Min Zhang, Shipei Zeng, and Zhongxiang Dai</p>
  <p class="paper-meta">First author · Research Assistant at Shenzhen Research Institute of Big Data · advised by Prof. Zhongxiang Dai</p>
  <div class="paper-actions">
    <a class="brand-link" href="https://arxiv.org/abs/2610.00948v1">arXiv paper</a>
    <a class="brand-link" href="https://github.com/GaryYang12345/GUI-HARVEST"><i class="fab fa-github" aria-hidden="true"></i>Code</a>
    <a class="brand-link" href="{{ '/' | relative_url }}#research">Back to projects</a>
  </div>

  <p class="article-deck">GUI-HARVEST enables a frozen GUI agent to improve its own executable runtime harness from repeated multimodal executions, without updating the backbone model’s weights.</p>

  <figure class="article-hero">
    <img src="{{ '/images/projects/gui-harvest/workflow.png' | relative_url }}" alt="GUI-HARVEST evidence-driven self-improvement loop for frozen GUI agents">
    <figcaption>Repeated GUI executions support evidence analysis, cross-task failure clustering, bounded harness edits, and score-plus-behavior validation before an update is promoted.</figcaption>
  </figure>

  <div class="metric-strip" aria-label="GUI-HARVEST results">
    <div><strong>6</strong><span>backbones improved</span></div>
    <div><strong>+12.33</strong><span>Qwen full-suite points</span></div>
    <div><strong>+13.87</strong><span>GPT-5 transfer points</span></div>
  </div>

  <h2>Why GUI harness evolution is different</h2>
  <p>A GUI harness controls how observations are assembled, actions are executed, and verification, recovery, and termination are handled. Optimizing it requires more than reading textual traces: the system must reconcile model intent with visible interface changes, diagnose failures despite run-to-run execution variability, and turn task-local evidence into reusable runtime changes.</p>

  <h2>Evidence-driven self-improvement</h2>
  <p>GUI-HARVEST aligns model outputs and executed actions with before-and-after screenshots, then compares repeated runs of each task as a joint evidence unit. Verified findings are consolidated into recurring cross-task failure patterns. A Harness Engineer maps those patterns to bounded source-code edits and records predicted behavioral effects before evaluation; a Validator promotes an edit only when repeated executions pass both score and behavior checks.</p>

  <h2>Results and transfer</h2>
  <p>On OSWorld-Verified, GUI-HARVEST produces consistent held-out gains across six general-purpose open, GUI-specialized open, and proprietary backbones. With Qwen3-VL-32B-Instruct at a 15-step budget, the full-suite score rises from 38.61% to 50.94% (+12.33 points). The frozen OSWorld-derived harness also transfers to WindowsAgentArena without further optimization, improving GPT-5 from 50.88% to 64.75% (+13.87 points) at 50 steps.</p>

  <p class="result-callout">The contribution is not a single hand-designed harness. It is an evidence-driven optimization procedure that lets frozen GUI agents convert their own repeated executions into validated, reusable runtime improvements.</p>
</article>
