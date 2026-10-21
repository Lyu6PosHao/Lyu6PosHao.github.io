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
    --blue: #255f99;
    --green: #2f6f5e;
    color: var(--ink);
  }

  .lzh-home .lzh-hero {
    padding: 0;
    margin-bottom: 1rem;
  }

  .lzh-home .lzh-name {
    margin: 0 0 0.35rem;
    font-size: 1.2rem;
    line-height: 1.2;
    letter-spacing: 0;
  }

  .lzh-home .lzh-lede {
    margin: 0.4rem 0 0;
    color: var(--muted);
    font-size: 0.8rem;
    line-height: 1.4;
  }

  .lzh-home .lzh-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem 0.85rem;
    margin-top: 0.65rem;
    font-size: 0.76rem;
  }

  .lzh-home .lzh-links a {
    font-weight: 500;
  }

  .lzh-home .lzh-section {
    margin-top: 1.8rem;
    padding: 1.1rem 0 0;
    border-top: 2px solid #a8b8c7;
  }

  .lzh-home .lzh-section-title {
    margin: 0 0 0.6rem;
    font-size: 0.9rem;
    line-height: 1.25;
    letter-spacing: 0;
    font-weight: 600;
    border-bottom: 0;
    padding-bottom: 0.35rem;
  }

  .lzh-home .lzh-more-publications { margin-top: 1.8rem; }
  .lzh-home .lzh-more-publications summary {
    cursor: pointer;
    color: var(--blue);
    font-size: 0.73rem;
    font-weight: 600;
    padding: 0.4rem 0;
  }
  .lzh-home .lzh-more-publications summary:focus-visible {
    outline: 2px solid var(--blue);
    outline-offset: 3px;
  }
  .lzh-home .lzh-more-publications[open] > summary { margin-bottom: 1rem; }
  .lzh-home .lzh-show-less,
  .lzh-home .lzh-more-publications[open] .lzh-show-more { display: none; }
  .lzh-home .lzh-more-publications[open] .lzh-show-less { display: inline; }
  .lzh-home .lzh-news-list { list-style: none; margin: 0; padding: 0; }
  .lzh-home .lzh-news-list li {
    display: grid;
    grid-template-columns: 5.2rem 1fr;
    gap: 0.6rem;
    margin-bottom: 0.65rem;
    font-size: 0.73rem;
    line-height: 1.35;
  }
  .lzh-home .lzh-news-list time { color: var(--muted); }

  .lzh-home .lzh-pub-list {
    display: grid;
    gap: 1.8rem;
  }

  .lzh-home .lzh-pub {
    border: 0;
  }

  .lzh-home .lzh-pub-body {
    padding: 0;
  }

  .lzh-home .lzh-pub-title {
    margin: 0;
    font-size: 0.8rem;
    line-height: 1.25;
    letter-spacing: 0;
    font-weight: 600;
  }

  .lzh-home .lzh-authors {
    margin: 0.15rem 0 0;
    color: var(--muted);
    font-size: 0.72rem;
    line-height: 1.3;
  }

  .lzh-home .lzh-pub-venue-full {
    margin: 0.12rem 0 0;
    color: var(--green);
    font-size: 0.73rem;
    line-height: 1.3;
    font-style: italic;
    font-weight: 500;
  }

  .lzh-home .lzh-pub-legend {
    margin: 0 0 0.6rem;
    color: var(--muted);
    font-size: 0.68rem;
    line-height: 1.3;
  }

  .lzh-home .lzh-pub-highlight {
    margin: 0.25rem 0 0;
    padding: 0;
    border: 0;
    background: transparent;
    font-size: 0.72rem;
    line-height: 1.3;
  }

  .lzh-home .lzh-pub-highlight strong {
    color: var(--green);
  }

  .lzh-home .lzh-highlight-evidence {
    margin-top: 0.35rem;
    font-size: 0.7rem;
    line-height: 1.3;
  }

  .lzh-home .lzh-highlight-evidence summary {
    color: var(--blue);
    cursor: pointer;
  }

  .lzh-home .lzh-highlight-evidence summary:focus-visible {
    outline: 2px solid var(--blue);
    outline-offset: 3px;
  }

  .lzh-home .lzh-highlight-evidence figure {
    display: block;
    margin: 0.65rem 0;
  }

  .lzh-home .lzh-highlight-evidence img {
    display: block;
    width: 100%;
    height: auto;
    border: 1px solid var(--line);
    border-radius: 4px;
  }

  .lzh-home .lzh-highlight-evidence figcaption {
    margin-top: 0.25rem;
    color: var(--muted);
    font-size: 0.7rem;
  }

  .lzh-home .lzh-pub-links {
    margin-top: 0.2rem;
    display: flex;
    flex-wrap: wrap;
    gap: 0.25rem 0.65rem;
    font-size: 0.72rem;
  }

  .lzh-home .lzh-pub-links a {
    font-weight: 500;
  }

  .lzh-home .lzh-pub-metric {
    color: var(--muted);
    font-weight: 500;
    white-space: nowrap;
  }

  .lzh-home .lzh-timeline {
    margin: 0;
    padding: 0;
  }

  .lzh-home .lzh-time-item {
    margin: 0;
    padding: 0;
  }

  .lzh-home .lzh-time-item + .lzh-time-item {
    margin-top: 1.5rem;
  }

  .lzh-home .lzh-time-item h3 {
    margin: 0;
    font-size: 0.8rem;
    line-height: 1.25;
    letter-spacing: 0;
    font-weight: 600;
  }

  .lzh-home .lzh-time-item p {
    margin: 0.12rem 0 0;
    color: var(--muted);
    font-size: 0.73rem;
    line-height: 1.3;
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
      I build AI systems for scientific discovery along two complementary research directions:
      <strong>molecular and protein understanding and design</strong>, and
      <strong>dry&ndash;wet closed-loop automated laboratories</strong>.
      Across both directions, I work with multimodal LLMs, LLM mid-training and post-training, and agents.
    </p>
    <div class="lzh-links">
      <a href="https://scholar.google.com/citations?user=lFUR8mQAAAAJ&hl=zh-CN">Google Scholar</a>
      <a href="https://github.com/Lyu6PosHao">GitHub</a>
      <a href="https://huggingface.co/GreatCaptainNemo">Hugging Face</a>
    </div>
  </section>

  <section class="lzh-section">
    <h2 class="lzh-section-title">News</h2>
    <ul class="lzh-news-list">
      <li><time datetime="2026-09">Sep 2026</time><span>RipplePLM was accepted to <strong>NeurIPS 2026</strong>.</span></li>
      <li><time datetime="2026-09">Sep 2026</time><span>HME was selected as an <strong>Editors&rsquo; Highlight</strong> in Nature Communications.</span></li>
      <li><time datetime="2026-07">Jul 2026</time><span>HME was published in <a href="https://www.nature.com/articles/s41467-026-74666-w">Nature Communications</a>.</span></li>
      <li><time datetime="2026-06">Jun 2026</time><span>BioProAgent was selected for an <strong>oral presentation at ACL 2026</strong>.</span></li>
      <li><time datetime="2026-05">May 2026</time><span>BioProBench was accepted to <strong>ICML 2026</strong>.</span></li>
      <li><time datetime="2026-04">Apr 2026</time><span>BioProAgent was accepted to <strong>ACL 2026</strong>.</span></li>
      <li><time datetime="2025-04">Apr 2025</time><span>ProLLaMA was accepted by <strong>IEEE Transactions on Artificial Intelligence</strong>.</span></li>
    </ul>
  </section>

  <section class="lzh-section">
    <h2 class="lzh-section-title">Selected Publications</h2>
    <p class="lzh-pub-legend"><sup>&dagger;</sup> Equal contribution.</p>
    <div class="lzh-pub-list">
<article class="lzh-pub">
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">Navigating Chemical-Linguistic Sharing Space with Heterogeneous Molecular Encoding</h3>
          <p class="lzh-authors"><strong>Liuzhenghao Lv</strong><sup>&dagger;</sup>, Hao Li<sup>&dagger;</sup>, Yu Wang, Zijun Chen, Zhiyuan Yan, Zongying Lin, Yuyang Liu, Li Yuan, Yonghong Tian</p>
          <p class="lzh-pub-venue-full">Nature Communications, 2026</p>
          <p class="lzh-pub-highlight"><strong>Selected as Editors&rsquo; Highlight</strong> &mdash; one of the 50 best papers recently published in materials science and chemistry.</p>
          <details class="lzh-highlight-evidence">
            <summary>View collection screenshots</summary>
            <figure>
              <a href="{{ '/images/hme/nature-communications-highlight-collection.png' | relative_url }}">
                <img src="{{ '/images/hme/nature-communications-highlight-collection.png' | relative_url }}" alt="Nature Communications Materials science and chemistry collection overview" width="2900" height="1144" loading="lazy">
              </a>
              <figcaption>Nature Communications &mdash; Materials science and chemistry collection.</figcaption>
            </figure>
            <figure>
              <a href="{{ '/images/hme/nature-communications-highlight-listing.png' | relative_url }}">
                <img src="{{ '/images/hme/nature-communications-highlight-listing.png' | relative_url }}" alt="Collection listing featuring Navigating chemical-linguistic sharing space with heterogeneous molecular encoding by Liuzhenghao Lv and colleagues" width="2906" height="1118" loading="lazy">
              </a>
              <figcaption>HME featured in the collection. Select an image to view it at full size.</figcaption>
            </figure>
          </details>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2412.20888">Paper</a>
            {% include github-repo-link.html repo="Lyu6PosHao/HME" %}
            <a href="https://huggingface.co/datasets/GreatCaptainNemo/HME_dataset">Dataset</a>
          </div>
        </div>
      </article>

<article class="lzh-pub">
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">RipplePLM: Structural and Property Decoupling for Protein Mutation Effect Generation</h3>
          <p class="lzh-authors"><strong>Liuzhenghao Lv</strong>, Yuyang Liu, Yuyang Gao, Li Yuan, Yonghong Tian</p>
          <p class="lzh-pub-venue-full">NeurIPS, 2026</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2610.01891">Paper</a>
            {% include github-repo-link.html repo="Lyu6PosHao/RipplePLM" %}
            <a href="https://huggingface.co/datasets/GreatCaptainNemo/RipplePLM-data">Dataset</a>
          </div>
        </div>
      </article>

<article class="lzh-pub">
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">Bridging the Gap in Autonomous Science: The Corpus and Benchmark for Biological Protocol Reasoning</h3>
          <p class="lzh-authors">Yuyang Liu<sup>&dagger;</sup>, <strong>Liuzhenghao Lv</strong><sup>&dagger;</sup>, Xiancheng Zhang, Jingya Wang, Li Yuan, Yonghong Tian</p>
          <p class="lzh-pub-venue-full">ICML, 2026</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2505.07889">Paper</a>
            {% include github-repo-link.html repo="YuyangSunshine/bioprotocolbench" %}
            <a href="https://huggingface.co/datasets/BioProBench/BioProBench">Dataset</a>
            <span class="lzh-pub-metric">100K+ downloads</span>
          </div>
        </div>
      </article>

<article class="lzh-pub">
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">ProLLaMA: A Protein Large Language Model for Multitask Protein Language Processing</h3>
          <p class="lzh-authors"><strong>Liuzhenghao Lv</strong>, Zongying Lin, Hao Li, Yuyang Liu, Jiaxi Cui, Calvin Yu-Chian Chen, Li Yuan, Yonghong Tian</p>
          <p class="lzh-pub-venue-full">IEEE Transactions on Artificial Intelligence, 2025</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2402.16445">Paper</a>
            {% include github-repo-link.html repo="PKU-YuanGroup/ProLLaMA" %}
            <a href="https://huggingface.co/collections/GreatCaptainNemo/prollama">Weights</a>
            <span class="lzh-pub-metric">60K+ downloads</span>
          </div>
        </div>
      </article>
    </div>
    <details class="lzh-more-publications">
      <summary><span class="lzh-show-more">Show more publications (6)</span><span class="lzh-show-less">Show fewer publications</span></summary>
      <div class="lzh-pub-list">
<article class="lzh-pub">
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">How to Detect and Defeat Molecular Mirage: A Metric-Driven Benchmark for Hallucination in LLM-based Molecular Comprehension</h3>
          <p class="lzh-authors">Hao Li<sup>&dagger;</sup>, <strong>Liuzhenghao Lv</strong><sup>&dagger;</sup>, He Cao, Zijing Liu, Zhiyuan Yan, Yu Wang, Yonghong Tian, Yu Li, Li Yuan</p>
          <p class="lzh-pub-venue-full">NeurIPS AI for Science Workshop, 2025</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2504.12314">Paper</a>
          </div>
        </div>
      </article>

<article class="lzh-pub">
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">TaxDiff: Taxonomic-Guided Diffusion Model for Protein Sequence Generation</h3>
          <p class="lzh-authors">Zongying Lin<sup>&dagger;</sup>, Hao Li<sup>&dagger;</sup>, <strong>Liuzhenghao Lv</strong>, Yu Wang, Bin Lin, Junwu Zhang, Zijun Chen, Calvin Yu-Chian Chen, Li Yuan, Yonghong Tian</p>
          <p class="lzh-pub-venue-full">Science China Information Sciences, 2025</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2402.17156">Paper</a>
            {% include github-repo-link.html repo="PKU-YuanGroup/TaxDiff" %}
          </div>
        </div>
      </article>

<article class="lzh-pub">
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">LabEvolver: Training-Free Experience Evolution for Safe and Grounded Wet-Lab Agents</h3>
          <p class="lzh-authors">Jingya Wang, Yuyang Gao, <strong>Liuzhenghao Lv</strong>, Yonghong Tian, Yuyang Liu</p>
          <p class="lzh-pub-venue-full">arXiv, 2026</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2607.27690">Paper</a>
            {% include github-repo-link.html repo="AndyGao6186/LabEvolver" %}
            <a href="https://andygao6186.github.io/LabEvolver/">Project</a>
          </div>
        </div>
      </article>

<article class="lzh-pub">
        <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">BioProAgent: Neuro-Symbolic Grounding for Constrained Scientific Planning</h3>
          <p class="lzh-authors">Yuyang Liu, Jingya Wang, <strong>Liuzhenghao Lv</strong>, Yonghong Tian</p>
          <p class="lzh-pub-venue-full">ACL Main (Oral), 2026</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2603.00876">Paper</a>
            {% include github-repo-link.html repo="YuyangSunshine/bioproagent" %}
            <a href="https://yuyangsunshine.github.io/BioPro-Project/">Project</a>
          </div>
        </div>
      </article>

<article class="lzh-pub">
          <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">Machine Mindset: An MBTI Exploration of Large Language Models</h3>
          <p class="lzh-authors">Jiaxi Cui<sup>&dagger;</sup>, <strong>Liuzhenghao Lv</strong><sup>&dagger;</sup>, Jing Wen, Rongsheng Wang, Jing Tang, Yonghong Tian, Li Yuan</p>
          <p class="lzh-pub-venue-full">arXiv, 2023</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2312.12999">Paper</a>
            {% include github-repo-link.html repo="PKU-YuanGroup/Machine-Mindset" %}
          </div>
          </div>
        </article>

<article class="lzh-pub">
          <div class="lzh-pub-body">
          <h3 class="lzh-pub-title">Optimal ANN-SNN Conversion with Group Neurons</h3>
          <p class="lzh-authors"><strong>Liuzhenghao Lv</strong>, Wei Fang, Li Yuan, Yonghong Tian</p>
          <p class="lzh-pub-venue-full">ICASSP, 2024</p>
          <div class="lzh-pub-links">
            <a href="https://arxiv.org/abs/2402.19061">Paper</a>
            {% include github-repo-link.html repo="Lyu6PosHao/ANN2SNN_GN" %}
          </div>
          </div>
        </article>
      </div>
    </details>
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
    <h2 class="lzh-section-title">Experience</h2>
    <div class="lzh-timeline">
      <div class="lzh-time-item">
        <h3>Ph.D. and M.Phil. Researcher, Peking University</h3>
        <p>Beijing / Shenzhen, China · 2023.09 - Present. Research on AI for biochemistry.</p>
      </div>
      <div class="lzh-time-item">
        <h3>Main Contributor, AI for Science Platform, Peking University</h3>
        <p>Beijing / Shenzhen, China · 2025 - Present. Developing grounded agents and dry&ndash;wet closed-loop workflows for automated scientific experimentation.</p>
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
        <p>Open-source deep learning framework for spiking neural networks · 2023. Published in Science Advances.</p>
      </div>
      <div class="lzh-time-item">
        <h3>Backend R&amp;D Intern, ByteDance</h3>
        <p>Shanghai, China · 2022.08 - 2022.11. Backend research and development for production software systems.</p>
      </div>
    </div>
  </section>

  <section class="lzh-section">
    <h2 class="lzh-section-title">Awards</h2>
    <div class="lzh-timeline">
      <div class="lzh-time-item">
        <p>Outstanding Research Award, Peking University · 2024</p>
      </div>
      <div class="lzh-time-item">
        <p>Merit Student, Peking University · 2026</p>
      </div>
      <div class="lzh-time-item">
        <p>Leo KoGuan Scholarship, Peking University · 2026</p>
      </div>
    </div>
  </section>

  <section class="lzh-section">
    <h2 class="lzh-section-title">Academic Service</h2>
    <div class="lzh-timeline">
      <div class="lzh-time-item">
        <p>Reviewer, AAAI and NeurIPS</p>
      </div>
    </div>
  </section>
</div>
