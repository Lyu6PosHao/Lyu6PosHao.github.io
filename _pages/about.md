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

  .lzh-hero {
    padding: 0;
    margin-bottom: 1rem;
  }

  .lzh-name {
    margin: 0 0 0.35rem;
    font-size: 1.2rem;
    line-height: 1.2;
    letter-spacing: 0;
  }

  .lzh-lede {
    margin: 0.4rem 0 0;
    color: var(--muted);
    font-size: 0.8rem;
    line-height: 1.4;
  }

  .lzh-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem 0.85rem;
    margin-top: 0.65rem;
    font-size: 0.76rem;
  }

  .lzh-links a {
    font-weight: 500;
  }

  .lzh-section {
    margin-top: 1.8rem;
    padding: 0;
  }

  .lzh-section-title {
    margin: 0 0 0.6rem;
    font-size: 0.9rem;
    line-height: 1.25;
    letter-spacing: 0;
    font-weight: 600;
    border-bottom: 0;
    padding-bottom: 0.35rem;
  }

  .lzh-direction-tabs {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1rem;
    margin-bottom: 0.75rem;
    border-bottom: 0;
  }

  .lzh-direction-tab {
    appearance: none;
    width: 100%;
    padding: 0.45rem 0 0.55rem;
    border: 0;
    border-radius: 0;
    background: transparent;
    color: var(--muted);
    font: inherit;
    font-size: 0.75rem;
    font-weight: 600;
    line-height: 1.25;
    text-align: left;
    cursor: pointer;
    transition: border-color 0.15s ease, background-color 0.15s ease, color 0.15s ease;
  }

  .lzh-direction-tab:hover,
  .lzh-direction-tab:focus-visible {
    color: var(--blue);
  }

  .lzh-direction-tab[aria-selected="true"] {
    color: var(--ink);
    box-shadow: inset 0 -2px 0 var(--blue);
  }

  .lzh-direction-panel[hidden] {
    display: none;
  }

  .lzh-pub-list {
    display: grid;
    gap: 1.8rem;
  }

  .lzh-pub {
    border: 0;
  }

  .lzh-pub-body {
    padding: 0;
  }

  .lzh-pub-title {
    margin: 0;
    font-size: 0.8rem;
    line-height: 1.25;
    letter-spacing: 0;
    font-weight: 600;
  }

  .lzh-authors {
    margin: 0.15rem 0 0;
    color: var(--muted);
    font-size: 0.72rem;
    line-height: 1.3;
  }

  .lzh-pub-venue-full {
    margin: 0.12rem 0 0;
    color: var(--green);
    font-size: 0.73rem;
    line-height: 1.3;
    font-style: italic;
    font-weight: 500;
  }

  .lzh-pub-legend {
    margin: 0 0 0.6rem;
    color: var(--muted);
    font-size: 0.68rem;
    line-height: 1.3;
  }

  .lzh-pub-highlight {
    margin: 0.25rem 0 0;
    padding: 0;
    border: 0;
    background: transparent;
    font-size: 0.72rem;
    line-height: 1.3;
  }

  .lzh-pub-highlight strong {
    color: var(--green);
  }

  .lzh-highlight-evidence {
    margin-top: 0.35rem;
    font-size: 0.7rem;
    line-height: 1.3;
  }

  .lzh-highlight-evidence summary {
    color: var(--blue);
    cursor: pointer;
  }

  .lzh-highlight-evidence summary:focus-visible {
    outline: 2px solid var(--blue);
    outline-offset: 3px;
  }

  .lzh-highlight-evidence figure {
    display: block;
    margin: 0.65rem 0;
  }

  .lzh-highlight-evidence img {
    display: block;
    width: 100%;
    height: auto;
    border: 1px solid var(--line);
    border-radius: 4px;
  }

  .lzh-highlight-evidence figcaption {
    margin-top: 0.25rem;
    color: var(--muted);
    font-size: 0.7rem;
  }

  .lzh-pub-links {
    margin-top: 0.2rem;
    display: flex;
    flex-wrap: wrap;
    gap: 0.25rem 0.65rem;
    font-size: 0.72rem;
  }

  .lzh-pub-links a {
    font-weight: 500;
  }

  .lzh-pub-metric {
    color: var(--muted);
    font-weight: 500;
    white-space: nowrap;
  }

  .lzh-timeline {
    margin: 0;
    padding: 0;
  }

  .lzh-time-item {
    margin: 0;
    padding: 0;
  }

  .lzh-time-item + .lzh-time-item {
    margin-top: 1.5rem;
  }

  .lzh-time-item h3 {
    margin: 0;
    font-size: 0.8rem;
    line-height: 1.25;
    letter-spacing: 0;
    font-weight: 600;
  }

  .lzh-time-item p {
    margin: 0.12rem 0 0;
    color: var(--muted);
    font-size: 0.73rem;
    line-height: 1.3;
  }

  @media (max-width: 640px) {
    .lzh-direction-tabs {
      grid-template-columns: 1fr;
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
    <h2 class="lzh-section-title">Selected Publications</h2>
    <p class="lzh-pub-legend"><sup>&dagger;</sup> Equal contribution.</p>
    <div data-direction-switcher>
      <div class="lzh-direction-tabs" role="tablist" aria-label="Publication categories">
        <button class="lzh-direction-tab" id="direction-tab-molecular" type="button" role="tab" aria-selected="true" aria-controls="direction-panel-molecular" tabindex="0">
          Molecular and Protein Understanding and Design
        </button>
        <button class="lzh-direction-tab" id="direction-tab-lab" type="button" role="tab" aria-selected="false" aria-controls="direction-panel-lab" tabindex="-1">
          Dry&ndash;Wet Closed-Loop Automated Laboratories
        </button>
        <button class="lzh-direction-tab" id="direction-tab-additional" type="button" role="tab" aria-selected="false" aria-controls="direction-panel-additional" tabindex="-1">
          Earlier and Additional Work
        </button>
      </div>

      <div class="lzh-direction-panel" id="direction-panel-molecular" role="tabpanel" aria-labelledby="direction-tab-molecular">
        <div class="lzh-pub-list">
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
        </div>
      </div>

      <div class="lzh-direction-panel" id="direction-panel-lab" role="tabpanel" aria-labelledby="direction-tab-lab" hidden>
        <div class="lzh-pub-list">
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
        </div>
      </div>

      <div class="lzh-direction-panel" id="direction-panel-additional" role="tabpanel" aria-labelledby="direction-tab-additional" hidden>
        <div class="lzh-pub-list">
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
    <h2 class="lzh-section-title">Academic Service</h2>
    <div class="lzh-timeline">
      <div class="lzh-time-item">
        <p>Reviewer, AAAI and NeurIPS</p>
      </div>
    </div>
  </section>
</div>

<script>
  (function () {
    var switcher = document.querySelector('[data-direction-switcher]');
    if (!switcher) return;

    var tabs = Array.prototype.slice.call(switcher.querySelectorAll('[role="tab"]'));
    var panels = Array.prototype.slice.call(switcher.querySelectorAll('[role="tabpanel"]'));

    function activateTab(tab, moveFocus) {
      tabs.forEach(function (item) {
        var selected = item === tab;
        item.setAttribute('aria-selected', selected ? 'true' : 'false');
        item.setAttribute('tabindex', selected ? '0' : '-1');
      });

      panels.forEach(function (panel) {
        panel.hidden = panel.id !== tab.getAttribute('aria-controls');
      });

      if (moveFocus) tab.focus();
    }

    tabs.forEach(function (tab, index) {
      tab.addEventListener('click', function () {
        activateTab(tab, false);
      });

      tab.addEventListener('keydown', function (event) {
        if (event.key !== 'ArrowLeft' && event.key !== 'ArrowRight') return;
        event.preventDefault();
        var offset = event.key === 'ArrowRight' ? 1 : -1;
        activateTab(tabs[(index + offset + tabs.length) % tabs.length], true);
      });
    });
  }());
</script>
