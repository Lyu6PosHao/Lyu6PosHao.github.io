---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .lzh-home {
    --ink: #1f2933;
    --muted: #5f6c7b;
    --line: #d9e2ec;
    --soft: #f7f9fb;
    --blue: #255f99;
    --green: #2f6f5e;
    --gold: #8a641d;
    color: var(--ink);
  }

  .lzh-hero {
    padding: 1.15rem 1.25rem;
    border: 1px solid var(--line);
    border-left: 5px solid var(--blue);
    border-radius: 8px;
    background: linear-gradient(180deg, #ffffff 0%, var(--soft) 100%);
    margin-bottom: 1.35rem;
  }

  .lzh-name {
    margin: 0 0 0.35rem;
    font-size: 1.55rem;
    line-height: 1.2;
    letter-spacing: 0;
  }

  .lzh-lede {
    margin: 0.55rem 0 0;
    color: var(--muted);
    font-size: 0.98rem;
    line-height: 1.65;
  }

  .lzh-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem 0.85rem;
    margin-top: 0.85rem;
    font-size: 0.9rem;
  }

  .lzh-links a {
    font-weight: 600;
  }

  .lzh-section {
    margin-top: 1.55rem;
  }

  .lzh-section-title {
    margin: 0 0 0.8rem;
    font-size: 1.08rem;
    line-height: 1.35;
    letter-spacing: 0;
    border-bottom: 1px solid var(--line);
    padding-bottom: 0.35rem;
  }

  .lzh-interest-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(12.5rem, 1fr));
    gap: 0.8rem;
  }

  .lzh-interest {
    border: 1px solid var(--line);
    border-radius: 8px;
    padding: 0.85rem;
    background: #fff;
  }

  .lzh-interest h3 {
    margin: 0 0 0.35rem;
    font-size: 0.98rem;
    line-height: 1.3;
    letter-spacing: 0;
  }

  .lzh-interest p {
    margin: 0;
    color: var(--muted);
    font-size: 0.86rem;
    line-height: 1.55;
  }

  .lzh-pub-list {
    display: grid;
    gap: 0.85rem;
  }

  .lzh-pub {
    display: grid;
    grid-template-columns: 5.2rem minmax(0, 1fr);
    border: 1px solid var(--line);
    border-radius: 8px;
    background: #fff;
    overflow: hidden;
  }

  .lzh-pub-meta {
    background: var(--soft);
    border-right: 1px solid var(--line);
    padding: 0.85rem 0.65rem;
    text-align: center;
  }

  .lzh-year {
    display: block;
    font-size: 1.08rem;
    line-height: 1.1;
    font-weight: 700;
    color: var(--blue);
  }

  .lzh-venue {
    display: block;
    margin-top: 0.35rem;
    font-size: 0.72rem;
    line-height: 1.25;
    color: var(--muted);
    font-weight: 700;
  }

  .lzh-pub-body {
    padding: 0.85rem 0.95rem;
  }

  .lzh-pub-title {
    margin: 0;
    font-size: 0.98rem;
    line-height: 1.38;
    letter-spacing: 0;
  }

  .lzh-authors {
    margin: 0.45rem 0 0;
    color: var(--muted);
    font-size: 0.84rem;
    line-height: 1.55;
  }

  .lzh-pub-venue-full {
    margin: 0.35rem 0 0;
    color: var(--ink);
    font-size: 0.84rem;
    line-height: 1.45;
    font-style: italic;
  }

  .lzh-pub-note {
    margin: 0.35rem 0 0;
    color: var(--green);
    font-size: 0.82rem;
    font-weight: 600;
  }

  .lzh-pub-links {
    margin-top: 0.55rem;
    display: flex;
    flex-wrap: wrap;
    gap: 0.25rem 0.65rem;
    font-size: 0.84rem;
  }

  .lzh-pub-links a {
    font-weight: 600;
  }

  .lzh-timeline {
    border-left: 2px solid var(--line);
    margin-left: 0.35rem;
    padding-left: 0.9rem;
  }

  .lzh-time-item {
    margin: 0 0 0.9rem;
  }

  .lzh-time-item:last-child {
    margin-bottom: 0;
  }

  .lzh-time-item h3 {
    margin: 0;
    font-size: 0.95rem;
    line-height: 1.35;
    letter-spacing: 0;
  }

  .lzh-time-item p {
    margin: 0.25rem 0 0;
    color: var(--muted);
    font-size: 0.86rem;
    line-height: 1.45;
  }

  @media (max-width: 760px) {
    .lzh-interest-grid {
      grid-template-columns: 1fr;
    }

    .lzh-pub {
      grid-template-columns: 1fr;
    }

    .lzh-pub-meta {
      display: flex;
      justify-content: space-between;
      align-items: center;
      text-align: left;
      border-right: 0;
      border-bottom: 1px solid var(--line);
    }

    .lzh-venue {
      margin-top: 0;
      text-align: right;
    }
  }
