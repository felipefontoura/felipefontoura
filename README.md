# Felipe Fontoura

**Senior Backend Developer — Fintech & Bitcoin Infrastructure**

Building payment gateways and exchange systems on the Liquid Network. 25+ years shipping production software, from satellite hardware at INPE to multi-currency checkout systems at TUI Group (23B EUR). Currently focused on bridging traditional payment rails to Bitcoin using AI-driven development workflows.

Bitcoin maximalist. 100% in. I don't advertise it — I just build on it.

---

### What I'm Building

**Payment Gateway & OTC Exchange on the Liquid Network** — Fiat on-ramp (PIX → tokens) with an exchange engine for trading against L-BTC and USDT, settled on-chain. Built in 70 days, solo, using AI-driven workflows. Private repo.

`Node.js` `TypeScript` `Fastify` `Drizzle ORM` `PostgreSQL` `BullMQ` `Redis` `Elements Core` `Kubernetes` `Terraform`

- 13-app monorepo (Turborepo), 3 Fastify APIs, 3 PostgreSQL databases
- Provider-agnostic PIX integration (4 PSPs via factory pattern)
- OTC exchange engine with VWAP pricing, 5-source price aggregation, asymmetric spreads
- Exchange Settler with deposit detection, tolerance-based auto-refund, crash recovery
- Full OAuth 2.1/OIDC auth server (5 roles, 19 scopes, JWKS, M2M)
- Kubernetes (DOKS, HPA), Prometheus/Grafana, GitHub Actions CI/CD

---

### Open Source

- [AI Engineering Dotfiles](https://github.com/felipefontoura/dotfiles/tree/main/ai) — dozen slash commands, passive skills, agent teams config, review pipeline. The full AI-augmented development workflow, open source.
- [Aqua Wallet PR #104](https://github.com/AquaWallet/aqua-wallet/pull/104) — Surface balances for non-curated Liquid assets. Fund visibility fix touching GDK's asset registry + balance resolution, 11 unit tests.

---

### Spec-Driven Development (SDD)

A methodology I developed for AI-assisted coding with Claude Code. Structured specs (requirements, design docs, API contracts) as the single source of truth for AI-generated implementations. Multi-agent patterns: architect, implementer, reviewer — each with defined boundaries and human approval gates.

Used to build the 13-app fintech monorepo in 70 days. Trained 400+ professionals in the methodology.

[Read the full article on LinkedIn](https://www.linkedin.com/in/felipefontoura/recent-activity/articles/)

---

### Stack

```
Backend                     Infrastructure              Bitcoin
─────────────────────       ─────────────────────       ─────────────────────
Node.js / TypeScript        Kubernetes (DOKS)           Liquid Network
Fastify                     Terraform                   Elements Core (RPC)
Ruby on Rails               Docker                      Blockstream GDK
Drizzle ORM / ActiveRecord  GitHub Actions CI/CD        L-BTC / UTXO
PostgreSQL 17               Prometheus / Grafana        Lightning Network
BullMQ / Redis              Cloudflare
```

---

### Other Projects

- **SmartMKT** — AI-powered SaaS (Ruby on Rails) for automated copywriting and video sales content. LLM integrations in production.
- **JusPro** — Legal Tech for judicial document processing using Claude and Gemini APIs in production.
- **SmartDev Academy** — 30,000+ students trained across software engineering and AI-augmented development.

---

### Links

- [LinkedIn](https://linkedin.com/in/felipefontoura)
- [YouTube](https://www.youtube.com/channel/UC-lHCBqKEtnXA0SBtdOP0bw/) — 80,000+ subscribers
