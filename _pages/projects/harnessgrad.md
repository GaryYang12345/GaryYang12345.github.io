---
permalink: /projects/harnessgrad/
title: "GUI-HarnessGrad"
author_profile: true
comments: false
share: false
related: false
read_time: false
stylesheets:
  - /assets/css/home.css
---

<div class="project-detail">
  <p class="section-kicker">GUI agents · Work in progress · Targeting ICLR 2027</p>
  <p class="paper-meta">Research Assistant at CUHK-Shenzhen · advised by Prof. Zhongxiang Dai</p>
  <div class="paper-actions">
    <a class="brand-link" href="https://osworld-v1.xlang.ai/#benchmark">OSWorld leaderboard</a>
    <a class="brand-link" href="{{ '/' | relative_url }}#research">Back</a>
  </div>

  <h2>Research question</h2>
  <p>GUI-agent performance depends not only on the underlying model, but also on the harness that surrounds it: prompts, action interfaces, execution feedback, termination rules, recovery logic, and other control components. GUI-HarnessGrad asks whether this harness can be improved automatically from rollout failures while the underlying model remains fixed.</p>

  <h2>Method</h2>
  <p>GUI-HarnessGrad is a failure-driven harness optimization algorithm, not a proposal for one manually engineered harness. The system collects trajectories, screenshots, execution feedback, and rewards; identifies recurring failure modes; attributes them to editable harness components; proposes candidate changes; and uses paired retesting with retain-or-rollback decisions to preserve only validated updates. The broader goal is to learn which harness configuration best supports a given model under explicit accuracy, step, latency, and cost budgets.</p>

  <h2>Current result</h2>
  <p class="result-callout">On the 361-task OSWorld evaluation with a 15-step budget, the final optimized harness improved a fixed Qwen3-VL-32B-Instruct agent from <strong>37.67%</strong> to <strong>50.95%</strong>: a gain of 13.28 percentage points, or 35.2% relative. This score is higher than reported OSWorld leaderboard results for Claude 4 Sonnet, o3, and several specialized GUI-agent models, even though many listed systems use larger step budgets.</p>

  <h2>Status and scope</h2>
  <p>The experiments and paper are ongoing, with a submission to ICLR 2027 planned. The current score is evidence that the optimization procedure can discover a substantially stronger harness; the research contribution is the optimization algorithm and its evaluation methodology, rather than the final harness as a fixed artifact. Additional models, repeated runs, ablations, and transfer experiments remain in progress.</p>
</div>
