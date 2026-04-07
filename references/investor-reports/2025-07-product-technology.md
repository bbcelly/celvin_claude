# Investor Report July 2025 - Product & Technology

*Due: 2025-08-06 | Completed: 2025-08-06*

## Department updates

- Opened internal hiring on superdomain leads
- Launched AI assistant for PMs
- Catalog 2 open hiring positions
- Opening new position for Marketplaces
- Started to adding AI coding tools to DEV env
- Looking for the way to optimize, how we work with multiple feedback streams in product team

## Mobile App

- Version 1.0.0 ready in stores, launched on 05.08.
- Release cadence set to one update / month with two-week QA window.

## API Team

- Webhook siloisation phase 2 live; phase 3 clean-up Q3.
- Rate-limit feedback loop delivering new endpoints (order/product snapshots, etc.).
- Owner-email change now self-service for trial projects, reducing support load.

## Cash Register

- InStoreSalesChannels endpoints and initial purchase flow endpoints implemented.
- New cash desk tables assigned to existing Shoptet carts.
- Initial design for purchase operations and cash management completed.
- FE code reuse between web and mobile explored; several bugs fixed.

## Multishop

- Language & currency management fully delivered; editing of markets, languages and currencies complete.
- Domain-routing epic now top priority; discovery nearly finished.
- Sales-channel refactor closed; Q3 topics under analysis.
- Pilot scope: limited feature set, selected merchants, Q3-Q4 2025.
- MVP full launch: Q2 2026 (confidence ~ 25 %).

## Risk Profile

- Automation of the "On-hold" merchant process is in testing; several issues are being fixed.
- All database views for the Data team are ready, currently verifying output consistency.
- Bug fixes implemented in whitelisting UI and alerts generation.
- Event log introduced to support audits and investigations.
- Alerts for insolvency credit-check codes now integrated into Slack (dry-run mode).

## Shoptet Pay (Internal + Sales Channels)

- First task for proforma invoice debiting flow released; other tasks in review.
- Refund permission management released, and refund with password feature is now available.
- Payment methods refactoring is in progress; iDeal and CB prepared for testing.
- Company ID change flow initial version released, with further improvements planned.
- Shoptet Pay repositories fully migrated to GitHub; Jira migration next.
- Bank connection now available in all European countries.
- Initial PayPal integration analysis completed; Shoptet Boost integration progressing.

## SOFA (Storefront API & 3G WYSIWYG)

- SOFA 4G theme - merchant research done; design/UI in WYSIWYG under way; multitenant architecture under discussion.
- GraphQL schema for products and variants nearly finished; feedback gathered for Catalog team.
- Multi-tenant research in Next.js ongoing; caching & optimization PoCs completed.
- Add-on integration approaches explored using isolated-vm.
- SOFA workspaces integrated with cms4; upgraded to Next 15 and React 19.
- 3G WYSIWYG rich-text tweaks and multishop editor exploration continue.

## Logistics

- Widget pilot live - pickup-point widget launched to first e-shops; phase 2 (carrier logos, filters, geolocation) in development for September.
- Cheapest-to-address option released (admin only) to simplify checkout.
- GLS irregular collection can now be ordered directly from admin.
- Contracting - Slovenska posta Komplet in final legal review; DPD awaiting commercial sign-off.
- SK Baliky pilot ready (Packeta tested); full pilot end-Sept.
- Discovery started on redesigned shipping-method page to unlock Baliky set-up during trial.

## Templates & Logistics

- Accessibility improvements in 3G and Classic templates (Add to Cart, Cookie Bar, links).
- Logistics Widget MVP completed with initial bug fixes.
- Cheapest address delivery feature released.
- Map widget MVP done; preparations for phase 2 underway.
- Pilot testing for new Balikovna service "Ceny Obsah."
- PickupPoint storage cleanup and performance improvements; shipment creation under 4s.

## Admin & Design System

- ESLint 9 upgrade and React 19 migration completed.
- StocksListing and Actions Log pages migrated to React.
- Fixed infinite re-render in FileField, MultiSelectField issues, and breakpoint logic.
- Developer Portal updated to utilize the new Design System.

## Marketplaces & Warehouses

- Allegro contract signed; Marketplace activation pages and sales channel integration in progress.
- After-sales policies refined; delivery settings and offer management under analysis.
- Warehouse visibility feature released; new warehouse types and event store tracking ready for release.
- Large migrations prepared in collaboration with SRE/ops; several bugs fixed.

## Catalog & Imports

- New image-processing pipeline rolled to 100 % of core stores; Premium rollout next.
- Batch-save tracking: 8/35 tables complete (22 %).
- Product image handling bugs resolved; single-product import with multi-pricelists tested OK.
- Wait-time issue on code reviews flagged and under action.

## Green Team

- PM on a leave
- Released features: Express Checkout consent, XML feed security improvements, Hubspot email logging, favicon management, 2FA improvements, and microdata updates.
- Preparing to release: simplified favicon management and social media addon metrics.
- 6 exceptions and 16 bugs fixed; additional GA4 and CMS password reset fixes deployed.

## Shoptet Campaigns

- New analytics - interactive charts now support date filters and data comparison.
- On-boarding flow simplification drafted; UX redesign of admin underway (statistics, settings).
- Google-limit fix for SK roll-out deployed; webinar with Dotidot held.
- Metrics: 784 paying projects (+0.3 %), spend -11.8 % MoM; ROAS trending up.
