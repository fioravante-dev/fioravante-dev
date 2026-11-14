# Pedro Fioravante

**AI Engineer · LLM Agents & Automation · Full-Stack (TypeScript / Next.js) · Rust · Python**

I build software that does real work: LLM agents that act on codebases and dev workflows, speech and vision pipelines, and the full-stack products around them. I ship fast with AI in the loop, and I care about what happens after the demo: tests, deploys, costs and the boring edge cases.

Open to **full-time and contract** roles · Remote · 🇧🇷 UTC-3 · English / Portuguese

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fioravante-dev/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:pedrocfioravante95+gitpage@gmail.com)

---

### What I work on

- **LLM agents in production:** tool-calling agents that read code, triage work, write fixes and open pull requests, with humans reviewing the result. Claude API, MCP, LangGraph.
- **Speech:** real-time and batch transcription with Whisper (whisper.cpp on GPU, hosted inference), VAD and speaker diarization.
- **Local & private AI:** llama.cpp models for data that can't leave the machine, PII anonymization.
- **Computer vision:** YOLO-family detection and segmentation, model benchmarking.
- **Systems:** Rust services and orchestration, Docker, CI/CD on Azure DevOps.
- **Full-stack products:** Next.js, React, Supabase/Postgres with row-level security, offline-first PWAs.

### Open source

| Project | What it is | Stack |
|---|---|---|
| [**talk**](https://github.com/fioravante-dev/talk) | 100% local voice dictation for Linux and Windows. Press a hotkey, speak, and the text lands at your cursor. Whisper on the GPU, ~100 MB RAM at rest, zero VRAM when idle. | Rust · whisper.cpp · CUDA · Silero VAD |
| [**op2**](https://github.com/fioravante-dev/op2) | Tray app that auto-applies runes, spells and item sets in the League of Legends client. Single 1.5 MB `.exe`, ~5 MB RAM, self-updating. | Rust · LCU API · WebSocket · MCP |
| [**sql-tool**](https://github.com/fioravante-dev/sql-tool) | Natural-language database query agent: classifies the question, inspects the schema, runs read-only SQL. | Python · LangGraph · FastAPI |
| [**FastAPI-MCP**](https://github.com/fioravante-dev/FastAPI-MCP) | Layered, containerized backend where an LLM agent drives CRUD operations through tools. | Python · FastAPI · Docker |

### Built for clients (private code)

- **Multi-tenant clinic scheduling SaaS:** weekly drag-and-drop calendar, patient records with audit history, per-dentist permissions, file storage on R2, tenant isolation with Postgres RLS. Installable PWA. *Next.js 16 · Supabase · TDD.*
- **Offline-first attendance PWA for a factory floor:** marks attendance without a connection, syncs through a queue, and enforces labor rest-day rules. *Next.js 16 · IndexedDB · Supabase · TDD.*

### Stack

`TypeScript` `Rust` `Python` `Next.js` `React` `Node.js` `Supabase` `PostgreSQL` `Docker` `Azure DevOps` `Claude API` `MCP` `LangGraph` `Whisper` `llama.cpp` `YOLO`
