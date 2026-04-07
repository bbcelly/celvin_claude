# Investor Report January 2026 - Product & Technology

*Due: 2026-02-09 | Completed: 2026-02-12*

## What did we release

- Redis-based rate limiter rollout across all projects
- Mobile App version 1.3.1 (EAN scanning, variant price improvements, reliability updates, Order completion)
- Seznam Order Overview integration (structured order data in emails)
- VAT improvements in API (purchase price VAT independence, item VAT breakdown)
- Option to disable pickup boxes per product (currently in pilot phase)

## Highlights

- Succesfull hiring PM for expansion (Jaroslav Soucek)
- Multishop Alpha confidence increased from 70% to 90%; pricing model defined (flat fee per domain)
- Allegro moved from development phase to pilot execution phase (core flows completed, Sandbox -> Production switch underway)
- Significant improvement in Marketplaces throughput (high delivery velocity, reduced cycle time)
- Platform modernization progress: sales channel architecture refactor, Redis rate limiter fully deployed
- Campaigns shifted toward automation strategy with optimization engine launch
- Cash Register roadmap strategically adjusted to maximize adoption impact (launch moved to May 2026)
- Automatic Campaign Optimization (self-optimizing campaigns based on performance data)
- Allegro Merchant Settings (production release, pilot-ready core flows)
- Multishop domain routing & sales channel assignment to orders

## Fuckups / Main risks

- Elevated category request latency (>1000ms) under investigation
- Multishop PM hiring failed; recruitment restarted
- Increased bug ratio in some teams due to architectural changes and cross-team integrations
- High cross-team dependency risk (Cash Register <-> Pay <-> Catalog <-> API)
- Pay transaction data & statement corrections still generating recurring fixes
- A lot of unclear stuff around Expansion project

## What do we need

- Successful Multishop Alpha onboarding and feedback loop
- Smooth Allegro pilot execution with validated E2E flows
- Stabilization of category performance and monitoring improvements
- Hiring and onboarding of Multishop PM
- Continued reduction of integration-related bug spikes

## Priorities next period

- Launch Allegro pilot (first merchants onboarded)
- Multishop Alpha go-live with selected clients
- Cash Register E2E testing start
- Product Webhooks partner pilot (March preparation)
- PayPal statements delivery
- Baliky Public API planning & box restriction full release
- Meta Ads integration completion
