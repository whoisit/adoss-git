# Alex Doss

Principal Engineering Director / Systems Architect  
Amsterdam, Netherlands  
[alexdoss.com](https://alexdoss.com) | [hello@alexdoss.com](mailto:hello@alexdoss.com) | [linkedin.com/in/alexdoss](https://linkedin.com/in/alexdoss) | [github.com/adoss](https://github.com/adoss)

## Systems Architecture

Twenty years focused on procedural pipeline development and large-scale systems architecture in high-end visual computing. Primary tools include SideFX Houdini, OpenUSD, VEX, the Python `hou` API, Solaris, Redshift, and Nuke. Production credits include 180+ shipped titles, real-time biomechanical cardiac simulation for HeartWorks, and multi-agent crowd systems exceeding 100,000 agents.

## Current Production Systems

### ConnectVFX

Production intelligence platform that maintains structured profiles for 1,200+ VFX, animation, and gaming studios across five continents.

**Architecture**
- Decoupled phase pipeline: Discovery -> ATS REST APIs + headless Playwright scrapers -> Git raw ledger -> Gemini 3.1 parser -> software intelligence layer -> CSR dashboard
- Multi-model failover waterfall using Gemini 3.1 Flash-Lite, DeepSeek, and Qwen with automatic key rotation and circuit breakers
- Cheerio DOM preprocessing layer reducing token consumption by approximately 70%
- Semantic extraction of DCC and pipeline requirements (Houdini, OpenUSD, VEX, Python, Maya, Unreal Engine, Nuke)

### CineScript

Generative AI script-to-storyboard system designed to maintain character and visual consistency through persistent visual anchor model sheets.

**Architecture**
- Chain-of-responsibility screenplay prompt parser that converts scene sluglines into explicit camera, lighting, and blocking directives
- In-browser client-side PDF document compiler
- Full stack: React 19, TypeScript, Vercel Serverless Functions, FLUX and SDXL inference, Stripe billing

### Procedural 3D Synthetic Data & Simulation

Houdini-based procedural asset synthesis pipeline with deterministic seed control and OpenUSD/Solaris domain randomization. Used for generating training data for robotics and computer vision models.

### AI Automation & Tooling

- VoiceMutex: IPC non-blocking concurrency lock that prevents speech collisions in multi-agent autonomous systems
- Zero-egress Playwright scrapers with local SQLite persistence
- Antigravity: CLI toolkit for autonomous agent orchestration

## Technical Focus Areas

- Production AI platforms at scale
- Procedural content generation and synthetic data pipelines
- Multi-agent systems and autonomous tooling
- Visual computing infrastructure (VFX, animation, simulation)
- Real-time systems architecture
- Data extraction, transformation, and intelligence platforms

---

**Amsterdam, Netherlands**
