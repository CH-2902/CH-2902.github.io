---
title: "MiAO MCP for Unity"
date: 2025-09-01
summary: "Open-source Model Context Protocol server that lets LLM coding agents (Claude Code, etc.) operate inside the Unity Editor. Contributor at Miao Worlds."
links:
  - type: site
    url: https://github.com/MiAO-AI-Lab/MiAO-MCP-for-Unity
  - type: custom
    label: GitHub
    url: https://github.com/MiAO-AI-Lab/MiAO-MCP-for-Unity
tags:
  - LLM Agents
  - MCP
  - Unity
  - C#
  - Python
weight: 20
---

Open-source MCP server developed at Miao Worlds that exposes Unity Editor
operations as tools for LLM coding agents (Claude Code, Cursor, etc.) over
the Model Context Protocol. Lets autonomous agents read scene state, edit
GameObjects, run editor scripts, and iterate on Unity projects without
human-in-the-loop.

**My contribution:** Used this MCP surface area as the substrate for a
benchmarking framework that I built separately to evaluate Miao's agentic
IDE assistants vs. Claude Code (Sonnet 4.5/4.6) head-to-head on **74 tasks
across 6 categories**, with an isolated Task Loader to prevent reward
hacking. Paper in preparation.

**Note:** This is the public, earlier-version repository — the production
product has since evolved beyond what's open-sourced.

**Stack:** C# · Python · Unity Editor APIs · Model Context Protocol.
