# Hi, I'm Bilal Qureshi 👋

BSCS graduate and software engineer from Pakistan, now focusing on **Artificial Intelligence and Data Science**.
I design and ship complete products end to end — from multi-tenant databases to LLM agents — and I'm pursuing a
master's degree to go deeper into the research side of applied AI.

**Interests:** LLM agents · retrieval-augmented generation (RAG) · evaluation of AI systems · data-driven business software

---

## 🤖 teammate. — AI agents for small businesses &nbsp;·&nbsp; *my product, pre-pilot*

> *"Hire a teammate for your clinic."* Ready-made AI agents that answer customers on WhatsApp from the business's own data,
> book appointments, take orders, send reminders and hand off to a human when needed.

One **multi-tenant agent engine**, with each business niche built as a set of agent templates on top of it.
Clinics, salons / spas / gyms and online shops are built; launching in Pakistan.

- **Agent engine** — conversation state, intent & language detection, routing, a tool-calling loop, guardrails,
  confidence scoring and human-takeover mode. Agents can only claim an action (e.g. "your order is placed") if the tool actually did it.
- **RAG knowledge base** — document chunking, embeddings in **pgvector** and **hybrid search** over each business's FAQs, text and website.
- **LLM gateway** — DeepSeek + Gemini with model tiers, automatic fallback, per-call cost tracking and Langfuse tracing.
- **Multimodal** — customers send a product photo; it is described by a vision model and matched against the shop's catalog.
- **Evaluation-driven development** — evaluation sets for every agent with a critical-failure gate
  (e.g. clinic receptionist 78/78, salon booking assistant 44/44, sales assistant 26/26).
- **Tools & scheduling** — zod-validated, tenant-scoped tools for bookings, orders and contacts; time-zone-aware availability;
  scheduled reminders, follow-ups and renewals.
- **Security** — PostgreSQL row-level security for tenant isolation, with cross-tenant tests.
- **Product** — owner dashboard with live inbox and takeover, 7-step onboarding, and a live demo built from a business's website URL.

`TypeScript` `NestJS` `Next.js` `PostgreSQL + pgvector` `Redis / BullMQ` `Turborepo` `Docker` `GitHub Actions CI`

---

## 📊 Fynledger — cloud ERP for Pakistani businesses &nbsp;·&nbsp; *my product*

A multi-tenant SaaS covering **sales, purchases, double-entry accounting, inventory, point of sale, manufacturing and payroll**,
with **FBR (tax authority) invoice reporting** and 50+ reports.

- Every financial document posts a balanced journal entry; errors are reversed, never deleted — with an approval queue and 13 roles.
- **Offline-capable POS** (service worker + local queue) with schemes, loyalty and barcode labels.
- Inventory with weighted-average costing and batch/expiry tracking (earliest-expiry-first).
- Gap-free document numbering per tenant under row locks; subscription plans, trials and billing built in.

`React 19` `Vite` `Laravel 12` `MySQL` `Docker`

---

## 📝 [GhostNote](https://github.com/bilalqureshiii/GhostNote) &nbsp;·&nbsp; *open source, on npm*

An always-on-top, edge-docked note widget launched from the terminal (`npm i -g ghostnote`). Crash-safe atomic
persistence with automatic backup recovery, and a sandboxed renderer. `Electron` `Next.js` `Node.js`

---

## 💼 Professional work

- **Mobile App Developer — Cabree** · Building the mobile apps of Cabree, a SaaS taxi-dispatch platform covering bookings,
  dispatch, drivers and passengers. *(Flutter / Dart)*
- **Freelance systems for clients**
  - **School management system** for a school
  - **Accounting software for an Airbnb business** — bookings, apartments, expenses, income and revenue
  - **Clinic management system and website** for a medical clinic
  - **Smart Attendance System** — university attendance with student, teacher and admin roles *(Flutter, ASP.NET Core, SQL Server)*

*Most of my work is commercial or client code and stays private — walkthroughs and details are available on request.*

## 🛠️ Tech
**Languages:** Python · TypeScript · JavaScript · Dart · PHP · C# · SQL  
**AI:** LLM agents & tool calling · RAG · embeddings / pgvector · evaluation sets · Langfuse  
**Frameworks:** NestJS · Next.js · React · Laravel · Flutter · Electron · ASP.NET Core  
**Data & infra:** PostgreSQL · MySQL · SQL Server · Redis · Docker · GitHub Actions
