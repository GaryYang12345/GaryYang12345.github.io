---
permalink: /projects/taskflow/
title: "TaskFlow AI"
author_profile: true
comments: false
share: false
related: false
read_time: false
stylesheets:
  - /assets/css/home.css
---

<article class="project-detail">
  <p class="section-kicker">Independent full-stack project · Apr. 2026</p>
  <p class="paper-meta">Visual task orchestration with human-in-the-loop automation</p>
  <div class="paper-actions">
    <a class="brand-link" href="https://github.com/GaryYang12345/TaskFlowAI"><i class="fab fa-github" aria-hidden="true"></i>GitHub</a>
    <a class="brand-link" href="{{ '/' | relative_url }}#development">Back to projects</a>
  </div>

  <p class="article-deck">TaskFlow AI turns personal work into a visual system of tasks, dependencies, deadlines, and executable sub-workflows. It combines a node-based workspace with an orchestration boundary for OpenClaw and Lark.</p>

  <figure class="article-hero">
    <img src="{{ '/images/projects/taskflow/dashboard.webp' | relative_url }}" alt="TaskFlow AI dashboard showing tasks connected across workflow stages">
    <figcaption>The main canvas connects tasks to a status pipeline while keeping task context visible in a side panel.</figcaption>
  </figure>

  <div class="project-facts" aria-label="Project overview">
    <div><span>Interface</span><strong>Nested node flows</strong></div>
    <div><span>Backend</span><strong>FastAPI + SQLite</strong></div>
    <div><span>Agent layer</span><strong>OpenClaw + Lark</strong></div>
  </div>

  <h2>Why I built it</h2>
  <p>Conventional task lists flatten complex work into isolated rows. TaskFlow uses two levels of graphs: a personal canvas for major tasks, and an internal workflow for the serial, parallel, or merged steps inside each task. Status, deadlines, details, and completion rules remain attached to the graph.</p>

  <h2>Human control, agent assistance</h2>
  <p>OpenClaw acts as the orchestration layer: it can extract a candidate task from email or chat, propose structured details through Lark, and advance work when a user confirms the action or when evidence satisfies an explicit rule. TaskFlow remains the deterministic system of record instead of pretending that the product itself reads private accounts.</p>

  <div class="article-gallery article-gallery--wide">
    <figure>
      <img src="{{ '/images/projects/taskflow/workflow.webp' | relative_url }}" alt="Internal TaskFlow workflow with serial and parallel sub-nodes">
      <figcaption>Each task can expand into an editable internal workflow.</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/projects/taskflow/analytics.webp' | relative_url }}" alt="TaskFlow analytics page with completion and risk summaries">
      <figcaption>Analytics surfaces workload, completion, and deadline risk.</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/projects/taskflow/calendar.webp' | relative_url }}" alt="TaskFlow deadline calendar">
      <figcaption>A calendar view keeps scheduled and overdue work in context.</figcaption>
    </figure>
  </div>
</article>
