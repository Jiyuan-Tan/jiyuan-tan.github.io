---
layout: publications
permalink: /publications/
title: Publications
description: "Papers by Jiyuan Tan on causal inference, partial identification, machine learning, and optimization."
tags: [publications]
modified: 7-28-2026
comments: false
image:
  feature: yftank.png
---

Also on <a href="https://scholar.google.com/citations?user={{ site.owner.google_scholar }}&hl=en" target="_blank" rel="noopener">Google Scholar</a>. An asterisk (\*) marks equal contribution or alphabetical author order.

## Preprints

<ul class="pub-list">
  <li class="pub">
    <span class="venue venue-preprint">Preprint<br>2026</span>
    <div>
      <span class="pub-title">CausalForge: A Formally Grounded, Self-Improving Agentic Framework for Automated Research in Causal Inference</span>
      <span class="pub-authors"><span class="me">Jiyuan Tan</span>*, Vasilis Syrgkanis</span>
      <span class="pub-note">Couples language models with machine-checked proofs: Causalean, a Lean library for causal inference with 7,035 verified declarations, and CausalSmith, an autonomous pipeline that proposes and formalizes new results, with a statement audit that checks each formal theorem against its informal claim.</span>
      <span class="pub-links"><a href="https://arxiv.org/abs/2607.22511" target="_blank" rel="noopener">arXiv</a><a href="https://jiyuan-tan.github.io/CausalForge/" target="_blank" rel="noopener">Website</a><a href="https://github.com/Jiyuan-Tan/CausalForge" target="_blank" rel="noopener">Code</a></span>
    </div>
  </li>

  <li class="pub">
    <span class="venue venue-preprint">Preprint<br>2026</span>
    <div>
      <span class="pub-title">Bucketing the Good Apples: A Method for Diagnosing and Improving Causal Abstraction</span>
      <span class="pub-authors">Puyin Li*, <span class="me">Jiyuan Tan</span>*, Ahmad Jabbar, Thomas Icard, Atticus Geiger</span>
      <span class="pub-note">A diagnostic for causal abstraction in neural networks, used to localize and repair failures of interpretability probes on language models.</span>
      <span class="pub-links"><a href="https://arxiv.org/abs/2605.02234" target="_blank" rel="noopener">arXiv</a></span>
    </div>
  </li>

  <li class="pub">
    <span class="venue venue-preprint">Preprint<br>2026</span>
    <div>
      <span class="pub-title">Partial Identification of Policy-Relevant Treatment Effects with Instrumental Variables via Optimal Transport</span>
      <span class="pub-authors"><span class="me">Jiyuan Tan</span>*, Vasilis Syrgkanis, Jose Blanchet</span>
      <span class="pub-note">Casts partial identification with instrumental variables as an optimal-transport problem, giving a tractable estimator with finite-sample guarantees.</span>
      <span class="pub-links"><a href="https://arxiv.org/abs/2604.12263" target="_blank" rel="noopener">arXiv</a></span>
    </div>
  </li>

  <li class="pub">
    <span class="venue venue-preprint">Preprint<br>2026</span>
    <div>
      <span class="pub-title">Adaptive Estimation and Inference in Conditional Moment Models via the Discrepancy Principle</span>
      <span class="pub-authors"><span class="me">Jiyuan Tan</span>*, Vasilis Syrgkanis</span>
      <span class="pub-note">Data-driven regularization for conditional moment models, including nonparametric IV, with oracle inequalities and valid inference.</span>
      <span class="pub-links"><a href="https://arxiv.org/abs/2603.01337" target="_blank" rel="noopener">arXiv</a></span>
    </div>
  </li>

  <li class="pub">
    <span class="venue venue-preprint">Preprint<br>2026</span>
    <div>
      <span class="pub-title">CausalReasoningBenchmark: A Real-World Benchmark for Disentangled Evaluation of Causal Identification and Estimation</span>
      <span class="pub-authors">Ayush Sawarni, <span class="me">Jiyuan Tan</span>, Vasilis Syrgkanis</span>
      <span class="pub-note">A benchmark built from published empirical studies that separates causal identification from estimation, enabling fine-grained evaluation of language models and causal methods.</span>
      <span class="pub-links"><a href="https://arxiv.org/abs/2602.20571" target="_blank" rel="noopener">arXiv</a></span>
    </div>
  </li>

</ul>

## Journal publications

