# Hi, I'm Dennis 👋

I build **local-first AI developer tools** -- utilities that make LLMs useful in real workflows without cloud lock-in or API costs.

Local-LLM-Tools, Open Source, made in the Ruhrgebiet.
Fokus: lauffaehige LLM-Workflows ohne Cloud-Abhaengigkeit.

## Ollama Tools

| Project | What it does | Install |
|---------|-------------|---------|
| [ollama-commit](https://github.com/dennisreichenberg/ollama-commit) | AI-generated Git commit messages via local Ollama | `pip install ollama-commit` |
| [ollama-tui](https://github.com/dennisreichenberg/ollama-tui) | Keyboard-driven Terminal UI for chatting with local Ollama models | `pip install git+https://github.com/dennisreichenberg/ollama-tui` |
| [devlog](https://github.com/dennisreichenberg/devlog) | Log daily work, generate standups & PR descriptions via local LLM | `pip install devlog` |
| [llm-bench](https://github.com/dennisreichenberg/llm-bench) | CLI benchmark suite for local LLM models | `pip install llm-bench` |
| [llm-shell](https://github.com/dennisreichenberg/llm-shell) | AI-powered shell command suggester via plain-text descriptions | `pip install llm-shell` |
| [local-rag](https://github.com/dennisreichenberg/local-rag) | Private document Q&A with local LLMs | `pip install ollama-local-rag` |
| [model-manager](https://github.com/dennisreichenberg/model-manager) | Unified Ollama model admin -- list, pull, remove, tag | `pip install model-manager` |
| [prompt-lab](https://github.com/dennisreichenberg/prompt-lab) | Side-by-side prompt testing across local Ollama models | `pip install git+https://github.com/dennisreichenberg/prompt-lab` |

## vLLM Tools

| Project | What it does | Install |
|---------|-------------|---------|
| [vllm-bench](https://github.com/dennisreichenberg/vllm-bench) | CLI benchmark for vLLM server performance (TTFT, throughput, ITL) | `pip install git+https://github.com/dennisreichenberg/vllm-bench` |
| [vllm-config](https://github.com/dennisreichenberg/vllm-config) | Hardware-aware vLLM configuration optimizer | `pip install git+https://github.com/dennisreichenberg/vllm-config` |
| [vllm-monitor](https://github.com/dennisreichenberg/vllm-monitor) | Real-time terminal dashboard for vLLM server metrics | `pip install git+https://github.com/dennisreichenberg/vllm-monitor` |

## AI Infrastructure

| Project | What it does | Install |
|---------|-------------|---------|
| [ollama-proxy](https://github.com/dennisreichenberg/ollama-proxy) | Unified OpenAI-compatible API router for Ollama and vLLM backends | `pip install ollama-proxy` |
| [agent-runner](https://github.com/dennisreichenberg/agent-runner) | CLI agent loop framework with tool use for local LLMs | `pip install agent-runner` |
| [model-eval](https://github.com/dennisreichenberg/model-eval) | Evaluate local LLM quality -- exact-match, fuzzy, and LLM-as-judge scoring | `pip install git+https://github.com/dennisreichenberg/model-eval` |
| [rag-eval](https://github.com/dennisreichenberg/rag-eval) | Evaluate local RAG pipelines -- recall@k, MRR, BLEU/ROUGE and LLM-as-judge | `pip install rag-eval` |

## Self-Hosted Stack

External open-source tools that Dennis self-hosts alongside his CLI tools. Configs, secrets templates and integration notes live in [reichenberg-ruhr](https://github.com/dennisreichenberg/reichenberg-ruhr). These are third-party OSS projects, not authored by Dennis.

| Component | What it does | Dennis's Config |
|-----------|-------------|-----------------|
| [Langfuse](https://github.com/langfuse/langfuse) | Self-hosted LLM observability -- traces, evals, prompt management and cost tracking across all local-LLM tools | [config](https://github.com/dennisreichenberg/reichenberg-ruhr/tree/main/langfuse) (UI on :3030) |
| [LiteLLM Proxy](https://github.com/BerriAI/litellm) | OpenAI-compatible unified API gateway for Ollama and vLLM, with optional Langfuse callback | [config](https://github.com/dennisreichenberg/reichenberg-ruhr/tree/main/litellm-proxy) (proxy on :4000) |

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![CLI](https://img.shields.io/badge/CLI_tools-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Open Source](https://img.shields.io/badge/Open_Source-red?style=flat)

## Philosophy

All my tools run **100% locally**. No API keys. No usage costs. No data leaving your machine. If you have [Ollama](https://ollama.com) installed, you already have everything you need.

---

🌐 [reichenberg.ruhr](https://reichenberg.ruhr) · 📦 [PyPI](https://pypi.org/user/dennisreichenberg/)

<!-- profile-repo-updater:pinned:start -->
## Pinned Tools

- **[agent-runner](https://github.com/dennisreichenberg/agent-runner)** -- CLI-based local agent loop with tool-use via Ollama
- **ai-doctor** -- Unified health/status CLI for a local AI stack (Ollama, llm-gateway, vLLM, local-rag)
- **[ai-stack](https://github.com/dennisreichenberg/ai-stack)** -- Lifecycle supervisor for the local AI stack (Ollama, vLLM, ollama-proxy/llm-gateway, n8n)
- **[devlog](https://github.com/dennisreichenberg/devlog)** -- AI-powered developer diary: log your work, generate weekly summaries and PR descriptions via local LLMs
- **[llm-bench](https://github.com/dennisreichenberg/llm-bench)** -- Benchmark local LLMs via Ollama — measure tokens/s, TTFT, and memory usage
- **llm-gateway** -- Local OpenAI-compatible proxy that routes by model prefix and tracks token cost across providers
<!-- profile-repo-updater:pinned:end -->
