# Investor Report Writer

Draft the monthly "Product & Technology" section of the Shoptet investor report.

## Trigger

User says: "write investor report", "prepare investor report", "draft investor report for [month]"

## Data Sources

Gather data from all available sources before writing. Not all sources may be connected -- use what's available and flag what's missing.

### 1. Asana (MCP: asana)
- Search for the current month's investor report subtasks in workspace `413336835149603`
- Look for tasks named "Investor report [Month] [Year] Product & Technology"
- Also check subtasks of the parent "Investor report [Month] [Year]" task
- Pull notes from related team tasks (other departments may have relevant cross-team info)

### 2. Slack (MCP: if available)
- Search relevant channels for release announcements, incidents, wins, and risks
- Key channels to check: engineering announcements, product updates, incident channels
- Time range: the reporting month

### 3. Slab (MCP: if available)
- Search for release notes, post-mortems, and team updates published during the month
- Look for any monthly/weekly summaries from team leads

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
