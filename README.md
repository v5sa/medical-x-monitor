# medical-x-monitor

**V5 Medical Company** – Internal repository for monitoring, collecting, and managing the latest medical industry information from the X (Twitter) platform.

## Purpose

This repository serves as the central hub for:
- Tracking real-time medical industry signals on X
- Organizing intelligence by workstream (regulatory, competitors, clinical, supply chain, AI/diagnostics, etc.)
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
│   ├── regulatory/
│   ├── competitors/
│   ├── clinical-trials/
│   ├── supply-chain/
│   ├── ai-diagnostics/
│   └── market-trends/
├── archives/
├── templates/
│   ├── issue-template-signal.md
│   └── weekly-digest.md
└── scripts/
```

## Getting Started

1. Review the documents in `/docs`
2. Use GitHub Issues to log new signals (use the provided template)
3. Assign issues to the relevant workstream labels
4. (Optional) Create a GitHub Project board linked to this repo for kanban-style tracking

## Recommended Labels

| Label            | Description                        | Color suggestion |
|------------------|------------------------------------|------------------|
| `signal`         | New X post / thread worth tracking | `#0E8A16`        |
| `regulatory`     | Regulatory / compliance            | `#B60205`        |
| `competitor`     | Competitor activity                | `#D93F0B`        |
| `clinical`       | Clinical trials / research         | `#1D76DB`        |
| `supply-chain`   | Supply chain / manufacturing       | `#FBCA04`        |
| `ai-diagnostics` | AI / diagnostics / imaging         | `#5319E7`        |
| `high-priority`  | Requires immediate attention       | `#B60205`        |
| `archive`        | Ready for weekly digest            | `#C5DEF5`        |

## Contributing

- Always add the original X post URL when logging a signal
- Tag the relevant workstream
- Keep summaries concise and actionable
- Move processed signals to `/archives` periodically

---

*Managed by the Office of the CEO – V5 Medical Company*
