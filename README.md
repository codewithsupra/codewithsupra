<div align="center">

# Supratim Sarkar

I build the parts of a product most demos skip — crash recovery, exactly-once
scheduling, conflict-free sync — and ship them live, alone, end to end.

**M.Sc. Software Engineering** · VU Amsterdam & University of Amsterdam, 2025 &nbsp;·&nbsp;
**AWS Certified Solutions Architect – Associate** &nbsp;·&nbsp;
Backend at **Mendix (Siemens)**, 2023

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/supratimsarkar99)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://supratim-software-portfolio.vercel.app)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:supratim347@gmail.com)

</div>

<br>

## Six live products, one engineer

Every link below is real and checked before this line was written. No dead demos, no placeholder screenshots.

<br>

**[Pulse](https://pulse-wy6e.onrender.com)** — Uptime monitoring that catches an outage before your customers do.
Watches sites and APIs around the clock; the hard part is doing it across many servers at once without ever firing a duplicate alert.
`Node.js` `Express` `MongoDB` `Socket.io` `worker_threads` `Docker`
→ [live](https://pulse-wy6e.onrender.com) · [source](https://github.com/codewithsupra/pulse)

**[Durable Agent Engine](https://durable-agent-engine-b034212e-e938-4496-b3f0-50045a25b6f9.fly.dev/)** — An LLM agent runner that survives being killed mid-task.
No Redis, no managed queue — just Postgres, claiming and reclaiming work so nothing is silently lost. Proven with a chaos test that `kill -9`s workers on purpose.
`Node.js` `PostgreSQL` `WebSocket` `Docker`
→ [live](https://durable-agent-engine-b034212e-e938-4496-b3f0-50045a25b6f9.fly.dev/) · [source](https://github.com/codewithsupra/durable-agent-engine)

**[Anchor](https://anchor-ai-indol.vercel.app)** — Notes that never lose a keystroke, on any number of devices, even offline.
Every edit is saved locally first and merged automatically when devices reconnect — the same conflict-free approach behind Figma and Notion.
`Yjs (CRDTs)` `IndexedDB (y-indexeddb)` `Tiptap/ProseMirror` `y-websocket`
→ [live](https://anchor-ai-indol.vercel.app) · [source](https://github.com/codewithsupra/anchor.ai)

**[PantryChef](https://pantry-chef-7s80.onrender.com)** — Turns what's already in your kitchen into meals you can cook tonight.
Tracks your pantry, shows what you can make right now, and explains each AI-assisted step before it happens instead of after.
`React Router v8` `Prisma` `PostgreSQL` `TypeScript`
→ [live](https://pantry-chef-7s80.onrender.com) · [source](https://github.com/codewithsupra/pantry-chef)

**[OSS Finder](https://oss-finder-phi.vercel.app)** — Helps first-time contributors find a pull request that will actually get merged.
Ranks GitHub projects by how likely an outsider's first PR is to succeed, so beginners stop wasting days on repos that never respond.
`React 19` `TypeScript` `Redux Toolkit` `Clerk`
→ [live](https://oss-finder-phi.vercel.app) · [source](https://github.com/codewithsupra/oss-finder)

<br>

## Open source

| Project | Contribution | Status |
|---|---|---|
| [tiptap](https://github.com/ueberdosis/tiptap) (37K★, 15.4M weekly downloads) | Fixed a crash open for seven months — the Link extension crashed instead of erroring gracefully when configured with an undefined `class` attribute | [Merged](https://github.com/ueberdosis/tiptap/pull/7977) |
| [tiptap](https://github.com/ueberdosis/tiptap) | Fixed a bug silently stripping bold/italic from nested lists, traced to a hardcoded parser value | [Merged](https://github.com/ueberdosis/tiptap/pull/7998) |

<br>

## Stack

**Frontend** — React, Next.js, TypeScript, Redux Toolkit, Tailwind CSS
**Backend** — Node.js, Express, PostgreSQL, MongoDB, GraphQL, WebSockets
**Infra** — Docker, GitHub Actions, AWS, Render, Fly.io, Vercel

<br>

<div align="center">

Based in Bengaluru. Open to backend, full-stack, and founding engineer roles.

</div>
