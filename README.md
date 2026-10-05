# Jinyan Shao

[Website](https://jinyanshao.ch) · [LinkedIn](https://www.linkedin.com/in/jinyanshao) · [Email](mailto:jinyanshao@proton.me)

I turn complex business rules into reliable software. Backend Developer in Fribourg, Switzerland: **Python/FastAPI in production**, current focus **C#/.NET business applications**.

My professional background is mainly in Python backend development, APIs, SQL, data processing, and workflow automation. My current engineering focus is C#/.NET, ASP.NET Core, EF Core, SQL Server, and related application technologies.

I am particularly interested in software where business rules, data integrity, and real-world processes matter: operational systems, administrative workflows, reliable APIs, and tools built around concrete user problems.

## Selected Projects

### [Swiss Event Permit Assistant](https://github.com/JinyanShao/swiss-event-permit-assistant)

A French-language web application for preparing temporary event permit dossiers in Fribourg, Switzerland.

Built with **C#/.NET and ASP.NET Core Razor Pages**, it turns publicly available administrative requirements into a guided questionnaire with required actions, documents, deadlines, confirmation points, and links back to official sources. The official source catalogue is itself a tested domain object, re-checked quarterly.

Externally tested by Bénévolat Fribourg Freiburg, whose feedback exposed a real questionnaire defect — fixed, with regression coverage.

**[Live demo](https://sepa-jinyan.azurewebsites.net)** (first load may take ~30 s: free-tier cold start)

**C# · .NET · ASP.NET Core · Razor Pages · xUnit · Azure**

### [Helvetic Operations Platform](https://github.com/JinyanShao/helvetic-operations-platform)

A multi-site work-order management application built around operational workflows and controlled state transitions.

The system includes domain-enforced lifecycle rules, Microsoft Entra ID authentication, role-based authorization, audit history, SQL Server persistence, optimistic concurrency with `rowversion`, generated API contracts, an Angular frontend, Docker-based environments, and automated testing across multiple layers.

**C# · .NET 8 · ASP.NET Core · EF Core · SQL Server · Angular · TypeScript · Docker**

### [Order Management API](https://github.com/JinyanShao/order-management-api)

A multi-tenant backend for order and inventory workflows.

It covers transactional inventory handling, PostgreSQL row locking in deterministic order, idempotent order creation scoped to user and organisation, optimistic concurrency control, tenant isolation, RBAC, audit logging, and concurrent integration testing.

**Python · FastAPI · PostgreSQL · SQLAlchemy · Docker · GitHub Actions**

### [Clinical Data Platform](https://github.com/JinyanShao/clinical-data-platform)

A FHIR-oriented backend for validated ingestion of synthetic clinical-research data.

Idempotent import jobs with per-record savepoints so one bad row does not fail an import, append-only provenance, asynchronous processing, and reads governed by API roles plus PostgreSQL row-level security.

**Python · FastAPI · PostgreSQL · Celery · Alembic · Docker**

## Built While Learning French

I moved to French-speaking Switzerland and needed the language, so I built my own tools for it. These are not client work; they are what a long-term commitment to living and working here looks like in code.

* [Plume Française](https://github.com/JinyanShao/Plume-Francaise) — a native macOS input method for French, written in Objective-C++ against the Input Method Kit: accent completion, French typographic spacing and apostrophes, 405 verbs conjugated across four tenses, pronoun-aware ranking, and agreement of past participles with a preceding direct object. Shipped as a signed `.pkg` with checksummed releases.
* [wordcloud](https://github.com/JinyanShao/wordcloud) — 9,067 French words as a navigable relation graph, rebuilt from pinned DBnary and Wiktionnaire snapshots. Source hashes are gated in CI, graph coordinates are deterministic across platforms, and relations taken from linguistic sources are kept explicitly separate from ones I authored myself. **[Live demo](https://jinyanshao.github.io/wordcloud/)**

## Other Work

* [EvidenceBid](https://github.com/JinyanShao/evidencebid) — source-aware workspace turning RFP documents into traceable compliance checklists and evidence-linked response drafts. Parses DOCX/XLSX with Docling; no LLM generates the prose.
* [Sales Data Pipeline](https://github.com/JinyanShao/sales-data-pipeline) — Python batch pipeline with explicit validation, rejected-record handling, reconciliation, reporting, and CI.
* [pencil-racer](https://github.com/JinyanShao/pencil-racer) — a 3D arcade racing prototype in Godot 4.6 with a notebook blue-pencil visual style. Built for fun.

## Current Focus

* C# and .NET
* ASP.NET Core
* EF Core and relational data modelling
* Backend and business application development
* Domain and workflow modelling
* Automated testing
* CI/CD and reproducible delivery

## Background

Before focusing on C#/.NET, I worked professionally with Python backend services, API integrations, SQL, data processing, and internal operational tools at Hangzhou Starlink Engine Network Technology (2021–2023): three production FastAPI modules covering live-streaming business data, host scheduling and third-party data synchronisation.

I also previously worked as an HR Business Partner. That experience gave me direct exposure to changing requirements, cross-functional processes, operational constraints, and the gap that often exists between a business rule on paper and its actual implementation in software.

HEIA-FR | HES-SO — Bachelor of Science HES-SO in Computer Science and Communication Systems (2026–present), taught in French

AWS Certified Developer – Associate (2025)

Lanqiao Cup (Blue Bridge Cup), Java — 1st prize in Shanghai, award of excellence in the national final (2019); the award carried an IBM-issued certificate

CS student at HEIA-FR (HES-SO) · Available Fridays and during academic breaks (summer 2027 internship)

Based in Fribourg, Switzerland · Swiss Permit B
