# Hi, I'm Bilal Qureshi 👋

Software engineer from Pakistan with a BSCS, focusing on **Artificial Intelligence and Data Science**.
I build complete products end to end, from multitenant databases to LLM agents, and I am pursuing a
master's degree to go deeper into applied AI research.

**Interests:** LLM agents · retrieval augmented generation (RAG) · evaluation of AI systems · data driven software

## 💼 Experience

* **Lead Software Developer** · Remote  
  Leading the design and development of software products for an international organization.
* **Mobile App Developer** · Cabree  
  Building the mobile apps for Cabree, a SaaS taxi dispatch platform. *(Flutter, Dart)*
* **Freelance Software Engineer**  
  Designed and delivered custom management, accounting and attendance systems for clients in education, healthcare and hospitality.

## 🚀 Featured projects

### 🤖 teammate.
**AI agents for small businesses.** Ready made AI teammates that answer customers on WhatsApp using the business's own data,
book appointments, take orders, send reminders and hand over to a human when needed. Built on one multitenant agent engine,
with each industry (clinics, salons and gyms, online shops) as a set of agent templates on top. Preparing for pilot launch.

* **Agent engine:** conversation state, intent and language detection, routing, tool calling, guardrails, confidence scoring and human takeover
* **RAG knowledge base:** document chunking, embeddings in pgvector and hybrid search over each business's FAQs, documents and website
* **LLM gateway:** DeepSeek and Gemini with model tiers, automatic fallback, cost tracking and Langfuse tracing
* **Vision:** customers send a product photo, which is described by a vision model and matched against the shop's catalog
* **Evaluation:** test sets for every agent with a critical failure gate (clinic receptionist 78/78, booking assistant 44/44, sales assistant 26/26)
* **Security:** PostgreSQL row level security for tenant isolation, covered by cross tenant tests

`TypeScript` `NestJS` `Next.js` `PostgreSQL` `pgvector` `Redis` `BullMQ` `Docker`

### 📊 Fynledger
**Cloud ERP for Pakistani businesses.** A multitenant SaaS for sales, purchases, double entry accounting, inventory,
point of sale, manufacturing and payroll, with FBR tax invoice reporting and 50+ reports.

* Every financial document posts a balanced journal entry, with approval workflows and 13 user roles
* Point of sale that keeps working offline and syncs when the connection returns
* Inventory with weighted average costing and batch and expiry tracking
* Subscription plans, free trials and billing built in

`React` `Laravel` `MySQL` `Docker`

### 📝 [GhostNote](https://github.com/bilalqureshiii/GhostNote) · open source
A note widget that stays on top, docks to the edge of the screen and launches from the terminal. Published on npm,
with crash safe saving and automatic backup recovery.

`Electron` `Next.js` `Node.js`

## 🛠️ Tech

**Languages:** Python · TypeScript · JavaScript · Dart · PHP · C# · SQL  
**AI:** LLM agents · tool calling · RAG · embeddings · pgvector · evaluation · Langfuse  
**Frameworks:** NestJS · Next.js · React · Laravel · Flutter · Electron · ASP.NET Core  
**Data and infra:** PostgreSQL · MySQL · SQL Server · Redis · Docker · GitHub Actions
