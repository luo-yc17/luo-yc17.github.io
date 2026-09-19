---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

<section class="intro-section">
  <p class="eyebrow">ABOUT ME</p>
  <p class="intro-lead">
    Hi, I am <strong>Yuechen Luo</strong>, a master's student at the
    <a href="https://www.svm.tsinghua.edu.cn/" target="_blank" rel="noopener">School of Vehicle and Mobility, Tsinghua University</a>,
    and a research intern at <strong>Xiaomi EV</strong>.
  </p>
  <p>
    My research focuses on <strong>vision-language-action models</strong>,
    <strong>reinforcement learning</strong>, <strong>world models</strong>, and
    <strong>end-to-end autonomous driving</strong>. I am especially interested in
    reasoning, verification, and robust policy learning for long-tail driving scenarios.
  </p>
  <div class="intro-actions">
    <a class="profile-button profile-button--primary" href="mailto:luo-yc24@mails.tsinghua.edu.cn">Email me</a>
    <a class="profile-button" href="https://scholar.google.com/citations?user=cNf7PjkAAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>
    <a class="profile-button" href="https://github.com/luo-yc17" target="_blank" rel="noopener">GitHub</a>
  </div>
</section>

<span class="anchor" id="education"></span>

<section class="content-section education-section">
  <div class="section-heading">
    <div>
      <p class="eyebrow">BACKGROUND</p>
      <h2>Education</h2>
    </div>
    <span class="section-count">02</span>
  </div>

  <div class="education-list">
    <article class="education-card">
      <div class="institution-mark institution-mark--logo" aria-hidden="true">
        <img src="{{ '/images/education/tsinghua-logo.png' | relative_url }}" alt="">
      </div>
      <div class="education-copy">
        <div class="education-title-row">
          <h3>Tsinghua University</h3>
          <span>2024 — Present</span>
        </div>
        <p class="education-degree">M.S. Student · School of Vehicle and Mobility</p>
        <p class="education-meta">Beijing, China · Autonomous driving, VLA models, reinforcement learning</p>
      </div>
    </article>

    <article class="education-card">
      <div class="institution-mark institution-mark--logo" aria-hidden="true">
        <img src="{{ '/images/education/hit-logo.png' | relative_url }}" alt="">
      </div>
      <div class="education-copy">
        <div class="education-title-row">
          <h3>Harbin Institute of Technology</h3>
          <span>2020 — 2024</span>
        </div>
        <p class="education-degree">Bachelor's Degree · School of Transportation</p>
        <p class="education-meta">Harbin, China</p>
      </div>
    </article>
  </div>
</section>

<span class="anchor" id="publications"></span>

