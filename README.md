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
- **[my-library](https://github.com/ryanqin/my-library)** — technical
  subjects rewritten as novellas: inference engineering, cloud + AI
  deployment, agent architecture. Writing a story about a system is my
  test for whether I actually understand it.
- **Personal infra** — [dashboard-me](https://github.com/ryanqin/dashboard-me)
  (Mini Habits dashboard; 苦功夫，每一分钟都算数),
  [health-detector](https://github.com/ryanqin/health-detector) (a
  stress-recovery index on the Oura API). Small tools, real daily use.
- **[job-hunter](https://github.com/ryanqin/job-hunter)** — a CLI that runs
  a job search like an ops pipeline: log applications, store JDs, generate
  interview prep against my own resume.

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
