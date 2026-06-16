# Alex Blanchard

Full-stack & AI developer. I build end-to-end products: backend, frontend, computer
vision, LLM integration, and some Rust on the side. I also do a fair amount of
quantitative research, where the discipline is mostly about *not* fooling yourself.

Currently open to full-stack / backend / AI / data engineering roles.

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
| [prompt-middleware](https://github.com/ablanchard-dev/prompt-middleware) | Local-first browser middleware that optimizes prompts before they reach LLM interfaces; pure Rust engine + TypeScript extension | Rust, TypeScript, axum |

### Quant research

One methodology — generate candidate strategies, backtest them with realistic costs,
then try hard to disprove the edge before believing it — applied across a few markets.

| Project | What it is | Stack |
|---|---|---|
| [edge-factory](https://github.com/ablanchard-dev/edge-factory) | The validation engine: a DSR / beta-neutral / PBO critic that kills false edges before they get trusted | Python, statistics |
| [dexterio](https://github.com/ablanchard-dev/dexterio) | The backtest engine: strategy backtesting with realistic costs and proper statistical validation | Python, pandas |
| [polyoracle](https://github.com/ablanchard-dev/polyoracle) | Same methodology applied to Polymarket: a local-first smart-money copy-trading research bot, full-stack (FastAPI + Next.js), paper-validated, 800+ tests | FastAPI, Next.js, pytest |
| [hyperdex](https://github.com/ablanchard-dev/hyperdex) | Same methodology applied to Hyperliquid perps: faithful fill simulation + risk layer, gated behind out-of-sample validation | Python, data eng |

### In progress

| Project | What it is | Stack |
|---|---|---|
| [lumenia](https://github.com/ablanchard-dev/lumenia) | Full-stack AI assistant for neurodivergent people (HPI / ASD / ADHD), with multi-LLM failover and distress detection — *work in progress* | FastAPI, multi-LLM, JS |
| [warzone-ai-montage](https://github.com/ablanchard-dev/warzone-ai-montage) | Auto-edits Call of Duty highlight reels: detects kills with HUD computer vision + audio + voice, then assembles a beat-synced montage — *work in progress* | Python, OpenCV, Whisper, FFmpeg |

![warzone-ai-montage demo](https://raw.githubusercontent.com/ablanchard-dev/warzone-ai-montage/main/docs/demo.gif)

## Contact

- **Email** — blanchardalexayrtongood@gmail.com
- **LinkedIn** — https://www.linkedin.com/in/alexandre-blanchard-a17435416
