# Hi, I'm Tima

Maintainer/contributor around agent tooling and multi-channel assistant workflows.
I focus on practical engineering: issue reproduction, real behavior testing, and shipping fixes that survive production traffic.
Recent work includes MiniRouter routing/eval infrastructure and competition tooling.

## 🚀 Start Here

- <img src="https://github.com/mini-router.png" width="20" align="center"/> **[mini-router/minirouter](https://github.com/mini-router/minirouter)** - Gittensor miner workspace for MiniRouter: routing trainer/eval code, benchmarks, submissions, and the web competition site
- <img src="https://github.com/touchpilot.png" width="20" align="center"/> **[touchpilot/touchpilot](https://github.com/touchpilot/touchpilot)** - Automation and control workflow experiments
- <img src="https://github.com/openclaw.png" width="20" align="center"/> **[openclaw/openclaw](https://github.com/openclaw/openclaw)** - Personal AI assistant across CLI, WebUI, Slack, Telegram, Discord, Matrix
- <img src="https://github.com/infiniflow.png" width="20" align="center"/> **[infiniflow/ragflow](https://github.com/infiniflow/ragflow)** - RAG engine: Go driver implementations and provider integrations
- <img src="https://github.com/langgenius.png" width="20" align="center"/> **[langgenius/dify](https://github.com/langgenius/dify)** - LLMOps platform: EnumText type-tightening sweep across the API

## 🛠️ Open Source Contributions

### Agent & Assistant Platforms

- <img src="https://github.com/openclaw.png" width="20" align="center"/> **[openclaw/openclaw](https://github.com/openclaw/openclaw)** - Telegram transport, daemon reliability, UI session state, gateway RPCs
- <img src="https://github.com/langgenius.png" width="20" align="center"/> **[langgenius/dify](https://github.com/langgenius/dify)** - EnumText migration, null-safety, and pyright cleanup across `api/`
- <img src="https://github.com/NousResearch.png" width="20" align="center"/> **[NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)** - Gateway platform-connect failure isolation
- <img src="https://github.com/OpenCoven.png" width="20" align="center"/> **[OpenCoven/open-meow-sdk](https://github.com/OpenCoven/open-meow-sdk)** - Cross-platform fixture validation path handling

### RAG, Embeddings & Model Providers

- <img src="https://github.com/infiniflow.png" width="20" align="center"/> **[infiniflow/ragflow](https://github.com/infiniflow/ragflow)** - Go model drivers (LongCat, Voyage AI, StepFun, Novita.ai, Mistral, Upstage, LocalAI rerank), Perplexity embeddings, OpenSearch doc-meta dispatch, async DB/Redis offload
- <img src="https://github.com/run-llama.png" width="20" align="center"/> **[run-llama/llama_index](https://github.com/run-llama/llama_index)** - sqlite-vec vector store integration
- <img src="https://github.com/llmsresearch.png" width="20" align="center"/> **[llmsresearch/paperbanana](https://github.com/llmsresearch/paperbanana)** - Cost estimation, budget guards, per-item status table for batch runs

### Data, Compilers & Systems

- <img src="https://github.com/pola-rs.png" width="20" align="center"/> **[pola-rs/polars](https://github.com/pola-rs/polars)** - Decimal32/64 support in `scan_parquet`
- <img src="https://github.com/denoland.png" width="20" align="center"/> **[denoland/deno](https://github.com/denoland/deno)** - `fs.watch` events firing for immediate writes in `ext/node`
- <img src="https://github.com/astral-sh.png" width="20" align="center"/> **[astral-sh/ruff](https://github.com/astral-sh/ruff)** - Recognize `pyrefly:` as a pragma comment in `E501`
- <img src="https://github.com/llvm.png" width="20" align="center"/> **[llvm/llvm-project](https://github.com/llvm/llvm-project)** - Inliner: persist inline history across devirt iterations via IR metadata
- <img src="https://github.com/google.png" width="20" align="center"/> **[google/flatbuffers](https://github.com/google/flatbuffers)** - Fix inconsistent Python union creator function naming
- <img src="https://github.com/dbeaver.png" width="20" align="center"/> **[dbeaver/dbeaver](https://github.com/dbeaver/dbeaver)** - Support inline ORDER BY inside aggregate functions
- <img src="https://github.com/bitcoinj.png" width="20" align="center"/> **[bitcoinj/bitcoinj](https://github.com/bitcoinj/bitcoinj)** - VersionMessage: make immutable with Builder pattern

### Web & Frontend

- <img src="https://github.com/withastro.png" width="20" align="center"/> **[withastro/astro](https://github.com/withastro/astro)** - Append `assetQueryParams` to inter-chunk JS imports
- <img src="https://github.com/penpot.png" width="20" align="center"/> **[penpot/penpot](https://github.com/penpot/penpot)** - Modern component syntax migrations (code-block, link, frame-preview, icons-preview, debug playground, inspect fill/stroke) and plugin schema-error formatter fix

### Crypto & Subnet Tooling

- <img src="https://github.com/mini-router.png" width="20" align="center"/> **[mini-router/minirouter](https://github.com/mini-router/minirouter)** - Gittensor miner workspace for router training, evaluation, submissions, and competition operations
- <img src="https://github.com/entrius.png" width="20" align="center"/> **[entrius/gittensor](https://github.com/entrius/gittensor)** - Stale miner cleanup when hotkey re-links to a new GitHub account
- <img src="https://github.com/entrius.png" width="20" align="center"/> **[entrius/gittensor-ui](https://github.com/entrius/gittensor-ui)** - Leaderboard sidebar dedupe, README link fixes, shared formatting helpers
- <img src="https://github.com/latent-to.png" width="20" align="center"/> **[latent-to/btcli](https://github.com/latent-to/btcli)** - Extensions framework for custom `btcli` plugins
- <img src="https://github.com/Desearch-ai.png" width="20" align="center"/> **[Desearch-ai/linkedin-dms](https://github.com/Desearch-ai/linkedin-dms)** - `POST /accounts/refresh` session cookie renewal, Chrome extension popup UI

## 🎯 What I Usually Work On

- Cross-channel behavior debugging (Slack / Telegram / Discord / WebUI)
- E2E reproduction and verification before/after fixes
- PR quality passes: conflict resolution, cleanup of stale code paths, focused regression checks
- Automation and developer tooling around issue triage and agent workflows

### ⌨️ Development Language

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111111)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## 🛠️ Recently I'm coding in...

![OpenClaw](https://img.shields.io/badge/OpenClaw-Issue%20Fixing-0A0A0A?style=for-the-badge)
![Slack](https://img.shields.io/badge/Slack-Behavior%20Testing-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-E2E%20Validation-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)
![WebUI](https://img.shields.io/badge/WebUI-Reply%20Flow%20Checks-2563EB?style=for-the-badge)
![MiniRouter](https://img.shields.io/badge/MiniRouter-Routing%20%26%20Eval-111827?style=for-the-badge)

---

If you're working on OpenClaw channel behavior or integration reliability, feel free to reach out.
