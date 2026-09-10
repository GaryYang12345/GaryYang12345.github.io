---
permalink: /projects/telos/
title: "Telos"
author_profile: true
comments: false
share: false
related: false
read_time: false
stylesheets:
  - /assets/css/home.css
---

<article class="project-detail">
  <p class="section-kicker">Independent full-stack project · Aug. 2026 – Present</p>
  <p class="paper-meta">Goal-conditioned, ready-to-learn course generation</p>
  <div class="paper-actions">
    <a class="brand-link" href="https://github.com/GaryYang12345/Telos"><i class="fab fa-github" aria-hidden="true"></i>GitHub</a>
    <a class="brand-link" href="{{ '/' | relative_url }}#development">Back to projects</a>
  </div>

  <p class="article-deck">Telos explores a different role for AI in education: not another answer box or reading-list generator, but a teaching-design system that turns a learning goal and fragmented sources into a course that can be opened and studied immediately.</p>

  <figure class="article-hero">
    <img src="{{ '/images/projects/telos/landing.webp' | relative_url }}" alt="Telos landing page with a generated course preview">
    <figcaption>The product promise is a finished learning workspace rather than a collection of links.</figcaption>
  </figure>

  <h2>From information to a learning deliverable</h2>
  <p>Users may begin with a question, saved posts, papers, webpages, or videos. Telos retrieves additional sources, removes overlap, evaluates quality, and sequences the useful material into chapters. Text, figures, code, and video stay inside the resulting course so the learner does not have to keep switching platforms.</p>

  <div class="project-facts" aria-label="Telos pipeline">
    <div><span>Input</span><strong>Goal + trusted sources</strong></div>
    <div><span>Pipeline</span><strong>Retrieve, rank, organize</strong></div>
    <div><span>Output</span><strong>Multimodal course</strong></div>
  </div>

  <h2>Goal-conditioned teaching</h2>
  <p>The same topic should look different for broad exploration, conceptual mastery, interview preparation, or academic research. A goal-configuration layer controls depth, prerequisites, emphasis, examples, and assessment before generation begins.</p>

  <div class="article-gallery article-gallery--wide">
    <figure>
      <img src="{{ '/images/projects/telos/create-task.webp' | relative_url }}" alt="Telos task form for learning goals and preferred sources">
      <figcaption>A task begins with the problem, learning objective, desired depth, and source preferences.</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/projects/telos/workspace.webp' | relative_url }}" alt="Telos learning workspace with generated courses">
      <figcaption>The workspace tracks course generation and completed learning units.</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/projects/telos/course-reader.webp' | relative_url }}" alt="Telos course reader with chapters, code, and local navigation">
      <figcaption>The reader combines chapter navigation, explanations, examples, and embedded media.</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/projects/telos/embedded-video.webp' | relative_url }}" alt="Video embedded inside a Telos course chapter">
      <figcaption>Useful external media is placed at the point where it supports the lesson.</figcaption>
    </figure>
  </div>

  <h2>Current status</h2>
  <p>The end-to-end prototype covers task creation, source ingestion, retrieval, course generation, and a structured learning reader. Editing, tutoring, exercises, flashcards, and broader source connectors remain under active development.</p>
</article>
