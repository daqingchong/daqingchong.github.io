---
layout: archive
title: "Tutorials"
permalink: /tutorial/
author_profile: true
---

<style>
  .tutorial-page {
    --tutorial-accent: #287a96;
    --tutorial-border: #e5e9ed;
    --tutorial-muted: #687580;
  }

  .tutorial-section {
    margin: 0 0 36px;
  }

  .tutorial-section h2 {
    margin: 0 0 18px;
    padding-bottom: 10px;
    border-bottom: 2px solid var(--tutorial-border);
    font-size: 1.3em;
    line-height: 1.4;
  }

  .tutorial-page .tutorial-list {
    display: grid;
    gap: 14px;
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .tutorial-page .tutorial-card {
    margin: 0;
    padding: 18px 22px;
    border: 1px solid var(--tutorial-border);
    border-left: 3px solid var(--tutorial-accent);
    border-radius: 8px;
    background: #fff;
  }

  .tutorial-card h3 {
    margin: 0 0 8px;
    color: #263746;
    font-size: 1.05em;
    line-height: 1.4;
  }

  .tutorial-speakers {
    margin: 0 0 12px;
    color: #4a5560;
    font-size: 0.92em;
    line-height: 1.7;
  }

  .tutorial-speakers strong {
    color: #263746;
  }

  .tutorial-footer {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 8px 18px;
    color: var(--tutorial-muted);
    font-size: 0.85em;
  }

  .tutorial-page .tutorial-link {
    display: inline-block;
    padding: 3px 11px;
    border: 1px solid #d5e7ee;
    border-radius: 5px;
    background: #f2f8fa;
    color: var(--tutorial-accent);
    font-weight: 600;
    text-decoration: none;
    transition: background-color 0.15s ease;
  }

  .tutorial-page .tutorial-link:hover,
  .tutorial-page .tutorial-link:focus-visible {
    background: #e2f0f5;
    text-decoration: underline;
  }

  @media (max-width: 600px) {
    .tutorial-page .tutorial-card {
      padding: 15px 16px;
    }

    .tutorial-section h2 {
      font-size: 1.15em;
    }
  }
</style>

<div class="tutorial-page">

  <section class="tutorial-section">
    <h2>Recent Advances in Generative Information Retrieval</h2>

    <ul class="tutorial-list">
      <li class="tutorial-card">
        <h3>SIGIR 2024</h3>
        <p class="tutorial-speakers">
          Yubao Tang, <strong>Ruqing Zhang</strong>, Zhaochun Ren,
          Jiafeng Guo and Maarten de Rijke
        </p>
        <div class="tutorial-footer">
          <span>Washington, D.C., USA</span>
          <a class="tutorial-link"
             href="https://generative-ir.github.io/"
             target="_blank" rel="noopener noreferrer">
            Tutorial Slides &rarr;
          </a>
        </div>
      </li>

      <li class="tutorial-card">
        <h3>WebConf 2024</h3>
        <p class="tutorial-speakers">
          Yubao Tang, <strong>Ruqing Zhang</strong>, Zhaochun Ren,
          WeiWei Sun, Jiafeng Guo and Maarten de Rijke
        </p>
        <div class="tutorial-footer">
          <span>Glasgow, Scotland</span>
          <a class="tutorial-link"
             href="https://TheWebConf2024-generative-IR.github.io"
             target="_blank" rel="noopener noreferrer">
            Tutorial Slides &rarr;
          </a>
        </div>
      </li>

      <li class="tutorial-card">
        <h3>ECIR 2024</h3>
        <p class="tutorial-speakers">
          Yubao Tang, <strong>Ruqing Zhang</strong>, Zhaochun Ren,
          Jiafeng Guo and Maarten de Rijke
        </p>
        <div class="tutorial-footer">
          <span>Glasgow, Scotland</span>
          <a class="tutorial-link"
             href="https://ecir2024-generativeir.github.io/"
             target="_blank" rel="noopener noreferrer">
            Tutorial Slides &rarr;
          </a>
        </div>
      </li>

      <li class="tutorial-card">
        <h3>SIGIR-AP 2023</h3>
        <p class="tutorial-speakers">
          Yubao Tang, <strong>Ruqing Zhang</strong>,
          Jiafeng Guo and Maarten de Rijke
        </p>
        <div class="tutorial-footer">
          <span>Beijing, China</span>
          <a class="tutorial-link"
             href="https://sigir-ap2023-generative-ir.github.io/"
             target="_blank" rel="noopener noreferrer">
            Tutorial Slides &rarr;
          </a>
        </div>
      </li>
    </ul>
  </section>

  <section class="tutorial-section">
    <h2>Robust Information Retrieval</h2>

    <ul class="tutorial-list">
      <li class="tutorial-card">
        <h3>WSDM 2025</h3>
        <p class="tutorial-speakers">
          Yu-An Liu, <strong>Ruqing Zhang</strong>,
          Jiafeng Guo and Maarten de Rijke
        </p>
        <div class="tutorial-footer">
          <span>Hannover, Germany</span>
          <a class="tutorial-link"
             href="https://wsdm2025-robust-information-retrieval.github.io/"
             target="_blank" rel="noopener noreferrer">
            Tutorial Slides &rarr;
          </a>
        </div>
      </li>

      <li class="tutorial-card">
        <h3>SIGIR 2024</h3>
        <p class="tutorial-speakers">
          Yu-An Liu, <strong>Ruqing Zhang</strong>,
          Jiafeng Guo and Maarten de Rijke
        </p>
        <div class="tutorial-footer">
          <span>Washington, D.C., USA</span>
          <a class="tutorial-link"
             href="https://sigir2024-robust-information-retrieval.github.io/"
             target="_blank" rel="noopener noreferrer">
            Tutorial Slides &rarr;
          </a>
        </div>
      </li>
    </ul>
  </section>

</div>