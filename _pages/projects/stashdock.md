---
permalink: /projects/stashdock/
title: "StashDock"
excerpt: "An AI-native personal context library for any AI, with a visual panel that keeps references within reach of the conversation."
---

<article class="project-detail">
  <p class="section-kicker"><img class="product-inline-mark" src="{{ '/images/projects/stashdock/icon.svg' | relative_url }}" alt="">Independent product · Oct. 2026 – Present</p>
  <p class="paper-meta">A Personal Context Library for Any AI · Creator &amp; full-stack developer</p>
  <div class="paper-actions">
    <a class="brand-link" href="https://stashdock.app"><i class="fas fa-globe" aria-hidden="true"></i>Website</a>
    <a class="brand-link" href="https://github.com/StashDock/StashDock"><i class="fab fa-github" aria-hidden="true"></i>GitHub</a>
    <a class="brand-link" href="https://stashdock.app/guide">Guide &amp; downloads</a>
    <a class="brand-link" href="{{ '/' | relative_url }}#products">Back to products</a>
  </div>

  <p class="article-deck">StashDock is an AI-native personal context library for any AI. I built it around a visual panel that keeps a user's links, files, prompts, and rules together and within reach, ready to bring into a conversation with a selection, copy, or drag.</p>

  <figure class="article-hero">
    <img src="{{ '/images/projects/stashdock/website.jpg' | relative_url }}" alt="StashDock product website showing its context library and desktop and ChatGPT entry points" width="1800" height="997">
    <figcaption>One personal context library to use across conversations and AI apps.</figcaption>
  </figure>

  <h2>A visual panel for personal context</h2>
  <p>Useful references accumulate in bookmarks, folders, and old chats. Preparing each new AI conversation means finding and assembling them again. StashDock presents those materials as cover cards in a personal library, with search, favorites, tags, and editable content. Users can browse and recognize their references, choose what to share, or reuse a tagged set for a recurring task.</p>
  <p>Browser bookmark import, local files and notes, and a Chrome extension make it easy to build the collection. The extension captures the page being read, including supported posts that require a logged-in browser session.</p>

  <h2>At hand on the desktop, beside the conversation</h2>
  <p>The interaction is designed to keep finding and using context close to the task. On Windows and macOS, a floating folder stays within reach: hover to search, copy or drag a reference into any AI app, or open the full library panel. In ChatGPT, the same library opens beside the conversation; users select references and add them directly to chat. Both share one library on the user's computer.</p>

  <figure class="article-hero">
    <img src="{{ '/images/projects/stashdock/desktop-workflow.gif' | relative_url }}" alt="Desktop demonstration of searching the floating folder, dragging a reference into AI, and opening the full library" loading="lazy">
    <figcaption>Hover to search, then copy or drag a reference into the AI app in use. Demo materials are sample references.</figcaption>
  </figure>
  <figure class="article-hero">
    <img src="{{ '/images/projects/stashdock/ai-sidebar.gif' | relative_url }}" alt="ChatGPT sidebar demonstration of selecting references and adding them to the conversation" loading="lazy">
    <figcaption>Browse the visual library beside the conversation and add selected references directly. Demo materials are sample references.</figcaption>
  </figure>

  <h2>AI-native, for both people and agents</h2>
  <p>Users can work with their collection through the visual panel, while MCP tools and Skills let AI help find relevant references, organize tags, and save useful context from the current task. A prompt or writing rule developed in one conversation can be kept for another conversation or another AI. The collection remains personal and locally stored, and users control what they share.</p>

  <h2>What I built</h2>
  <p>I independently led product design, UI/UX, full-stack development, and open-source release. React/TypeScript powers the visual interfaces; Tauri/Rust and SQLite support the Windows/macOS desktop apps and local library. I also built the Chrome collection extension, ChatGPT sidebar, MCP tools and Skills, and the public website and guide.</p>
  <p>The <a href="https://stashdock.app">product website</a> includes interactive previews, installation guidance, and downloads.</p>
  <!-- Add verified adoption, community response, and launch milestones when available. -->
</article>
