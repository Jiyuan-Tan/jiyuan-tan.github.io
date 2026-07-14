---
layout: home2
hero: true
title: Jiyuan Tan
description: "Jiyuan Tan is a PhD student in Management Science and Engineering at Stanford University, working on causal inference, machine learning, and trustworthy automation for data science."
tags: [causal inference, partial identification, machine learning, Stanford, econometrics]
image:
  feature: flowertank.png
---

<div class="hero">
  <img src="{{ site.url }}/images/profile.jpg" alt="Jiyuan Tan" class="hero-photo">
  <div>
    <h1 class="hero-name">Jiyuan Tan</h1>
    <p class="hero-role">PhD Student, Management Science and Engineering &middot; Stanford University</p>
    <p class="hero-tagline">Causal inference &middot; machine learning &middot; trustworthy automation for data science</p>
    <div class="hero-links">
      <a href="mailto:{{ site.owner.email }}"><i class="fa fa-envelope"></i> Email</a>
      <a href="https://scholar.google.com/citations?user={{ site.owner.google_scholar }}" target="_blank" rel="noopener"><i class="ai ai-google-scholar"></i> Google Scholar</a>
      <a href="https://github.com/{{ site.owner.github }}" target="_blank" rel="noopener"><i class="fa fa-github"></i> GitHub</a>
      <a href="{{ site.url }}/cv/"><i class="fa fa-file-text-o"></i> CV</a>
    </div>
  </div>
</div>

## About

I am a third-year PhD student in [Management Science and Engineering](https://msande.stanford.edu/) at Stanford University, co-advised by Prof. [Vasilis Syrgkanis](https://vsyrgkanis.com/) and Prof. [Jose Blanchet](https://web.stanford.edu/~jblanche/).

My research asks how far we can automate causal inference — from the statistical estimator to the AI agent — without giving up the mathematical guarantees, transparency, and domain sensitivity that scientific and policy applications require. It sits at the boundary of statistics, econometrics, machine learning, and human-centered AI.

Before Stanford, I studied mathematics at Fudan University. There I worked with Prof. [Yinyu Ye](https://web.stanford.edu/~yyye/) on [SOLNP+](https://github.com/COPT-Public/SOLNP), a derivative-free solver for general nonlinear optimization, and with Prof. [Zhaoran Wang](https://zhaoranwang.github.io/) and Prof. [Zhuoran Yang](https://www.princeton.edu/~zy6/) on offline learning in zero-sum Markov games.

## Research

<ul class="threads">
  <li>
    <h3>Partial identification</h3>
    <p>When data and assumptions cannot pin down a single causal effect, they often still imply informative bounds. I build methods — neural and optimal-transport based — that compute those bounds with consistency guarantees.</p>
  </li>
  <li>
    <h3>Automating Causal Inference</h3>
    <p>Causal estimation is full of choices that today demand an expert: regularization, tuning, estimator selection. I make those choices data-driven while keeping the theory intact.</p>
  </li>
  <li>
    <h3>Causal reasoning in AI</h3>
    <p>Can we trust an AI system's causal reasoning? I build benchmarks that test it, methods that audit a model's internal computation, and Lean-based formal verification for causal results.</p>
  </li>
</ul>

<p><a href="{{ site.url }}/research/">Read more about my research &rarr;</a></p>

## News

<ul class="news">
  <li><span class="date">May 2026</span><span>New preprint: <a href="https://arxiv.org/abs/2605.02234">Bucketing the Good Apples</a>, a diagnostic for causal abstraction in neural networks, with Puyin Li, Ahmad Jabbar, Thomas Icard, and Atticus Geiger.</span></li>
  <li><span class="date">Apr 2026</span><span>New preprint: <a href="https://arxiv.org/abs/2604.12263">partial identification of policy-relevant treatment effects with instrumental variables</a>, via optimal transport.</span></li>
  <li><span class="date">Mar 2026</span><span>New preprint: <a href="https://arxiv.org/abs/2603.01337">adaptive estimation and inference in conditional moment models</a> using the discrepancy principle.</span></li>
  <li><span class="date">Feb 2026</span><span>New preprint: <a href="https://arxiv.org/abs/2602.20571">CausalReasoningBenchmark</a>, which separates causal identification from estimation when evaluating language models.</span></li>
  <li><span class="date">Oct 2025</span><span>Talk on neural causal partial identification at the <em>INFORMS Annual Meeting</em>.</span></li>
  <li><span class="date">Sep 2025</span><span><a href="https://arxiv.org/abs/2506.14051">Estimation of Treatment Effects in Extreme and Unobserved Data</a> was accepted at <em>NeurIPS 2025</em>.</span></li>
  <li><span class="date">Jun 2025</span><span>Started a summer internship as a Data Scientist at LinkedIn, working on long-term treatment effects with debiased machine learning.</span></li>
</ul>

## Contact

The fastest way to reach me is <a href="mailto:{{ site.owner.email }}">{{ site.owner.email }}</a>. I am always glad to chat about everything.
