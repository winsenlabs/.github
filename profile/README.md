<div align="center">

# Winsen Labs

**We rebuild and reimagine legacy systems for the AI world.**

Winsen Labs builds the AI for financial services, manufacturing, logistics and healthcare.
We start with your problems, not our product, then work with teams to build it for real.

[winsenlabs.com](https://winsenlabs.com) · [winsen.one](https://winsen.one) · [winsenrho.com](https://winsenrho.com)

</div>

---

## What we build

We take on a small number of engagements a year with teams in regulated and operationally heavy industries, and we build products out of what we learn there. Two of them we sell. The rest we give away.

### Products for financial services

| | |
|---|---|
| **[Winsen One](https://winsen.one)**<br>AI employees for financial services. | Role-specific AI employees for operational work: credit file review, reconciliation, alert disposition. Each one owns a defined queue and works the full volume, not a sample. Nothing it produces counts until a named person signs it, and every action is logged and replayable. |
| **[Winsen Rho](https://winsenrho.com)**<br>Effortless accountability for every AI action. | Measure, monitor and evaluate every AI agent a bank runs, whether built in-house or by a vendor. Rho checks every decision against what actually happened in the bank's own systems, and turns that record into the evidence regulators ask for and the numbers the business needs. |

---

## Built in the open

### [OCSO](https://github.com/winsenlabs/ocso): Open Customer Success Orchestration

[![Apache 2.0](https://img.shields.io/badge/license-Apache--2.0-5F7A1A?style=flat-square)](https://github.com/winsenlabs/ocso/blob/main/LICENSE)
[![Status](https://img.shields.io/badge/status-pre--1.0-5F7A1A?style=flat-square)](https://github.com/winsenlabs/ocso)
[![Site](https://img.shields.io/badge/site-ocso.winsenlabs.dev-5F7A1A?style=flat-square)](https://ocso.winsenlabs.dev)

Customer success is scattered across channels, tools and teams, with AI bolted on at the edges. OCSO is one open layer where AI agents and people serve customers on every channel, under controls you can audit.

- **Channels:** WhatsApp, web chat, Slack and Microsoft Teams behind one conversation model.
- **Human handoff both ways**, with explicit control states and the AI summary carried across.
- **Tools over MCP** from your own systems, with per-agent grants and confirmation for sensitive actions.
- **Maker-checker on every configuration change**, and a separate, hash-chained, signed audit store.
- **Six model providers**, self-hosted with Docker Compose or Terraform for AWS.

```bash
git clone https://github.com/winsenlabs/ocso.git && cd ocso
cp .env.example .env
OCSO_DEMO_SEED=true docker compose --profile demo up -d --build
```

[Website](https://ocso.winsenlabs.dev) · [Docs](https://github.com/winsenlabs/ocso/tree/main/docs) · [Roadmap](https://github.com/winsenlabs/ocso/blob/main/ROADMAP.md)

### [OVO](https://github.com/winsenlabs/ovo): Open Voice Orchestrator

Build, run and observe voice agents on your own infrastructure. Everything is a plugin: the conversation engine, speech, telephony, tools and the console. OVO is what we are building now. The repository holds the product requirements, architecture and engineering plan, and the code is being written in the open. Research findings and architecture feedback are welcome.

### [Platos](https://github.com/winsenlabs/platos): the agent runtime, v2 in progress

Our model-agnostic, self-hostable agent runtime. We are rebuilding it as **Platos v2**, taking what we learned running it in production. The current version stays available while the new one takes shape. [platos.dev](https://platos.dev)

### [Rocketman](https://github.com/winsenlabs/rocketman)

Project management for the age of AI coding agents. A hub that lives inside your repo as one offline file, plus a skill stack that walks an idea from spec to shipped, so an agent picks up durable project context instead of starting cold every session. MIT.

---

## Working with us

We take on a small number of engagements a year, usually with teams who have a hard problem in a regulated or operationally heavy environment and who want to own what gets built.

**[winsenlabs.com](https://winsenlabs.com)** · **hello@winsenlabs.com** · [Discord](https://discord.gg/7zxegt73zr)

Contributions are welcome on any of the open repositories. Start with their issues.

<div align="center">

<sub>Made in Chennai. Work is better with Winsen.</sub>

</div>
