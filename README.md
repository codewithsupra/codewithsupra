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




## Sponsorbound

**[Sponsorbound](https://h1bound.vercel.app)** helps international students find jobs in the UK, the Netherlands and Ireland at employers on the official visa-sponsor registers: three government datasets (UK Home Office, Dutch IND, Irish permits), normalised into one employer table and matched to jobs pulled daily from public job-board APIs. The part I care about is what it refuses to claim. Being on a register is not a promise to sponsor a particular job, so every job-to-employer link carries a confidence and only confirmed ones say "Licensed sponsor"; the rest say "Possible sponsor". I measured that against a hand-labeled evaluation set with a held-out split, and the evaluation is how I found (and fixed) a matcher that read "we can't offer visa sponsorship" as an offer. Gmail sending needs your approval for every email and can't double-send; CVs, chats and tokens are AES-256-GCM encrypted. Early, no users yet; the evaluation, incident log and runbook are in the repo.

`Next.js 16` `TypeScript` `Postgres RLS` `AI SDK` `Gmail API` `Vitest`

→ [live](https://h1bound.vercel.app) · [source](https://github.com/codewithsupra/h1bound) · [how it's measured](https://github.com/codewithsupra/h1bound/blob/main/docs/EVAL.md)

<br>

## Infrastructure for AI agents

Most people are building agents. I've been building what the agents run *on* — the boring,
load-bearing parts: what happens when a worker dies mid-task, how you watch one from the
outside, what it actually costs. Demos run on free hosting, so the first load can take a minute
while they wake up.


**[Terrain](https://terrain-3oqc.onrender.com)** — How much does it actually cost an agent to work in your codebase? Terrain finds the static-analysis issues already sitting in a repo, hands a sample to a real coding agent one at a time in isolated git worktrees, verifies every fix mechanically, and reports the dollar/token/hour cost of fixing the rest — a number instead of an opinion.
`TypeScript` `Git worktrees` `Static analysis`
→ [live](https://terrain-3oqc.onrender.com) · [source](https://github.com/codewithsupra/terrain)


**[AgentScrub](https://agentscrub.vercel.app)** — A scrubbable timeline for [Browser Use](https://github.com/browser-use/browser-use) agent runs: drag across a completed run like a video and see, at every step, the screenshot the agent looked at, the action it took, and the reasoning it gave — side by side, instead of buried in a flat log.
`TypeScript` `Browser automation`
→ [live](https://agentscrub.vercel.app) · [source](https://github.com/codewithsupra/agentscrub)

<br>



## Open source

| Project | Contribution | Status |
|---|---|---|
| [tiptap](https://github.com/ueberdosis/tiptap) (39K★, ~33M weekly downloads of `@tiptap/core`) | Fixed a crash open for seven months — the Link extension crashed instead of erroring gracefully when configured with an undefined `class` attribute | [Merged](https://github.com/ueberdosis/tiptap/pull/7977) |
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
