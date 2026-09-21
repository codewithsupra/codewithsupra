<div align="center">

# Supratim Sarkar

Backend engineer. I build the parts of a product most demos skip — crash recovery,
exactly-once scheduling, statistically honest testing — and ship them live, alone, end to end.

**M.Sc. Software Engineering** · VU Amsterdam & University of Amsterdam, 2025 &nbsp;·&nbsp;
**AWS Certified Solutions Architect – Associate** &nbsp;·&nbsp;
Software Engineer Intern at **Mendix (Siemens)**, 2023

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/supratimsarkar99)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://supratim-software-portfolio.vercel.app)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:supratim347@gmail.com)

</div>

<br>

## Six live systems, one engineer

Every link below returns a working page. Every repository is public.

<br>

**[Verdict](https://verdict-pi-peach.vercel.app)** — Tells you whether a prompt change really made your LLM agent worse, or whether you are looking at sampling noise.
Paired two-level bootstrap over cases, a measured noise floor, and no verdict when there are too few cases to support one.
`TypeScript` `Node.js` `PostgreSQL` `PGlite` `Vitest`
→ [live](https://verdict-pi-peach.vercel.app) · [source](https://github.com/codewithsupra/verdict)

**[Durable Agent Engine](https://durable-agent-engine-b034212e-e938-4496-b3f0-50045a25b6f9.fly.dev/)** — An LLM agent runner that survives being killed mid-task.
No Redis, no managed queue — just Postgres, claiming and reclaiming work so nothing is silently lost. Proven with a chaos test that `kill -9`s workers on purpose.
`Node.js` `PostgreSQL` `WebSocket` `Docker`
→ [live](https://durable-agent-engine-b034212e-e938-4496-b3f0-50045a25b6f9.fly.dev/) · [source](https://github.com/codewithsupra/durable-agent-engine)

**[Pulse](https://pulse-wy6e.onrender.com)** — Uptime monitoring that catches an outage before your customers do.
Runs each check exactly once across many servers, so there are never duplicate alerts.
`Node.js` `Express` `MongoDB` `Socket.io` `worker_threads` `Docker`
→ [live](https://pulse-wy6e.onrender.com) · [source](https://github.com/codewithsupra/pulse)

**[OSS Finder](https://oss-finder-phi.vercel.app)** — Helps first-time contributors find a pull request that will actually get merged.
Ranks GitHub projects by how likely an outsider's first PR is to succeed.
`React 19` `TypeScript` `Redux Toolkit` `Clerk`
→ [live](https://oss-finder-phi.vercel.app) · [source](https://github.com/codewithsupra/oss-finder)

**[Anchor](https://anchor-ai-indol.vercel.app)** — Notes that never lose a keystroke, on any number of devices, even offline.
Every edit is saved locally first and merged automatically when devices reconnect.
`Yjs (CRDTs)` `IndexedDB` `Tiptap/ProseMirror` `y-websocket`
→ [live](https://anchor-ai-indol.vercel.app) · [source](https://github.com/codewithsupra/anchor.ai)

**[Aria](https://aria-acess.vercel.app)** — WCAG accessibility auditor: paste a URL, get a report in about ten seconds.
Pairs axe-core rules with a vision model on the rendered page to catch contrast and layout failures rules alone miss.
`Next.js` `TypeScript` `Drizzle ORM` `PostgreSQL` `Puppeteer`
→ [live](https://aria-acess.vercel.app) · [source](https://github.com/codewithsupra/aria-acess.ai)

<br>

## Open source

| Project | Contribution | Status |
|---|---|---|
| [tiptap](https://github.com/ueberdosis/tiptap) (38K★, 16.8M weekly downloads) | Fixed a crash open for seven months — the Link extension crashed instead of erroring gracefully when configured with an undefined `class` attribute | [Merged](https://github.com/ueberdosis/tiptap/pull/7977) |
| [tiptap](https://github.com/ueberdosis/tiptap) | Fixed a bug silently stripping bold/italic from nested lists, traced to a hardcoded parser value | [Merged](https://github.com/ueberdosis/tiptap/pull/7998) |

<br>

## Stack

**Backend** — Node.js, Express, PostgreSQL, MongoDB, GraphQL, WebSockets
**Frontend** — React, Next.js, TypeScript, Redux Toolkit, Tailwind CSS
**Infra & testing** — Docker, GitHub Actions, AWS, Fly.io, Vercel, Vitest, Jest

<br>

<div align="center">

Based in Muscat, Oman. Open to remote roles worldwide, or on-site in Bengaluru — backend, full-stack, and founding engineer.

</div>
