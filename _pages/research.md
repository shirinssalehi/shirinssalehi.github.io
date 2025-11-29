---
title: "Research Experience"
permalink: /research/
layout: single
author_profile: true
---

## Research Experience

<div class="research-grid">

  <div class="research-card">
    <div class="research-logo-wrap">
      <img src="/images/tmulogo.jpg" alt="TMU logo" class="research-logo">
    </div>
    <h3>Assistant Professor</h3>
    <p class="research-org">Toronto Metropolitan University</p>
    <p class="research-dates">2025 – Present</p>
    <p>
      I conduct research on responsible AI, fairness in information retrieval, and neural ranking models,
      and supervise student projects on bias mitigation and evaluation in search systems.
    </p>
  </div>

  <div class="research-card">
    <div class="research-logo-wrap">
      <img src="/images/uoftlogo.png" alt="University of Toronto logo" class="research-logo">
    </div>
    <h3>Research Assistant, LS3 Lab</h3>
    <p class="research-org">University of Toronto</p>
    <p class="research-dates">2021 – 2025</p>
    <p>
      Worked on debiasing dense neural rankers and query performance prediction, with publications in
      SIGIR, ECIR, CIKM, EDBT, and MLJ.
    </p>
  </div>

  <div class="research-card">
    <div class="research-logo-wrap">
      <img src="/images/msr_logo.jpeg" alt="Microsoft Research logo" class="research-logo">
    </div>
    <h3>Research Scientist Intern</h3>
    <p class="research-org">Microsoft Research</p>
    <p class="research-dates">2022</p>
    <p>
      Contributed to the IGLU project on multimodal next-action prediction and collaborated on
      fair ranking methods to mitigate gender bias in neural ranking systems.
    </p>
  </div>

  <div class="research-card">
    <div class="research-logo-wrap">
      <img src="/images/railogo.jpg" alt="NSERC Responsible AI logo" class="research-logo">
    </div>
    <h3>Researcher</h3>
    <p class="research-org">NSERC Responsible AI</p>
    <p class="research-dates">2020 – 2021</p>
    <p>
      Organized and participated in seminars, talks, and panels on fairness, accountability,
      transparency, and ethics in AI and ML with a transdisciplinary perspective.
    </p>
  </div>

  <div class="research-card">
    <div class="research-logo-wrap">
      <img src="/images/partlogo.png" alt="Partdp.ai logo" class="research-logo">
    </div>
    <h3>NLP Research Scientist</h3>
    <p class="research-org">Partdp.ai</p>
    <p class="research-dates">2020 – 2021</p>
    <p>
      Worked on summarization, sentiment analysis, emotion detection, and market trend prediction
      using large-scale text analytics and neural NLP models.
    </p>
  </div>

</div>

<style>

/* ——— GRID ——— */
.research-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(290px, 1fr));
  gap: 2rem;
  margin-top: 1.5rem;
}

/* ——— CARD STYLE (Wix / Negara.me style) ——— */
.research-card {
  background: #ffffff;
  border-radius: 14px;
  padding: 1.8rem 1.6rem;
  box-shadow: 0 12px 28px rgba(0, 0, 0, 0.08);
  border: 1px solid #e8e8e8;
  transition: all 0.2s ease;
}

.research-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 18px 36px rgba(0, 0, 0, 0.12);
}

/* ——— LOGO STYLE ——— */
.research-logo-wrap {
  display: flex;
  justify-content: center;
  margin-bottom: 1.2rem;
}

.research-logo {
  max-height: 100px;   /* MUCH larger logos */
  max-width: 200px;
  width: auto;
  height: auto;
  object-fit: contain;
}

/* ——— TEXT ——— */
.research-card h3 {
  text-align: center;
  margin: 0.2rem 0 0.4rem 0;
  font-size: 1.2rem;
  font-weight: 600;
}

.research-org {
  text-align: center;
  font-weight: 500;
  color: #555;
  margin: 0;
  margin-bottom: 0.25rem;
}

.research-dates {
  text-align: center;
  margin: 0 0 1rem 0;
  font-size: 0.9rem;
  color: #777;
}

.research-card p {
  font-size: 0.95rem;
  line-height: 1.55;
}

</style>
