---
title: "Full-Stack Code-Aware RAG Infrastructure"
date: 2025-10-01
summary: "Production retrieval system for an LLM coding agent at Miao Worlds. Two-stage retrieval, AST-aware indexing, Merkle-tree incremental sync, deployed on FastAPI + MongoDB + Docker."
tags:
  - Retrieval-Augmented Generation
  - LLM Agents
  - FastAPI
  - MongoDB
  - Docker
weight: 30
---

Production-grade RAG infrastructure I built at Miao Worlds to ground the
company's LLM coding agent in real codebases.

**What it does**

- **Two-stage retrieval:** FAISS dense vector search for recall, cross-encoder
  re-ranking for precision.
- **Tree-sitter AST indexing:** chunks code along structural boundaries
  (functions, classes, modules) instead of fixed-size text windows, so
  retrieved snippets are always syntactically meaningful.
- **Merkle-tree incremental sync:** large codebases re-ingest in seconds —
  only changed subtrees are re-embedded, not the whole project.
- **Agent-callable tool:** semantic search is exposed via the LLM's tool-use
  loop, materially reducing hallucinated API calls.

**Deployment:** GPU-accelerated FastAPI service backed by MongoDB, packaged
with Docker.

**Stack:** Python · FastAPI · MongoDB · Docker · FAISS · cross-encoder rerankers
· tree-sitter.

*Code is internal to Miao Worlds — happy to discuss design and trade-offs in
detail.*
