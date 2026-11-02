---
permalink: /projects/stashdock/
title: "StashDock"
excerpt: "A local-first context library for collecting, organizing, and reusing references across AI conversations."
---

<article class="project-detail">
  <p class="section-kicker"><img class="product-inline-mark" src="{{ '/images/projects/stashdock/icon.svg' | relative_url }}" alt="">Independent product · Oct. 2026 – Present</p>
  <p class="paper-meta">Creator &amp; full-stack developer · Product design, UI/UX, engineering, and release</p>
  <div class="paper-actions">
    <a class="brand-link" href="https://stashdock.app"><i class="fas fa-globe" aria-hidden="true"></i>Website</a>
    <a class="brand-link" href="https://github.com/StashDock/StashDock"><i class="fab fa-github" aria-hidden="true"></i>GitHub</a>
    <a class="brand-link" href="https://stashdock.app/guide">Guide &amp; downloads</a>
    <a class="brand-link" href="{{ '/' | relative_url }}#products">Back to products</a>
  </div>

  <p class="article-deck">Useful context is scattered across browser bookmarks, local folders, saved posts, and old conversations. I built StashDock to keep those references together and make them easy to bring into the next AI conversation.</p>

  <figure class="article-hero">
    <img src="{{ '/images/projects/stashdock/website.jpg' | relative_url }}" alt="StashDock product website showing its context library and desktop and ChatGPT entry points" width="1800" height="997">
    <figcaption>A personal context library that works across AI conversations.</figcaption>
  </figure>

  <h2>From collecting references to using them</h2>
  <p>StashDock brings links, files, notes, prompts, and writing rules into a visual library with search, favorites, tags, and editable content. Users can import browser bookmarks, add local materials, or save the current page through the Chrome extension, including supported pages that require a logged-in browser session. Tags also serve as reusable context sets for recurring tasks.</p>

  <h2>At hand on the desktop, beside the conversation</h2>
  <p>The Windows and macOS desktop apps offer a floating folder, quick search, and a full library panel. References can be copied or dragged into an AI conversation. The ChatGPT plugin presents the same library in a sidebar, where users select references and add them directly to chat. Both surfaces share local storage, so users can choose either or use them together.</p>

  <figure class="article-hero">
    <img src="{{ '/images/projects/stashdock/desktop-workflow.gif' | relative_url }}" alt="Desktop demonstration of searching the floating folder, dragging a reference into AI, and opening the full library" loading="lazy">
    <figcaption>The floating folder keeps reference search and handoff within reach. Demo materials are sample references.</figcaption>
  </figure>
  <figure class="article-hero">
    <img src="{{ '/images/projects/stashdock/ai-sidebar.gif' | relative_url }}" alt="ChatGPT sidebar demonstration of selecting references and adding them to the conversation" loading="lazy">
    <figcaption>The ChatGPT sidebar connects the collection to the conversation. Demo materials are sample references.</figcaption>
  </figure>

  <h2>A library AI can work with</h2>
  <p>MCP tools and an accompanying skill allow AI to search for relevant references, help organize tags, and save useful prompts or rules from the current conversation for later reuse. The product supports both directions: bringing saved context into a task and preserving useful context that emerges from it. The library stays on the user's device, and users choose what to share with AI.</p>

  <h2>What I built</h2>
  <p>I owned the product concept, interaction and visual design, full-stack implementation, integration across desktop, browser, and AI surfaces, release packaging, and the public website and guide. The implementation combines React and TypeScript interfaces, a Tauri/Rust desktop app, SQLite storage, a Chrome extension, and an MCP app and tool layer.</p>
  <p>The product is open source and available for Windows and macOS, with a Chrome extension and ChatGPT plugin. The <a href="https://stashdock.app">product website</a> includes interactive previews, installation guidance, and downloads.</p>
  <!-- Add verified adoption, community response, and launch milestones when available. -->
</article>
