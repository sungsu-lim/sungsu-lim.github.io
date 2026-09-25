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
/* Section headings */
.page__content h1 {
  margin-top: 2.4em;
  margin-bottom: 0.9em;
  padding-bottom: 0.35em;
  border-bottom: 2px solid #e3edf4;
  color: #234f73;
  font-size: 1.45em;
  font-weight: 700;
}

/* Lists */
.page__content li {
  margin-bottom: 0.32em;
}

/* Links */
.page__content a {
  text-decoration: none;
}

.page__content a:hover {
  text-decoration: underline;
}

/* Publication titles */
#publications ~ h3 {
  margin-top: 1.35em;
  margin-bottom: 0.35em;
  color: #252a2e;
  font-size: 1.02em;
  line-height: 1.45;
}

/* Publication separators */
.page__content hr {
  margin: 1.25em 0;
  border: 0;
  border-top: 1px solid #edf0f2;
}

/* Thumbnail blocks */
.feature-item {
  display: flex;
  gap: 1.25em;
  align-items: flex-start;
  margin: 0 0 1.7em 0;
}

.feature-thumb {
  position: relative;
  flex: 0 0 180px;
  width: 180px;
}

.venue-badge {
  position: absolute;
  top: 7px;
  left: 7px;
  z-index: 2;

  padding: 3px 7px;
  background: rgba(255, 255, 255, 0.94);
  border: 1px solid #d9e0e5;
  border-radius: 4px;

  color: #234f73;
  font-size: 0.68em;
  font-weight: 700;
  line-height: 1.2;
  letter-spacing: 0.02em;
}

.feature-thumb img {
  width: 100%;
  height: 125px;
  object-fit: contain;
  object-position: center;
  border-radius: 5px;
  border: 1px solid #e5e8eb;
  background: #fff;
}

.feature-content {
  flex: 1;
  min-width: 0;
}

.feature-content h3 {
  margin: 0 0 0.35em 0;
  color: #252a2e;
  font-size: 1.02em;
  line-height: 1.45;
}

.feature-content p {
  margin: 0 0 0.35em 0;
}

