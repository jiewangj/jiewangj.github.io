---
permalink: /
title: "Personalized AI & Recommender Systems Researcher"
author_profile: true
excerpt: "Jie Wang researches personalized AI, recommender systems, large language models, reinforcement learning, and multimodal retrieval."
redirect_from:
  - /about/
  - /about.html
---

<div class="home-shell">

<div class="opportunity-kicker">
  <span aria-hidden="true">📢</span>
  <span>Open to researcher and applied scientist opportunities</span>
</div>

<p class="home-lede">
I am <strong>Jie Wang</strong>, a researcher building personalized AI systems across
large language models, reinforcement learning, recommender systems, and multimodal
retrieval. My Ph.D. research at the <strong>University of Glasgow</strong> connects
method development with real user needs, while my work at <strong>Amazon</strong>
and <strong>Tencent</strong> has applied these ideas to large-scale interaction and
video data. I have authored or co-authored 14+ papers at venues including SIGIR,
WSDM, CIKM, ECIR, IEEE TKDE, and IEEE TPAMI.
</p>

<div class="home-actions">
  <a class="home-button home-button--primary" href="https://github.com/jieWANGforwork" target="_blank" rel="noopener">View GitHub</a>
  <a class="home-button" href="https://scholar.google.com/citations?user=dK1hORsAAAAJ" target="_blank" rel="noopener">Google Scholar</a>
  <a class="home-button" href="/files/CV.pdf" target="_blank" rel="noopener">Download CV</a>
</div>

<section class="home-section" id="research">
  <h2>Research Focus</h2>
  <p class="section-intro">I study how intelligent systems can model evolving user intent, balance competing objectives, and retrieve the right content efficiently.</p>

  <div class="focus-grid">
    <article class="focus-card">
      <span class="card-label">Personalization</span>
      <h3>Personalized AI</h3>
      <p>User-aware learning and generation that adapt to individual preferences, histories, and goals.</p>
    </article>
    <article class="focus-card">
      <span class="card-label">Decision making</span>
      <h3>LLMs & Reinforcement Learning</h3>
      <p>Language models as state, reward, action, and user-simulation components for safer policy learning.</p>
    </article>
    <article class="focus-card">
      <span class="card-label">Beyond accuracy</span>
      <h3>Multi-objective Recommendation</h3>
      <p>Sequential recommenders that jointly consider relevance, diversity, novelty, and serendipity.</p>
    </article>
    <article class="focus-card">
      <span class="card-label">Multimodality</span>
      <h3>Video & Cross-modal Retrieval</h3>
      <p>Scalable retrieval and recommendation from visual, textual, temporal, and behavioral signals.</p>
    </article>
  </div>
</section>

<section class="home-section" id="current-research">
  <h2>Current Research</h2>
  <p class="section-intro">Recent projects extend personalized recommendation into efficient, fine-grained video understanding and retrieval.</p>

  <div class="current-grid">
    <article class="current-card">
      <span class="card-label">Scalable video retrieval</span>
      <h3>Composed Video Retrieval with Semantic IDs</h3>
      <p>A residual-quantized retrieval pipeline combines frozen vision-language representations, a shared Q-Former, and beam search for scalable composed-video retrieval.</p>
      <div class="metric-row">
        <span class="metric-chip">16.07× faster at 1M scale</span>
        <span class="metric-chip">36.85× less storage</span>
        <span class="metric-chip">86.81% mean Recall</span>
      </div>
    </article>
    <article class="current-card">
      <span class="card-label">Personalized video moments</span>
      <h3>User-aware E-commerce Video Recommendation</h3>
      <p>A two-stage system first retrieves candidate product videos, then identifies personalized moments through user-aware visual-temporal matching.</p>
      <div class="metric-row">
        <span class="metric-chip">100-user study</span>
        <span class="metric-chip">36% faster discovery</span>
        <span class="metric-chip">23% less task time</span>
      </div>
    </article>
  </div>
</section>

