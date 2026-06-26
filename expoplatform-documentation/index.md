## Start Here
Reconstructed product documentation for the **ExpoPlatform** ecosystem — rebuilt from the **ExpoDoc** and **P2** Confluence spaces and the **EP** Jira project (delivered/active work only). Designed so a new PM, BA, QA Lead, Engineering Lead — or an AI agent — can understand and rebuild the platform. **20 products** have full 15-section specs; all 21 are covered at breadth.

> [!GOOD] Open the HTML files for the full interactive experience: live search, collapsible sections, sidebar navigation, dark/light mode and rendered Mermaid diagrams. Each `.html` has a matching `.md` (same content, portable).


## ⭐ Interactive Flows Explorer
- **[Open the Flows Explorer](Flows_Explorer.html)** — all **102 flow diagrams** in one interactive viewer. Pick a product and flow type, then **pan, zoom, go fullscreen, and download as SVG/PNG** — no Mermaid code, nothing to install. Renders offline.

## Cross-Product Analysis
- **[Product Ecosystem Map](00_Cross-Product_Ecosystem_Map.html)** — 21 modules across 7 domains, shared components, shared business rules, product-to-product integration matrix, external integrations and the master event-lifecycle journey.
- **[Coverage & Validation Report](05_Coverage_Report.html)** — what's covered vs scope, totals, excluded-by-status work, and honest caveats.

## Organizer & Admin
- **[Client Manager](products/01_Client_Manager.html)** — internal control plane that provisions every client environment.
- **[Admin / Platform Core](products/21_Admin_Platform_Core.html)** — organiser client: event & admin management, permissions, participant categories, global search.
- **[Organiser Analytics](products/02_Organiser_Analytics.html)** — dashboards and 25+ exportable reports.
- **[Onsite & Kiosks](products/03_Onsite_and_Kiosks.html)** — badges (print + digital), kiosk self-print, check-in & attendance.
- **[Transactions & Purchasing](products/04_Transactions_and_Purchasing.html)** — basket, ticketing, payments, invoicing, discounts.

## Visitor & Engagement
- **[Online Registration](products/06_Online_Registration.html)** — flows, form builder, conditional logic, participant categories.
- **[Event Website](products/07_Event_Website.html)** — website builder, blocks, content management, SEO.
- **[Networking & Interactions](products/08_Networking_and_Interactions.html)** — matchmaking, recommendations, speed networking, messaging.
- **[Meetings & Matchmaking](products/09_Meetings_and_Matchmaking.html)** — meeting formats, statuses, reminders, ratings.
- **[Sessions & Speakers](products/10_Sessions_and_Speakers.html)** — programme, agenda, schedules, online/on-demand sessions.
- **[Community](products/11_Community.html)** — year-round networking, groups, collaboration.
- **[User Engagement](products/12_User_Engagement.html)** — email campaigns, push and platform notifications.
- **[Mobile App](products/13_Mobile_App.html)** — onsite app: networking, schedule, digital badge, lead scan.

## Exhibitor & Sponsor
- **[Exhibitor Portal](products/14_Exhibitor_Portal.html)** — the Exhibitor Manual: info collection, equipment shop, team, lead capture.
- **[Exhibitor Marketplace](products/15_Exhibitor_Marketplace.html)** — public directory of exhibitors, products, brands & news.
- **[Lead Intelligence](products/16_Lead_Intelligence.html)** — lead capture config, question builders, dashboard, scanning, export.
- **[Floor Plan](products/17_Floor_Plan.html)** — halls, stands, DXF import, vendor integrations, wayfinding.
- **[Sponsorship](products/18_Sponsorship.html)** — packages and placements across the platform.
- **[Hosted Buyer Management](products/19_Hosted_Buyer_Management.html)** — agents, categories, benefits, document dashboard, filters.

## Platform & Integrations
- **[Integrations (Open API & Native)](products/20_Integrations.html)** — API, webhooks and the external-connector catalogue.

## How It Was Built
Two-phase method: **Phase 1** discovered the whole ecosystem (1,262 Confluence pages enumerated; 1,149 Jira Story/Epic issues triaged to 653 in-scope; 521 stories mapped 100% to products). **Phase 2** produced full per-product specifications for 20 products across all four clusters. Only delivered/active Jira statuses were included; Tasks, Bugs and Sub-tasks were excluded by type. *Profile* is documented as a shared identity layer within Registration, Networking and the ecosystem map.

## Supporting Datasets
Consolidated data backing this reconstruction lives in `_data/`: `jira/issues_full.jsonl`, `jira/epics.json`, `jira/status_distribution.json`, `confluence/pages_expodoc.json`, `confluence/pages_p2.json`, `mapping/story_product_map.csv`, `mapping/product_inventory.json`, and per-product `confluence_pack.md` source packs under `_data/products/`.
