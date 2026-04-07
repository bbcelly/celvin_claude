# Investor Report Writer

Draft the monthly "Product & Technology" section of the Shoptet investor report.

## Trigger

User says: "write investor report", "prepare investor report", "draft investor report for [month]"

## Data Sources

Gather data from all available sources before writing. Not all sources may be connected -- use what's available and flag what's missing.

### 1. Asana (MCP: asana)

**Primary source -- biweekly status reports:**
- Parent task GID: `1212742790406013` (in project `1212662190575399`, workspace `413336835149603`)
- Get subtasks of this task -- they are biweekly "CZ & SK status product" reports
- For a given report month, pull subtasks whose `due_on` falls within the month +/- 10 days
  - Example: for March 2026 report, pull subtasks with due_on between 2026-02-19 and 2026-04-10
- Read the full notes of each matching subtask -- this is the main raw data

**Secondary source -- investor report tasks:**
- Search for tasks named "Investor report [Month] [Year] Product & Technology"
- Pull notes from related team tasks (other departments may have relevant cross-team info)

### 2. Slack (MCP: if available)
- Channels to pull from:
  - `cz3-product-news-en` -- product releases and feature announcements
  - `cz3-it-updates` -- engineering and IT updates
  - `cz3-infrastructure` -- infrastructure changes and incidents
  - `cz3-infra-updates` -- infrastructure status updates
  - `cz3-incident-en` -- incidents and outages
- Time range: the reporting month
- Look for: releases, incidents, outages, metrics, wins, and risks

### 3. Slab
- Primary source: Product Management Status Updates post
  - Q1 2026: https://shoptet.slab.com/posts/product-management-status-updates-2026-q-1-3czv3g1g
  - For other quarters, ask Pavel for the URL
- If Slab MCP is available, fetch the post content directly
- If not, ask Pavel to paste the relevant section from the Slab post

## Report Structure

Use this structure (matches the format used since January 2026):

```
## What did we release
- [Shipped features and launches, bullet points]

## Highlights
- [Positive outcomes, metrics, wins]

## Fuckups / Main risks
- [Incidents, delays, risks, honest assessment]

## What do we need
- [Blockers, decisions needed, resources needed]

## Priorities next period
- [Key focus areas for next month]
```

## Writing Style

- Concise bullet points, not paragraphs
- Specific metrics where available (%, MoM, counts)
- Honest tone -- don't sugarcoat risks or fuckups
- No corporate jargon
- No emojis
- Reference concrete projects/products by name (Multishop, Allegro, Baliky, Shoptet Pay, etc.)
- Keep each bullet to 1-2 lines max

## Reference Examples

Read 2-3 recent reports from `references/investor-reports/` before drafting to match tone and depth:
- `references/investor-reports/2026-02-product-technology.md` (latest completed, current format)
- `references/investor-reports/2026-01-product-technology.md`
- `references/investor-reports/2025-10-product-technology.md`

## Output

1. Save draft to `references/investor-reports/[YYYY]-[MM]-product-technology.md`
2. If the Asana task for this month exists, offer to update its notes with the draft
3. Flag any sections where data was thin or missing so Pavel can fill in

## Checklist Before Submitting Draft

- [ ] All 5 sections present
- [ ] At least 5 bullets in "What did we release"
- [ ] At least 3 bullets in "Fuckups / Main risks" (there are always risks)
- [ ] Metrics included where available
- [ ] Compared against previous month's report for continuity (carry-over items, progress on ongoing initiatives)
- [ ] Flagged gaps where input is needed from Pavel
