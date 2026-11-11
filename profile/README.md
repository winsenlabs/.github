<div align="center">

# Winsen Labs

**We help companies where AI matters most.**

We know how to build AI and how to govern it.
We advise companies in financial services, healthcare, government, manufacturing and logistics
on what they can do with AI, and we build it with them.

[winsenlabs.com](https://winsenlabs.com) · [winsenrho.com](https://winsenrho.com) · [ocso.winsenlabs.dev](https://ocso.winsenlabs.dev)

</div>

---

## How we work

| | |
|---|---|
| **Strategic partner**<br>We advise, your team builds. | We advise leadership and internal teams on which use cases to back, which models and vendors to use, and what the regulator will ask for. |
| **Deployed AI team**<br>Our engineers, inside your team. | We place engineers we have hired and trained inside your organisation. They build in your systems and follow your approval rules. |
| **Governance review**<br>We review the AI you already run. | We list what is running and who owns it, check what records it keeps, and give you a written report of what to fix first. |

Every team has four points of view on it: engineering, audit, risk and legal.

[More on how we work](https://winsenlabs.com/consulting)

---

## Winsen Rho

**Effortless accountability for every AI action.** [winsenrho.com](https://winsenrho.com)

Rho is our AI governance platform for banks, financial services and insurance. It keeps a record of every AI agent an institution runs and every decision each one makes, whether the agent was built in-house or by a vendor, and checks those decisions against what happened next in the institution's own systems. When a regulator asks, the evidence is already there.

Rho is proprietary. It is our flagship product.

---

## In the open

### [OCSO](https://github.com/winsenlabs/ocso): Open Customer Success Orchestration

[![Apache 2.0](https://img.shields.io/badge/license-Apache--2.0-5F7A1A?style=flat-square)](https://github.com/winsenlabs/ocso/blob/main/LICENSE)
[![Status](https://img.shields.io/badge/status-pre--1.0-5F7A1A?style=flat-square)](https://github.com/winsenlabs/ocso)
[![Site](https://img.shields.io/badge/site-ocso.winsenlabs.dev-5F7A1A?style=flat-square)](https://ocso.winsenlabs.dev)

Customer service is usually spread over several channels, tools and teams. OCSO puts it in one self-hosted layer, where AI agents and your own people answer customers together.

- **Channels:** WhatsApp, web chat, Slack and Microsoft Teams behind one conversation model.
- **Handoff both ways** between agents and people, with the AI's summary carried across.
- **Tools from your own systems** over MCP, with per-agent grants and confirmation for sensitive actions.
- **A second person approves every configuration change**, and everything is kept in a signed, tamper-evident audit store.
- **Six model providers**, self-hosted with Docker Compose or Terraform for AWS.

```bash
git clone https://github.com/winsenlabs/ocso.git && cd ocso
cp .env.example .env
OCSO_DEMO_SEED=true docker compose --profile demo up -d --build
```

[Website](https://ocso.winsenlabs.dev) · [Docs](https://github.com/winsenlabs/ocso/tree/main/docs) · [Roadmap](https://github.com/winsenlabs/ocso/blob/main/ROADMAP.md)

### [OVO](https://github.com/winsenlabs/ovo): Open Voice Orchestrator

We think a company should own its voice channel. OVO lets you build, run and monitor voice agents on your own servers, so the calls, recordings and transcripts stay with you. Every part is a plugin you can swap: the conversation engine, speech, telephony, tools and the console.

The repository has the runnable applications, tests, documentation and deployment profiles. OVO is in use at a few organisations today.

[Docs](https://github.com/winsenlabs/ovo/tree/main/docs)

---

## Also from Winsen Labs

**[Ahada Health](https://ahadahealth.com)** is coming soon. After a clinic visit, it follows up on each step the doctor set with the patient on WhatsApp, in the clinic's own name.

---

## Get in touch

**[Talk to us](https://winsenlabs.com/contact)** · hello@winsenlabs.com · [Careers](https://winsenlabs.com/careers) · [Discord](https://discord.gg/7zxegt73zr)

Contributions are welcome on the open repositories. Start with their issues.

<div align="center">

<sub>Mumbai and Chennai. Work is better with Winsen.</sub>

</div>
