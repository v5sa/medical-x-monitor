# medical-x-monitor

**V5 Medical Company** – Internal repository for monitoring, collecting, and managing the latest medical industry information from the X (Twitter) platform.

## Company Focus

V5 Medical specializes in:
- **Disposable syringes** (3-piece, 2-piece, safety syringes)
- **Surgical sutures** (absorbable/non-absorbable, surgical needles)
- **Medical packaging** (blister packs, sterilization pouches, thermoformed trays)
- **IVD reagents & consumables** (pipette tips, sample cups, transport media)

**Key Markets**: Turkey, Philippines, Middle East, Latin America, Southeast Asia
**Certifications**: ISO 13485, CE Mark, FDA 510(k) ready
**Manufacturing Base**: Jiangsu Province, China

## Purpose

This repository serves as the central hub for:
- Tracking real-time medical device industry signals on X
- Organizing intelligence by workstream (regulatory, competitors, clinical, supply chain, etc.)
- Archiving important posts, threads, and trends
- Coordinating team monitoring tasks via Issues and Projects

## Repository Structure

```
medical-x-monitor/
├── README.md
├── docs/
│   ├── monitoring-guidelines.md
│   ├── key-accounts.md
│   ├── search-operators.md
│   └── hashtags-keywords.md
├── workstreams/
│   ├── regulatory/          # FDA, CE, NMPA updates
│   ├── competitors/         # Competitor intelligence
│   ├── clinical-trials/     # Clinical evidence
│   ├── supply-chain/        # Logistics, raw materials
│   ├── ai-diagnostics/      # AI in medical devices
│   └── market-trends/       # Regional market insights
├── archives/                # Weekly/monthly digests
├── templates/
│   ├── issue-template-signal.md
│   └── weekly-digest.md
└── scripts/                 # Automation helpers
```

## Getting Started

1. Review the documents in `/docs`
2. Use GitHub Issues to log new signals (use the provided template)
3. Assign issues to the relevant workstream labels
4. (Optional) Create a GitHub Project board linked to this repo for kanban-style tracking

## Recommended Labels

| Label | Description | Color |
|-------|-------------|-------|
| `signal` | New X post / thread worth tracking | `#0E8A16` |
| `regulatory` | Regulatory / compliance | `#B60205` |
| `competitor` | Competitor activity | `#D93F0B` |
| `clinical` | Clinical trials / research | `#1D76DB` |
| `supply-chain` | Supply chain / manufacturing | `#FBCA04` |
| `ai-diagnostics` | AI / diagnostics / imaging | `#5319E7` |
| `high-priority` | Requires immediate attention | `#B60205` |
| `archive` | Ready for weekly digest | `#C5DEF5` |

## Contributing

- Always add the original X post URL when logging a signal
- Tag the relevant workstream
- Keep summaries concise and actionable
- Move processed signals to `/archives` periodically

---

*Managed by the Office of the CEO – V5 Medical Company*
