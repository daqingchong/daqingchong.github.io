---
layout: archive
title: "Tutorials"
permalink: /tutorial/
author_profile: true
---

<style>
  .tutorial-page {
    --tt-accent: #287a96;
    --tt-text: #263746;
    --tt-muted: #687580;
    --tt-border: #e5e9ed;
    color: var(--tt-text);
    line-height: 1.7;
  }

  .tutorial-page,
  .tutorial-page * {
    box-sizing: border-box;
  }

  .tutorial-page a {
    color: var(--tt-accent);
    text-decoration: none;
  }

  .tutorial-page a:hover,
  .tutorial-page a:focus-visible {
    text-decoration: underline;
    text-underline-offset: 3px;
  }

  /* Topic sections */
  .tutorial-page .tt-section {
    margin: 0 0 32px;
    overflow: hidden;
    border: 1px solid var(--tt-border);
    border-radius: 10px;
    background: #fff;
  }

  .tutorial-page .tt-section:last-child {
    margin-bottom: 0;
  }

  .tutorial-page .tt-section-generative {
    --tt-topic: #287a96;
    --tt-tint: #f0f7fa;
  }

  .tutorial-page .tt-section-robust {
    --tt-topic: #3c736a;
    --tt-tint: #f0f7f4;
  }

  .tutorial-page .tt-header {
    padding: 22px 24px;
    border-top: 3px solid var(--tt-topic);
    border-bottom: 1px solid var(--tt-border);
    background: var(--tt-tint);
  }

  .tutorial-page .tt-eyebrow {
    margin: 0 0 7px;
    color: var(--tt-topic);
    font-size: 0.68em;
    font-weight: 700;
    letter-spacing: 0.1em;
    line-height: 1.5;
    text-transform: uppercase;
  }

  .tutorial-page .tt-topic-title {
    margin: 0;
    padding: 0;
    border: 0;
    color: var(--tt-text);
    font-size: 1.12em;
    font-weight: 650;
    line-height: 1.5;
  }

  /* Tutorial rows */
  .tutorial-page .tt-list {
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .tutorial-page .tt-item {
    display: grid;
    grid-template-columns: 112px minmax(0, 1fr);
    gap: 22px;
    margin: 0;
    padding: 22px 24px;
    border-bottom: 1px solid var(--tt-border);
  }

  .tutorial-page .tt-item:last-child {
    border-bottom: 0;
  }

  .tutorial-page .tt-venue {
    align-self: start;
    padding: 11px 8px;
    border: 1px solid var(--tt-border);
    border-radius: 7px;
    background: #fafcfd;
    text-align: center;
  }

  .tutorial-page .tt-conference {
    display: block;
    margin: 0;
    padding: 0;
    border: 0;
    color: var(--tt-topic);
    font-size: 0.85em;
    font-weight: 700;
    line-height: 1.5;
  }

  .tutorial-page .tt-year {
    display: block;
    margin-top: 3px;
    color: var(--tt-muted);
    font-size: 0.77em;
    font-variant-numeric: tabular-nums;
    line-height: 1.5;
  }

  .tutorial-page .tt-content {
    min-width: 0;
  }

  .tutorial-page .tt-speakers {
    margin: 0;
    color: #52616d;
    font-size: 0.84em;
    line-height: 1.8;
  }

  .tutorial-page .tt-speakers strong {
    color: var(--tt-text);
    font-weight: 650;
  }

  .tutorial-page .tt-footer {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
    gap: 10px 18px;
    margin-top: 12px;
  }

  .tutorial-page .tt-location {
    color: var(--tt-muted);
    font-size: 0.75em;
    line-height: 1.6;
  }

  .tutorial-page .tt-link {
    display: inline-flex;
    align-items: center;
    gap: 7px;
    padding: 4px 10px;
    border: 1px solid #d5e7ee;
    border-radius: 5px;
    background: #f2f8fa;
    color: var(--tt-accent);
    font-size: 0.73em;
    font-weight: 600;
    line-height: 1.6;
    white-space: nowrap;
    transition: background-color 0.15s ease;
  }

  .tutorial-page .tt-link:hover,
  .tutorial-page .tt-link:focus-visible {
    background: #e2f0f5;
    text-decoration: none;
  }

  /* Mobile */
  @media (max-width: 600px) {
    .tutorial-page .tt-header {
      padding: 18px;
    }

    .tutorial-page .tt-topic-title {
      font-size: 1em;
    }

    .tutorial-page .tt-item {
      grid-template-columns: 1fr;
      gap: 12px;
      padding: 18px;
    }

    .tutorial-page .tt-venue {
      display: inline-flex;
      align-items: baseline;
      justify-self: start;
      gap: 8px;
      padding: 4px 10px;
      text-align: left;
    }

    .tutorial-page .tt-year {
      margin-top: 0;
    }

    .tutorial-page .tt-footer {
      justify-content: flex-start;
    }
  }

  @media (prefers-reduced-motion: reduce) {
    .tutorial-page .tt-link {
      transition: none;
    }
  }
</style>

<div class="tutorial-page">

  <section class="tt-section tt-section-generative"
           aria-labelledby="generative-tutorials">

    <header class="tt-header">
      <h2 class="tt-topic-title" id="generative-tutorials">
        Recent Advances in Generative Information Retrieval
      </h2>
    </header>

    <ul class="tt-list">

      <li class="tt-item">
        <div class="tt-venue">
          <h3 class="tt-conference">SIGIR</h3>
          <span class="tt-year">2024</span>
        </div>

        <div class="tt-content">
          <p class="tt-speakers">
            Yubao Tang, <strong>Ruqing Zhang</strong>, Zhaochun Ren,
            Jiafeng Guo and Maarten de Rijke
          </p>

          <div class="tt-footer">
            <span class="tt-location">Washington, D.C., USA</span>
            <a class="tt-link"
               href="https://generative-ir.github.io/"
               target="_blank" rel="noopener noreferrer"
               aria-label="Tutorial website and slides for Generative IR at SIGIR 2024">
              Website &amp; Slides
              <span aria-hidden="true">&nearr;</span>
            </a>
          </div>
        </div>
      </li>

      <li class="tt-item">
        <div class="tt-venue">
          <h3 class="tt-conference">WebConf</h3>
          <span class="tt-year">2024</span>
        </div>

        <div class="tt-content">
          <p class="tt-speakers">
            Yubao Tang, <strong>Ruqing Zhang</strong>, Zhaochun Ren,
            WeiWei Sun, Jiafeng Guo and Maarten de Rijke
          </p>

          <div class="tt-footer">
            <span class="tt-location">Glasgow, Scotland</span>
            <a class="tt-link"
               href="https://TheWebConf2024-generative-IR.github.io"
               target="_blank" rel="noopener noreferrer"
               aria-label="Tutorial website and slides for Generative IR at WebConf 2024">
              Website &amp; Slides
              <span aria-hidden="true">&nearr;</span>
            </a>
          </div>
        </div>
      </li>

      <li class="tt-item">
        <div class="tt-venue">
          <h3 class="tt-conference">ECIR</h3>
          <span class="tt-year">2024</span>
        </div>

        <div class="tt-content">
          <p class="tt-speakers">
            Yubao Tang, <strong>Ruqing Zhang</strong>, Zhaochun Ren,
            Jiafeng Guo and Maarten de Rijke
          </p>

          <div class="tt-footer">
            <span class="tt-location">Glasgow, Scotland</span>
            <a class="tt-link"
               href="https://ecir2024-generativeir.github.io/"
               target="_blank" rel="noopener noreferrer"
               aria-label="Tutorial website and slides for Generative IR at ECIR 2024">
              Website &amp; Slides
              <span aria-hidden="true">&nearr;</span>
            </a>
          </div>
        </div>
      </li>

      <li class="tt-item">
        <div class="tt-venue">
          <h3 class="tt-conference">SIGIR-AP</h3>
          <span class="tt-year">2023</span>
        </div>

        <div class="tt-content">
          <p class="tt-speakers">
            Yubao Tang, <strong>Ruqing Zhang</strong>,
            Jiafeng Guo and Maarten de Rijke
          </p>

          <div class="tt-footer">
            <span class="tt-location">Beijing, China</span>
            <a class="tt-link"
               href="https://sigir-ap2023-generative-ir.github.io/"
               target="_blank" rel="noopener noreferrer"
               aria-label="Tutorial website and slides for Generative IR at SIGIR-AP 2023">
              Website &amp; Slides
              <span aria-hidden="true">&nearr;</span>
            </a>
          </div>
        </div>
      </li>

    </ul>
  </section>

  <section class="tt-section tt-section-robust"
           aria-labelledby="robust-tutorials">

    <header class="tt-header">
      <h2 class="tt-topic-title" id="robust-tutorials">
        Robust Information Retrieval
      </h2>
    </header>

    <ul class="tt-list">

      <li class="tt-item">
        <div class="tt-venue">
          <h3 class="tt-conference">WSDM</h3>
          <span class="tt-year">2025</span>
        </div>

        <div class="tt-content">
          <p class="tt-speakers">
            Yu-An Liu, <strong>Ruqing Zhang</strong>,
            Jiafeng Guo and Maarten de Rijke
          </p>

          <div class="tt-footer">
            <span class="tt-location">Hannover, Germany</span>
            <a class="tt-link"
               href="https://wsdm2025-robust-information-retrieval.github.io/"
               target="_blank" rel="noopener noreferrer"
               aria-label="Tutorial website and slides for Robust IR at WSDM 2025">
              Website &amp; Slides
              <span aria-hidden="true">&nearr;</span>
            </a>
          </div>
        </div>
      </li>

      <li class="tt-item">
        <div class="tt-venue">
          <h3 class="tt-conference">SIGIR</h3>
          <span class="tt-year">2024</span>
        </div>

        <div class="tt-content">
          <p class="tt-speakers">
            Yu-An Liu, <strong>Ruqing Zhang</strong>,
            Jiafeng Guo and Maarten de Rijke
          </p>

          <div class="tt-footer">
            <span class="tt-location">Washington, D.C., USA</span>
            <a class="tt-link"
               href="https://sigir2024-robust-information-retrieval.github.io/"
               target="_blank" rel="noopener noreferrer"
               aria-label="Tutorial website and slides for Robust IR at SIGIR 2024">
              Website &amp; Slides
              <span aria-hidden="true">&nearr;</span>
            </a>
          </div>
        </div>
      </li>

    </ul>
  </section>

</div>