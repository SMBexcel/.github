# SMBexcel

**Skills, workflows, and AI tooling for searchers, investors, and operators.**

Open-source utilities built on top of Claude, n8n, and Notion. Each release ships alongside a write-up at [www.smbexcel.com](https://www.smbexcel.com).

---

## What's here

### Skills (Claude.ai / Claude Code)

| Repo | Status | What it does |
|---|---|---|
| [**skills**](https://github.com/SMBexcel/skills) | active | Plug-and-play Claude skills. Drop a folder into your skills directory and they work. |

Currently shipping in [`skills`](https://github.com/SMBexcel/skills):

- **[lemonade](https://github.com/SMBexcel/skills/tree/main/lemonade)** `v1.2` — Persistent memory for Claude chats backed by a Notion database you own. Distill at end of session, rehydrate at the start of the next. Counters context rot.
- **[smb-find-dealstream](https://github.com/SMBexcel/skills/tree/main/smb-find-dealstream)** `v1.0` — Pull filtered Dealstream listings into a CSV using your own logged-out browser session. No API key, no paid tool. Guided flow with legal-posture briefing. _Claude Code only._
- **[smb-find-ibba](https://github.com/SMBexcel/skills/tree/main/smb-find-ibba)** `v1.0` — Pull every IBBA business broker (~2,800) into a CSV — name, company, email, phone, website, location — straight from the directory's own public endpoints. No login, no cookie, no paid tool. _Claude Code only._

### Workflows (n8n)

_Coming soon._

---

## Stay in the loop

The build notes, the prompt patterns I actually use, and the next release ship in the newsletter:

**→ [www.smbexcel.com](https://www.smbexcel.com)**

---

_Maintained by [David Schreiber](https://www.smbexcel.com). All code MIT licensed unless noted in the project folder._
