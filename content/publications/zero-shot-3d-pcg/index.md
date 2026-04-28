---
title: "Zero-Shot 3D Map Generation with LLM Agents: A Dual-Agent Architecture for Procedural Content Generation"
authors:
  - me
date: "2025-12-10T00:00:00Z"
publishDate: "2025-12-10T00:00:00Z"

publication_types: ["article"]
publication: "arXiv preprint arXiv:2512.10501"
publication_short: "arXiv 2512.10501"

abstract: |
  We propose a training-free dual-agent architecture for zero-shot 3D
  procedural content generation (PCG), eliminating the fine-tuning and
  reinforcement-learning loops that prior LLM-based PCG methods rely on.
  The system pairs an Actor agent — which proposes 3D map layouts — with a
  Critic agent that evaluates and refines them against task-level objectives.
  This Actor–Critic decomposition lets the system exploit large pre-trained
  LLMs' spatial reasoning without any task-specific training, and yields an
  80% task success rate — a 20-percentage-point improvement over single-agent
  baselines under the same prompting and resource budget.

summary: |
  A training-free dual-agent (Actor–Critic) architecture for zero-shot 3D
  procedural content generation. Achieves 80% task success — a 20-point
  improvement over single-agent baselines without any fine-tuning or RL.

tags:
  - LLM Agents
  - Procedural Content Generation
  - 3D Generation
  - Multi-Agent Systems

featured: true

hugoblox:
  ids:
    arxiv: "2512.10501"

links:
  - type: preprint
    provider: arxiv
    id: "2512.10501"
  - type: custom
    label: arXiv PDF
    url: https://arxiv.org/abs/2512.10501

projects: []
slides: ""
---

This work was done while I was an AI Engineer at Miao Worlds. The full PDF
is on [arXiv](https://arxiv.org/abs/2512.10501).
