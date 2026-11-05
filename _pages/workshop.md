---
layout: archive
title: "Workshops"
permalink: /workshop/
author_profile: true
---

<style>
  .workshop-page {
    --workshop-accent: #287a96;
    --workshop-border: #e5e9ed;
    --workshop-muted: #687580;
  }

  .workshop-page .workshop-list {
    display: grid;
    gap: 18px;
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .workshop-page .workshop-card {
    margin: 0;
    padding: 20px 24px;
    border: 1px solid var(--workshop-border);
    border-left: 3px solid var(--workshop-accent);
    border-radius: 8px;
    background: #fff;
  }

  .workshop-meta {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 8px 12px;
    margin-bottom: 10px;
    color: var(--workshop-muted);
    font-size: 0.85em;
  }

  .workshop-meta strong {
    color: var(--workshop-accent);
  }

  .workshop-badge {
    display: inline-block;
    padding: 2px 9px;
    border-radius: 4px;
    background: #eaf5ef;
    color: #347354;
    font-size: 0.85em;
    font-weight: 600;
  }

  .workshop-page .workshop-title {
    margin: 0 0 12px;
    font-size: 1.08em;
    line-height: 1.5;
  }

  .workshop-page .workshop-title a {
    color: #263746;
    text-decoration: none;
    overflow-wrap: anywhere;
  }

  .workshop-page .workshop-title a:hover,
  .workshop-page .workshop-title a:focus-visible {
    color: var(--workshop-accent);
    text-decoration: underline;
  }

  .workshop-organizers {
    margin: 0 0 14px;
    color: #4a5560;
    font-size: 0.92em;
    line-height: 1.75;
  }

  .workshop-label {
    color: var(--workshop-muted);
  }

  .workshop-organizers strong {
    color: #263746;
  }

  .workshop-footer {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 8px 18px;
    color: var(--workshop-muted);
    font-size: 0.85em;
  }

  .workshop-page .workshop-report {
    display: inline-block;
    padding: 3px 11px;
    border: 1px solid #d5e7ee;
    border-radius: 5px;
    background: #f2f8fa;
    color: var(--workshop-accent);
    font-weight: 600;
    text-decoration: none;
  }

  .workshop-page .workshop-report:hover,
  .workshop-page .workshop-report:focus-visible {
    background: #e2f0f5;
    text-decoration: underline;
  }

  .workshop-page .workshop-invitation {
    margin: 16px 0 0;
    padding-top: 14px;
    border-top: 1px solid var(--workshop-border);
    color: #4a5560;
    font-size: 0.92em;
    line-height: 1.75;
  }

  @media (max-width: 600px) {
    .workshop-page .workshop-card {
      padding: 16px;
    }

    .workshop-page .workshop-title {
      font-size: 1em;
    }
  }
</style>

<div class="workshop-page">
  <ul class="workshop-list">

    <li class="workshop-card">
      <div class="workshop-meta">
        <span>Co-located with <strong>WSDM 2027</strong></span>
        <span class="workshop-badge">Upcoming</span>
      </div>

      <h2 class="workshop-title">
        <a href="https://autor2-workshop.github.io/WSDM2027/"
           target="_blank" rel="noopener noreferrer">
          The First Workshop on AutoResearch for Information Retrieval
          and Recommender Systems
        </a>
      </h2>

      <p class="workshop-organizers">
        <span class="workshop-label">Organizers:</span>
        Yingchen Zhang, Mingwei Zhang, Ming Li, Andy Wang,
        Yinglong Xia, Zhaochun Ren and <strong>Ruqing Zhang</strong>
      </p>

      <div class="workshop-footer">
        <span>Location: Hong Kong</span>
      </div>

      <p class="workshop-invitation">
        Join us to explore how AI-driven research and autonomous agents
        can advance information retrieval and recommender systems.
        <strong>We welcome your participation and contributions!</strong>
      </p>
    </li>

    <li class="workshop-card">
      <div class="workshop-meta">
        <span>Co-located with <strong>SIGIR 2025</strong></span>
      </div>

      <h2 class="workshop-title">
        <a href="https://sigir-2025-workshop-on-robust-ir.github.io/"
           target="_blank" rel="noopener noreferrer">
          The First Workshop on Robust Information Retrieval (Robust-IR)
        </a>
      </h2>

      <p class="workshop-organizers">
        <span class="workshop-label">Organizers:</span>
        Yu-An Liu, Haya Nachimovsky, <strong>Ruqing Zhang</strong>,
        Oren Kurland, Jiafeng Guo and Moshe Tennenholtz
      </p>

      <div class="workshop-footer">
        <span>Location: Padua, Italy</span>
      </div>
    </li>

    <li class="workshop-card">
      <div class="workshop-meta">
        <span>Co-located with <strong>SIGIR 2024</strong></span>
      </div>

      <h2 class="workshop-title">
        <a href="https://coda.io/@sigir/gen-ir-24"
           target="_blank" rel="noopener noreferrer">
          The Second Workshop on Generative Information Retrieval (Gen-IR)
        </a>
      </h2>

      <p class="workshop-organizers">
        <span class="workshop-label">Organizers:</span>
        Gabriel Bénédict, <strong>Ruqing Zhang</strong>,
        Donald Metzler, Andrew Yates and Ziyan Jiang
      </p>

      <div class="workshop-footer">
        <span>Location: Washington, D.C., USA</span>
      </div>
    </li>

    <li class="workshop-card">
      <div class="workshop-meta">
        <span>Co-located with <strong>SIGIR 2023</strong></span>
      </div>

      <h2 class="workshop-title">
        <a href="https://coda.io/@sigir/gen-ir"
           target="_blank" rel="noopener noreferrer">
          The First Workshop on Generative Information Retrieval (Gen-IR)
        </a>
      </h2>

      <p class="workshop-organizers">
        <span class="workshop-label">Organizers:</span>
        Gabriel Bénédict, <strong>Ruqing Zhang</strong> and Donald Metzler
      </p>

      <div class="workshop-footer">
        <span>Location: Taipei, China</span>
        <a class="workshop-report"
           href="https://dl.acm.org/doi/pdf/10.1145/3642979.3642995"
           target="_blank" rel="noopener noreferrer">
          Workshop Report &rarr;
        </a>
      </div>
    </li>

  </ul>
</div>