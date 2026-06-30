<div align="center">

**Supratim Sarkar** — Backend & Full-Stack Engineer

Open-source contributor at [tiptap](https://github.com/ueberdosis/tiptap) (37k★) · AWS Certified Solutions Architect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/supratimsarkar99)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://supratim-software-portfolio.vercel.app)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:supratim347@gmail.com)

</div>

---

## What I've Built

**[Durable Agent Engine](https://durable-agent-engine-b034212e-e938-4496-b3f0-50045a25b6f9.fly.dev/)** — Fault-tolerant LLM agent orchestration on raw Postgres. `SELECT ... FOR UPDATE SKIP LOCKED` durable queue, idempotent DAG execution, crash recovery via lock-TTL reaper, cross-process pub/sub on `LISTEN/NOTIFY`. No Redis, no managed queue. Proven with a chaos test that SIGKILLs workers mid-run.
`Node.js` `PostgreSQL` `WebSocket` `Docker` — [GitHub](https://github.com/codewithsupra/durable-agent-engine)

**[FounderOS](https://founder-os.insforge.site)** — Multi-tenant backend for a founder workspace app. Streaming AI pipeline via `ReadableStream.tee()`, HMAC-verified Stripe webhooks, Postgres row-level security with an isolated admin service-role client.
`Next.js` `TypeScript` `PostgreSQL (RLS)` `Stripe` `GPT-4o` — [GitHub](https://github.com/codewithsupra/founder-os)

**[Anchor](https://anchor-ai-indol.vercel.app)** — Offline-first notes with conflict-free multi-device sync. Every keystroke persisted to IndexedDB as a Yjs CRDT operation before any network call — the same replication strategy behind Figma and Notion.
`Yjs (CRDTs)` `Tiptap/ProseMirror` `IndexedDB` `y-webrtc` `y-websocket` — [GitHub](https://github.com/codewithsupra/anchor.ai)

---

## Open Source

| Repo | PR | Status |
|---|---|---|
| [tiptap](https://github.com/ueberdosis/tiptap) (37k★) | [#7976](https://github.com/ueberdosis/tiptap/pull/7976) — fix `character-count` `autoTrim` boundary logic | ✅ Merged |
| [tiptap](https://github.com/ueberdosis/tiptap) (37k★) | [#7977](https://github.com/ueberdosis/tiptap/pull/7977) — fix Link extension `HTMLAttributes` coercion | ✅ Merged |
| [infisical](https://github.com/Infisical/infisical) (28k★) | [#7028](https://github.com/Infisical/infisical/pull/7028) — fix unreachable admin signup button (flex/scroll clipping) | 🔄 Open |

---

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_SAA--C03-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