<section class="content-section publications-section">
  <div class="section-heading">
    <div>
      <p class="eyebrow">RESEARCH</p>
      <h2>Selected Publications</h2>
    </div>
    <span class="section-count">10</span>
  </div>
  <p class="section-intro">
    Selected work on autonomous driving and embodied intelligence. <span class="muted">* denotes equal contribution.</span>
  </p>

  <div class="publication-list">
    <article class="publication-card">
      <a class="publication-figure" href="https://arxiv.org/abs/2608.26058" target="_blank" rel="noopener">
        <img src="{{ '/images/publications/ucag-p-figure-3.png' | relative_url }}" alt="UCAG-P Figure 3 overview" loading="lazy">
        <span class="venue-badge venue-badge--preprint">Xiaomi Technical Report</span>
      </a>
      <div class="publication-copy">
        <p class="publication-kicker">Xiaomi Technical Report · Cross-Embodiment Learning</p>
        <h3><a href="https://arxiv.org/abs/2608.26058" target="_blank" rel="noopener">One Policy, Many Embodiments: Unified Camera-Centric Action Geometry Pre-training for Heterogeneous Embodied Manipulation</a></h3>
        <p class="publication-authors"><strong>Core Contributor</strong></p>
        <p class="publication-summary">UCAG-P aligns heterogeneous robot and human demonstrations in a shared camera-centric action space for transferable manipulation.</p>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2608.26058" target="_blank" rel="noopener">Paper</a>
          <a href="https://public-bots.github.io/UCAG-P/" target="_blank" rel="noopener">Project</a>
          <a href="https://github.com/Public-BOTs/ucag-p" target="_blank" rel="noopener">Repository</a>
          <span class="resource-note">Code coming soon</span>
        </div>
      </div>
    </article>

    <article class="publication-card">
      <a class="publication-figure" href="https://eccv.ecva.net/virtual/2026/poster/4231" target="_blank" rel="noopener">
        <img src="{{ '/images/publications/world-in-loop-figure-3.png' | relative_url }}" alt="World-in-Loop Figure 3 overview" loading="lazy">
        <span class="venue-badge">ECCV 2026</span>
        <span class="ccf-badge ccf-badge--b">CCF B</span>
      </a>
      <div class="publication-copy">
        <p class="publication-kicker">World Models · Online Correction</p>
        <h3><a href="https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/5018.pdf" target="_blank" rel="noopener">World-in-Loop: Online Correction via Event-Triggered World Models for Robust VLA Policies</a></h3>
        <p class="publication-authors">Shaoqing Xu*, Fang Li*, <strong>Yuechen Luo*</strong>, Qimao Chen*, Yifan Yang, Zhixiang Duan, Long Chen, Zhi-Xin Yang</p>
        <p class="publication-summary">An event-triggered world model detects risky grasp attempts and imagines successful futures to correct VLA policies online.</p>
        <div class="publication-links">
          <a href="https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/5018.pdf" target="_blank" rel="noopener">Paper</a>
          <a href="https://eccv.ecva.net/virtual/2026/poster/4231" target="_blank" rel="noopener">ECCV page</a>
          <span class="resource-note resource-note--muted">Code not public</span>
        </div>
      </div>
    </article>

    <article class="publication-card">
      <a class="publication-figure" href="https://arxiv.org/abs/2607.00399" target="_blank" rel="noopener">
        <img src="{{ '/images/publications/drivever-figure-2.jpg' | relative_url }}" alt="DriveVer Figure 2 architecture" loading="lazy">
        <span class="venue-badge">IROS 2026</span>
        <span class="ccf-badge ccf-badge--c">CCF C</span>
      </a>
      <div class="publication-copy">
        <p class="publication-kicker">Test-Time Verification · Planning</p>
        <h3><a href="https://arxiv.org/abs/2607.00399" target="_blank" rel="noopener">DriveVer: Lightweight Trajectory Evaluator as Test-Time Verifier for Autonomous Driving</a></h3>
        <p class="publication-authors">Chong He*, <strong>Yuechen Luo*</strong>, Fang Li, Shaoqing Xu, Fuxi Wen</p>
        <p class="publication-summary">A compact plug-and-play verifier scores and refines candidate trajectories at test time with minimal latency overhead.</p>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2607.00399" target="_blank" rel="noopener">Paper</a>
          <span class="resource-note resource-note--muted">Code not public</span>
        </div>
      </div>
    </article>

    <article class="publication-card">
      <a class="publication-figure" href="https://arxiv.org/abs/2606.08525" target="_blank" rel="noopener">
        <img src="{{ '/images/publications/drivereward.jpg' | relative_url }}" alt="DriveReward overview" loading="lazy">
        <span class="venue-badge venue-badge--preprint">arXiv 2026</span>
      </a>
      <div class="publication-copy">
        <p class="publication-kicker">Reward Modeling · Driving Dataset</p>
        <h3><a href="https://arxiv.org/abs/2606.08525" target="_blank" rel="noopener">DriveReward: A Comprehensive Dataset and Generative Vision-Language Reward Model for Autonomous Driving</a></h3>
        <p class="publication-authors">Qimao Chen*, Fang Li*, <strong>Yuechen Luo*</strong>, Zehan Zhang, Haiyang Sun, et al.</p>
        <p class="publication-summary">DriveReward introduces a counterfactual driving dataset and a compact generative reward model for trajectory evaluation and RL.</p>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2606.08525" target="_blank" rel="noopener">Paper</a>
          <span class="resource-note resource-note--muted">Code not public</span>
        </div>
      </div>
    </article>

    <article class="publication-card">
      <a class="publication-figure" href="https://xiaomi-embodied-intelligence.github.io/OneVL/" target="_blank" rel="noopener">
        <img src="{{ '/images/publications/onevl.png' | relative_url }}" alt="Xiaomi OneVL framework" loading="lazy">
        <span class="venue-badge venue-badge--preprint">Technical Report 2026</span>
      </a>
      <div class="publication-copy">
        <p class="publication-kicker">Latent Reasoning · World Models</p>
        <h3><a href="https://arxiv.org/abs/2604.18486" target="_blank" rel="noopener">Xiaomi OneVL: One-Step Latent Reasoning and Planning with Vision-Language Explanation</a></h3>
        <p class="publication-authors">Xiaomi Embodied Intelligence Team</p>
        <p class="publication-summary">OneVL compresses visual prediction and language reasoning into latent tokens for fast, interpretable planning.</p>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2604.18486" target="_blank" rel="noopener">Paper</a>
          <a href="https://xiaomi-embodied-intelligence.github.io/OneVL/" target="_blank" rel="noopener">Project</a>
          <a href="https://github.com/xiaomi-research/onevl" target="_blank" rel="noopener">Code</a>
          <a href="https://huggingface.co/collections/xiaomi-research/onevl-models" target="_blank" rel="noopener">Models</a>
        </div>
      </div>
    </article>

    <article class="publication-card">
      <a class="publication-figure" href="https://arxiv.org/abs/2603.01928" target="_blank" rel="noopener">
        <img src="{{ '/images/publications/last-vla.jpg' | relative_url }}" alt="LaST-VLA framework" loading="lazy">
        <span class="venue-badge venue-badge--preprint">arXiv 2026</span>
      </a>
      <div class="publication-copy">
        <p class="publication-kicker">Latent Reasoning · Autonomous Driving</p>
        <h3><a href="https://arxiv.org/abs/2603.01928" target="_blank" rel="noopener">LaST-VLA: Thinking in Latent Spatio-Temporal Space for Vision-Language-Action in Autonomous Driving</a></h3>
        <p class="publication-authors"><strong>Yuechen Luo*</strong>, Fang Li*, Shaoqing Xu*, Yang Ji, Zehan Zhang, et al.</p>
        <p class="publication-summary">LaST-VLA grounds latent reasoning with geometric constraints from 3D models and dynamic foresight from world models.</p>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2603.01928" target="_blank" rel="noopener">Paper</a>
          <a href="https://github.com/luo-yc17/LaST-VLA" target="_blank" rel="noopener">Repository</a>
          <span class="resource-note">Code coming soon</span>
        </div>
      </div>
    </article>

    <article class="publication-card">
      <a class="publication-figure" href="https://arxiv.org/abs/2603.01063" target="_blank" rel="noopener">
        <img src="{{ '/images/publications/elf-vla.png' | relative_url }}" alt="ELF-VLA training pipeline" loading="lazy">
        <span class="venue-badge">CVPR 2026</span>
        <span class="ccf-badge ccf-badge--a">CCF A</span>
      </a>
      <div class="publication-copy">
        <p class="publication-kicker">Reinforcement Learning · Failure Feedback</p>
        <h3><a href="https://arxiv.org/abs/2603.01063" target="_blank" rel="noopener">Unleashing VLA Potentials in Autonomous Driving via Explicit Learning from Failures</a></h3>
        <p class="publication-authors"><strong>Yuechen Luo*</strong>, Qimao Chen*, Fang Li*, Shaoqing Xu, Jiaxin Liu, Ziying Song, Zhi-Xin Yang, Fuxi Wen</p>
        <p class="publication-summary">ELF-VLA turns persistent RL failures into structured feedback and high-value corrective rollouts.</p>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2603.01063" target="_blank" rel="noopener">Paper</a>
          <a href="https://github.com/luo-yc17/ELF-VLA" target="_blank" rel="noopener">Repository</a>
          <span class="resource-note">Code coming soon</span>
        </div>
      </div>
    </article>

    <article class="publication-card">
      <a class="publication-figure" href="https://arxiv.org/abs/2509.13769" target="_blank" rel="noopener">
        <img src="{{ '/images/publications/adathinkdrive.jpg' | relative_url }}" alt="AdaThinkDrive overview" loading="lazy">
        <span class="venue-badge">ICRA 2026</span>
        <span class="ccf-badge ccf-badge--b">CCF B</span>
      </a>
      <div class="publication-copy">
        <p class="publication-kicker">Adaptive Reasoning · Reinforcement Learning</p>
        <h3><a href="https://arxiv.org/abs/2509.13769" target="_blank" rel="noopener">AdaThinkDrive: Adaptive Thinking via Reinforcement Learning for Autonomous Driving</a></h3>
        <p class="publication-authors"><strong>Yuechen Luo*</strong>, Fang Li*, Shaoqing Xu*, Zhiyi Lai, Lei Yang, Qimao Chen, et al.</p>
        <p class="publication-summary">AdaThinkDrive learns when to reason and when to act directly, reducing unnecessary chain-of-thought in simple scenes.</p>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2509.13769" target="_blank" rel="noopener">Paper</a>
          <a href="https://github.com/luo-yc17/AdaThinkDrive" target="_blank" rel="noopener">Repository</a>
          <span class="resource-note">Code coming soon</span>
        </div>
      </div>
    </article>

    <article class="publication-card">
      <a class="publication-figure" href="https://arxiv.org/abs/2509.20843" target="_blank" rel="noopener">
        <img src="{{ '/images/publications/mtrdrive.png' | relative_url }}" alt="MTRDrive framework" loading="lazy">
        <span class="venue-badge">ICRA 2026</span>
        <span class="ccf-badge ccf-badge--b">CCF B</span>
      </a>
      <div class="publication-copy">
        <p class="publication-kicker">Memory · Tool Use · Corner Cases</p>
        <h3><a href="https://arxiv.org/abs/2509.20843" target="_blank" rel="noopener">MTRDrive: Memory-Tool Synergistic Reasoning for Robust Autonomous Driving in Corner Cases</a></h3>
        <p class="publication-authors">Ziang Luo*, Kangan Qian*, Jiahua Wang, <strong>Yuechen Luo</strong>, Jinyu Miao, et al.</p>
        <p class="publication-summary">MTRDrive combines procedural memory retrieval with dynamic tools to improve robust reasoning in unseen construction scenarios.</p>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2509.20843" target="_blank" rel="noopener">Paper</a>
          <span class="resource-note resource-note--muted">Code not public</span>
        </div>
      </div>
    </article>

    <article class="publication-card">
      <a class="publication-figure" href="https://ojs.aaai.org/index.php/AAAI/article/view/37290" target="_blank" rel="noopener">
        <img src="{{ '/images/publications/vilta.png' | relative_url }}" alt="VILTA framework" loading="lazy">
        <span class="venue-badge">AAAI 2026</span>
        <span class="ccf-badge ccf-badge--a">CCF A</span>
      </a>
      <div class="publication-copy">
        <p class="publication-kicker">Adversarial Training · Long-Tail Robustness</p>
        <h3><a href="https://arxiv.org/abs/2601.12672" target="_blank" rel="noopener">VILTA: A VLM-in-the-Loop Adversary for Enhancing Driving Policy Robustness</a></h3>
        <p class="publication-authors">Qimao Chen*, Fang Li*, Shaoqing Xu*, Zhiyi Lai, Zixun Xie, <strong>Yuechen Luo</strong>, et al.</p>
        <p class="publication-summary">VILTA places a VLM adversary inside closed-loop training to generate challenging yet plausible agent trajectories.</p>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2601.12672" target="_blank" rel="noopener">Paper</a>
          <a href="https://ojs.aaai.org/index.php/AAAI/article/view/37290" target="_blank" rel="noopener">AAAI</a>
          <span class="resource-note resource-note--muted">Code not public</span>
        </div>
      </div>
    </article>
  </div>
</section>

<footer class="site-note">
  <p>© {{ site.time | date: '%Y' }} Yuechen Luo · Built with Jekyll and GitHub Pages.</p>
</footer>
