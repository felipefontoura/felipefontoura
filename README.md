# Felipe Fontoura

**Engineered with AI.** Production systems that can't fail.

Staff Engineer · Production Systems with AI · builder

I build secure, reliable, scalable systems with AI agents. 25+ years shipping production software, from satellite kernel drivers at INPE to the global checkout serving 20M+ customers at TUI Group (€23B revenue), to a crypto fintech built solo in 70 days.

→ [felipefontoura.com](https://felipefontoura.com/?utm_source=github&utm_medium=social&utm_campaign=bio)

---

### What I built

A crypto fintech on Bitcoin's Liquid Network: a payment gateway, an OTC exchange, and on-chain settlement. Engineered solo in 70 days with AI agents. Private repo.

`TypeScript` `Node.js` `Fastify` `PostgreSQL` `Kubernetes` `Terraform` `Redis` `BullMQ`

- 13-app monorepo, 3 Fastify APIs, 3 isolated PostgreSQL databases
- PIX gateway, 4 PSPs behind a factory pattern (HMAC-SHA256, mTLS to BACEN)
- OTC exchange engine: rolling 24h VWAP, 5 sources, asymmetric spreads
- On-chain settler: confirmation polling, deviation refunds, crash recovery
- OAuth 2.1 / OIDC: 5 roles, 19 scopes, JWKS, M2M, TOTP 2FA
- Kubernetes (DOKS, HPA 2-10), Prometheus and Grafana, CI/CD

→ [Read the case study](https://felipefontoura.com/articles/spec-driven-development-case-study?utm_source=github&utm_medium=social&utm_campaign=spec-driven-development-case-study)

---

### How I build

Build the right thing, engineer it to hold, direct the agents that write it. The bar has always been production: satellites where a failed signal has no patch, a €23B checkout at 99.9% uptime, a fintech moving real money. The AI writes the code. The architecture, the specs, and the call on what "done" means are mine.

The method is plain: structured specs (requirements, design, tasks) are the source of truth, agents execute against them, humans review and ship. I have trained 400+ people in it.

- [What Is Spec-Driven Development?](https://felipefontoura.com/articles/what-is-spec-driven-development?utm_source=github&utm_medium=social&utm_campaign=what-is-spec-driven-development), the complete guide
- [Harness Engineering](https://felipefontoura.com/articles/harness-engineering-ai-coding-agent?utm_source=github&utm_medium=social&utm_campaign=harness-engineering-ai-coding-agent), stop upgrading the model and fix the harness
- [How to write a spec an AI can build from](https://felipefontoura.com/articles/how-to-write-a-spec?utm_source=github&utm_medium=social&utm_campaign=how-to-write-a-spec), the EARS format and templates

---

### Open source

- [pi-sdd-kit](https://github.com/felipefontoura/pi-sdd-kit): spec-driven development as skills for the Pi coding agent. Steering docs as durable memory, `.status` approval gates, EARS, and a gated PRD to review pipeline.
- [pi-skill-model-handoff](https://github.com/felipefontoura/pi-skill-model-handoff): let each Pi skill pick its own model and thinking level from the `SKILL.md` frontmatter.
- [AI engineering dotfiles](https://github.com/felipefontoura/dotfiles/tree/main/ai): slash commands, agent teams, review pipeline.

---

### Writing

Notes on building production software with AI coding agents: harness engineering, spec-driven development, context, and architecture.

→ [felipefontoura.com/articles](https://felipefontoura.com/articles?utm_source=github&utm_medium=social&utm_campaign=bio)

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

- [Website](https://felipefontoura.com/?utm_source=github&utm_medium=social&utm_campaign=bio)
- [LinkedIn](https://felipefontoura.com/linkedin/?utm_source=github&utm_medium=social&utm_campaign=bio)
- [YouTube](https://felipefontoura.com/youtube/?utm_source=github&utm_medium=social&utm_campaign=bio) (80K+ subscribers)
- [X/Twitter](https://felipefontoura.com/x/?utm_source=github&utm_medium=social&utm_campaign=bio)
