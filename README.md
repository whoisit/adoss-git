# Alex Doss — Pipeline TD & Applied AI Developer

Amsterdam, Netherlands | [alexdoss.com](https://alexdoss.com) | [hello@alexdoss.com](mailto:hello@alexdoss.com) | [linkedin.com/in/alexdoss](http://linkedin.com/in/alexdoss) | [github.com/whoisit](https://github.com/whoisit)

---

## Overview

- **Procedural 3D & Pipeline Engineering:** 20 years building DCC tools, procedural workflows (Houdini, OpenUSD, VEX, Python), and simulation setups across 180+ productions.
- **Applied AI Applications:** Built ConnectVFX (job scraping & indexing pipeline for 1,200+ studios) and CineScript (AI storyboard generator with character consistency).
- **CLI & Automation Tools:** Headless Playwright scrapers, multi-model LLM failovers (Gemini, DeepSeek, Qwen), and process-safe audio concurrency (`VoiceMutex`).
- **Full-Stack & Data:** TypeScript, React 19, Node.js, Vercel Serverless, SQLite, and Supabase.

---

## Projects

### 1. ConnectVFX — Automated Job Board & Scraper Pipeline
Aggregates and filters job postings from 1,200+ VFX, animation, and gaming studios globally.
- **Data Ingestion:** Direct REST connectors for Greenhouse/Lever/Workday + headless Playwright scrapers for custom career portals. Raw HTML snapshots are committed locally to a Git ledger.
- **Parsing & Fallback:** Gemini with automated fallback to DeepSeek and Qwen when rate-limited.
- **Token Reduction:** Cheerio-based HTML preprocessor strips unnecessary tags, reducing LLM token consumption by ~70%.
- **Skill Extraction:** Parses job descriptions to automatically index tool requirements (Houdini, USD, VEX, Python, Maya, Unreal, Nuke).

---

### 2. CineScript — AI Storyboard Generator
Converts screenplays into visual storyboards while keeping character appearance and camera style consistent across shots.
- **Character Consistency:** Generates and references character model sheets across shot prompts to prevent character drift between scenes.
- **Screenplay Parser:** Converts screenplay sluglines and scene actions into camera, lighting, and lens directives for image models (FLUX / SDXL).
- **Client-Side Export:** Generates multi-page storyboard PDFs directly in the browser via canvas rendering.
- **Stack:** React 19, TypeScript, Vercel Serverless Functions, Stripe billing.

---

### 3. Procedural 3D & Synthetic Data
Procedural 3D generation and simulation in SideFX Houdini for VFX and computer vision datasets.
- **Synthetic Datasets:** Procedural asset generation in Houdini with OpenUSD / Solaris domain randomization (lighting, textures, wear) for training computer vision models.
- **Procedural Tooling:** Custom HDAs and VEX scripts for geometry processing, debris, and crowd networks.
- **Production Background:** Biomechanical cardiac simulation (*HeartWorks*) and crowd simulations exceeding 100,000 agents across 180+ productions.

---

### 4. CLI & Agentic Tooling
- **`VoiceMutex`:** Inter-process concurrency lock preventing audio collision when multiple autonomous agent tasks run in parallel.
- **Local Scrapers:** Playwright collectors that parse and write directly to local SQLite without sending data to third parties.
- **Antigravity Toolkits:** Custom CLI commands and skill integrations for agent workflows.

---

## Technical Skills

| Area | Technologies |
| :--- | :--- |
| **Applied AI & LLMs** | Gemini, Claude, GPT, Grok, DeepSeek, Perplexity, FLUX, SDXL, Structured JSON |
| **Pipeline & 3D** | SideFX Houdini (SOPs, HDAs, Solaris), OpenUSD, VEX, Python (hou API), Redshift, Nuke |
| **Web & Automation** | TypeScript, React 19, Node.js, Playwright, SQLite, Supabase, Vercel Serverless, REST APIs |
| **Languages & Core** | Python, TypeScript, JavaScript, VEX, SQL, Bash, PowerShell, Git |

---

## Contact & Links

- Website: [alexdoss.com](https://alexdoss.com)
- Email: [hello@alexdoss.com](mailto:hello@alexdoss.com)
- LinkedIn: [linkedin.com/in/alexdoss](http://linkedin.com/in/alexdoss)
- GitHub: [github.com/whoisit](https://github.com/whoisit)
