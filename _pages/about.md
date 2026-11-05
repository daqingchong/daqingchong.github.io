---
layout: archive
permalink: /
title: "Ruqing Zhang (张儒清) 🐛"
excerpt: "Ruqing Zhang"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>

/* All rules are scoped to this page to preserve the site theme. */
.home-page {
  --home-accent: #287a96;
  --home-text: #243746;
  --home-muted: #61727e;
  --home-border: #e2e9ed;
  color: var(--home-text);
  font-size: .96em;
  line-height: 1.8;
  container-type: inline-size;
}
.home-page, .home-page * { box-sizing: border-box; }
.home-page a { color: var(--home-accent); text-decoration: none; overflow-wrap: anywhere; }
.home-page a:hover { text-decoration: underline; text-underline-offset: 3px; }
.home-page a:focus-visible { outline: 2px solid var(--home-accent); outline-offset: 4px; border-radius: 2px; }
.home-page p { margin: 0 0 16px; }
.home-page .home-intro { padding: 5px 0 0; }
.home-page .home-eyebrow {
  color: var(--home-accent); font-size: .66em; font-weight: 700;
  letter-spacing: .12em; line-height: 1.7; margin-bottom: 14px;
}
.home-page .home-intro > p:last-child { font-size: 1.02em; line-height: 1.85; margin-bottom: 20px; }
.home-page .home-intro strong { color: #1d5367; }
.home-page .home-jumpnav {
  display: flex; flex-wrap: wrap; gap: 7px 24px; padding: 12px 0;
  border-top: 1px solid var(--home-border); border-bottom: 1px solid var(--home-border);
  margin-bottom: 32px;
}
.home-page .home-jumpnav a { color: #526775; font-size: .75em; font-weight: 600; }
.home-page .home-jumpnav a:hover { color: var(--home-accent); }
.home-page .home-section { margin: 38px 0 0; }
.home-page .home-section > h2 {
  display: flex; align-items: center; gap: 16px; margin: 0 0 22px;
  padding: 0; border: 0; color: var(--home-text); font-size: 1.22em;
  font-weight: 650; letter-spacing: -.025em; line-height: 1.4; scroll-margin-top: 30px;
}
.home-page .home-section > h2::after { content: ''; height: 1px; flex: 1; background: var(--home-border); }
/* Research: a shared mission followed by two complementary directions. */
.home-page .research-panel { margin-top: 0; }
.home-page .research-lead {
  position: relative; padding: 23px 25px; border: 1px solid #dbe8ee;
  border-left: 3px solid var(--home-accent); border-radius: 0 10px 10px 0;
  background: linear-gradient(115deg, #edf6f9, #f8fbfc);
  color: #2a5265; font-size: 1.04em; line-height: 1.85; margin-bottom: 16px;
}
.home-page .research-grid { display: grid; grid-template-columns: 1fr; gap: 16px; }
.home-page .research-card { min-width: 0; padding: 23px; border: 1px solid var(--home-border); border-radius: 10px; background: #fff; }
.home-page .research-card-2 { background: #fbfcfa; border-color: #e0e8e1; }
.home-page .research-kicker { color: var(--home-accent); font-size: .62em; font-weight: 700; letter-spacing: .1em; line-height: 1.6; margin: 0 0 10px; }
.home-page .research-card-2 .research-kicker { color: #477368; }
.home-page .research-card h3 { margin: 0 0 12px; padding: 0; border: 0; font-size: 1em; letter-spacing: -.015em; line-height: 1.5; }
.home-page .research-card > p:not(.research-kicker) { color: #52626d; font-size: .86em; line-height: 1.8; margin: 0 0 16px; }
.home-page .research-topics { display: flex; flex-wrap: wrap; gap: 6px; list-style: none; margin: 0; padding: 0; }
.home-page .research-topics li { margin: 0; padding: 3px 8px; border: 1px solid #dce8ed; border-radius: 4px; background: #f5f9fb; color: #476777; font-size: .64em; line-height: 1.65; }
.home-page .research-card-2 .research-topics li { background: #f2f7f3; border-color: #dfe9e1; color: #4d6b60; }
.home-page .research-summary { margin-top: 20px; padding: 0 2px; color: #5b6a75; font-size: .85em; line-height: 1.85; }
.home-page .research-summary strong { color: #2b5367; }
/* Experience: a quiet vertical timeline. */
.home-page .experience-list { list-style: none; padding: 0; margin: 0; }
.home-page .experience-item { position: relative; display: grid; grid-template-columns: 145px minmax(0,1fr); gap: 24px; padding: 0 0 25px; margin: 0; }
.home-page .experience-item::before { content: ''; position: absolute; left: 156px; top: 11px; bottom: -10px; width: 1px; background: var(--home-border); }
.home-page .experience-item::after { content: ''; position: absolute; left: 152px; top: 9px; width: 9px; height: 9px; border: 2px solid #8daebc; border-radius: 50%; background: #fff; }
.home-page .experience-item:first-child::after { background: var(--home-accent); border-color: var(--home-accent); box-shadow: 0 0 0 4px #edf5f8; }
.home-page .experience-item:last-child { padding-bottom: 0; }
.home-page .experience-item:last-child::before { display: none; }
.home-page .experience-date { padding-top: 2px; color: var(--home-muted); font-size: .72em; line-height: 1.8; font-variant-numeric: tabular-nums; }
.home-page .experience-role { margin: 0 0 3px; padding: 0; border: 0; font-size: .93em; font-weight: 650; line-height: 1.5; }
.home-page .experience-institution { margin: 0; color: #4b606c; font-size: .83em; line-height: 1.7; }
.home-page .experience-detail { margin: 4px 0 0; color: var(--home-muted); font-size: .75em; line-height: 1.75; }
/* Honors: warm accents reserved for the three featured awards. */
.home-page .honors-group-title { display: flex; align-items: center; gap: 13px; margin: 25px 0 12px; padding: 0; border: 0; color: var(--home-muted); font-size: .67em; font-weight: 600; letter-spacing: .1em; text-transform: uppercase; line-height: 1.5; }
.home-page .honors-group-title::after { content: ''; flex: 1; height: 1px; background: var(--home-border); }
.home-page .honors-list { list-style: none; padding: 0; margin: 0; }
.home-page .honor-item { display: grid; grid-template-columns: 46px minmax(0,1fr); align-items: baseline; gap: 15px; margin: 0; padding: 10px 17px; border-left: 3px solid transparent; font-size: .85em; line-height: 1.7; }
.home-page .honor-year { color: var(--home-muted); font-size: .86em; font-weight: 600; font-variant-numeric: tabular-nums; }
.home-page .honor-content { min-width: 0; }
.home-page .honor-featured { margin: 9px 0; padding: 18px 17px; border: 1px solid #ebdfc6; border-left: 3px solid #b6904c; border-radius: 0 8px 8px 0; background: linear-gradient(110deg,#fff9ed,#fffdf8); }
.home-page .honor-featured .honor-year { color: #8a672c; }
.home-page a.honor-title { color: #79581f; font-weight: 650; }
.home-page .honor-content .honor-description { margin: 6px 0 0; color: #52616b; font-size: .91em; line-height: 1.75; }
.home-page .honor-content .honor-note { margin: 5px 0 0; color: #65717a; font-size: .84em; line-height: 1.75; }
.home-page .honor-paper { white-space: nowrap; font-weight: 600; }
/* Service */
.home-page .service-list { display: grid; grid-template-columns: 1fr; gap: 14px; margin: 0; }
.home-page .service-list > div { min-width: 0; padding: 21px; border: 1px solid var(--home-border); border-radius: 8px; background: #f9fbfc; }
.home-page .service-list dt { margin: 0 0 9px; color: #315e72; font-size: .83em; font-weight: 650; line-height: 1.6; }
.home-page .service-list dd { margin: 0; color: #566975; font-size: .81em; line-height: 1.85; }
/* Use the available content width, including layouts with a profile sidebar. */
@container (min-width: 660px) {
  .home-page .research-grid { grid-template-columns: repeat(2,minmax(0,1fr)); }
  .home-page .service-list { grid-template-columns: repeat(2,minmax(0,1fr)); }
}
@media (max-width: 640px) {
  .home-page .home-eyebrow { font-size: .59em; letter-spacing: .08em; }
  .home-page .home-jumpnav { gap: 8px 18px; }
  .home-page .research-lead { padding: 18px; font-size: .98em; }
  .home-page .research-card { padding: 19px; }
  .home-page .experience-item { grid-template-columns: 1fr; gap: 4px; padding: 0 0 24px 23px; }
  .home-page .experience-item::before { left: 4px; }
  .home-page .experience-item::after { left: 0; }
  .home-page .honor-item { grid-template-columns: 36px minmax(0,1fr); gap: 10px; padding: 11px; }
  .home-page .honor-featured { padding: 15px 11px; }
  .home-page .home-section > h2 { font-size: 1.12em; }
}
</style>

<div class="home-page">
<div class="home-intro">
<p>
      I am currently an <strong>Associate Professor</strong> at the
      <a href="http://www.ict.ac.cn">Institute of Computing Technology (ICT)</a>,
      <a href="http://www.cas.cn">Chinese Academy of Sciences (CAS)</a>.
      I received my Ph.D. in Computer Science from ICT, CAS in 2019
      and my B.S. in Computer Science from the
      <a href="https://scs.bupt.edu.cn">Department of Computer Science</a>,
      <a href="https://www.bupt.edu.cn">
        Beijing University of Posts and Telecommunications
      </a>
      in 2014.
    </p>
</div><nav aria-label="On this page" class="home-jumpnav"><a href="#research-heading">Research</a><a href="#experience-heading">Experience</a><a href="#honors-heading">Honors &amp; Awards</a><a href="#services-heading">Service</a></nav>
<section aria-labelledby="research-heading" class="research-panel home-section">
<h2 id="research-heading">Research Interests</h2>
<p class="research-lead">
    My research connects information retrieval and autonomous agents, 
    with the goal of building self-evolving intelligent systems that acquire useful 
    information, generate trustworthy answers, and continually improve their capabilities through experience.
   </p>
<div class="research-grid"><article class="research-card research-card-1"><p class="research-kicker">01 / SEARCH &amp; INFORMATION</p><h3>Generative Information Retrieval</h3>
<p>
    I study search for agents and agents for search: adapting retrieval 
    to the diverse and evolving information needs of AI agents, and using 
    agents to improve information seeking. 
   </p>
<ul aria-label="Research topics" class="research-topics">
<li>Generative Retrieval</li>
<li>Agent-Aware Retrieval</li>
<li>Agentic Search</li>
<li>Multimodal Search</li>
<li>Trustworthy LLM Reasoning</li>
</ul>
</article><article class="research-card research-card-2"><p class="research-kicker">02 / LEARNING &amp; DISCOVERY</p><h3>Autonomous Research Agents</h3>
<p>
      More recently, I develop autonomous agents for scientific research 
      that learn from experience, reason and act efficiently over long horizons, 
      and operate safely in real-world environments.
    </p>
<ul aria-label="Research topics" class="research-topics">
<li>Experience-Driven Self-Improvement</li>
<li>Long-Horizon Planning</li>
<li>Efficient Agentic Reasoning</li>
<li>Agent Safety Evaluation</li>
</ul>
</article></div></section>
<div class="research-summary">
<p>
      I have authored over <strong>100 peer-reviewed publications</strong>
      in leading international journals and conferences, including
      ACM TOIS, SIGIR, WebConf, KDD, NeurIPS, WSDM, ACL, and EMNLP.
      My research is supported by the National Key Research and
      Development Program of China, the National Natural Science
      Foundation of China, the CAS Strategic Priority Research Program,
      and industry partners including Baidu, Tencent, ByteDance,
      and Alibaba.
    </p>
</div>
<section aria-labelledby="experience-heading" class="home-section">
<h2 id="experience-heading">Experience</h2>
<ul class="experience-list">
<li class="experience-item">
<div class="experience-date">Sept. 2022 – Present</div>
<div>
<h3 class="experience-role">Associate Professor</h3>
<p class="experience-institution">
            Institute of Computing Technology, Chinese Academy of Sciences
          </p>
<p class="experience-detail">Beijing, China</p>
</div>
</li>
<li class="experience-item">
<div class="experience-date">Oct. 2022 – Oct. 2023</div>
<div>
<h3 class="experience-role">Visiting Scholar</h3>
<p class="experience-institution">
<a href="https://irlab.science.uva.nl/">IRLab</a>,
            University of Amsterdam
          </p>
<p class="experience-detail">
            Advised by Prof.
            <a href="https://staff.fnwi.uva.nl/m.derijke/">
              Maarten de Rijke
            </a>
            · Amsterdam, The Netherlands
          </p>
</div>
</li>
<li class="experience-item">
<div class="experience-date">Jul. 2019 – Sept. 2022</div>
<div>
<h3 class="experience-role">Assistant Professor</h3>
<p class="experience-institution">
            Institute of Computing Technology, Chinese Academy of Sciences
          </p>
<p class="experience-detail">Beijing, China</p>
</div>
</li>
<li class="experience-item">
<div class="experience-date">Sept. 2014 – Jul. 2019</div>
<div>
<h3 class="experience-role">Ph.D. Student</h3>
<p class="experience-institution">
            Institute of Computing Technology, Chinese Academy of Sciences
          </p>
<p class="experience-detail">
            Advised by Prof.
            <a href="http://www.ict.cas.cn/sourcedb/cn/jssrck/200909/t20090917_2496654.html">
              Guojie Li
            </a>
            and Prof.
            <a href="https://scholar.google.com/citations?user=nD0I3PUAAAAJ&amp;hl=en">
              Jiafeng Guo
            </a>
            · Beijing, China
          </p>
</div>
</li>
<li class="experience-item">
<div class="experience-date">Sept. 2017 – Jun. 2018</div>
<div>
<h3 class="experience-role">Ph.D. Intern</h3>
<p class="experience-institution">ByteDance, Toutiao</p>
<p class="experience-detail">Beijing, China</p>
</div>
</li>
<li class="experience-item">
<div class="experience-date">Sept. 2010 – Jul. 2014</div>
<div>
<h3 class="experience-role">Undergraduate Student</h3>
<p class="experience-institution">
            Beijing University of Posts and Telecommunications
          </p>
<p class="experience-detail">Beijing, China</p>
</div>
</li>
</ul>
</section>
<section aria-labelledby="honors-heading" class="home-section">
<h2 id="honors-heading">
  Honors &amp; Awards
 </h2>
<h3 class="honors-group-title">
  Professional Honors
 </h3>
<ul class="honors-list">
<li class="honor-item honor-featured">
<span class="honor-year">
    2026
   </span>
<div class="honor-content">
<a class="honor-title" href="https://sigir.org/awards/sigir-ecr-awards/">
     ACM SIGIR Early Career Researcher Award (for Research)
    </a>
<p class="honor-description">
     In recognition of outstanding research contributions and leadership
    in the SIGIR community at an early career stage.
    </p>
</div>
</li>
<li class="honor-item">
<span class="honor-year">
    2025
   </span>
<div class="honor-content">
    Beijing Youth Talent Support Project
   </div>
</li>
<li class="honor-item honor-featured">
<span class="honor-year">
    2024
   </span>
<div class="honor-content">
<a class="honor-title" href="https://2024.emnlp.org/program/best_papers/">
     EMNLP Best Paper Award
    </a>
<p class="honor-description">
     For proposing a new dataset and method for black-box detection of
    pretraining data in large language models.
     <a class="honor-paper" href="https://aclanthology.org/2024.emnlp-main.300/">
      [Paper]
     </a>
</p>
<p class="honor-note">
     The second Best Long Paper award in EMNLP history
      for research led by an institution in mainland China.
    </p>
</div>
</li>
<li class="honor-item">
<span class="honor-year">
    2024
   </span>
<div class="honor-content">
    Youth Innovation Promotion Association, CAS
   </div>
</li>
<li class="honor-item">
<span class="honor-year">
    2024
   </span>
<div class="honor-content">
    Outstanding Researcher, ICT, CAS
   </div>
</li>
<li class="honor-item">
<span class="honor-year">
    2022
   </span>
<div class="honor-content">
    New Hundred Stars Talent Program, ICT, CAS
   </div>
</li>
<li class="honor-item">
<span class="honor-year">
    2021
   </span>
<div class="honor-content">
    Outstanding Researcher, ICT, CAS
   </div>
</li>
</ul>
<h3 class="honors-group-title">
  Doctoral Honors
 </h3>
<ul class="honors-list">
<li class="honor-item honor-featured">
<span class="honor-year">
    2020
   </span>
<div class="honor-content">
<a class="honor-title" href="https://www.ccf.org.cn/yxbsxwlwjtm/2021-01-14/721439.shtml">
     China Computer Federation (CCF) Outstanding Doctoral
        Dissertation Award Nomination
    </a>
<p class="honor-description">
     For my Ph.D. thesis,
     <em>Research on Deep Sequence Model for Text Generation</em>.</p>
<p class="honor-note">
     Established by CCF to recognize outstanding doctoral research in China that advances computer science and addresses theoretical and practical challenges.
    </p>
</div>
</li>
<li class="honor-item">
<span class="honor-year">
    2019
   </span>
<div class="honor-content">
    President Award of Chinese Academy of Sciences
   </div>
</li>
<li class="honor-item">
<span class="honor-year">
    2018
   </span>
<div class="honor-content">
    Special Award of the Director of the Institute of
          Computing Technology, CAS
   </div>
</li>
<li class="honor-item">
<span class="honor-year">
    2018
   </span>
<div class="honor-content">
    National Scholarship for Doctoral Students
   </div>
</li>
<li class="honor-item">
<span class="honor-year">
    2018
   </span>
<div class="honor-content">
    Excellent Paper Award, Chinese Conference on
          Information Retrieval (CCIR 2018)
   </div>
</li>
</ul>
</section>
<section aria-labelledby="services-heading" class="home-section">
<h2 id="services-heading">Academic Service</h2>
<dl class="service-list">
<div>
<dt>Senior Program Committee / Area Chair</dt>
<dd>SIGIR, ACL, WebConf, AAAI, CIKM</dd>
</div>
<div>
<dt>Reviewer</dt>
<dd>
          TOIS, TKDE, TPAMI, ICLR, NeurIPS, KDD, WebConf,
          WSDM, EMNLP, CVPR, NAACL, ECIR, etc.
        </dd>
</div>
</dl>
</section>
</div>
