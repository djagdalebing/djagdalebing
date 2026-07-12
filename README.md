# Devang Jagdale

**AI Engineer — LLM systems, retrieval, and agents.**

I build generative AI systems from first principles: transformer internals, retrieval pipelines, and agentic architectures — with an emphasis on understanding *why* things work, not just wiring libraries together.

📍 Binghamton University &nbsp;·&nbsp; 📫 djagdale@binghamton.edu

---

## Featured Projects

| Project | What it demonstrates |
|---|---|
| [**llm-from-scratch**](https://github.com/djagdalebing/llm-from-scratch) | A decoder-only GPT implemented from first principles in PyTorch — manual multi-head causal attention, a from-scratch BPE tokenizer, KV-cache incremental decoding, and **LoRA fine-tuning implemented from the math up** (no HuggingFace/PEFT). Trained end-to-end on CPU with a full test suite. |
| [**rag-engine**](https://github.com/djagdalebing/rag-engine) | A hybrid-retrieval RAG system built without LangChain: **BM25 from scratch**, dense vector search, reciprocal rank fusion, three chunking strategies, citation-grounded generation, and a retrieval **evaluation harness** (recall@k, MRR, nDCG) comparing retrieval modes on a labeled query set. |
| [**agent-forge**](https://github.com/djagdalebing/agent-forge) | A minimal LLM agent framework from scratch: the tool-calling loop, auto-generated JSON Schema tool definitions from Python type hints, **ReAct** for models without native tool use, token-budget-aware memory, and **multi-agent orchestration** (supervisor/router, pipelines, parallel fan-out) — fully tested with deterministic providers. |
| [**llmscope**](https://github.com/djagdalebing/llmscope) | An **LLM observability platform** from scratch (Langfuse-lite): tracing SDK with nested spans, token/cost analytics, latency percentiles, guardrail checks (PII, refusals), **PSI-based drift detection**, an alerting rules engine, and a dependency-free SVG dashboard — shipped with a **production-grade CI/CD pipeline** (Actions test matrix, coverage gate, Docker → GHCR, automated releases). |
| [**flowforge**](https://github.com/djagdalebing/flowforge) | An **n8n-style workflow automation engine**: JSON-defined DAG workflows, a safe template-expression parser (no `eval`), from-scratch cron parsing and scheduling, webhook triggers, per-node retries with error-branch routing, and offline-testable AI nodes — stdlib-only core, 186 tests. |

Each project implements its core algorithms directly (attention, BM25, RRF, LoRA, the agent loop) rather than importing them, and every number in every README comes from a real, reproducible run.

## Focus Areas

- **LLM internals** — transformer architecture, tokenization (BPE), sampling strategies, KV caching, parameter-efficient fine-tuning (LoRA)
- **Retrieval & RAG** — hybrid sparse + dense retrieval, rank fusion, reranking, chunking, retrieval evaluation
- **Agents** — tool use, ReAct, memory management, multi-agent orchestration, trajectory tracing for evals
- **LLM Ops** — tracing/observability, cost accounting, drift detection, guardrails, alerting; workflow automation
- **Engineering** — Python, PyTorch, NumPy, FastAPI, pytest; Docker, GitHub Actions CI/CD; Anthropic & OpenAI APIs

## Currently

Exploring LLM evaluation methodology, LLM observability, and inference-time optimization. Open to AI/ML engineering roles and collaborations.

---

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=djagdalebing&show_icons=true&theme=default&hide_border=true&hide_title=true" alt="GitHub stats" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=djagdalebing&layout=compact&hide_border=true" alt="Top languages" height="150"/>
</p>
