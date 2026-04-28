---
title: "Dual-Agent Architecture for Zero-Shot 3D PCG"
date: 2025-12-10
summary: "First-authored arXiv paper. Training-free Actor–Critic LLM system for zero-shot 3D procedural content generation — 80% task success, +20% over single-agent baselines."
links:
  - type: custom
    label: arXiv 2512.10501
    url: https://arxiv.org/abs/2512.10501
tags:
  - LLM Agents
  - Multi-Agent Systems
  - Procedural Content Generation
  - Research
weight: 10
---

A training-free dual-agent (Actor–Critic) architecture for zero-shot 3D
procedural content generation. Eliminates the fine-tuning and reinforcement-
learning steps required by prior LLM-based PCG methods, and achieves an **80%
task success rate** — a **20 percentage-point improvement** over single-agent
baselines under the same prompting and resource budget.

**Role:** First author. Designed the agent decomposition, evaluation protocol,
and ran all benchmarks.

**Stack:** Claude · multi-agent orchestration · Python · 3D evaluation harness.

**Read the paper:** [arXiv:2512.10501](https://arxiv.org/abs/2512.10501).
