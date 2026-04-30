**These repos are working drafts, not finished products. The point is to show how I think when I have to figure something out from scratch.**

Most of my recent work — including a 0-to-1 generative AI video platform — is closed source, so this profile leans on what I build outside of the day job.

---

## How I build

I learn and design as a **mesh topology** rather than a checklist. When I pick up a new system, I start from the architecture — what are the rooms, what are the edges between them — then drill into the individual nodes. The CS + Psychology background shows up here: I'm equally interested in how a system is wired and in how the person on the other end of it actually behaves.

In practice that means I tend to:

- Read the whole codebase before changing anything in it. I'd rather spend a day mapping the topology than two weeks fighting it.
- Ship rough, study the friction, rewrite. Most of my public repos are visibly mid-loop.
- Treat docs and dashboards as part of the system, not commentary on it.

## What I'm exploring

- **Local AI agent deployment.** Running Gemma 4 (E2B / E4B) on local hardware and building a small agent framework around it — see [`tideline`](https://github.com/ryanqin/tideline), an on-device translation agent where language learning emerges as a passive byproduct. The hackathon driving its first milestone is a forcing function; the framework is the point.
- **Reverse-engineering production agent codebases.** Reading [openclaw](https://github.com/openclaw/openclaw) and [hermes-agent](https://github.com/NousResearch/hermes-agent) end to end to understand how real coding agents handle planning, tool use, and context. Notes live in Obsidian.
- **Knowledge management as personal infra.** A long-running Obsidian vault organized around MOCs, with Git sync underneath. Habits and dashboards built on top of it — see [`dashboard-me`](https://github.com/ryanqin/dashboard-me).
- **Personal data pipelines.** Wearable and health data piped through Python into local agents — quietly the most useful thing I've built for myself.

## Tech stack

**Languages** — Python, TypeScript

**AI / Agents** — Anthropic Claude API, MCP, local Gemma inference, agent loop / tool design, evals

**Infra & tooling** — Git, Docker, dotfiles, Obsidian as a working-memory layer

**Comfortable in** — system design, agent architecture, prompt and context engineering, the boring parts of shipping (logging, configs, deploy)

---

*Outside the terminal: top-rope climber, currently exploring 5.12a. Same problem-solving loop, different walls.*
