# Felipe Fontoura

**The code writes itself. The spec doesn't.**

Staff Engineer · Spec-Driven Development practitioner · CTO and builder

I build production systems with AI agents using Spec-Driven Development. 25+ years shipping software, from satellite drivers at INPE to the global checkout serving 20M+ customers at TUI Group (€23B revenue).

→ [felipefontoura.com](https://felipefontoura.com)

---

### What I built

A crypto fintech on Bitcoin's Liquid Network: a payment gateway, an OTC exchange, and on-chain settlement. Built solo in 70 days with SDD and AI agents. Private repo.

`TypeScript` `Node.js` `Fastify` `PostgreSQL` `Kubernetes` `Terraform` `Redis` `BullMQ`

- 13-app monorepo, 3 Fastify APIs, 3 isolated PostgreSQL databases
- PIX gateway, 4 PSPs behind a factory pattern (HMAC-SHA256, mTLS to BACEN)
- OTC exchange engine: rolling 24h VWAP, 5 sources, asymmetric spreads
- On-chain settler: confirmation polling, deviation refunds, crash recovery
- OAuth 2.1 / OIDC: 5 roles, 19 scopes, JWKS, M2M, TOTP 2FA
- Kubernetes (DOKS, HPA 2-10), Prometheus and Grafana, CI/CD

→ [Read the case study](https://felipefontoura.com/articles/spec-driven-development-case-study)

---

### Spec-driven development

I practice SDD. I did not invent it. The authority comes from applying it at scale: 13 apps, 70 days, solo, in production. I have also trained 400+ people in AI-augmented workflows.

The method is plain. Structured specs (requirements, design, tasks) are the source of truth. The agent executes against them. Humans review and ship.

- [What Is Spec-Driven Development?](https://felipefontoura.com/articles/what-is-spec-driven-development), the complete guide
- [Spec-Driven Development with Claude Code](https://felipefontoura.com/articles/spec-driven-development-with-claude-code), the hands-on workflow
- [How to write a spec an AI can build from](https://felipefontoura.com/articles/how-to-write-a-spec), the EARS format and templates

---

### Open source

- [pi-sdd-kit](https://github.com/felipefontoura/pi-sdd-kit): spec-driven development as skills for the Pi coding agent. Steering docs as durable memory, `.status` approval gates, EARS, and a gated PRD to review pipeline.
- [pi-skill-model-handoff](https://github.com/felipefontoura/pi-skill-model-handoff): let each Pi skill pick its own model and thinking level from the `SKILL.md` frontmatter.
- [AI engineering dotfiles](https://github.com/felipefontoura/dotfiles/tree/main/ai): slash commands, agent teams, review pipeline.

---

### Writing

Notes on building production software with AI coding agents: spec-driven development, Claude skills, harness engineering.

→ [felipefontoura.com/articles](https://felipefontoura.com/articles)

---

### Stack

| Backend | Infrastructure |
| --- | --- |
| Node.js / TypeScript | Kubernetes (DOKS) |
| Fastify / NestJS | Terraform |
| Drizzle ORM / Prisma | Docker |
| PostgreSQL | GitHub Actions CI/CD |
| BullMQ / Redis | Prometheus / Grafana |

---

### Links

- [Website](https://felipefontoura.com)
- [LinkedIn](https://linkedin.com/in/felipefontoura)
- [YouTube](https://www.youtube.com/@f.fontoura) (80K+ subscribers)
- [X/Twitter](https://x.com/felipefontoura)
