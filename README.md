Most of my recent professional work — including a 0-to-1 generative AI
video platform — is closed source. This profile is the workbench:
things I build for myself out of curiosity or mild annoyance, and
then keep using.

---

## On the bench

- **[tideline](https://github.com/ryanqin/tideline)** — an on-device
  translation agent (text, photo, voice) where every translation quietly
  becomes part of a personal phrasebook: each word keeps its photo, audio,
  and the situation it came from, then resurfaces for spaced-repetition
  review. Fully offline, Gemma 4 on local hardware, web + Android. The bet:
  language learning as a byproduct of living somewhere, not a curriculum.
- **[crabwatch](https://github.com/ryanqin/crabwatch)** — a macOS tray app
  that renders every local Claude Code session as a pixel crab on a beach.
  Click a crab for that session's audit timeline — what changed, what it
  cost, with a jump back to the exact terminal. Built because I never clear
  sessions and wanted that history legible at a glance.
- **[switchboard](https://github.com/ryanqin/switchboard)** — a demo
  customer-support ops console: one inbox across chat, email, and phone
  transcripts, an AI assist layer for agents (summary, intent, grounded
  reply drafts), and an ops dashboard where every metric's definition
  ships next to the number — plus an eval that scores the exact outputs
  the product serves.
- **Personal infra** — [dashboard-me](https://github.com/ryanqin/dashboard-me)
  (Mini Habits dashboard — every minute counts),
  [health-detector](https://github.com/ryanqin/health-detector) (a
  stress-recovery index on the Oura API). Small tools, real daily use.
- **[job-hunter](https://github.com/ryanqin/job-hunter)** — a CLI that runs
  a job search like an ops pipeline: log applications, store JDs, generate
  interview prep against my own resume.

## What I'm exploring

- **How much a small on-device model can actually carry.** Tideline runs
  quantized Gemma 4 (E2B / E4B) on phone-class hardware, lately including
  vision for photo translation. Working principle: engineering bears the
  load, the model adds the finishing touch — a weak LLM decorates the
  structure, it never holds it up.
- **What supervising a fleet of agents should feel like.** As more of my
  work runs through coding agents, my own attention becomes the scarce
  resource. CrabWatch is the testbed: ambient awareness on top — pixel
  crabs, quiet by default, motion reserved for real signal — and a full
  audit trail underneath for when I actually want to look.
- **Replay forensics for game AI.** A Kaggle bot competition turned into
  reverse-engineering winning strategies from hundreds of downloaded
  episodes — behavioral signatures, local arenas, red-teaming my own
  conclusions before acting on them. The recurring lesson: the bottleneck
  is rarely a better bot, it's a referee you can trust.
## How I build

I learn and design as a **mesh topology** rather than a checklist: start
from the architecture — what are the rooms, what are the edges between
them — then drill into the nodes. The CS + Psychology double major shows
up everywhere: I'm equally interested in how a system is wired and in how
the person on the other end of it actually behaves.

- Read the whole codebase before changing anything in it.
- Ship rough, study the friction, rewrite.
- Treat docs and dashboards as part of the system, not commentary on it.

Mostly Python and TypeScript; on the AI side — Claude API, MCP, local
Gemma inference, agent loop and eval design.

---

*Outside the terminal: top-rope climber, currently exploring 5.12a.
Same problem-solving loop, different walls.*
