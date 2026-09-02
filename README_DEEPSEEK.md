# Alex Doss

Systems architect specializing in procedural pipeline development and applied AI for high-end visual computing. Based in Amsterdam, working globally.

[Website](https://alexdoss.com) · [Email](mailto:hello@alexdoss.com) · [LinkedIn](https://linkedin.com/in/alexdoss) · [GitHub](https://github.com/adoss)

---

## Focus

Designing and building the intersection of visual computing and machine intelligence: automated pipeline infrastructure, generative content systems, and synthetic data generation for computer vision and robotics.

Two decades of procedural pipeline development across 180+ shipped productions. Domain depth in SideFX Houdini, OpenUSD, VEX, Python (hou API), Solaris, Redshift, and Nuke. Notable prior work includes biomechanical cardiac simulation (HeartWorks) and multi-agent crowd networks exceeding 100,000 concurrent agents.

---

## Current Platforms

### ConnectVFX — Automated AI Job Intelligence & ETL Platform

A production system tracking employment and technology signals across 1,200+ VFX, animation, and gaming studios on five continents.

**Architecture — Decoupled Phase Pipeline:**

```
Discovery -> ATS REST APIs & Headless Playwright Scrapers -> Git Raw Ledger -> Gemini 3.1 Parser -> Software Intelligence Layer -> CSR Dashboard
```

**Key Engineering Decisions:**

- **Multi-Model Failover Waterfall:** Gemini 3.1 Flash-Lite primary, with DeepSeek and Qwen fallbacks. Automated key rotation and circuit breakers prevent single-point failure across model providers.
- **Token Optimization:** Cheerio DOM preprocessing strips boilerplate before LLM inference, reducing token overhead by approximately 70%.
- **Semantic Extraction:** Structured parsing of DCC and pipeline requirements from job postings — Houdini, USD, VEX, Python, Maya, Unreal, Nuke — enabling technology trend analysis across the industry.
- **Resilient Ingestion:** Headless browser automation handles JavaScript-rendered ATS interfaces; raw payloads persist to a Git ledger for auditability and re-processing without re-scraping.

### CineScript — Generative Script-to-Storyboard Studio

A full-stack application converting screenplays into visual storyboards, engineered to solve character and visual consistency drift across generated frames.

**Core Innovation — Persistent Visual Anchor Model Sheets:**

Generated characters maintain a canonical visual reference (model sheet) that is injected into subsequent generation contexts. This eliminates the common failure mode of character appearance shifting between shots.

**Pipeline:**

- Chain-of-responsibility screenplay parser converts scene sluglines into structured directives: camera lens selection, lighting setup, and blocking instructions.
- Client-side PDF document compiler runs entirely in-browser — no server-side rendering overhead.
- Image generation via FLUX/SDXL with prompt construction derived from parsed screenplay semantics.

**Stack:** React 19, TypeScript, Vercel Serverless Functions, Stripe billing integration.

### Procedural 3D Synthetic Data & Simulation

SideFX Houdini-based procedural asset synthesis for robotics and computer vision training data.

- Deterministic seed control enables reproducible dataset generation across distributed workers.
- OpenUSD / Solaris domain randomization produces controlled variation in lighting, texture, and geometry — critical for robust model training.
- Assets are generated procedurally, not scanned or manually modeled, allowing parametric scaling of dataset size and complexity.

### AI Automation & Tooling

- **VoiceMutex:** IPC-based non-blocking concurrency lock preventing speech collisions across multi-agent autonomous runs. Solves the real-world problem of multiple agents attempting simultaneous voice output in shared environments.
- **Zero-Egress Scrapers:** Playwright-based collectors persisting directly to local SQLite — no data leaves the host machine, addressing strict data-residency requirements.
- **Antigravity Agent CLI Toolkits:** Command-line utilities for orchestrating autonomous agent workflows.

---

## Engineering Principles

- **Systems over scripts.** Every component is designed as part of a pipeline with defined interfaces, failure modes, and recovery paths.
- **Data persistence before processing.** Raw data is always captured and stored before transformation. Re-processing must never require re-acquisition.
- **Determinism where it matters.** Synthetic data generation, pipeline execution, and testing require reproducible seeds and controlled randomness.
- **Failover is a feature.** Multi-provider, multi-path architectures are not optional in production AI systems.

---

## Technical Depth

| Domain | Technologies |
|---|---|
| Procedural Pipeline | SideFX Houdini, VEX, Python (hou API), Solaris, OpenUSD |
| Rendering & Compositing | Redshift, Nuke |
| AI/ML Integration | Gemini 3.1, DeepSeek, Qwen, FLUX, SDXL, multi-model orchestration |
| Data Engineering | ETL pipelines, headless scraping, SQLite, structured extraction |
| Frontend | React 19, TypeScript |
| Backend/Infrastructure | Vercel Serverless, REST API integration, IPC systems |

---

## Selected Prior Work

- **HeartWorks (Biomechanical Cardiac Simulation):** Real-time interactive 3D heart model for medical education and clinical training.
- **Crowd Simulation Systems:** Multi-agent networks supporting 100,000+ concurrent agents with procedural behavior.
- **180+ Productions:** Procedural pipeline development across film, broadcast, and advertising.

---

## Contact

Engineering leadership, architecture consultation, and technical collaboration inquiries are welcome.

**Email:** [hello@alexdoss.com](mailto:hello@alexdoss.com)  
**Website:** [alexdoss.com](https://alexdoss.com)  
**LinkedIn:** [linkedin.com/in/alexdoss](https://linkedin.com/in/alexdoss)
