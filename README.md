# Hossam Hany (Dapour)

**Retail operations → AI & automation.** 9+ years running stores and branches in Egyptian grocery, convenience and food retail. For the past year I've been building the AI and data tools my company runs on.

📍 Cairo, Egypt · 🔗 [LinkedIn](https://www.linkedin.com/in/hossam-hany-1748821a5/) · ✉️ dapourhosam@gmail.com

---

### What I build

Internal systems for multi-branch retail, built with AI coding agents (Claude Code, Codex) and running in production.

| Project | What it does | Stack |
|---|---|---|
| **Retail operations platform** | Sales and inventory reporting, purchasing, HR and attendance, KPI-based bonuses, and multi-step approvals with an audit trail, on top of Odoo 17. Used daily by branch and head-office staff. | NestJS · Prisma · PostgreSQL · Redis · Next.js · Capacitor |
| **Replenishment planning** | An automatic branch supply plan built from 90 days of real transfer data (3,000+ requests), plus a feed for items out of stock in one branch but selling in others. | TypeScript · PostgreSQL |
| **Arabic business assistant** | Answers managers' questions from live sales and inventory data, routes between LLM providers with failover, and falls back to a data-only answer if a model is slow. | LLM APIs (DeepSeek, Gemini) · NestJS |
| **Competitor price monitoring** | A nightly worker that checks public competitor catalogs and verifies product matches. | Node.js |
| **Store CCTV analytics** *(prototype)* | Turns existing store cameras into operational events (queues, occupancy, dwell time), with evidence, human review and privacy by default. | Python · open-source vision |
| **Kiosk apps** | An in-store barcode price checker and an ordering kiosk. | Web · Firebase |

> 🔒 **These repositories are private** because they run live business systems. I'm happy to walk through any of them on a screen-share call.

### How I work
- I start from the store floor: the KPI, the bottleneck, the process people actually follow.
- I write specs, let AI agents build, and review every change. The main platform has around 800 automated tests and CI on every push.
- Data I can't verify shows as "unavailable", never as a confident wrong number.

### Toolbox
`TypeScript` `Python` `SQL` `PostgreSQL` `Odoo` `SAP (store)` `Power BI` `Claude Code` `Codex` `LLM APIs` `Docker`