<section class="home-section" id="publications">
  <h2>Selected Publications</h2>
  <p class="section-intro">Representative first-author work on LLM-driven recommendation, reinforcement learning, and multi-objective decision making.</p>

  <div class="paper-list">
    <article class="paper-card">
      <span class="paper-venue">WSDM 2025 · Full Paper</span><br>
      <a class="paper-title" href="https://doi.org/10.1145/3701551.3703496" target="_blank" rel="noopener">Large Language Model Driven Policy Exploration for Recommender Systems</a>
      <p class="paper-authors"><strong>Jie Wang</strong>, Alexandros Karatzoglou, Ioannis Arapakis, Joemon M. Jose</p>
      <p class="paper-summary">Uses LLM-simulated user feedback to pre-train exploratory recommendation policies and reduce deployment risk under distribution shift.</p>
      <div class="paper-links"><a href="https://doi.org/10.1145/3701551.3703496" target="_blank" rel="noopener">Paper ↗</a></div>
    </article>

    <article class="paper-card">
      <span class="paper-venue">IEEE TKDE 2025</span><br>
      <a class="paper-title" href="https://doi.org/10.1109/TKDE.2025.3582506" target="_blank" rel="noopener">Beyond Accuracy: Decision Transformers for Reward-Driven Multi-Objective Recommendations</a>
      <p class="paper-authors"><strong>Jie Wang</strong>, Alexandros Karatzoglou, Ioannis Arapakis, Joemon M. Jose, Xuri Ge</p>
      <p class="paper-summary">A decision-transformer framework for optimizing recommendation accuracy alongside diversity and novelty.</p>
      <div class="paper-links">
        <a href="https://doi.org/10.1109/TKDE.2025.3582506" target="_blank" rel="noopener">Paper ↗</a>
        <a href="https://github.com/jieWANGforwork/MODT" target="_blank" rel="noopener">Code ↗</a>
      </div>
    </article>

    <article class="paper-card">
      <span class="paper-venue">CIKM 2024 · Full Paper</span><br>
      <a class="paper-title" href="https://doi.org/10.1145/3627673.3679533" target="_blank" rel="noopener">Sparks of Surprise: Multi-objective Recommendations with Hierarchical Decision Transformers for Diversity, Novelty, and Serendipity</a>
      <p class="paper-authors"><strong>Jie Wang</strong>, Alexandros Karatzoglou, Ioannis Arapakis, Xin Xin, Xuri Ge, Joemon M. Jose</p>
      <p class="paper-summary">Hierarchical decision transformers balance relevance with diversity, novelty, and serendipity in sequential recommendation.</p>
      <div class="paper-links">
        <a href="https://doi.org/10.1145/3627673.3679533" target="_blank" rel="noopener">Paper ↗</a>
        <a href="https://github.com/jieWANGforwork/HDT" target="_blank" rel="noopener">Code ↗</a>
      </div>
    </article>

    <article class="paper-card">
      <span class="paper-venue">SIGIR 2024 · Full Paper</span><br>
      <a class="paper-title" href="https://doi.org/10.1145/3626772.3657767" target="_blank" rel="noopener">Reinforcement Learning-based Recommender Systems with Large Language Models for State, Reward, and Action Modeling</a>
      <p class="paper-authors"><strong>Jie Wang</strong>, Alexandros Karatzoglou, Ioannis Arapakis, Joemon M. Jose</p>
      <p class="paper-summary">Introduces LLM-based state, reward, and action modeling inside a reinforcement-learning recommendation pipeline.</p>
      <div class="paper-links">
        <a href="https://doi.org/10.1145/3626772.3657767" target="_blank" rel="noopener">Paper ↗</a>
        <a href="https://github.com/jieWANGforwork/LEA" target="_blank" rel="noopener">Code ↗</a>
      </div>
    </article>

    <article class="paper-card">
      <span class="paper-venue">ECIR 2024 · Full Paper</span><br>
      <a class="paper-title" href="https://doi.org/10.1007/978-3-031-56027-9_19" target="_blank" rel="noopener">Empowering Legal Citation Recommendation via Efficient Instruction-Tuning of Pre-trained Language Models</a>
      <p class="paper-authors"><strong>Jie Wang</strong>, Kanha Bansal, Ioannis Arapakis, Xuri Ge, Joemon M. Jose</p>
      <p class="paper-summary">Applies efficient instruction tuning to improve legal citation recommendation with pre-trained language models.</p>
      <div class="paper-links"><a href="https://doi.org/10.1007/978-3-031-56027-9_19" target="_blank" rel="noopener">Paper ↗</a></div>
    </article>
  </div>

  <div class="home-actions">
    <a class="home-button" href="https://scholar.google.com/citations?user=dK1hORsAAAAJ" target="_blank" rel="noopener">See complete publication record</a>
  </div>
</section>

<section class="home-section" id="experience">
  <h2>Experience</h2>
  <p class="section-intro">Research experience spanning academic method development, industrial-scale systems, and user-centered evaluation.</p>

  <div class="experience-list">
    <article class="experience-item">
      <div class="experience-date">Jul–Oct 2025</div>
      <div>
        <h3>Applied Scientist Intern</h3>
        <p class="experience-org">Amazon · Seattle, USA</p>
        <p class="experience-copy">Built and evaluated a two-stage personalized video-moment recommender, combining large-scale candidate retrieval with user-aware visual-temporal matching.</p>
      </div>
    </article>
    <article class="experience-item">
      <div class="experience-date">Dec 2022–Jan 2025</div>
      <div>
        <h3>Teaching Assistant — AI & Machine Learning</h3>
        <p class="experience-org">University of Glasgow · Glasgow, UK</p>
        <p class="experience-copy">Led laboratory instruction, coursework support, assessment, and mentoring for master's and senior undergraduate students.</p>
      </div>
    </article>
    <article class="experience-item">
      <div class="experience-date">Dec 2021–May 2022</div>
      <div>
        <h3>Research Intern</h3>
        <p class="experience-org">Tencent · Shenzhen, China</p>
        <p class="experience-copy">Developed transferable multimodal recommendation models from 10 million user-feedback events and supported deployment on Tencent News.</p>
      </div>
    </article>
  </div>
</section>

<section class="home-section" id="news">
  <h2>Recent Highlights</h2>
  <div class="news-list">
    <div class="news-item"><span class="news-date">2026</span><span>Developing scalable composed-video retrieval with residual-quantized semantic IDs.</span></div>
    <div class="news-item"><span class="news-date">Jun 2025</span><span><em>Beyond Accuracy</em> published in IEEE Transactions on Knowledge and Data Engineering.</span></div>
    <div class="news-item"><span class="news-date">2025</span><span>Presented LLM-driven policy exploration for recommender systems at WSDM.</span></div>
    <div class="news-item"><span class="news-date">2024</span><span>Published first-author full papers at SIGIR, CIKM, and ECIR.</span></div>
  </div>
</section>

<section class="home-section" id="contact">
  <div class="contact-panel">
    <h2>Let’s connect</h2>
    <p>I am interested in research and applied-science opportunities involving personalization, recommender systems, LLMs, reinforcement learning, and multimodal retrieval.</p>
    <p><a href="mailto:j.wang.9@research.gla.ac.uk">Email</a> · <a href="https://github.com/jieWANGforwork" target="_blank" rel="noopener">GitHub</a> · <a href="https://www.linkedin.com/in/jie-wang-a05759250/" target="_blank" rel="noopener">LinkedIn</a></p>
  </div>
</section>

</div>