<ul class="pub-list">
  <li class="pub">
    <span class="venue">ACM TOMS<br>2024</span>
    <div>
      <span class="pub-title">Algorithm 1053: SOLNP+: A Derivative-Free Solver for Constrained Nonlinear Optimization</span>
      <span class="pub-authors">Dongdong Ge, Jinsong Liu, Tianhao Liu, <span class="me">Jiyuan Tan</span>, Yinyu Ye* <em>(alphabetical order)</em></span>
      <span class="pub-note"><em>ACM Transactions on Mathematical Software</em>, 50(4), Article 29, 1&ndash;24. An ANSI C solver for constrained nonlinear optimization, made robust to noisy function evaluations via implicit filtering and coordinate search.</span>
      <span class="pub-links"><a href="https://doi.org/10.1145/3699956" target="_blank" rel="noopener">Paper</a><a href="https://arxiv.org/abs/2210.07160" target="_blank" rel="noopener">arXiv</a><a href="https://github.com/COPT-Public/SOLNP_plus" target="_blank" rel="noopener">Code</a></span>
    </div>
  </li>
</ul>

## Conference publications

<ul class="pub-list">
  <li class="pub">
    <span class="venue">NeurIPS<br>2025</span>
    <div>
      <span class="pub-title">Estimation of Treatment Effects in Extreme and Unobserved Data</span>
      <span class="pub-authors"><span class="me">Jiyuan Tan</span>*, Jose Blanchet, Vasilis Syrgkanis</span>
      <span class="pub-note">An extreme-value estimator for treatment effects beyond the observed support of the data, with consistency guarantees and validation on synthetic and real data.</span>
      <span class="pub-links"><a href="https://arxiv.org/abs/2506.14051" target="_blank" rel="noopener">arXiv</a></span>
    </div>
  </li>

  <li class="pub">
    <span class="venue">NeurIPS<br>2024</span>
    <div>
      <span class="pub-title">Consistency of Neural Causal Partial Identification</span>
      <span class="pub-authors"><span class="me">Jiyuan Tan</span>, Jose Blanchet, Vasilis Syrgkanis</span>
      <span class="pub-note">A generative method for computing partial-identification bounds under structural causal constraints, with a consistency proof and an analysis of the model class's approximation power.</span>
      <span class="pub-links"><a href="https://arxiv.org/abs/2405.15673" target="_blank" rel="noopener">arXiv</a></span>
    </div>
  </li>

  <li class="pub">
    <span class="venue">UAI<br>2024</span>
    <div>
      <span class="pub-title">A Homogenization Approach for Gradient-Dominated Stochastic Optimization</span>
      <span class="pub-authors"><span class="me">Jiyuan Tan</span>*, Chenyu Xue*, Chuwen Zhang, Qi Deng, Dongdong Ge, Yinyu Ye</span>
      <span class="pub-note">A homogenized second-order method for gradient-dominated stochastic optimization, including policy optimization, with state-of-the-art sample-complexity guarantees.</span>
      <span class="pub-links"><a href="https://arxiv.org/abs/2308.10630" target="_blank" rel="noopener">arXiv</a></span>
    </div>
  </li>

  <li class="pub">
    <span class="venue">ICML<br>2022</span>
    <div>
      <span class="pub-title">Pessimistic Minimax Value Iteration: Provably Efficient Equilibrium Learning from Offline Datasets</span>
      <span class="pub-authors">Han Zhong*, Wei Xiong*, <span class="me">Jiyuan Tan</span>*, Liwei Wang, Tong Zhang, Zhaoran Wang, Zhuoran Yang</span>
      <span class="pub-note">Characterizes the data coverage needed to learn Nash equilibria from offline Markov-game data, with a pessimistic algorithm attaining minimax-optimal sample complexity. Spotlight at the ICLR 2022 Workshop on Gamification and Multiagent Solutions.</span>
      <span class="pub-links"><a href="https://arxiv.org/abs/2202.07511" target="_blank" rel="noopener">arXiv</a></span>
    </div>
  </li>
</ul>

## Talks

<ul class="news">
  <li><span class="date">2025</span><span><em>Consistency of Neural Causal Partial Identification</em> &mdash; INFORMS Annual Meeting.</span></li>
  <li><span class="date">2024</span><span><em>Consistency of Neural Causal Partial Identification</em> &mdash; California Econometrics Conference (CEC).</span></li>
</ul>
