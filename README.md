# Alexandre Blanchard

Full-stack product engineer, AI-accelerated. I build end-to-end products — backend,
frontend, LLM integration — and I measure them honestly before I trust them. I also do a fair amount of
quantitative research, where the discipline is mostly about *not* fooling yourself.

Open to AI / product / full-stack engineer roles.

## Stack

- **Languages** — Python, TypeScript / JavaScript, Rust (learning)
- **Backend** — FastAPI, axum, REST APIs, SQLite / MongoDB, Docker
- **Frontend** — React, Next.js, Streamlit, Chrome extensions
- **AI / ML** — LLM orchestration with multi-provider failover, computer vision (OpenCV), Whisper, scikit-learn
- **Quant / data** — backtesting, statistical validation (DSR, PBO/CSCV, Bonferroni), data pipelines
- **Tooling** — Git, GitHub Actions (CI), FFmpeg

## Projects

| Project | What it is | Stack |
|---|---|---|
| [dexcheck](https://github.com/ablanchard-dev/dexcheck) | Read-only anti-cheat PC check for Call of Duty / Warzone screen-share vetting: 40 probes on traces that survive deletion (USN journal, Prefetch, Shimcache…), one double-click, verdict tuned so a clean PC comes out clean. 270+ tests in CI | PowerShell, bash |
| [lumenia](https://github.com/ablanchard-dev/lumenia) | Full-stack AI assistant for neurodivergent people (HPI / ASD / ADHD): multi-LLM failover, server-enforced entry gate, and crisis detection | FastAPI, multi-LLM, JS |

### Quant research & backtesting infrastructure

The same discipline applied to three very different venues (traditional brokerage, crypto
perps, prediction markets): measure an edge honestly before trusting it. None of them
claims a profit, and each repository states its limits.

| Project | What it is | Stack |
|---|---|---|
| [dexterio](https://github.com/ablanchard-dev/dexterio) | Backtest engine for US ETFs and index futures: stop checked before take-profit inside a bar, IBKR commission models, ideal vs conservative fill models, 590+ tests | Python, FastAPI, React |
| [edge-factory](https://github.com/ablanchard-dev/edge-factory) | A critic that kills false edges: residual alpha after beta, Deflated Sharpe deflated by the measured variance of all trials, tail/convexity check; PBO/CSCV and permutation tests available | Python, statistics |
| [hyperdex](https://github.com/ablanchard-dev/hyperdex) | Paper copy-trading on Hyperliquid perps: fills simulated by walking the real L2 order book, sharded WebSocket ingestion with watchdogs, risk layer | Python, data eng |
| [polyoracle](https://github.com/ablanchard-dev/polyoracle) | Research bot for Polymarket: wallet discovery with out-of-sample validation, paper trading behind a locked live path, full-stack (FastAPI + Next.js), 930+ tests | FastAPI, Next.js, pytest |

### In progress

| Project | What it is | Stack |
|---|---|---|
| [warzone-ai-montage](https://github.com/ablanchard-dev/warzone-ai-montage) | Auto-edits Call of Duty highlight reels: detects kills with HUD computer vision + audio + voice, then assembles a beat-synced montage — *work in progress* | Python, OpenCV, Whisper, FFmpeg |

## Contact

- **Email** — blanchardalexayrtongood@gmail.com
- **LinkedIn** — https://www.linkedin.com/in/alexandre-blanchard-a17435416
