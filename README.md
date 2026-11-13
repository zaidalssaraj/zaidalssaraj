<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Zaid Alssaraj. Compsci senior, ML + AI minor, building Bravix Media." src="assets/banner-light.svg" width="100%">
</picture>

Compsci senior with a minor in machine learning and AI. By day I'm a Digital Banking Specialist at Gate City Bank, where I troubleshoot the online and mobile banking apps for 200,000+ users and chase down iOS and Android bugs with our vendors. The rest of the time I run [Bravix Media](https://bravixmedia.com), building the ad and lead systems for home service contractors, and I build most of its tooling myself.

### Building now

- **F1 race strategy simulator.** Replays a real Formula 1 race with a different pit stop and predicts where the driver would have finished. Live telemetry from OpenF1 and Jolpica, a bronze/silver/gold lakehouse on Azure Databricks, and a lap-time model trained on 2023-2025 races. *(class project, public once it's graded)*
- **Bravix Hub.** Private ops dashboard that aggregates the HighLevel REST API (SMS export, opportunities, calendars), the Meta Graph API, Stripe, and Fathom into one server-rendered view. Scores each sending number's deliverability from carrier error codes (spam filtering, A2P blocks), computes MRR and monthly cash from Stripe charges and subscriptions, and runs a rules engine that flags problems and pushes them to Slack from an hourly GitHub Actions job, deduped in Upstash Redis. A polling endpoint drives real-time events in the UI. Read-only scoped keys stay server-side, behind JWT sessions with a Redis-backed login lockout. Next.js, TypeScript, Vercel, Upstash Redis, GitHub Actions.
- **ledger.** My own bookkeeping app: bank CSV import, auto-sort rules, budgets, and a tax set-aside estimate. Next.js + Postgres.

### Shipped

- [bravixmedia.com](https://bravixmedia.com): the agency site
- [Revenue Leak Report](https://leak.bravixmedia.com): a free calculator that shows contractors how much money missed calls and slow replies cost them each year
- Client onboarding portal: intake survey, file uploads into an auto-built Google Drive folder, and email updates
- [spa-management-system](https://github.com/zaidalssaraj/spa-management-system): spa booking and management web app with 6 user roles, C# / Blazor / Entity Framework Core *(team project)*
- [store-database-manager](https://github.com/zaidalssaraj/store-database-manager): Java + PostgreSQL store manager with orders, price history, and sales reports *(team project)*
- [tcp-multithreaded-chat-server](https://github.com/zaidalssaraj/tcp-multithreaded-chat-server): multithreaded TCP chat server in Java
- [udp-multithreaded-chat-server](https://github.com/zaidalssaraj/udp-multithreaded-chat-server): UDP chat server in Java, one thread per datagram with a synchronized message counter

### Tools I use

`Python` `Java` `C#` `TypeScript` `SQL` `PostgreSQL` `React` `Next.js` `.NET` `Astro` `Spark` `Databricks` `Azure` `Cloudflare` `Vercel` `Linux`

### Find me

[LinkedIn](https://www.linkedin.com/in/zaidalssaraj/) · [bravixmedia.com](https://bravixmedia.com)
