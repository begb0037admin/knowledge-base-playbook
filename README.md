# AI Knowledge Base Playbook

Complete build and replication guide for the HR FA AI Knowledge Base — University of Oxford, HR Systems.

## What This Is

A detailed playbook documenting how an AI-assisted knowledge base was designed, built, debugged, and populated for the HR Functional Analysis team. It records everything so the system can be replicated for other departments or organisations without repeating months of iteration.

**Live playbook:** [knowledge-base-playbook/playbook.html](https://begb0037admin.github.io/knowledge-base-playbook/playbook.html)

## The System It Documents

- **Live KB:** https://kb.lelitte.co.uk/
- **KB repo:** https://github.com/begb0037admin/hr-fa-knowledge-base
- 2,515 documents · 567 PDFs · 13,472 searchable chunks · £0 infrastructure cost

## What the Playbook Covers

| Section | Contents |
|---|---|
| What Was Built | Full stack — scraper, index builder, Cloudflare Worker, static SPA, voice UI |
| Architecture | Component diagram, technology decisions with rationale |
| Data Sources | Three sources: SharePoint (260 docs), Help Centre articles (~1,948), Salesforce guide PDFs (307) |
| Authentication | Salesforce community login, GitHub secrets, Cloudflare Worker secrets |
| Build Guide | 10 steps to stand up a replica from scratch |
| Guide PDF Journey | Full failure history — 4 attempts, root causes, the fix (`download_salesforce_via_page()`) |
| Pain Points | 10 documented lessons learned |
| What Was Ruled Out | Intercom API, direct HTTP to Salesforce, `requests.get()`, `context.request.get()` |
| Maintenance | Routine tasks, triggers, session expiry |
| Expansion | Recommendations for replication in other departments or organisations |

## Owner

Kevin Lelitte · Manager/Director HR Systems · University of Oxford
