# X Monitoring Guidelines – V5 Medical

## Goals
Capture timely, high-value information from X that can inform:
- Regulatory strategy
- Competitive intelligence
- Clinical / R&D decisions
- Supply-chain risk management
- AI & diagnostics opportunities
- Regional market entry / expansion (Turkey, Philippines, Middle East, LATAM, SEA)

## Daily / Weekly Cadence

| Frequency | Action |
|-----------|--------|
| Daily     | Scan priority accounts + saved searches |
| Daily     | Log high-priority signals as GitHub Issues |
| Weekly    | Produce a short digest and place it in `/archives` |
| Monthly   | Review key accounts list and update keywords |

## What to Capture

- Official announcements from regulators (FDA, EMA, NMPA, etc.)
- Competitor product launches, partnerships, funding, or regulatory wins
- Clinical trial results or major protocol changes
- Supply-chain disruptions or quality issues (especially China manufacturing)
- New AI medical device clearances or publications
- Industry reports, conference highlights (MEDICA, Arab Health, CMEF), or KOL insights
- Regional tender, import, or regulatory changes in key markets

## What Not to Capture

- Pure marketing fluff without substance
- Unverified rumors (unless flagged as such)
- Personal non-industry content

## Logging a Signal

1. Open a new Issue using the “Signal” template
2. Paste the X post URL
3. Write a 1–3 sentence summary + why it matters to V5
4. Apply the appropriate labels (`signal`, `regulatory`, `competitor`, `clinical`, `supply-chain`, `ai-diagnostics`, `high-priority`, etc.)
5. Assign to the relevant team member if action is needed

## Labels (already configured)
- `signal` – New X post / thread worth tracking
- `regulatory` – Regulatory / compliance
- `competitor` – Competitor activity
- `clinical` – Clinical trials / research
- `supply-chain` – Supply chain / manufacturing
- `ai-diagnostics` – AI / diagnostics / imaging
- `high-priority` – Requires immediate attention
- `archive` – Ready for weekly digest

## Weekly Digest Process
1. Collect all open Issues labeled `archive` or closed signals from the week
2. Summarize the most important items by workstream
3. Create a new file in `/archives` named `YYYY-WXX-digest.md`
4. Close or move processed Issues as appropriate
