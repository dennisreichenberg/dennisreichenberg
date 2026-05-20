# Hi, I'm Dennis 👋

I build **local-first AI developer tools** -- utilities that make LLMs useful in real workflows without cloud lock-in or API costs.

Local-LLM-Tools, Open Source, made in the Ruhrgebiet.
Fokus: lauffaehige LLM-Workflows ohne Cloud-Abhaengigkeit.

## Ollama Tools

| Project | What it does | Install |
|---------|-------------|---------|
| [ollama-commit](https://github.com/dennisreichenberg/ollama-commit) | AI-generated Git commit messages via local Ollama | `pip install ollama-commit` |
| [ollama-tui](https://github.com/dennisreichenberg/ollama-tui) | Keyboard-driven Terminal UI for chatting with local Ollama models | Coming soon |
| [devlog](https://github.com/dennisreichenberg/devlog) | Log daily work, generate standups & PR descriptions via local LLM | `pip install devlog` |
| [llm-bench](https://github.com/dennisreichenberg/llm-bench) | CLI benchmark suite for local LLM models | `pip install llm-bench` |
| [llm-shell](https://github.com/dennisreichenberg/llm-shell) | AI-powered shell command suggester via plain-text descriptions | `pip install llm-shell` |
| [local-rag](https://github.com/dennisreichenberg/local-rag) | Private document Q&A with local LLMs | `pip install ollama-local-rag` |
| [model-manager](https://github.com/dennisreichenberg/model-manager) | Unified Ollama model admin -- list, pull, remove, tag | `pip install model-manager` |
| [prompt-lab](https://github.com/dennisreichenberg/prompt-lab) | Side-by-side prompt testing across local Ollama models | Coming soon |

## vLLM Tools

| Project | What it does | Install |
|---------|-------------|---------|
| [vllm-bench](https://github.com/dennisreichenberg/vllm-bench) | CLI benchmark for vLLM server performance (TTFT, throughput, ITL) | Coming soon |
| [vllm-config](https://github.com/dennisreichenberg/vllm-config) | Hardware-aware vLLM configuration optimizer | Coming soon |
| [vllm-monitor](https://github.com/dennisreichenberg/vllm-monitor) | Real-time terminal dashboard for vLLM server metrics | Coming soon |

## AI Infrastructure

| Project | What it does | Install |
|---------|-------------|---------|
| [ollama-proxy](https://github.com/dennisreichenberg/ollama-proxy) | Unified OpenAI-compatible API router for Ollama and vLLM backends | `pip install ollama-proxy` |
| [agent-runner](https://github.com/dennisreichenberg/agent-runner) | CLI agent loop framework with tool use for local LLMs | `pip install agent-runner` |
| [model-eval](https://github.com/dennisreichenberg/model-eval) | Evaluate local LLM quality -- exact-match, fuzzy, and LLM-as-judge scoring | Coming soon |

## Self-Hosted Stack

Docker Compose setups for running open-source LLM-ops infrastructure alongside the CLI tools above. Configs, secrets templates and integration notes live in [reichenberg-ruhr](https://github.com/dennisreichenberg/reichenberg-ruhr).

| Component | What it does | Setup |
|-----------|-------------|-------|
| [langfuse](https://github.com/dennisreichenberg/reichenberg-ruhr/tree/main/langfuse) | Self-hosted LLM observability -- traces, evals, prompt management and cost tracking across all local-LLM tools | `docker compose up -d` (UI on :3030) |
| [litellm-proxy](https://github.com/dennisreichenberg/reichenberg-ruhr/tree/main/litellm-proxy) | OpenAI-compatible unified API gateway for Ollama and vLLM, with optional Langfuse callback | `docker compose up -d` (proxy on :4000) |

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![CLI](https://img.shields.io/badge/CLI_tools-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Open Source](https://img.shields.io/badge/Open_Source-red?style=flat)

## Philosophy

All my tools run **100% locally**. No API keys. No usage costs. No data leaving your machine. If you have [Ollama](https://ollama.com) installed, you already have everything you need.

---

🌐 [reichenberg.ruhr](https://reichenberg.ruhr) · 📦 [PyPI](https://pypi.org/user/dennisreichenberg/)