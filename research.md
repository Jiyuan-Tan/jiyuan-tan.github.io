---
layout: page
permalink: /research/
title: Research
description: "Jiyuan Tan's research on causal partial identification, adaptive causal estimation, and the causal reasoning of AI systems."
tags: [causal inference, partial identification, machine learning, formal verification]
comments: false
image:
  feature: flowertank_2.png
---

My research develops reliable methods for causal inference and human-centered AI, with a focus on trustworthy automation for data science. It is organized around a single question:

<div class="note">
How can we automate causal inference — from the statistical estimator to the AI agent — without giving up the mathematical guarantees, transparency, and domain sensitivity that scientific and policy applications require?
</div>

I pursue that question along two complementary lines. The **theoretical** line develops statistical and computational methods that automate parts of causal analysis which currently demand substantial expert judgment, while preserving rigorous guarantees. The **empirical** line studies how AI systems themselves reason about cause and effect, and builds tools to evaluate and formally verify that reasoning.

## Partial identification: making uncertainty explicit

In many empirical settings, the data and assumptions are not strong enough to identify a single causal estimand, but they still imply informative bounds. I treat partial identification not as a last resort but as a principled way to report what the data can and cannot support: where a point estimate would over-promise precision, credible bounds tell decision-makers the truth.

- [Consistency of Neural Causal Partial Identification](https://arxiv.org/abs/2405.15673) (NeurIPS 2024) gives a general computational approach to partial identification under structural causal constraints, proves consistency, and characterizes the approximation power of the model class.
- [Partial Identification of Policy-Relevant Treatment Effects with Instrumental Variables via Optimal Transport](https://arxiv.org/abs/2604.12263) casts the problem as optimal transport and derives a tractable estimator with finite-sample guarantees, for settings where researchers need interpretable bounds under credible but incomplete assumptions.

## Automating causal inference

Causal and econometric estimation is full of decisions that today rest on an expert's intuition — how much to regularize, which estimator to trust, how to tune it. These choices can decide whether an estimator is stable or misleading, especially in ill-posed problems that recur across empirical economics, from demand estimation to program evaluation.

- [Adaptive Estimation and Inference in Conditional Moment Models via the Discrepancy Principle](https://arxiv.org/abs/2603.01337) selects regularization parameters from the data in nonparametric instrumental-variable problems, with oracle inequalities and valid inference.
- During a summer at LinkedIn, I prototyped a debiased machine learning framework for predicting long-term treatment effects when short-term A/B-test outcomes are noisy or delayed, and identified failure modes under confounding shifts.

Making these choices data-driven and theoretically controlled lowers the barrier between advanced causal methodology and reliable empirical practice.

## How AI systems reason about cause and effect

The same question, turned on AI itself: is a model's causal reasoning real, or only apparent? I study this at two levels.

At the level of **behavior**, [CausalReasoningBenchmark](https://arxiv.org/abs/2602.20571) builds a benchmark from published empirical studies that separates causal *identification* from causal *estimation*. The separation matters: a fluent causal explanation can still rest on the wrong identification conditions or target the wrong estimand.

At the level of **internal mechanism**, [Bucketing the Good Apples](https://arxiv.org/abs/2605.02234) studies causal abstraction — whether a model's internal computation faithfully realizes a higher-level causal structure — and gives a method for diagnosing and repairing where that abstraction breaks down.

## Formally verified causal inference

My current work brings the two lines together. [CausalSmith](https://arxiv.org/abs/2607.22511) is an agentic framework for automated research in causal inference in which every formal statement is machine-checked in Lean 4. It has two halves: **Causalean**, a foundational Lean library for causal inference with 7,035 verified declarations, and **CausalForge**, an autonomous pipeline in which agents propose structured causal questions, develop candidate theorems, and submit them to formal verification.

Automating research raises an evaluation problem of its own: a theorem can be perfectly verified and still fail to say what its informal abstract claims. CausalSmith therefore includes a **statement audit** that checks each formal theorem against the scientific claim it is meant to express — a check that does not rely on an LLM reviewer's judgment about whether a result is correct.

The resulting working papers, together with the underlying Lean code, are browsable on the [project website](https://jiyuan-tan.github.io/CausalSmith/). The aim is to let AI assist with literature organization, theorem discovery, and proof checking, while the human retains responsibility for judgment.

## Other work

Some questions do not belong to any of the three threads above.

**Treatment effects in the tails.** [Estimation of Treatment Effects in Extreme and Unobserved Data](https://arxiv.org/abs/2506.14051) (NeurIPS 2025) asks what can be said about treatment effects in regions the data barely reach. Rather than bounding the effect, it uses extreme-value theory to extrapolate beyond the observed support, with consistency guarantees and validation on synthetic and real data.

**Optimization and reinforcement learning.** Before turning to causal inference, I worked on a [homogenization approach for gradient-dominated stochastic optimization](https://arxiv.org/abs/2308.10630) (UAI 2024), the derivative-free solver [SOLNP+](https://github.com/COPT-Public/SOLNP_plus), and [pessimistic minimax value iteration](https://arxiv.org/abs/2202.07511) (ICML 2022), which characterizes the data coverage needed to learn Nash equilibria offline.

<p><a href="{{ site.url }}/publications/">See all publications &rarr;</a></p>
