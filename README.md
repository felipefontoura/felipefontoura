# Felipe Fontoura

**The code writes itself. The spec doesn't.**

Staff Engineer | Spec-Driven Development Practitioner | CTO & Builder

I build production systems with AI agents using Spec-Driven Development. 25+ years shipping software — from satellite drivers at INPE to the global checkout serving 20M+ customers at TUI Group (€23B revenue).

→ [felipefontoura.com](https://felipefontoura.com)

---

### What I Built

**Crypto Fintech on Bitcoin's Liquid Network** — payment gateway, OTC exchange, and on-chain settlement. Built in 70 days, solo, using SDD + AI agents. Private repo.

`TypeScript` `Node.js` `Fastify` `PostgreSQL` `Kubernetes` `Terraform` `Redis` `BullMQ`

- 13-app monorepo, 3 Fastify APIs, 3 isolated PostgreSQL databases
- PIX integration with 4 PSPs (factory pattern, HMAC-SHA256, mTLS to BACEN)
- OTC exchange engine — rolling 24h VWAP, 5 sources, asymmetric spreads
- On-chain settler — confirmation polling, deviation refunds, crash recovery
- OAuth 2.1/OIDC (5 roles, 19 scopes, JWKS, M2M, 2FA TOTP)
- Kubernetes (DOKS, HPA 2-10), Prometheus/Grafana, CI/CD

→ [Read the full case study](https://felipefontoura.com/articles/spec-driven-development-case-study)

---

### Spec-Driven Development

I'm a practitioner of SDD — not the creator. My authority comes from applying it at scale: 13 apps, 70 days, solo, in production. I've also trained 400+ professionals in AI-augmented workflows.

The methodology: structured specs (requirements → design → tasks) as the single source of truth. AI agents execute against them. Humans review and ship.

- [What Is Spec-Driven Development?](https://felipefontoura.com/articles/what-is-spec-driven-development) — the complete guide
- [Spec-Driven Development with Claude Code](https://felipefontoura.com/articles/spec-driven-development-with-claude-code) — the hands-on workflow
- [How to write a spec an AI can build from](https://felipefontoura.com/articles/how-to-write-a-spec) — the EARS format and templates

---

### Open Source

- [pi-sdd-kit](https://github.com/felipefontoura/pi-sdd-kit) — Spec-Driven Development as skills for the Pi coding agent: steering docs as durable memory, `.status` approval gates, EARS, a PRD→SPEC→TASKS→EXEC→REVIEW pipeline.
- [pi-skill-model-handoff](https://github.com/felipefontoura/pi-skill-model-handoff) — let each Pi skill pick its own model and thinking level from the `SKILL.md` frontmatter.
- [AI Engineering Dotfiles](https://github.com/felipefontoura/dotfiles/tree/main/ai) — slash commands, agent teams, review pipeline.

---

### Writing

Notes on building production software with AI coding agents — Spec-Driven Development, Claude skills, harness engineering.

→ [felipefontoura.com/articles](https://felipefontoura.com/articles)

---

### Stack

| Backend | Infrastructure |
|---|---|
| Node.js / TypeScript | Kubernetes (DOKS) |
| Fastify / NestJS | Terraform |
| Drizzle ORM / Prisma | Docker |
| PostgreSQL | GitHub Actions CI/CD |
| BullMQ / Redis | Prometheus / Grafana |

---

### Links

- [Website](https://felipefontoura.com)
- [LinkedIn](https://linkedin.com/in/felipefontoura)
- [YouTube](https://www.youtube.com/@f.fontoura) — 80K+ subscribers
- [X/Twitter](https://x.com/felipefontoura)
