<div align="center">

# Supratim Sarkar

I build the infrastructure other engineers' systems need to survive contact with reality —
crash recovery, exactly-once execution, and the tooling to see what an AI agent is actually
doing when it's wrong. Then I ship the whole thing live, alone, end to end.

**M.Sc. Software Engineering** · VU Amsterdam & University of Amsterdam, 2025 &nbsp;·&nbsp;
**AWS Certified Solutions Architect – Associate** &nbsp;·&nbsp;
Software Engineer Intern at **Mendix (Siemens)**, 2023

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/supratimsarkar99)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://supratim-software-portfolio.vercel.app)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:supratim347@gmail.com)

</div>

<br>

## Flagship — Lull

**[Lull](https://lull-ai.vercel.app)** is a mental-health app built to a standard most side
projects skip entirely: every health field is AES-256-GCM encrypted before it reaches the
database, Postgres row-level security is enforced on every table, PII is stripped from
anything an LLM sees or returns, and every AI call is routed through zero-data-retention
providers only. The crisis-detection layer runs in English, Hindi and romanized Hinglish
**simultaneously**, because a person in crisis doesn't code-switch to match the UI language —
and it's verified with a red-team suite that runs 40+ adversarial prompts against the live
model in CI, not just unit tests of the regex.

`Next.js 16` `TypeScript` `Postgres RLS` `AES-256-GCM` `OpenRouter` `WebGL` `Web Audio` `i18n`

→ [live](https://lull-ai.vercel.app) · [source](https://github.com/codewithsupra/lull)

<br>

## Infrastructure for AI agents

Most people are building agents. I've been building what the agents run *on* — the boring,
load-bearing parts: what happens when a worker dies mid-task, how you watch one from the
outside, what it actually costs. Every link below is live; I checked each one before writing
this sentence.

**[Durable Agent Engine](https://durable-agent-engine-b034212e-e938-4496-b3f0-50045a25b6f9.fly.dev/)** — An LLM agent runner that survives being killed mid-task.
No Redis, no managed queue — Postgres `SKIP LOCKED` claims and reclaims work so nothing is silently lost. Proven with a chaos test that `kill -9`s workers on purpose, mid-run.
`Node.js` `PostgreSQL` `WebSocket` `Docker`
→ [live](https://durable-agent-engine-b034212e-e938-4496-b3f0-50045a25b6f9.fly.dev/) · [source](https://github.com/codewithsupra/durable-agent-engine)

**[Terrain](https://terrain-3oqc.onrender.com)** — How much does it actually cost an agent to work in your codebase? Terrain finds the static-analysis issues already sitting in a repo, hands a sample to a real coding agent one at a time in isolated git worktrees, verifies every fix mechanically, and reports the dollar/token/hour cost of fixing the rest — a number instead of an opinion.
`TypeScript` `Git worktrees` `Static analysis`
→ [live](https://terrain-3oqc.onrender.com) · [source](https://github.com/codewithsupra/terrain)

**[Relay](https://relay-multiplayer.onrender.com)** — Multiplayer AI agent sessions: one shared live workspace where anyone with the link watches the agent stream token by token, interrupts it mid-sentence, and takes or hands off control — closer to a live Google Doc than a solo chat window. An append-only, sequence-numbered event log makes a join an hour in replay exactly what everyone else already saw, with no gaps.
`TypeScript` `WebSockets` `Event sourcing`
→ [live](https://relay-multiplayer.onrender.com) · [source](https://github.com/codewithsupra/relay)

**[AgentScrub](https://agentscrub.vercel.app)** — A scrubbable timeline for [Browser Use](https://github.com/browser-use/browser-use) agent runs: drag across a completed run like a video and see, at every step, the screenshot the agent looked at, the action it took, and the reasoning it gave — side by side, instead of buried in a flat log.
`TypeScript` `Browser automation`
→ [live](https://agentscrub.vercel.app) · [source](https://github.com/codewithsupra/agentscrub)

<br>

## More live systems

| Project | What it does | Stack |
|---|---|---|
| **[Verdict](https://verdict-pi-peach.vercel.app)** | Tells you whether a prompt change really made your LLM agent worse, or whether you're looking at sampling noise — paired two-level bootstrap over cases, a measured noise floor, no verdict without enough power | `TypeScript` `PostgreSQL` `Vitest` |
| **[PantryChef](https://pantry-chef-63808735-68ed-4572-ad6e-8395ee50d819.fly.dev)** | Tracks a kitchen's pantry, ranks saved recipes by what's actually on hand, and hands the busywork to a tool-calling agent with a real fallback chain across three free-tier models | `React Router v8` `Prisma` `Postgres` |
| **[Anchor](https://anchor-ai-indol.vercel.app)** | Notes that never lose a keystroke on any device, even offline — every edit saved locally first, merged automatically on reconnect | `Yjs (CRDTs)` `IndexedDB` `ProseMirror` |
| **[Aria](https://aria-acess.vercel.app)** | WCAG accessibility auditor — pairs `axe-core` with a vision model on the rendered page to catch the contrast and layout failures rules alone miss | `Next.js` `Drizzle ORM` `Puppeteer` |
| **[OSS Finder](https://oss-finder-phi.vercel.app)** | Ranks GitHub projects by how likely a first-time contributor's PR is to actually get merged | `React 19` `Redux Toolkit` `Clerk` |

<br>

## Open source

| Project | Contribution | Status |
|---|---|---|
| [tiptap](https://github.com/ueberdosis/tiptap) (38K★, 16.8M weekly downloads) | Fixed a crash open for seven months — the Link extension crashed instead of erroring gracefully when configured with an undefined `class` attribute | [Merged](https://github.com/ueberdosis/tiptap/pull/7977) |
| [tiptap](https://github.com/ueberdosis/tiptap) | Fixed a bug silently stripping bold/italic from nested lists, traced to a hardcoded parser value | [Merged](https://github.com/ueberdosis/tiptap/pull/7998) |

<br>

## Stack

**Backend** — Node.js, Express, PostgreSQL (RLS), MongoDB, GraphQL, WebSockets, field-level encryption
**AI / agents** — OpenRouter, tool-calling agents, durable execution, agent observability, i18n-safe prompting
**Frontend** — React, Next.js, TypeScript, Redux Toolkit, Tailwind CSS
**Infra & testing** — Docker, GitHub Actions, AWS, Fly.io, Render, Vercel, Vitest, Jest

<br>

<div align="center">

Based in Muscat, Oman. Open to remote roles worldwide, or on-site in Bengaluru — backend, AI infrastructure, and founding engineer roles.

</div>
