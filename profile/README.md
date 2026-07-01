# SMBexcel

**Skills, workflows, and AI tooling for searchers, investors, and operators.**

Open-source utilities built on top of Claude, [n8n](https://n8n.partnerlinks.io/qsoyb0o2mh2x), and Notion. Each release ships alongside a write-up at [www.smbexcel.com](https://www.smbexcel.com).

---

## What's here

Everything lives in one repo — **[free-ai-tools](https://github.com/SMBexcel/free-ai-tools)** — split into two folders:

### 🧠 Claude Skills (claude.ai / Claude Code)

Self-contained skills you drop into your Claude skills directory. → [browse all](https://github.com/SMBexcel/free-ai-tools/tree/main/claude-skills)

- **[lemonade](https://github.com/SMBexcel/free-ai-tools/tree/main/claude-skills/lemonade)** `v1.2` — Persistent memory for Claude chats backed by a Notion database you own. Distill at end of session, rehydrate at the start of the next. Counters context rot.
- **[smb-find-ibba](https://github.com/SMBexcel/free-ai-tools/tree/main/claude-skills/smb-find-ibba)** `v1.1` — Pull every IBBA business broker (~2,800) into a CSV — name, company, email, phone, website, location — straight from the directory's own public endpoints. No login, no cookie, no paid tool. _Claude Code only._
- **[smb-free-website](https://github.com/SMBexcel/free-ai-tools/tree/main/claude-skills/smb-free-website)** `v1.0` — A real, distinctive small-business website live at your own free URL in ~20 minutes. Claude scaffolds Astro, designs through a self-improving screenshot-driven loop, walks you through GitHub + Cloudflare. No credit card, no design experience, no developer CLI install. _Claude Code only._
- **[sms-free-imessage-agent](https://github.com/SMBexcel/free-ai-tools/tree/main/claude-skills/sms-free-imessage-agent)** `v1.0` — Stand up your own AI sales/concierge agent on iMessage & SMS in ~40 minutes. It answers 24/7, captures leads, books calls, and remembers customers — on infrastructure you own (Cloudflare Workers + Blooio + Supabase + Claude), for pennies per conversation. Ships a working TypeScript template and an optional referral engine. _Claude Code only._

### ⚙️ AI Workflows

Importable [n8n](https://n8n.partnerlinks.io/qsoyb0o2mh2x) automations that wire Claude into your search-and-buy operations. → [browse all](https://github.com/SMBexcel/free-ai-tools/tree/main/ai-workflows)

- **[smb-bizquest-daily](https://github.com/SMBexcel/free-ai-tools/tree/main/ai-workflows/smb-bizquest-daily)** `v1.0` — Scrapes new BizQuest listings every morning, scores each against your buy box with Claude, drafts a personalized broker outreach for the strong fits, and posts the shortlist to Slack — every listing logged to a Google Sheet for an audit trail. Runs for ~$25–30/month (mostly the [n8n](https://n8n.partnerlinks.io/qsoyb0o2mh2x) plan).

### Roadmap (preview)

The full plan is organized around the SMB owner-operator journey — from "should I buy a business?" through "now I'm running it." Each stage will get its own skills and workflows.

```
SMB·excel Roadmap/
├── Prerequisites/
│   ├── e.g., AI Skills vs Workflows
│   ├── e.g., Claude Basics
│   └── e.g., Change Management for AI
├── Search/
│   ├── Find
│   ├── Offer
│   └── Win
├── Buy/
│   ├── Diligence
│   ├── Fund
│   └── Close
├── Lead/
│   ├── Strategy
│   ├── Transition
│   └── Operate
└── Grow/
    ├── Marketing
    ├── Sales & Pricing
    └── Hiring
```

Full breakdown and what's next ships in the newsletter.

---

## Stay in the loop

The build notes, the prompt patterns I actually use, and the next release ship in the newsletter:

**→ [www.smbexcel.com](https://www.smbexcel.com)**

---

_Maintained by [David Schreiber](https://www.smbexcel.com). All code MIT licensed unless noted in the project folder._