</style>

<div class="lzh-home">
  <section class="lzh-hero">
    <h1 class="lzh-name">Liuzhenghao Lv <span lang="zh">吕刘正浩</span></h1>
    <p class="lzh-lede">
      I am a Ph.D. student in the School of Computer Science at Peking University, advised by
      <a href="https://scholar.google.com/citations?user=fn6hJx0AAAAJ&hl=zh-CN">Prof. Yonghong Tian</a>
      (co-advised by <a href="https://yuanli2333.github.io/">Prof. Li Yuan</a>).
    </p>
    <p class="lzh-lede">
      My research lies at the intersection of <strong>scientific foundation models</strong>,
      <strong>molecular and protein LLMs</strong>, <strong>scientific agents</strong>, and
      <strong>scientific evaluation</strong>, with a focus on models and agentic systems that understand,
      generate, and reason over molecules, proteins, and biological protocols.
    </p>
    <div class="lzh-links">
      <a href="https://scholar.google.com/citations?user=lFUR8mQAAAAJ&hl=zh-CN">Google Scholar</a>
      <a href="https://github.com/Lyu6PosHao">GitHub</a>
      <a href="https://huggingface.co/GreatCaptainNemo">Hugging Face</a>
    </div>
  </section>

  <section class="lzh-section">
    <h2 class="lzh-section-title">Research Interests</h2>
    <div class="lzh-interest-grid">
      <div class="lzh-interest">
        <h3>Scientific Foundation Models</h3>
        <p>Large-scale models for scientific representation learning, generation, and reasoning.</p>
      </div>
      <div class="lzh-interest">
        <h3>Molecular and Protein LLMs</h3>
        <p>Language-model-driven molecular design, protein understanding, and protein sequence generation.</p>
      </div>
      <div class="lzh-interest">
        <h3>Scientific Agents</h3>
        <p>Tool-augmented agents, workflow automation, and biological protocol reasoning.</p>
      </div>
      <div class="lzh-interest">
        <h3>Scientific Evaluation</h3>
        <p>Hallucination evaluation, benchmark construction, and reliability analysis for scientific LLMs.</p>
      </div>
    </div>
  </section>

  <section class="lzh-section">
    <h2 class="lzh-section-title">Education</h2>
    <div class="lzh-timeline">
      <div class="lzh-time-item">
        <h3>Ph.D. Student, Computer Science, Peking University (Successive Postgraduate and Doctoral Programs)</h3>
        <p>School of Computer Science · 2025.09 - 2028.06 (expected)</p>
      </div>
      <div class="lzh-time-item">
        <h3>M.Phil. Student, Computer Science, Peking University</h3>
        <p>School of Electronic and Computer Engineering · 2023.09 - 2025.06</p>
      </div>
      <div class="lzh-time-item">
        <h3>B.Eng., Information Security, Tongji University</h3>
        <p>School of Electronic and Information Engineering · 2019.09 - 2023.07</p>
      </div>
    </div>
  </section>

  <section class="lzh-section">
    <h2 class="lzh-section-title">Selected Publications</h2>
    <div class="lzh-pub-list">
      <article class="lzh-pub">
        <div class="lzh-pub-meta">
          <span class="lzh-year">2026</span>
          <span class="lzh-venue">Nat.<br>Commun.</span>
        </div>
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">Navigating Chemical-Linguistic Sharing Space with Heterogeneous Molecular Encoding</h3>
          <p class="lzh-authors"><strong>Liuzhenghao Lv</strong><sup>*</sup>, Hao Li<sup>*</sup>, Yu Wang, Zijun Chen, Zhiyuan Yan, Zongying Lin, Yuyang Liu, Li Yuan, Yonghong Tian</p>
          <p class="lzh-pub-venue-full">Nature Communications</p>
          <p class="lzh-pub-note"><sup>*</sup> Equal contribution.</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2412.20888">Paper</a>
            <a href="https://github.com/Lyu6PosHao/HME">Code</a>
            <a href="https://huggingface.co/datasets/GreatCaptainNemo/HME_dataset">Dataset</a>
          </div>
        </div>
      </article>

      <article class="lzh-pub">
        <div class="lzh-pub-meta">
          <span class="lzh-year">2026</span>
          <span class="lzh-venue">ICML</span>
        </div>
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">Bridging the Gap in Autonomous Science: The Corpus and Benchmark for Biological Protocol Reasoning</h3>
          <p class="lzh-authors">Yuyang Liu<sup>*</sup>, <strong>Liuzhenghao Lv</strong><sup>*</sup>, Xiancheng Zhang, Jingya Wang, Li Yuan, Yonghong Tian</p>
          <p class="lzh-pub-venue-full">International Conference on Machine Learning (ICML 2026)</p>
          <p class="lzh-pub-note"><sup>*</sup> Equal contribution</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2505.07889">Paper</a>
            <a href="https://github.com/YuyangSunshine/bioprotocolbench">Code</a>
            <a href="https://huggingface.co/datasets/BioProBench/BioProBench">Dataset</a>
          </div>
        </div>
      </article>

      <article class="lzh-pub">
        <div class="lzh-pub-meta">
          <span class="lzh-year">2026</span>
          <span class="lzh-venue">ACL Oral</span>
        </div>
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">BioProAgent: Neuro-Symbolic Grounding for Constrained Scientific Planning</h3>
          <p class="lzh-authors">Yuyang Liu, Jingya Wang, <strong>Liuzhenghao Lv</strong>, Yonghong Tian</p>
          <p class="lzh-pub-venue-full">Annual Meeting of the Association for Computational Linguistics (ACL 2026)</p>
          <p class="lzh-pub-note">Oral Presentation</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2603.00876">Paper</a>
            <a href="https://github.com/YuyangSunshine/bioproagent">Code</a>
            <a href="https://yuyangsunshine.github.io/BioPro-Project/">Project</a>
          </div>
        </div>
      </article>

      <article class="lzh-pub">
        <div class="lzh-pub-meta">
          <span class="lzh-year">2025</span>
          <span class="lzh-venue">IEEE TAI</span>
        </div>
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">ProLLaMA: A Protein Large Language Model for Multitask Protein Language Processing</h3>
          <p class="lzh-authors"><strong>Liuzhenghao Lv</strong>, Zongying Lin, Hao Li, Yuyang Liu, Jiaxi Cui, Calvin Yu-Chian Chen, Li Yuan, Yonghong Tian</p>
          <p class="lzh-pub-venue-full">IEEE Transactions on Artificial Intelligence</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2402.16445">Paper</a>
            <a href="https://github.com/PKU-YuanGroup/ProLLaMA">Code</a>
          </div>
        </div>
      </article>

      <article class="lzh-pub">
        <div class="lzh-pub-meta">
          <span class="lzh-year">2025</span>
          <span class="lzh-venue">NeurIPS<br>AI4Sci.</span>
        </div>
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">How to Detect and Defeat Molecular Mirage: A Metric-Driven Benchmark for Hallucination in LLM-based Molecular Comprehension</h3>
          <p class="lzh-authors">Hao Li<sup>*</sup>, <strong>Liuzhenghao Lv</strong><sup>*</sup>, He Cao, Zijing Liu, Zhiyuan Yan, Yu Wang, Yonghong Tian, Yu Li, Li Yuan</p>
          <p class="lzh-pub-venue-full">NeurIPS 2025 Workshop on AI for Science</p>
          <p class="lzh-pub-note"><sup>*</sup> Equal contribution</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2504.12314">Paper</a>
            <a href="https://openreview.net/forum?id=REcdfjLUSI">OpenReview</a>
          </div>
        </div>
      </article>


      <article class="lzh-pub">
        <div class="lzh-pub-meta">
          <span class="lzh-year">2024</span>
          <span class="lzh-venue">SCIS</span>
        </div>
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">TaxDiff: Taxonomic-Guided Diffusion Model for Protein Sequence Generation</h3>
          <p class="lzh-authors">Zongying Lin, Hao Li, <strong>Liuzhenghao Lv</strong>, Yu Wang, Bin Lin, Junwu Zhang, Zijun Chen, Calvin Yu-Chian Chen, Li Yuan, Yonghong Tian</p>
          <p class="lzh-pub-venue-full">Science China Information Sciences</p>
          <div class="lzh-pub-links">
            <a href="https://doi.org/10.1007/s11432-024-4296-6">Paper</a>
            <a href="https://arxiv.org/abs/2402.17156">arXiv</a>
          </div>
        </div>
      </article>

      <article class="lzh-pub">
        <div class="lzh-pub-meta">
          <span class="lzh-year">2024</span>
          <span class="lzh-venue">ICASSP</span>
        </div>
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">Optimal ANN-SNN Conversion with Group Neurons</h3>
          <p class="lzh-authors"><strong>Liuzhenghao Lv</strong>, Wei Fang, Li Yuan, Yonghong Tian</p>
          <p class="lzh-pub-venue-full">IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP 2024)</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2402.19061">Paper</a>
            <a href="https://github.com/Lyu6PosHao/ANN2SNN_GN">Code</a>
          </div>
        </div>
      </article>

      <article class="lzh-pub">
        <div class="lzh-pub-meta">
          <span class="lzh-year">2023</span>
          <span class="lzh-venue">GPB</span>
        </div>
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">HPC-Atlas: Computationally Constructing a Comprehensive Atlas of Human Protein Complexes</h3>
          <p class="lzh-authors">Yuliang Pan, Ruiyi Li, Wengen Li, <strong>Liuzhenghao Lv</strong>, Jihong Guan, Shuigeng Zhou</p>
          <p class="lzh-pub-venue-full">Genomics, Proteomics &amp; Bioinformatics</p>
          <div class="lzh-pub-links">
            <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC10928439/">Paper</a>
            <a href="https://github.com/yul-pan/HPC-Atlas">Code</a>
          </div>
        </div>
      </article>

      <article class="lzh-pub">
        <div class="lzh-pub-meta">
          <span class="lzh-year">2023</span>
          <span class="lzh-venue">arXiv</span>
        </div>
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">Machine Mindset: An MBTI Exploration of Large Language Models</h3>
          <p class="lzh-authors">Jiaxi Cui<sup>*</sup>, <strong>Liuzhenghao Lv</strong><sup>*</sup>, Jing Wen, Rongsheng Wang, Jing Tang, Yonghong Tian, Li Yuan</p>
          <p class="lzh-pub-venue-full">arXiv</p>
          <p class="lzh-pub-note"><sup>*</sup> Equal contribution</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2312.12999">Paper</a>
            <a href="https://github.com/PKU-YuanGroup/Machine-Mindset">Code</a>
          </div>
        </div>
      </article>
    </div>
  </section>

  <section class="lzh-section">
    <h2 class="lzh-section-title">Experience</h2>
    <div class="lzh-timeline">
      <div class="lzh-time-item">
        <h3>Ph.D. and M.Phil. Researcher, Peking University</h3>
        <p>Beijing / Shenzhen, China · 2023.09 - Present. Research on HME, ProLLaMA, BioProBench, BioProAgent, and reliability evaluation for scientific LLMs.</p>
      </div>
      <div class="lzh-time-item">
        <h3>First Student Contributor, AI for Science Platform, Peking University</h3>
        <p>Beijing / Shenzhen, China · 2025 - Present. Contributing to digital laboratory workflows and experimental-protocol agents for scientific automation.</p>
      </div>
      <!-- <div class="lzh-time-item">
        <h3>Research Intern, AI Search Group, Baidu</h3>
        <p>Beijing, China · 2025.12 - 2026.03. Working on agentic reinforcement learning for skill-using AI agents.</p>
      </div> -->
      <div class="lzh-time-item">
        <h3>Research Intern, Peking University HSBC Business School</h3>
        <p>Shenzhen, China · 2023.10 - 2024.05. Applied retrieval-augmented generation to AI-related patent identification and patent corpus analysis.</p>
      </div>
      <div class="lzh-time-item">
        <h3>Official Contributor, SpikingJelly</h3>
        <p>Open-source deep learning framework for spiking neural networks · 2023. Contributed to a widely used SNN framework recommended by Nature Computational Science.</p>
      </div>
      <div class="lzh-time-item">
        <h3>Backend R&amp;D Intern, ByteDance</h3>
        <p>Shanghai, China · 2022.08 - 2022.11. Backend research and development for production software systems.</p>
      </div>
    </div>
  </section>
</div>
