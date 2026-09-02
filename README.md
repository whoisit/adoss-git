# Alex Doss — Systems Architect & Applied AI Builder

Alex Doss | Systems Architect & Pipeline Developer | Amsterdam, NL  
Website: [alexdoss.com](http://alexdoss.com) | Email: [hello@alexdoss.com](mailto:hello@alexdoss.com) | LinkedIn: [linkedin.com/in/alexdoss](http://linkedin.com/in/alexdoss) | GitHub: [github.com/adoss](https://github.com/adoss)

> "Systems Architect & Pipeline Developer with 20 years of procedural problem-solving experience in visual computing, transitioned into engineering production-grade AI pipelines, full-stack tools, and synthetic data platforms at high velocity."

---

## Live Portfolio Website

This repository contains the source for the portfolio website deployed to GitHub Pages:
[https://adoss.github.io](https://adoss.github.io)

*(Note: GitHub Pages serves this URL after the repository is published to GitHub under `adoss.github.io` or configured via repository Settings > Pages).*

---

## Key Production Systems

### 1. ConnectVFX — Global AI Job Intelligence & Scraper Pipeline
An automated, AI-powered intelligence platform aggregating job listings from 1,200+ global VFX, animation, and gaming studios across 5 continents.
- Decoupled Phase Architecture: Discovery -> Direct ATS REST Connectors (Greenhouse, Lever, Workday) & Headless Playwright Chrome engines -> Local Git-tracked raw ledger -> Gemini 3.1 Flash-Lite semantic parser -> Software-first enricher -> CSR Client Dashboard.
- Multi-Model Failover Waterfall: Automatic key rotation & model fallback (Gemini 3.1 -> DeepSeek -> Qwen) with automated circuit breakers to guarantee continuous uptime under rate limits.
- Token Cost Engineering: Cheerio DOM sanitization preprocessing strips scripts, styles, and navigational chrome, reducing LLM token consumption by ~70%.
- Software-First Intelligence: Semantic extraction of deep pipeline requirements (Houdini, USD, VEX, Python, Maya, Unreal, Nuke) for high-precision filtering.

---

### 2. CineScript — Generative AI Storyboard & Visual Script Studio
Full-stack platform converting screenplays and shot lists into production-grade visual storyboards with strict character model consistency and cinematic camera continuity.
- Visual Anchor Conditioning: Generates persistent multi-angle character and environment reference sheets to eliminate AI character drift across multi-shot sequences.
- Chain-of-Responsibility Parser: Deconstructs standard screenplay sluglines and actions into photoreal camera lens, lighting, and blocking directives.
- Client-Side Document Engine: High-resolution multi-page PDF generation rendered directly in the browser via memory-managed Canvas streaming.
- Tech Stack: React 19, TypeScript, Vercel Serverless Functions, FLUX / Stable Diffusion, Tailwind CSS, Stripe.

---

### 3. Procedural 3D & Synthetic Simulation Engine
High-throughput procedural systems in SideFX Houdini generating photoreal synthetic datasets, physics simulations, and domain-randomized training data for computer vision and robotics.
- Domain Randomization: OpenUSD & Solaris pipeline randomizing camera intrinsics, lighting spectra, micro-surface imperfections, and wear to eliminate the sim-to-real gap.
- Procedural HDAs & VEX: Parametric asset synthesis with deterministic seed control for dataset scalability.
- Production Pedigree: 20 years of mission-critical production rigor, including biomechanical cardiac simulation (HeartWorks) and 100,000+ agent autonomous crowd simulations.

---

### 4. AI Automation & Concurrency Architecture
Custom agent tooling and workflow acceleration extensions built for autonomous engineering.
- VoiceMutex IPC Locking: Multi-process non-blocking audio queue preventing speech overlap during multi-agent autonomous runs.
- Zero-Egress Scraping: Playwright-driven aggregators persisting structured deal metrics and listings directly into local SQLite/Git ledgers.
- Antigravity Toolkits: Custom CLI skill bindings and MCP tools extending Google DeepMind Antigravity capabilities.

---

## Technical Matrix

| Domain | Technologies & Frameworks |
| :--- | :--- |
| AI & LLM Orchestration | Gemini 3.1 / 1.5 Pro & Flash, DeepSeek, Qwen, FLUX, Structured JSON Schemas, Multi-Model Failover Waterfalls, Prompt Pipelines, MCP |
| Full-Stack & Cloud | TypeScript, React 19, Node.js, Vercel Serverless, Supabase, PostgreSQL, SQLite, Playwright, Tailwind CSS, REST & ATS APIs |
| Procedural 3D & VFX | SideFX Houdini (SOPs, HDAs, Solaris), OpenUSD, VEX, Python hou API, Redshift, Arnold, Foundry Nuke, Biomechanical Rigging |
| Languages & Core | Python 3.x, TypeScript / ESNext, VEX, SQL, C++, PowerShell, Bash, Git & GitHub Actions CI/CD |

---

## Local Preview & Deployment

### Local Preview
To preview the website locally:
```bash
# Python local server
python -m http.server 8000

# or Node.js serve
npx serve .
```
Open `http://localhost:8000` in your browser.

### Publishing to GitHub Pages
1. Create a repository on GitHub (named `adoss.github.io` or `adoss`).
2. Add remote and push:
   ```bash
   git remote add origin https://github.com/adoss/adoss.github.io.git
   git push -u origin main
   ```
3. If using repository name `adoss` instead of `adoss.github.io`, enable Pages in GitHub: **Settings -> Pages -> Build and deployment -> Source: Deploy from a branch (`main` / `/root`)**.

---

## Contact & Links

- Website: [alexdoss.com](http://alexdoss.com)
- Email: [hello@alexdoss.com](mailto:hello@alexdoss.com)
- LinkedIn: [linkedin.com/in/alexdoss](http://linkedin.com/in/alexdoss)
- GitHub: [github.com/adoss](https://github.com/adoss)
- Location: Amsterdam, Netherlands
