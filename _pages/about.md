---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>

/* ---------- Intro ---------- */

.lab-intro {
  margin-bottom: 1.2rem;
}

.lab-intro p {
  font-size: 1.02em;
  line-height: 1.75;
  color: #444;
}


/* ---------- DILAB × Chacha ---------- */

.dilab-hero {
  text-align: center;
  margin: 1.0rem auto 2.5rem;
}

.dilab-hero img {
  display: block;
  width: 100%;
  max-width: 620px;
  height: auto;
  margin: 0 auto;
}


/* ---------- Research ---------- */

.research-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 14px;
  margin: 1.2rem 0 2.6rem;
}

.research-card {
  position: relative;
  overflow: hidden;
  padding: 20px 20px 18px;
  background: #f7fafc;
  border: 1px solid #e5edf3;
  border-radius: 10px;
  transition: transform 0.18s ease,
              box-shadow 0.18s ease,
              border-color 0.18s ease;
}

.research-card::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 3px;
  background: #3976a8;
  opacity: 0.75;
}

.research-card:hover {
  transform: translateY(-2px);
  border-color: #d4e3ee;
  box-shadow: 0 7px 18px rgba(35, 79, 115, 0.09);
}

.research-card h3 {
  margin: 0 0 7px;
  color: #234f73;
  font-size: 1.02em;
  font-weight: 600;
}

.research-card p {
  margin: 0;
  color: #626b73;
  font-size: 0.91em;
  line-height: 1.55;
}


/* ---------- News ---------- */

.news-list {
  margin: 1rem 0 2.8rem;
}

.news-item {
  margin-bottom: 0.65rem;
  line-height: 1.55;
  color: #4d555c;
}

.news-date {
  display: inline-block;
  min-width: 72px;
  color: #3976a8;
  font-weight: 600;
}


/* ---------- Join Us ---------- */

.join-text {
  color: #4d555c;
  line-height: 1.7;
}

.openlab-link {
  margin: 18px 0 20px;
  padding: 13px 16px;
  background: #f4f8fb;
  border-left: 3px solid #3976a8;
  border-radius: 4px;
  font-size: 0.95em;
}

.openlab-link a {
  color: #2563a6;
  font-weight: 600;
  text-decoration: none;
}

.openlab-link a:hover {
  text-decoration: underline;
}


/* ---------- Section headings ---------- */

.page__content h1 {
  color: #234f73;
  font-weight: 600;
}

.section-title {
  margin-top: 2.7rem;
  margin-bottom: 1rem;
  padding-bottom: 0.45rem;
  border-bottom: 2px solid #e3edf4;
  color: #234f73;
  font-size: 1.45em;
  font-weight: 600;
}

.news-more {
  margin-top: 0.6rem;
}

.news-more summary {
  display: inline-block;
  cursor: pointer;
  color: #3976a8;
  font-size: 0.9em;
  font-weight: 600;
  list-style: none;
}

.news-more summary::-webkit-details-marker {
  display: none;
}

.news-more summary::after {
  content: " ↓";
}

.news-more[open] summary::after {
  content: " ↑";
}

.news-more-content {
  margin-top: 0.9rem;
}

/* ---------- Mobile ---------- */

@media (max-width: 650px) {

  .research-grid {
    grid-template-columns: 1fr;
  }

  .dilab-hero img {
    max-width: 100%;
  }

  .news-date {
    min-width: 68px;
  }
}

.lab-header {
  margin: 0.4rem 0 1.1rem;
}

.lab-kicker {
  margin-bottom: 0.35rem;
  color: #3976a8;
  font-size: 0.75em;
  font-weight: 700;
  letter-spacing: 0.12em;
}

.lab-header h1 {
  margin: 0 0 0.55rem;
  color: #234f73;
  font-size: 2.15em;
  font-weight: 650;
  letter-spacing: -0.02em;
}

.lab-header p {
  max-width: 720px;
  margin: 0;
  color: #59636b;
  font-size: 1.05em;
  line-height: 1.65;
}

</style>


<div class="lab-header">
  <div class="lab-kicker">CHUNGNAM NATIONAL UNIVERSITY</div>
  <h1>Data Intelligence Lab</h1>
</div>

<div class="lab-intro">
<p>
We are the <strong>Data Intelligence Lab (DILAB)</strong> at the
Department of Computer Science and Engineering, Chungnam National University, Korea 🇰🇷.
Our research focuses on <strong>graph machine learning</strong>,
<strong>trustworthy AI</strong>, <strong>recommender systems & IR</strong>,
and <strong>GraphRAG & LLMs</strong>.
</p>
</div>


<div class="dilab-hero">
  <img src="/images/dilab-chacha.png"
       alt="DILAB — Data Intelligence Lab at Chungnam National University">
</div>


