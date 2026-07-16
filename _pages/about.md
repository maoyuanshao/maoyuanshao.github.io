---
permalink: /
title: "maoyuanshao"
layout: academic-home
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section id="about-me" class="home-section home-intro">
  <p>
    Hi! I am currently a junior undergraduate student at Minzu University of China.
    My academic interests include artificial intelligence, data science, and interdisciplinary research.
    I am interested in building reliable computational methods and applying them to real-world research problems.
  </p>
  <p>
    I am actively looking for opportunities to collaborate on research projects. Please feel free to contact me by email if you are interested in my work.
  </p>
</section>

<section id="news" class="home-section">
  <h2>News</h2>
  <ul>
    <li><strong>2026.02:</strong> &#127881;&#127881; My first-authored paper, <em>CAPT: Confusion-Aware Prompt Tuning for Reducing Vision-Language Misalignment</em>, has been accepted by the main conference of CVPR 2026, with the paper available on <a href="https://arxiv.org/abs/2603.02557">arXiv</a> and the code available on <a href="https://github.com/greatest-gourmet/CAPT">GitHub</a>.</li>
    <li><strong>2025.08:</strong> &#127881;&#127881; My first co-first-authored paper, <em>Spotlighter: Revisiting Prompt Tuning from a Representative Mining View</em>, has been accepted by EMNLP 2025. The paper is available on <a href="https://arxiv.org/abs/2509.00905">arXiv</a>, and the code is available on <a href="https://github.com/greatest-gourmet/Spotlighter">GitHub</a>.</li>
  </ul>
</section>

<section id="publications" class="home-section">
  <h2>Publications</h2>
  <!-- <p class="publication-note">Please replace this section with your real publications. A recommended format is:</p> -->

  <div class="publication-item">
    <div class="publication-thumb">
      <img src="/images/CVPR2026.png" alt="Publication preview">
      <span>CVPR26</span>
    </div>
    <div class="publication-body">
      <h3>CAPT: Confusion-Aware Prompt Tuning for Reducing Vision-Language Misalignment</h3>
      <p><strong>Maoyuan Shao</strong>,Yutong Gao,Xinyang Huang,Lijuan Sun,Guoshun Nan,Chuang Zhu</p>
      <p class="publication-venue"><em>Computer Vision and Pattern Recognition Conference(CVPR)</em>, 2026</p>
      <p class="publication-links">
        <a href="https://arxiv.org/abs/2603.02557">[paper]</a>
        <a href="https://github.com/greatest-gourmet/CAPT">[code]</a>
        <!-- <a href="/files/bibtex1.bib">[bibtex]</a> -->
      </p>
      <p>Current vision-language models such as CLIP suffer from persistent confusion patterns among similar categories and cross-modal semantic misalignment. To address this, we construct a Confusion Bank from misclassified samples to capture stable confusion structures, and further model multi-granularity confusion features from both semantic (SEM) and sample (SAM) perspectives. These features are then unified and integrated through a Multi-Granularity Discrepancy Expert (MGDE) for confusion-aware reasoning. As a result, the method effectively resolves most confusing category pairs and significantly improves fine-grained discrimination and generalization performance across 11 benchmark datasets.
</p>
    </div>
    
  </div>

  <div class="publication-item">
    <div class="publication-thumb">
      <img src="/images/EMNLP2025.png" alt="Publication preview">
      <span>EMNLP25</span>
    </div>
    <div class="publication-body">
      <h3>Spotlighter: Revisiting Prompt Tuning from a Representative Mining View</h3>
      <p>Yutong Gao*, <strong>Maoyuan Shao*</strong>(Equally Contribute), Xinyang Huang, Chuang Zhu, Lijuan Sun, Yu Weng, Xuan Liu, Guoshun Nan</p> 
      <p class="publication-venue"><em>Conference on Empirical Methods in Natural Language Processing (EMNLP)</em>, 2025</p>
      <p class="publication-links">
        <a href="https://arxiv.org/abs/2509.00905">[paper]</a>
        <a href="https://github.com/greatest-gourmet/Spotlighter">[code]</a>
      </p>
      <p>In prompt tuning for vision-language models such as CLIP, redundant features often introduce noise and create computational bottlenecks. To address this, we propose a lightweight token selection framework, <strong>Spotlighter</strong>, which preserves high-activation tokens from both sample-level and semantic-level perspectives. It further incorporates a semantic memory bank and a two-stage ranking mechanism to dynamically fuse core features and compensate for missing semantics. As a result, the method introduces only 21 additional parameters, achieves up to a 11.19% improvement in harmonic mean (HM) accuracy, and increases average inference speed by 0.8K FPS.
</p>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-thumb">
      <img src="/images/mode.png" alt="Publication preview">
      <span>Neurocomputing</span>
    </div>
    <div class="publication-body">
      <h3>MoDe: Multi-modal Discriminative Priors for Prompt Tuning</h3>
      <p>Xinyang Huang, Chuang Zhu, <strong>Maoyuan Shao</strong>, Zekuan Yu</p>
      <p class="publication-venue"><em>Neurocomputing</em></p>
      <!-- <p class="publication-links">
        <a href="https://arxiv.org/abs/2509.00905">[paper]</a>
        <a href="https://github.com/greatest-gourmet/Spotlighter">[code]</a>
      </p> -->
      <p>CLIP suffers from limited discriminative capability in cross-category generalization due to its over-reliance on global representations while overlooking fine-grained local details. To address this, we propose MoDe, a multimodal prior-driven framework that enhances feature representation and generalization through Multimodal Knowledge Injection (MKI), Vision Prior Enhancement (VPE) for global-local feature fusion, and Knowledge-Guided Optimization (KGO). Extensive experiments on 11 datasets demonstrate that MoDe achieves 85.45% accuracy on Base-to-New tasks, significantly improving discriminability and cross-domain generalization.
</p>
    </div>
  </div>


</section>



<section id="education" class="home-section">
  <h2>Educations</h2>
  <ul>
    <li><strong>2023.09-present:</strong> Undergraduate student in Data Science and Big Data Technology, <a href="https://xingong.muc.edu.cn/">School of Information Engineering, Minzu University of China</a>.</li>
  </ul>
</section>

<section id="internships" class="home-section">
  <h2>Internships</h2>
  <ul>

    <li><strong>2025:</strong> <a href="https://cmpdc.iphy.ac.cn/">Science Data Center for Condensed Matter Physics, Institute of Physics, Chinese Academy of Sciences</a>.</li>
    <li><strong>2024:</strong> <a href="https://ai.bupt.edu.cn/">School of Artificial Intelligence, Beijing University of Posts and Telecommunications</a>.</li>
  </ul>
</section>

<section id="competitions" class="home-section">
  <h2>Competitions</h2>
  <ul>
    <li>The 27th China Robotics and Artificial Intelligence Competition, <span class="award-highlight">National First Prize</span>.</li>
    <li>The 8th China University Intelligent Robot Creative Competition, <span class="award-highlight">National Second Prize</span>.</li>
    <li>"Youth Innovation Beijing" 2025 "Challenge Cup" Capital College Students' Extracurricular Academic Science and Technology Works Competition, <span class="award-highlight">Beijing First Prize</span>.</li>
  </ul>
</section>

<section id="service" class="home-section">
  <h2>Service</h2>
</section>
