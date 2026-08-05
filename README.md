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
| [scamshield](https://github.com/ablanchard-dev/scamshield) | Scam / phishing text detection with an explainable scoring engine, a Chrome extension and CI | Python, scikit-learn, Docker |
| [dexcheck](https://github.com/ablanchard-dev/dexcheck) | Read-only forensic PC check for Call of Duty / Warzone screen-share vetting — 36 probes, 190 tests, used by a real anti-cheat community | PowerShell, bash |
| [lumenia](https://github.com/ablanchard-dev/lumenia) | Full-stack AI assistant for neurodivergent people (HPI / ASD / ADHD): multi-LLM failover, server-enforced entry gate, and crisis detection | FastAPI, multi-LLM, JS |
| [prompt-middleware](https://github.com/ablanchard-dev/prompt-middleware) | Local-first browser middleware that optimizes prompts before they reach LLM interfaces; pure Rust engine + TypeScript extension | Rust, TypeScript, axum |

### Quant research & backtesting infrastructure

I built a reusable backtesting + statistical-validation stack, then put it to work across
three very different execution venues — traditional brokerage, crypto perps, and prediction markets.

| Project | What it is | Stack |
|---|---|---|
| [dexterio](https://github.com/ablanchard-dev/dexterio) | Institutional-grade backtest engine for IBKR equities / futures: intrabar stop/take-profit priority, real commission tiers, slippage + spread fill model | Python, pandas |
| [edge-factory](https://github.com/ablanchard-dev/edge-factory) | The statistical-validation layer that grew out of it: a DSR / PBO / CSCV critic that kills false edges before they're trusted | Python, statistics |
| [hyperdex](https://github.com/ablanchard-dev/hyperdex) | The same stack on Hyperliquid perps: faithful L2-orderbook fill simulation + copy-trading + risk layer | Python, data eng |
| [polyoracle](https://github.com/ablanchard-dev/polyoracle) | The same stack on Polymarket prediction markets: smart-money copy-trading, full-stack (FastAPI + Next.js), paper-validated, 800+ tests | FastAPI, Next.js, pytest |

### In progress

| Project | What it is | Stack |
|---|---|---|
| [warzone-ai-montage](https://github.com/ablanchard-dev/warzone-ai-montage) | Auto-edits Call of Duty highlight reels: detects kills with HUD computer vision + audio + voice, then assembles a beat-synced montage — *work in progress* | Python, OpenCV, Whisper, FFmpeg |

## Contact

- **Email** — blanchardalexayrtongood@gmail.com
- **LinkedIn** — https://www.linkedin.com/in/alexandre-blanchard-a17435416