@media (max-width: 600px) {
  .feature-item {
    display: block;
  }

  .feature-thumb {
    width: 100%;
    margin-bottom: 0.7em;
  }

  .feature-thumb img {
    width: 100%;
    height: auto;
    max-height: 180px;
    object-fit: cover;
  }
}
  
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am an Associate Professor of [Computing and AI](https://comai.cnu.ac.kr/) at Chungnam National University (CNU), where I lead the [Data Intelligence Lab (DILAB)](https://cnudi.github.io/).

I received my Ph.D. in Data Science from KAIST, where I was advised by Prof. [Jae-Gil Lee](https://www.kaistdmlab.org/jaegil) and Prof. [Kyomin Jung](https://milab.snu.ac.kr/kjung/). My current research interests include graph machine learning, trustworthy AI, GraphRAG and LLM applications, and recommender systems, with broader interests in the theory and applications of data modeling, mining, and learning.


# 🔥 News

- **2026.09** · Our paper on traffic forecasting robust to aperiodicity was accepted to [NeurIPS 2026](https://neurips.cc/Conferences/2026).
- **2026.08** · Our paper on few-shot node classification on text-attributed graphs was accepted to [CIKM 2026](https://cikm2026.diag.uniroma1.it/).
- **2026.07** · Our paper on quantile-free uncertainty quantification for GNNs was presented at [ICML 2026](https://icml.cc/Conferences/2026).
- **2026.07** · Two papers on GraphRAG and recommendation were presented at [SIGIR 2026](https://sigir2026.org/).
- **2026.03** · Our paper on visual token pruning for multimodal LLMs was presented at [WACV 2026](https://wacv.thecvf.com/Conferences/2026).
- **2026.02** · Our paper on LLM-enhanced graph representation learning was presented at [WSDM 2026](https://wsdm-conference.org/2026/).
- **2026.01** · I received the CNU President's Commendation for Outstanding Faculty Member.


# 🔬 Research Interests

- Graph Machine Learning
- Trustworthy and Reliable AI
- GraphRAG and LLM Applications
- Recommender Systems and Information Retrieval


<span class='anchor' id='publications'></span>

# 📝 Recent Publications

<div class="feature-item">
  <div class="feature-thumb">
    <span class="venue-badge">ICML</span>
    <img src="/images/publications/qpignn.png" alt="QpiGNN">
  </div>
  <div class="feature-content">
    <h3>Quantile-Free Uncertainty Quantification in Graph Neural Networks</h3>
    <p>Soyoung Park, Hwanjun Song, and <strong>Sungsu Lim</strong>*</p>
    <p><em>ICML 2026</em> · <a href="https://openreview.net/forum?id=zlU90YE4EJ">Regular Paper</a> · Acceptance Rate: 26.6%</p>
  </div>
</div>

<div class="feature-item">
  <div class="feature-thumb">
    <span class="venue-badge">SIGIR</span>
    <img src="/images/publications/star.png" alt="StAR">
  </div>
  <div class="feature-content">
    <h3>StAR: Adaptive Structure-Aware Reranking for Semantic-Structural Alignment in GraphRAG</h3>
    <p>Junghyun Oh and <strong>Sungsu Lim</strong>*</p>
    <p><em>SIGIR 2026</em> · <a href="https://dl.acm.org/doi/10.1145/3805712.3809897">Short Paper</a> · Acceptance Rate: 26.7%</p>
  </div>
</div>

<div class="feature-item">
  <div class="feature-thumb">
    <span class="venue-badge">SIGIR</span>
    <img src="/images/publications/discorec.png" alt="DisCoRec">
  </div>
  <div class="feature-content">
    <h3>DisCoRec: Disentangled Conformity-aware Recommendation with LLM-Guided Multi-View Learning</h3>
    <p>Minkyung Song, Soyoung Park*, and <strong>Sungsu Lim</strong>*</p>
    <p><em>SIGIR 2026</em> · <a href="https://dl.acm.org/doi/10.1145/3805712.3809854">Short Paper</a> · Acceptance Rate: 26.7%</p>
  </div>
</div>

<div class="feature-item">
  <div class="feature-thumb">
    <span class="venue-badge">WACV</span>
    <img src="/images/publications/mr-pruner.png" alt="MR-Pruner">
  </div>
  <div class="feature-content">
    <h3>MR-Pruner: Training-free Multi-resolution Visual Token Pruning for Multi-modal Large Language Models</h3>
    <p>Seunghoon Han, Hyewon Lee, Soyoung Park, Jong-Ryul Lee*, and <strong>Sungsu Lim</strong>*</p>
    <p><em>WACV 2026</em> · <a href="https://openaccess.thecvf.com/content/WACV2026/papers/Han_MR-Pruner_Training-free_Multi-resolution_Visual_Token_Pruning_for_Multi-modal_Large_Language_WACV_2026_paper.pdf">Regular Paper</a> · Acceptance Rate: 33.7%</p>
  </div>
</div>


# 🎖 Honors and Awards

- *2026*: CNU Teaching Award Candidate (Top 7% among faculty; selection in progress)
- *2025*: CNU President's Commendation for Outstanding Faculty Member
- *2023–2026*: Outstanding Young Researchers Grant, NRF of Korea
- *2023*: [KSEE Young Engineering Educator Award](https://www.ksee.org/html/?pmode=prize)
- *2022*: [NVIDIA Applied Research Accelerator Award](https://www.nvidia.com/en-us/industries/higher-education-research/applied-research-program/)
- *2022*: [CNU Teaching Award](https://plus.cnu.ac.kr/html/kr/sub01/sub01_01071504.html) (Top 1% among faculty)
- *2021*: Commissioner's Citation, Korea Customs Service
- *2021*: Best Paper Award (3rd Place), IEEE BigComp
- *2016*: Qualcomm Innovation Award
- *2014*: KT ICT Award, Big Data Analysis Contest (Big Contest)
- *2012*: Nomination Award, Microsoft Research Asia Fellowship
- *2012*: Honorable Mention, Samsung Humantech Paper Award


# 💼 Experience

- *2023–present*: Associate Professor, Chungnam National University
- *2024–2025*: Advisor & Visiting Researcher, [Nota AI](https://www.nota.ai/), Sunnyvale, CA, USA
- *2020-2024*: Advisor, [Institute of Science Education for the Gifted](https://gifted.cnu.ac.kr/gifted/), Chungnam National University
- *2018–2023*: Assistant Professor, Chungnam National University
- *2013–2016*: Research Assistant, Data Mining Lab., KAIST (Advisor: [Jae-Gil Lee](https://www.kaistdmlab.org/jaegil))
- *2010–2013*: Research Assistant, Applied Algorithm Lab., KAIST (Advisor: [Kyomin Jung](https://milab.snu.ac.kr/kjung/))
- *2009-2011*: Research Assistant, Statistical Lab., KAIST (Advisor: [Sung-Ho Kim](https://mathsci.kaist.ac.kr/~slki/index.files/prof.htm))


# 📖 Education

- *2016*: Ph.D. in [Data Science, KAIST](https://gsds.kaist.ac.kr/)  
- *2011*: M.S. in [Mathematical Sciences, KAIST](https://mathsci.kaist.ac.kr/home/)
- *2009*: B.S. in [Mathematical Sciences, KAIST](https://mathsci.kaist.ac.kr/home/)
- *2004*: Chungnam Science High School (early graduation)


# 👥 Data Intelligence Lab

<div class="feature-item">
  <div class="feature-thumb">
    <a href="https://cnudi.github.io/">
      <img src="/images/dilab.png" alt="Data Intelligence Lab">
    </a>
  </div>
  <div class="feature-content">
    <p>I have led the <a href="https://cnudi.github.io/">Data Intelligence Lab (DILAB)</a> since 2018. Our research focuses on graph machine learning, trustworthy AI, GraphRAG and LLMs, and recommender systems.</p>
    <p>📢 We are recruiting graduate students. Please contact me at <a href="mailto:sungsu@cnu.ac.kr">sungsu@cnu.ac.kr</a> if interested.</p>
  </div>
</div>


# 🎓 Teaching @ CNU

- Graduate: Machine Learning with Graphs, Lightweight Deep Learning, Topics in Data Mining, Advanced Algorithms, etc.

- Undergraduate: Deep Learning, Data Science, Math for AI, Numerical Analysis, Linear Algebra, Discrete Math, etc.


# 🤝 Professional Service

- Organizing Committee: [KDD 2026](https://kdd2026.kdd.org/acm-kdd-2026-organizing-committee/) (Poster Chair), [BigComp 2027](https://bigcomp2027-website.pages.dev/organization/) (Social Media Chair), [KCC 2026](https://www.kiise.or.kr/conference/main/getContent.do?CC=kcc&CS=2026&content_no=2417&PARENT_ID=010100), [KCC 2022](https://www.kiise.or.kr/conference/main/getContent.do?CC=kcc&CS=2022&content_no=1525&PARENT_ID=010700), etc.
- Program Committee: AAAI, SIGIR, CIKM, DASFAA, PAKDD, ECAI, BigData, BigComp, KSIAM Spring/Fall, etc.
- Editorial Board Member: Frontiers in Big Data, Journal of KIISE, Communications of KIISE, etc.
- Reviewer: Proceedings of the IEEE, IEEE TKDE, VLDB Journal, Information Sciences, ML Conferences, etc.
- Advisory Board Member: [Daejeon AI Innovation Strategy](https://n.news.naver.com/article/056/0012255252?sid=102), Ministry of Data and Statistics, KISTI DataON, etc.


# 🎤 Invited Talks

- *2026*: Graph Learning: Representation, Recommendation, Reasoning, and Reliability, UNIST (upcoming)
- *2026*: Generative & Trustworthy AI, Chungnam National University Hospital
- *2026*: Trustworthy AI, Korea Astronomy and Space Science Institute
- *2025*: Uncertainty Quantification in GNNs, Winter Conference of Korean Statistical Society
- *2025*: Generative AI - LLM & RAG, Public Procurement Service
- *2024*: Heterogeneous Graph Embedding, Kangwon National University
- *2022*: Heterogeneous Graph Embedding, UNIST EE
- *2021*: Multi-aspect Graph Embedding, KSIAM Annual Meeting
- *2021*: Learning on Graphs, Univ. of Seoul AI
- *2020*: Learning on Graphs, IBS Data Science Group
- *2020*: Detecting Communities and Anomalies in Large Real-world Graphs, IEEE BigComp (Tutorial)
- *2019*: Community Detection in Graphs, Kyung Hee University CS
- *2019*: Learning on Graphs, Korea-Japan Database Workshop
- *2019*: Graph Representation Learning, KCC (Tutorial)
