# CPG Platform (working name: AI Brand Operator)

A CPG operating company as a service. An ERP configured to run a complete CPG
company, operated by AI agents that draw on a knowledge graph of end-to-end CPG
processes. Brands plug in and out. One geography is one legal entity. Stock is
held on consignment: the brand owns it, we warehouse it and bill for the service.

Founders: Aurelien Villemonteix (commercial, go-to-market), VJ (operations,
brand P&L, first pilot account), Julien Villemonteix (product, technology).

## Map

| Folder | What lives here | Proposed owner |
|---|---|---|
| `00-admin/` | Founders' agreements, equity, IP, employer permissions, meetings, decisions | All |
| `01-strategy/` | Whitepaper versions, market and competitor view, business model | Aurelien |
| `02-discovery/` | The 12-week workplan: brand shortlist, interviews, category analysis, pilots | Aurelien, VJ |
| `03-harness/` | The platform by layer: ERP, knowledge graph, agents, channels, warehousing, entities | Julien |
| `04-brands/` | Onboarding template and one folder per plugged-in brand | VJ |
| `05-finance/` | Platform P&L, unit economics, margin profiles, fundraising | VJ |
| `06-legal-compliance/` | GPSR, EU responsible person, VAT, consignment and pilot contracts | Aurelien, VJ |
| `src/` | Prototype code once the build-vs-orchestrate question is answered | Julien |

## Conventions

- Folder names are numbered and hyphenated so they sort in reading order and
  work in git, terminals and code.
- Every folder has a README saying what belongs in it. Git does not keep empty
  folders, so the README is what makes the structure travel.
- Decisions go in `00-admin/decisions/`, one dated file each, using the template.
- Word documents for anything shared outside the founders. Markdown for working
  notes, so they diff cleanly in git.
- Dates in file names are `YYYY-MM-DD`.
