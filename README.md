<div align="center">

# 🗺️ Synapse

**A complete campus platform for Adamas University** — verified department chat
rooms, a RAG-powered AI campus assistant, a WebGL campus map with AI navigation
and live bus tracking, punch-in location tracking, notices and a photobooth.

A **product-design + systems-architecture case study**, specified end-to-end in
[`plan.md`](plan.md) and [`docs/PLAN.md`](docs/PLAN.md).

</div>

---

## 🧭 What's in scope

| Area | Details |
|---|---|
| **Campus UMS** | Dashboard, My Account, exams, previous qualifications, academics, hostel, transport, feedback |
| **AI assistant** | Chatbot answering anything about Adamas campus, backed by RAG over campus docs |
| **Department chat** | Per-school, per-department, per-year rooms — verified students only, note sharing |
| **Campus map** | Canvas/WebGL map with **AI navigation** and **live bus tracking** |
| **Notices** | Publish + push notifications across the campus |
| **Presence** | Punch-in / punch-out location tracking during college hours — find anyone on campus |
| **Photobooth & clubs** | On-campus photobooth, club discovery and activity feeds |
| **AI agent** | An agent driven by the chatbot for multi-step campus tasks |

## 📐 Design docs

- [`plan.md`](plan.md) — original product requirements & feature breakdown
- [`docs/PLAN.md`](docs/PLAN.md) — structured plan and architecture notes

## 💻 Intended stack

```
Next.js · Expo (mobile) · NestJS · PostgreSQL · Redis
Prisma · Socket.io · OpenAI · WebGL · Razorpay
```

## Status

📋 **Specified & designed** — full product spec and systems architecture are
locked in the docs above. Implementation in progress.

---

<div align="center">

Designed & built by [Saptarshi Mukherjee](https://github.com/Saptarshi2006)

</div>
