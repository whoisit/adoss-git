# Alex Doss — Pipeline TD & Applied AI Developer

Amsterdam, Netherlands | [alexdoss.com](https://alexdoss.com) | [hello@alexdoss.com](mailto:hello@alexdoss.com) | [linkedin.com/in/alexdoss](http://linkedin.com/in/alexdoss) | [github.com/whoisit](https://github.com/whoisit)

---

## Overview

Pipeline Technical Director & Applied AI Developer with 20 years of experience building procedural 3D systems, simulation workflows, and software automation across 180+ productions. Specialized in taking technical challenges end-to-end—from DCC pipeline architecture (Houdini, OpenUSD, VEX, Python) to full-stack web applications, headless data scrapers, and applied AI systems.

---

## Projects

### [ConnectVFX](https://www.connectvfx.app/) — Studio Job Board & Scraper Pipeline
Automated pipeline monitoring open roles across 1,200+ VFX, animation, and gaming studios globally.
- **Data Ingestion:** Direct REST connectors for Greenhouse/Lever/Workday + headless Playwright scrapers for custom career portals. Stores raw HTML snapshots in Git for change tracking and debugging.
- **Parsing & Fallback:** Multi-model parsing waterfall (DeepSeek primary with automated fallback to Gemini and Qwen) with structured schema extraction.
- **LLM Preprocessing:** Cheerio-based HTML extraction strips navigational boilerplate, reducing input token volume by ~70%.
- **Skill Extraction:** Parses job descriptions to automatically index tool requirements (Houdini, USD, VEX, Python, Maya, Unreal, Nuke).
- **Multi-Channel Syndication:** Automated broadcast engine formatting and distributing curated job alerts to LinkedIn, Discord webhooks, and Reddit communities.

---

### [CineScript](https://cinescript-storyboarder.vercel.app/) — AI Storyboard Generator
Full-stack web application converting screenplays and shot lists into multi-panel visual storyboards.
- **Character Consistency:** Generates and injects character reference model sheets into image prompts (FLUX / SDXL) to eliminate visual drift across shots.
- **Screenplay Parser:** Multi-step prompt parser deconstructing script sluglines and scene action into camera lenses, lighting setups, and blocking directives.
- **Client-Side Export:** Renders multi-page storyboard PDFs directly in the browser via canvas streaming to minimize server load.
- **Stack:** React 19, TypeScript, Vercel Serverless Functions, Stripe billing.

---

### Procedural 3D & Synthetic Training Data
Procedural asset generation and simulation systems in SideFX Houdini for VFX and computer vision datasets.
- **Synthetic Datasets:** OpenUSD & Solaris pipelines with domain randomization (lighting, textures, wear) to generate training data for computer vision models.
- **Procedural Tooling:** Custom HDAs and VEX algorithms for geometry synthesis, destruction, and crowd behavior.
- **Production Background:** 20 years in VFX production, including biomechanical cardiac simulation (*HeartWorks*) and crowd systems exceeding 100,000 agents across 180+ productions.

---

### CLI Tools & Automation
- **`VoiceMutex`:** Inter-process concurrency lock preventing audio collisions during parallel terminal agent runs.
- **Local Scrapers:** Playwright collectors that parse and write directly to local SQLite without external dependencies.
- **Workflow Tooling:** Custom developer CLI extensions and automation scripts for terminal-driven coding.

---

## Technical Matrix

| Domain | Technologies |
| :--- | :--- |
| **Pipeline & 3D** | SideFX Houdini (SOPs, HDAs, Solaris), OpenUSD, VEX, Python (`hou` API), Redshift, Nuke |
| **Applied AI & LLMs** | LLM APIs (DeepSeek, Gemini, Claude, GPT), FLUX, SDXL, Schema Enforcement, Prompt Pipelines |
| **Full-Stack & Cloud** | TypeScript, React 19, Node.js, Playwright, SQLite, Supabase, Vercel, Cloudflare Wrangler, Stripe |
| **Core & Tooling** | Python, TypeScript, VEX, SQL, Bash, PowerShell, Git, GitHub Actions, Antigravity CLI |

---

## Contact & Links

- Website: [alexdoss.com](https://alexdoss.com)
- Email: [hello@alexdoss.com](mailto:hello@alexdoss.com)
- LinkedIn: [linkedin.com/in/alexdoss](http://linkedin.com/in/alexdoss)
- GitHub: [github.com/whoisit](https://github.com/whoisit)
