<div align="center">

# Winsen Labs

**We rebuild and reimagine legacy systems for the AI world.**

Winsen Labs builds the AI for financial services, manufacturing, logistics and healthcare.
We go and find what AI has made newly possible, then work with teams to build it for real.

[winsenlabs.com](https://winsenlabs.com) · [winsen.ai](https://winsen.ai) · [platos.dev](https://platos.dev)

</div>

---

## What we do

Most AI in the enterprise sits beside the work rather than inside it. It operates on a context window, not on a model of the company, so nobody can hand it anything that matters. We build the other thing: systems that hold enough real context to be trusted with real work, deployed where the data already lives, with a named human approving every output.

The work runs in two directions. We take on a small number of engagements a year with teams in regulated and operationally heavy industries, and we build products out of what we learn there.

**[Winsen One](https://winsen.ai)** — a command centre for AI employees that work alongside your team. Credit file review, reconciliation, alert disposition, quality records, freight audit. They read, check and draft; a person on your team approves. Isolated deployments, and your data stays yours.

**[Walle](https://walle.winsenlabs.dev)** — your AI helps you think, write and decide, and then every consequence still lands on you: contacts to update, follow-ups to chase, records to fix. Walle sits in your Slack with your tools connected and takes that part. It drafts before it sends and asks before it acts.

---

## Open source

### [Platos](https://github.com/winsenlabs/platos) — the agent runtime

[![Apache 2.0](https://img.shields.io/github/license/winsenlabs/platos?style=flat-square&color=8B6B3D)](https://github.com/winsenlabs/platos/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/winsenlabs/platos?style=flat-square&color=8B6B3D)](https://github.com/winsenlabs/platos/stargazers)
[![Docs](https://img.shields.io/badge/docs-platos.dev-8B6B3D?style=flat-square)](https://platos.dev/docs)

Platos is the piece of our own stack we think should not be anybody's competitive advantage, so we gave it away. It is a complete agent runtime: the open-source replacement for hosted services like Claude Managed Agents and OpenAI Assistants.

Build, ship and operate AI agents on infrastructure you own.

- **Streaming chat runtime** with prompt caching, tool-calling, structured outputs, sub-agents and multi-turn compaction.
- **Durable execution** on [trigger.dev](https://trigger.dev). Every long-running tool call, scheduled job and batch operation is a resumable run with retries, queues and traces.
- **Universal MCP gateway** federating entity-pushed, native, skill and control-plane tools behind one endpoint, with OAuth scoping and per-tool ACL.
- **Memory, skills and observability** wired in at the runtime layer: vector store, knowledge graph, manifest-driven skills, OpenTelemetry traces, ClickHouse cost ledger.
- **Multi-tenant by default.** Every row is keyed by organisation, project and environment, so the same primitives fit a SaaS product or an internal platform.
- **BYOK across providers.** Anthropic, OpenAI, Google, Vertex AI, OpenRouter. Keys are encrypted in your database and never leave it.

You own the infrastructure, the data and the model choice. No seat licence, no telemetry-based billing, no lock-in.

```bash
git clone https://github.com/winsenlabs/platos.git
cd platos
cp .env.example .env          # set ANTHROPIC_API_KEY, or any other provider
docker compose -f docker-compose.platos.yml up -d
open http://localhost:3030
```

Chat-ready in about two minutes. Apache 2.0.

[Quickstart](https://platos.dev/guides/quickstart) · [Docs](https://platos.dev/docs) · [Architecture](https://platos.dev/docs/architecture) · [Roadmap](https://platos.dev/roadmap) · [Discord](https://discord.gg/7zxegt73zr)

### [Rocketman](https://github.com/winsenlabs/rocketman)

Project management for the age of AI coding agents. A hub that lives inside your repo as one offline file, plus a skill stack that walks an idea from spec to shipped, so an agent picks up durable project context instead of starting cold every session. MIT.

---

## Working with us

We take on a small number of engagements a year, usually with teams who have a hard problem in a regulated or operationally heavy environment and who want to own what gets built.

**[winsenlabs.com](https://winsenlabs.com)** · **hello@winsenlabs.com**

Contributions to Platos are welcome. Start with the [issues](https://github.com/winsenlabs/platos/issues), or come and say hello in [Discord](https://discord.gg/7zxegt73zr).

<div align="center">

<sub>Made in Chennai. Work is better with Winsen.</sub>

</div>
