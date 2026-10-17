## Jinyan Shao

Back-end developer (C#/.NET and Python) and Computer Science student at HEIA-FR (HES-SO),
Fribourg.

From 2021 to 2023 I built and maintained three FastAPI modules in production at Hangzhou
Starlink Engine Network Technology, a live-streaming and e-commerce company — 1 year and
5 months, during which a daily job that runs seven days a week went from about 40 minutes
to 2. I now study in French and build public projects around one question: what must still
be true when two requests collide, a row is bad, or a user should not see a record?

Available Fridays during the semester and full time during academic breaks, including
summer 2027. Swiss Permit B.
[jinyanshao.ch](https://jinyanshao.ch/) · [LinkedIn](https://www.linkedin.com/in/jinyanshao) · [jinyanshao@proton.me](mailto:jinyanshao@proton.me)

### Start here

- [Helvetic Operations Platform](https://github.com/JinyanShao/helvetic-operations-platform)
  (.NET 8, EF Core, SQL Server, Angular). A multi-site work-order application with Entra ID,
  role-based authorisation, audit history and `rowversion` concurrency.
- [Order Management API](https://github.com/JinyanShao/order-management-api)
  (FastAPI, PostgreSQL). Inventory changes lock order and product rows in a fixed order;
  order creation is idempotent per user and organisation. A PostgreSQL test makes two
  confirmations compete for stock that covers one: exactly one succeeds. CI requires 90%
  coverage.
- [Clinical Data Platform](https://github.com/JinyanShao/clinical-data-platform)
  (FastAPI, Celery, PostgreSQL). Imports are idempotent and use per-record savepoints, so
  one bad row does not fail the job. Source rows are kept as append-only provenance, and
  row-level security backs the API roles. Synthetic data; not a FHIR server.
- [Swiss Event Permit Assistant](https://github.com/JinyanShao/swiss-event-permit-assistant)
  (ASP.NET Core Razor Pages). An independent, non-official tool that turns Fribourg's
  event-permit requirements into a guided checklist with links to the official sources. The
  source catalogue is itself a tested domain object, re-checked quarterly. Tested by
  Bénévolat Fribourg Freiburg; their feedback exposed a questionnaire defect, now fixed with
  regression coverage. [Live demo](https://sepa-jinyan.azurewebsites.net/) (first load may
  take ~30 s).

### Built while learning French

I moved to French-speaking Switzerland and needed the language, so I built my own tools for it.

- [Plume Française](https://github.com/JinyanShao/Plume-Francaise): a native macOS input
  method for French in Objective-C++ (Input Method Kit): accent completion, French
  typographic spacing and apostrophes, 405 verbs conjugated across four tenses, and
  agreement of past participles with a preceding direct object. Shipped as a signed `.pkg`
  with checksummed releases.
- [wordcloud](https://github.com/JinyanShao/wordcloud): 9,067 French words as a navigable
  relation graph, rebuilt from pinned DBnary and Wiktionnaire snapshots. Source hashes are
  gated in CI, and relations from linguistic sources are kept separate from ones I authored.
  [Live demo](https://jinyanshao.github.io/wordcloud/)

### Tools I built for my own work

- [automation-toolkit](https://github.com/JinyanShao/automation-toolkit): tested Python CLI
  utilities for safe file processing — dry-run first, never overwrite, conflicts resolved by
  rule. CI on every push.

### Also

[Sales Data Pipeline](https://github.com/JinyanShao/sales-data-pipeline) (validated batch
ingestion with rejected-record handling and CI) ·
[EvidenceBid](https://github.com/JinyanShao/evidencebid) (RFP documents to traceable
compliance checklists; no LLM writes the prose) ·
[pencil-racer](https://github.com/JinyanShao/pencil-racer) (a Godot prototype, for fun) ·
[jinyanshao-site](https://github.com/JinyanShao/jinyanshao-site) (this site)

### Background

Python back end at Hangzhou Starlink Engine Network Technology (2021–2023), then HR Business
Partner for data and digital teams at Junyi (Hong Kong) Digital Technology. AWS Certified
Developer – Associate (2025).
