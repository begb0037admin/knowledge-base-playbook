# Handover — AI Knowledge Base Playbook

**To:** New session
**From:** Session of 7 July 2026
**Owner:** Kevin Lelitte (kevin.lelitte@admin.ox.ac.uk · GitHub `begb0037admin`)

---

## Current State — 7 July 2026

**Playbook published** ✅ — initial version committed to main.

This repo was created on 7 July 2026 at the conclusion of the hr-fa-knowledge-base guide PDF harvest project. The playbook documents the entire system end-to-end so it can be replicated for other departments or organisations.

The playbook HTML was produced as a Claude Artifact and approved by Kevin before being committed here — in compliance with CONSTITUTION.md Section 11.

**No immediate next steps.**

Optional (Kevin's call):
- Enable GitHub Pages on this repo (Settings → Pages → Deploy from main) so `playbook.html` is publicly accessible at `https://begb0037admin.github.io/knowledge-base-playbook/playbook.html`
- Propagate the updated AGENT_MODEL.md (which now lists this repo in Section 8) to all other governed repos

---

## What This Is

A complete, standalone reference document covering:

1. Introduction — what the system is and why it exists
2. What Was Built — the full stack, from scraper to voice UI
3. Architecture — component diagram and technology decisions
4. Technology Stack — every tool with rationale and cost
5. Data Sources — all three sources, with document counts
6. Authentication — Salesforce community login, GitHub secrets
7. Build Guide — 10 steps to replicate from scratch
8. Workflow Configuration — GitHub Actions workflow inputs
9. The Guide PDF Journey — full failure history, 4 attempts, root causes, the fix
10. Pain Points & Lessons Learned — 10 rows, all documented
11. What Was Ruled Out — approaches that failed and why
12. Maintenance — routine tasks and triggers
13. Expansion Recommendations — next steps for other departments
14. Appendix — file reference and git commit table

---

## Knowledge Base This Documents

| Item | Detail |
|---|---|
| KB repo | https://github.com/begb0037admin/hr-fa-knowledge-base |
| Live KB | https://kb.lelitte.co.uk/ |
| Documents | 2,515 |
| PDFs indexed | 567 (260 SharePoint + 307 Salesforce guide PDFs) |
| Web articles | ~1,948 (deep-scraped from Access Group Help Centres) |
| Index chunks | 13,472 |
| Infrastructure cost | £0 (GitHub Pages + Cloudflare free tier) |
| Completed | 7 July 2026 |

---

## Git Reference

| Commit | What it represents |
|---|---|
| `a0ec4ab` | Initial repo creation (GitHub auto-init) |
| (initial push) | CLAUDE.md, HANDOVER.md, CONSTITUTION.md, AGENT_MODEL.md, README.md, playbook.html |