<div class="section-title">🔬 Research</div>

<div class="research-grid">

<div class="research-card">
<h3>Graph Machine Learning</h3>
<p>
Representation learning and machine learning for complex
graph-structured data.
</p>
</div>

<div class="research-card">
<h3>Trustworthy AI</h3>
<p>
Fairness, uncertainty quantification, and reliability
of machine learning models.
</p>
</div>

<div class="research-card">
<h3>Recommender Systems & IR</h3>
<p>
Learning and retrieval methods for personalized and
knowledge-rich information systems.
</p>
</div>

<div class="research-card">
<h3>GraphRAG & LLMs</h3>
<p>
Graph-enhanced retrieval, reasoning, and knowledge
augmentation for large language models.
</p>
</div>

</div>


<div class="section-title">🔥 News</div>

<div class="news-list">

<!-- 항상 보이는 최신 News -->

<div class="news-item">
<span class="news-date">2026.08</span>
🎉 Our work on <strong>few-shot learning on text-attributed graphs</strong>
was accepted to <em>CIKM 2026</em>.
</div>

<div class="news-item">
<span class="news-date">2026.08</span>
🎓 Congratulations to <strong>Soyoung</strong> on completing her Ph.D.!
</div>

<div class="news-item">
<span class="news-date">2026.07</span>
🎉 Our work on <strong>uncertainty quantification for GNNs</strong>
was presented at <em>ICML 2026</em>.
</div>

<div class="news-item">
<span class="news-date">2026.07</span>
🎉 Two papers on <strong>GraphRAG</strong> and
<strong>recommendation</strong> were presented at <em>SIGIR 2026</em>.
</div>

<div class="news-item">
<span class="news-date">2026.03</span>
🎉 Our work on <strong>visual token pruning for multimodal LLMs</strong>
was presented at <em>WACV 2026</em>.
</div>


<!-- 이전 News -->

<details class="news-more">
<summary>Show more</summary>

<div class="news-more-content">

<div class="news-item">
<span class="news-date">2026.02</span>
🎉 Our work on <strong>LLM-enhanced graph representation learning</strong>
was presented at <em>WSDM 2026</em>.
</div>

<div class="news-item">
<span class="news-date">2026.02</span>
🎓 Congratulations to <strong>Jongmin</strong> on completing his Ph.D.
and <strong>Hyewon</strong> on completing her M.S.!
</div>

<div class="news-item">
<span class="news-date">2025.11</span>
🏆 DILAB placed <strong>4th and received a Special Award</strong>
in the <em><a href="https://alibaba-international-cikm2025.github.io/">CIKM 2025 AnalytiCup Alibaba Challenge</a></em>.
</div>

<div class="news-item">
<span class="news-date">2025.11</span>
🏆 DILAB won <strong>2nd Place</strong> in the
<em>ScienceON AI Challenge 2025</em>.
</div>

<div class="news-item">
<span class="news-date">2025.11</span>
🎉 Two papers on <strong>fair graph learning</strong> and
<strong>signed community detection</strong> were presented at <em>CIKM 2025</em>.
</div>

<div class="news-item">
<span class="news-date">2025.08</span>
🎓 Congratulations to <strong>Soohwan</strong> and <strong>Jeongseon</strong>
on completing their Ph.D. degrees!
</div>

<div class="news-item">
<span class="news-date">2025.06</span>
🎉 Our work on <strong>zero-shot industrial anomaly segmentation</strong>
was presented at <em>PAKDD 2025</em>.
</div>

<div class="news-item">
<span class="news-date">2025.03</span>
🎉 Our work on <strong>in-context learning in text-attributed graphs</strong>
was presented at <em>EDBT 2025</em>.
</div>

<div class="news-item">
<span class="news-date">2025.02</span>
🎓 Congratulations to <strong>Hwan</strong> on completing his Ph.D.
and <strong>Mingyu</strong> on completing his M.S.!
</div>

</div>

</details>

</div>


<div class="section-title">📢 Join Us</div>

<div class="join-text">
We welcome motivated students interested in learning from complex and structured data,
from fundamental methods to real-world applications.
We currently have <strong>multiple openings for M.S. and Ph.D. students</strong>.
To apply, please send a CV with a brief introduction and motivation for joining DILAB.
</div>

<div class="openlab-link">
📘 <a href="https://drive.google.com/drive/folders/1pWMrR6roJSVIM6VxuWWHNx3PQeg9yfk0?usp=sharing">
DILAB 2026 Open Lab Materials →
</a>
</div>

<div class="join-text">
For research collaborations, feel free to reach out to
<a href="https://sungsu-lim.github.io/"><strong>Prof. Sungsu Lim</strong></a>
at <a href="mailto:sungsu@cnu.ac.kr">sungsu@cnu.ac.kr</a>.
</div>
