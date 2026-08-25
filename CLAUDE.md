# CLAUDE.md — knowledge-base-playbook
> AI bootstrap entry point. Read this first.
> Keep this file under 200 lines. Push details to linked docs.

## Identity
- **Project:** AI Knowledge Base Playbook
- **Purpose:** Complete build and replication guide for the HR FA AI Knowledge Base — architecture, lessons learned, pain points, and expansion recommendations. A reference so the system can be stood up for other departments or organisations without repeating the same effort.
- **Owner:** Kevin Lelitte, Manager/Director HR Systems, University of Oxford
- **Status:** Active — playbook published
- **Repo:** https://github.com/begb0037admin/knowledge-base-playbook
- **Live playbook:** https://begb0037admin.github.io/knowledge-base-playbook/playbook.html
- **Last updated:** 2026-07-07

## Bootstrap Order
0. **Accountable lead: Adam** (`agent-commons/AGENT_DIRECTORY.md`). Any local session working in this repo should dispatch to Adam immediately rather than operating as a generic session — Adam reads its own `AGENT.md`, `MEMORY.md`, and this file before doing anything.
1. This file (orientation)
2. `HANDOVER.md` (current state — read for any task)
3. `playbook.html` — the playbook itself

Do NOT ask Kevin for a recap. HANDOVER.md is the recap.

## Architecture
| File | Description |
|---|---|
| `playbook.html` | The complete playbook — self-contained single HTML file. Oxford navy theme, dual light/dark mode, sidebar navigation. Covers: Introduction, What Was Built, Architecture, Technology Stack, Data Sources, Authentication, 10-step Build Guide, Workflow Config, Guide PDF Journey (4 attempts + root causes + fix), Pain Points & Lessons Learned, What Was Ruled Out, Maintenance, Expansion Recommendations, Appendix. |
| `CLAUDE.md` | This file. AI bootstrap entry point. |
| `HANDOVER.md` | Current state and session notes. |
| `CONSTITUTION.md` | Governance principles — applies to all repos. |
| `AGENT_MODEL.md` | Runtime operating model — applies to all repos. |
| `README.md` | Public-facing description and links. |

## The Knowledge Base This Documents
- **Live KB:** https://kb.lelitte.co.uk/
- **KB repo:** https://github.com/begb0037admin/hr-fa-knowledge-base
- **Current state:** 2,515 documents, 567 PDFs, 13,472 searchable index chunks
- **Data sources:** Access Group PeopleXD Help Centres, Salesforce-hosted guide PDFs (11 modules), SharePoint (260 documents)

## How to Update the Playbook
1. Edit `playbook.html` — it is a single self-contained file
2. Show the updated Artifact to Kevin for approval
3. Push to main — GitHub Pages will serve the updated file within ~60 seconds

## Effort Level Governance
Before any task where higher effort is warranted, signal to Kevin: what the task is, why higher effort is needed, and an explicit request to raise the effort level. Wait — do not proceed until Kevin raises it. Signal when the high-effort phase is done; Kevin decides when to return to normal. Never change effort level unilaterally. See CONSTITUTION.md Section 10 (v2.1, 2026-07-02).

## Hard Rules
- Never commit API keys or credentials
- Always update HANDOVER.md at end of session
- GitHub is the only working surface
- **NEVER embed the Oxford crest as base64.** The crest is `images/oxford-crest.jpg`; do not delete it, move it, rename it, or replace the `<img class="sidebar-crest">` source with a data URI. (Not currently in this repo — applies if crest is added.)
- All mockups and visual designs are produced as Claude Artifacts — never committed to the repository (see CONSTITUTION.md Section 11)
- **Approval gate:** Never push any update to playbook.html without first showing the full content to Kevin and receiving his explicit approval. Show → Approve → Push. No exceptions.

## Branch and Merge Protocol
Always push directly to main. If a branch must be used, merge it to main immediately upon completion — never leave files on a branch.
