---
layout: archive
title: "Workshops"
permalink: /workshop/
author_profile: true
---

<style>
  .workshop-page {
    --ws-accent: #287a96;
    --ws-text: #263746;
    --ws-muted: #687580;
    --ws-border: #e5e9ed;
    color: var(--ws-text);
    line-height: 1.7;
  }

  .workshop-page,
  .workshop-page * {
    box-sizing: border-box;
  }

  .workshop-page a {
    color: var(--ws-accent);
    text-decoration: none;
  }

  .workshop-page a:hover,
  .workshop-page a:focus-visible {
    text-decoration: underline;
    text-underline-offset: 3px;
  }

  .workshop-page .ws-group-title {
    display: flex;
    align-items: center;
    gap: 14px;
    margin: 30px 0 16px;
    padding: 0;
    border: 0;
    color: var(--ws-muted);
    font-size: 0.78em;
    font-weight: 600;
    letter-spacing: 0.09em;
    line-height: 1.5;
    text-transform: uppercase;
  }

  .workshop-page .ws-group-title:first-child {
    margin-top: 0;
  }

  .workshop-page .ws-group-title::after {
    content: "";
    flex: 1;
    height: 1px;
    background: var(--ws-border);
  }

  /* Upcoming workshop */
  .workshop-page .ws-featured {
    position: relative;
    overflow: hidden;
    padding: 28px;
    border: 1px solid #d6e6ed;
    border-top: 4px solid var(--ws-accent);
    border-radius: 10px;
    background: linear-gradient(135deg, #f0f8fb 0%, #ffffff 80%);
  }

  .workshop-page .ws-featured::after {
    content: "";
    position: absolute;
    top: -70px;
    right: -70px;
    width: 210px;
    height: 210px;
    border: 28px solid rgba(40, 122, 150, 0.045);
    border-radius: 50%;
    pointer-events: none;
  }

  .workshop-page .ws-featured > * {
    position: relative;
    z-index: 1;
  }

  .workshop-page .ws-topline {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 10px;
    margin-bottom: 12px;
  }

  .workshop-page .ws-conference {
    color: var(--ws-accent);
    font-size: 0.8em;
    font-weight: 700;
    letter-spacing: 0.04em;
  }

  .workshop-page .ws-badge {
    display: inline-block;
    padding: 2px 9px;
    border: 1px solid #d5e8dc;
    border-radius: 20px;
    background: #edf7f0;
    color: #347354;
    font-size: 0.68em;
    font-weight: 600;
    line-height: 1.6;
  }

  .workshop-page .ws-featured-name {
    margin: 0 0 6px;
    padding: 0;
    border: 0;
    color: var(--ws-accent);
    font-size: 2em;
    font-weight: 700;
    letter-spacing: -0.04em;
    line-height: 1.2;
  }

  .workshop-page .ws-featured-title {
    max-width: 650px;
    margin: 0 0 12px;
    padding: 0;
    border: 0;
    font-size: 1.08em;
    font-weight: 600;
    line-height: 1.5;
  }

  .workshop-page .ws-featured-title a {
    color: var(--ws-text);
  }

  .workshop-page .ws-meta {
    display: flex;
    flex-wrap: wrap;
    gap: 4px 16px;
    margin: 0 0 14px;
    color: var(--ws-muted);
    font-size: 0.8em;
    line-height: 1.6;
  }

  .workshop-page .ws-organizers {
    margin: 0;
    color: #52616d;
    font-size: 0.8em;
    line-height: 1.8;
  }

  .workshop-page .ws-organizers-label {
    color: var(--ws-muted);
  }

  .workshop-page .ws-organizers strong {
    color: var(--ws-text);
    font-weight: 650;
  }

  .workshop-page .ws-invitation {
    margin: 18px 0 0;
    padding-top: 16px;
    border-top: 1px solid #dce9ee;
    color: #46616e;
    font-size: 0.85em;
    line-height: 1.75;
  }

  .workshop-page .ws-actions {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 10px 18px;
    margin-top: 16px;
  }

  .workshop-page .ws-primary-link {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 8px 15px;
    border: 1px solid var(--ws-accent);
    border-radius: 6px;
    background: var(--ws-accent);
    color: #fff;
    font-size: 0.78em;
    font-weight: 600;
    line-height: 1.5;
    transition: background-color 0.15s ease;
  }

  .workshop-page .ws-primary-link:hover,
  .workshop-page .ws-primary-link:focus-visible {
    background: #20647b;
    color: #fff;
    text-decoration: none;
  }

  /* Past workshops */
  .workshop-page .ws-list {
    display: grid;
    gap: 16px;
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .workshop-page .ws-card {
    display: grid;
    grid-template-columns: 145px minmax(0, 1fr);
    margin: 0;
    overflow: hidden;
    border: 1px solid var(--ws-border);
    border-radius: 9px;
    background: #fff;
  }

  /* Consistent typographic covers */
  .workshop-page .ws-cover {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 8px;
    min-height: 180px;
    padding: 22px 12px;
    border-right: 1px solid rgba(40, 122, 150, 0.08);
    background: #eef5f8;
    color: #37697e;
    text-align: center;
  }

  .workshop-page .ws-cover-robust {
    background: linear-gradient(145deg, #eaf4f2, #f5f9f8);
    color: #3c736a;
  }

  .workshop-page .ws-cover-gen24 {
    background: linear-gradient(145deg, #edf2fa, #f7f9fc);
    color: #526e99;
  }

  .workshop-page .ws-cover-gen23 {
    background: linear-gradient(145deg, #f1eef8, #faf8fc);
    color: #79648f;
  }

  .workshop-page .ws-cover-name {
    font-size: 1.12em;
    font-weight: 700;
    letter-spacing: -0.03em;
    line-height: 1.3;
  }

  .workshop-page .ws-cover-edition {
    font-size: 0.65em;
    letter-spacing: 0.07em;
    line-height: 1.5;
    text-transform: uppercase;
  }

  .workshop-page .ws-cover-year {
    margin-top: 5px;
    padding: 2px 10px;
    border: 1px solid currentColor;
    border-radius: 20px;
    font-size: 0.72em;
    font-weight: 600;
    line-height: 1.5;
  }

  .workshop-page .ws-card-body {
    min-width: 0;
    padding: 20px 22px;
  }

  .workshop-page .ws-card .ws-conference {
    margin-bottom: 5px;
    font-size: 0.72em;
  }

  .workshop-page .ws-card-title {
    margin: 0 0 8px;
    padding: 0;
    border: 0;
    font-size: 0.97em;
    font-weight: 600;
    line-height: 1.5;
  }

  .workshop-page .ws-card-title a {
    color: var(--ws-text);
  }

  .workshop-page .ws-card-title a:hover,
  .workshop-page .ws-card-title a:focus-visible {
    color: var(--ws-accent);
  }

  .workshop-page .ws-card .ws-meta {
    margin-bottom: 9px;
    font-size: 0.74em;
  }

  .workshop-page .ws-card .ws-organizers {
    font-size: 0.76em;
  }

  .workshop-page .ws-card .ws-actions {
    gap: 8px 18px;
    margin-top: 12px;
  }

  .workshop-page .ws-text-link {
    display: inline-block;
    font-size: 0.75em;
    font-weight: 600;
    line-height: 1.6;
  }

  /* Mobile */
  @media (max-width: 600px) {
    .workshop-page .ws-featured {
      padding: 22px 18px;
    }

    .workshop-page .ws-featured-name {
      font-size: 1.75em;
    }

    .workshop-page .ws-featured-title {
      font-size: 1em;
    }

    .workshop-page .ws-card {
      grid-template-columns: 1fr;
    }

    .workshop-page .ws-cover {
      flex-direction: row;
      justify-content: flex-start;
      flex-wrap: wrap;
      gap: 8px 12px;
      min-height: 0;
      padding: 14px 18px;
      border-right: 0;
      border-bottom: 1px solid rgba(40, 122, 150, 0.08);
      text-align: left;
    }

    .workshop-page .ws-cover-name {
      font-size: 1em;
    }

    .workshop-page .ws-cover-edition {
      font-size: 0.62em;
    }

    .workshop-page .ws-cover-year {
      margin: 0 0 0 auto;
      font-size: 0.65em;
    }

    .workshop-page .ws-card-body {
      padding: 18px;
    }
  }

  @media (prefers-reduced-motion: reduce) {
    .workshop-page .ws-primary-link {
      transition: none;
    }
  }
</style>

<div class="workshop-page">

  <h2 class="ws-group-title" id="upcoming-workshops">
    Upcoming
  </h2>

  <article class="ws-featured" aria-labelledby="autor2-title">
    <div class="ws-topline">
      <span class="ws-conference">WSDM 2027</span>
      <span class="ws-badge">Upcoming</span>
    </div>

    <p class="ws-featured-name">AutoR&sup2;</p>

    <h3 class="ws-featured-title" id="autor2-title">
      <a href="https://autor2-workshop.github.io/WSDM2027/"
         target="_blank" rel="noopener noreferrer">
        The First Workshop on AutoResearch for Information Retrieval
        and Recommender Systems
      </a>
    </h3>

    <div class="ws-meta">
      <span>
        <time datetime="2027-02-19">February 19, 2027</time>
      </span>
      <span>Hong Kong, China</span>
    </div>

    <p class="ws-organizers">
      <span class="ws-organizers-label">Organizers:</span>
      Yingchen Zhang, Mingwei Zhang, Ming Li, Andy Wang,
      Yinglong Xia, Zhaochun Ren and <strong>Ruqing Zhang</strong>
    </p>

    <p class="ws-invitation">
      Join us to explore how autonomous research agents can advance
      information retrieval and recommender systems.
      <strong>We welcome your participation and contributions!</strong>
    </p>

    <div class="ws-actions">
      <a class="ws-primary-link"
         href="https://autor2-workshop.github.io/WSDM2027/"
         target="_blank" rel="noopener noreferrer">
        Workshop Website <span aria-hidden="true">&nearr;</span>
      </a>
    </div>
  </article>

  <h2 class="ws-group-title" id="past-workshops">
    Past Workshops
  </h2>

  <ul class="ws-list" aria-labelledby="past-workshops">

    <li class="ws-card">
      <div class="ws-cover ws-cover-robust" aria-hidden="true">
        <span class="ws-cover-name">Robust-IR</span>
        <span class="ws-cover-edition">First Edition</span>
        <span class="ws-cover-year">2025</span>
      </div>

      <div class="ws-card-body">
        <div class="ws-conference">SIGIR 2025</div>

        <h3 class="ws-card-title">
          <a href="https://sigir-2025-workshop-on-robust-ir.github.io/"
             target="_blank" rel="noopener noreferrer">
            The First Workshop on Robust Information Retrieval
            (Robust-IR)
          </a>
        </h3>

        <div class="ws-meta">
          <span>Padua, Italy</span>
        </div>

        <p class="ws-organizers">
          <span class="ws-organizers-label">Organizers:</span>
          Yu-An Liu, Haya Nachimovsky, <strong>Ruqing Zhang</strong>,
          Oren Kurland, Jiafeng Guo and Moshe Tennenholtz
        </p>

        <div class="ws-actions">
          <a class="ws-text-link"
             href="https://sigir-2025-workshop-on-robust-ir.github.io/"
             target="_blank" rel="noopener noreferrer">
            Workshop Website <span aria-hidden="true">&nearr;</span>
          </a>
        </div>
      </div>
    </li>

    <li class="ws-card">
      <div class="ws-cover ws-cover-gen24" aria-hidden="true">
        <span class="ws-cover-name">Gen-IR</span>
        <span class="ws-cover-edition">Second Edition</span>
        <span class="ws-cover-year">2024</span>
      </div>

      <div class="ws-card-body">
        <div class="ws-conference">SIGIR 2024</div>

        <h3 class="ws-card-title">
          <a href="https://coda.io/@sigir/gen-ir-24"
             target="_blank" rel="noopener noreferrer">
            The Second Workshop on Generative Information Retrieval
            (Gen-IR)
          </a>
        </h3>

        <div class="ws-meta">
          <span>Washington, D.C., USA</span>
        </div>

        <p class="ws-organizers">
          <span class="ws-organizers-label">Organizers:</span>
          Gabriel Bénédict, <strong>Ruqing Zhang</strong>,
          Donald Metzler, Andrew Yates and Ziyan Jiang
        </p>

        <div class="ws-actions">
          <a class="ws-text-link"
             href="https://coda.io/@sigir/gen-ir-24"
             target="_blank" rel="noopener noreferrer">
            Workshop Website <span aria-hidden="true">&nearr;</span>
          </a>
        </div>
      </div>
    </li>

    <li class="ws-card">
      <div class="ws-cover ws-cover-gen23" aria-hidden="true">
        <span class="ws-cover-name">Gen-IR</span>
        <span class="ws-cover-edition">First Edition</span>
        <span class="ws-cover-year">2023</span>
      </div>

      <div class="ws-card-body">
        <div class="ws-conference">SIGIR 2023</div>

        <h3 class="ws-card-title">
          <a href="https://coda.io/@sigir/gen-ir"
             target="_blank" rel="noopener noreferrer">
            The First Workshop on Generative Information Retrieval
            (Gen-IR)
          </a>
        </h3>

        <div class="ws-meta">
          <span>Taipei, China</span>
        </div>

        <p class="ws-organizers">
          <span class="ws-organizers-label">Organizers:</span>
          Gabriel Bénédict, <strong>Ruqing Zhang</strong>
          and Donald Metzler
        </p>

        <div class="ws-actions">
          <a class="ws-text-link"
             href="https://coda.io/@sigir/gen-ir"
             target="_blank" rel="noopener noreferrer">
            Workshop Website <span aria-hidden="true">&nearr;</span>
          </a>

          <a class="ws-text-link"
             href="https://dl.acm.org/doi/pdf/10.1145/3642979.3642995"
             target="_blank" rel="noopener noreferrer">
            Workshop Report <span aria-hidden="true">&rarr;</span>
          </a>
        </div>
      </div>
    </li>

  </ul>
</div>