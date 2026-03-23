# Felipe Fontoura

**Senior Backend Developer — Fintech & Bitcoin Infrastructure**

Building payment gateways and exchange systems on the Liquid Network. 25+ years shipping production software, from satellite hardware at INPE to multi-currency checkout systems at TUI Group (23B EUR). Currently focused on bridging traditional payment rails to Bitcoin.

Bitcoin maximalist. 100% in. I don't advertise it — I just build on it.

---

### What I'm Building

**[liqpay.net](https://liqpay.net)** — Payment gateway and OTC exchange on the Liquid Network. PIX (Brazil) → LIQ tokens → L-BTC / USDT, with on-chain settlement.

`Node.js` `TypeScript` `Fastify` `Drizzle ORM` `PostgreSQL` `BullMQ` `Redis` `Elements Core` `Kubernetes` `Terraform`

- 13-app monorepo (Turborepo), 3 Fastify APIs, 3 PostgreSQL databases
- Provider-agnostic PIX integration (4 PSPs via factory pattern)
- OTC exchange engine with VWAP pricing, 5-source price aggregation, asymmetric spreads
- Exchange Settler with deposit detection, tolerance-based auto-refund, crash recovery
- Full OAuth 2.1/OIDC auth server (5 roles, 19 scopes, JWKS, M2M)
- Kubernetes (DOKS, HPA), Prometheus/Grafana, GitHub Actions CI/CD

LIQ Token on Liquid Network: [8a4053ef...707e](https://blockstream.info/liquid/asset/8a4053ef4b0ad70ee88284e3589829da3ac6f9ce9475c45802faf1f46627707e)

---

### Open Source

- [Aqua Wallet PR #104](https://github.com/AquaWallet/aqua-wallet/pull/104) — Surface balances for non-curated Liquid assets. Fund visibility fix touching GDK's asset registry + balance resolution, 11 unit tests.

---

### Stack

```
Backend                     Infrastructure              Bitcoin
─────────────────────       ─────────────────────       ─────────────────────
Node.js / TypeScript        Kubernetes (DOKS)           Liquid Network
Fastify                     Terraform                   Elements Core (RPC)
Drizzle ORM                 Docker                      Blockstream GDK
PostgreSQL 17               GitHub Actions CI/CD        L-BTC / UTXO
BullMQ / Redis              Prometheus / Grafana        Lightning Network
Zod / Pino                  Cloudflare
```

---

### Other Projects

- **JusPro** — Legal Tech for judicial document processing using Claude and Gemini APIs in production
- **SmartDev Academy** — 30,000+ students trained across software engineering and AI-augmented development
- **Spec-Driven Development** — Proven methodology for AI-assisted coding with Claude Code

---

### Links

- [LinkedIn](https://linkedin.com/in/felipefontoura)
- [YouTube](https://www.youtube.com/channel/UC-lHCBqKEtnXA0SBtdOP0bw/) — 80,000+ subscribers
