# Jinyan Shao

**Business application engineer building reliable systems with .NET, Angular and cloud-delivery foundations.**

Based in Fribourg, Switzerland, I build operational software around explicit business rules, transactional data, controlled access, automated testing and maintainable delivery workflows.

My commercial experience includes Python backend development, API integration, SQL data processing and workflow automation. My public engineering portfolio extends that foundation through verified projects using C#, .NET 8, ASP.NET Core, Angular, SQL Server, PostgreSQL, Docker, GitHub Actions and cloud-delivery foundations.

## Current focus

I am building [[Helvetic Operations Platform](https://github.com/JinyanShao/helvetic-operations-platform)](https://github.com/JinyanShao/helvetic-operations-platform), a multi-site Work Order management Web application for dispatchers and operations managers.

The application supports controlled creation, prioritisation, assignment, updating, status transitions and cancellation of operational work while preserving lifecycle rules, role-based access, audit history and concurrent-update safety.

The verified implementation includes:

* A guarded Work Order lifecycle with explicit transition rules
* Application-service and Work Order-specific repository boundaries
* .NET 8 and ASP.NET Core Minimal APIs
* EF Core 8 persistence with SQL Server and official migrations
* SQL Server `rowversion` optimistic concurrency
* Atomic audit-event persistence
* FluentValidation and standards-based Problem Details responses
* Server-side pagination, filtering and allowlisted sorting
* Microsoft Entra ID and MSAL integration code with role-based authorization
* A generated NSwag TypeScript client with deterministic drift checking
* Angular 22 list, detail, create, edit, transition, cancellation and conflict-recovery workflows
* Automated domain, application, persistence, API, authorization and Angular tests

The repository also contains Docker delivery assets, GitHub Actions validation and an Azure Bicep infrastructure baseline. Production Azure deployment, Key Vault, private endpoints, production observability and live authenticated Entra E2E execution remain explicitly documented roadmap work.

## Featured engineering work

### [[Helvetic Operations Platform](https://github.com/JinyanShao/helvetic-operations-platform)](https://github.com/JinyanShao/helvetic-operations-platform)

A multi-site Work Order management Web application that helps dispatchers and operations managers control operational work, identify SLA risk, preserve audit history and handle concurrent updates safely.

Current engineering evidence includes 30 passing backend tests: 8 API integration tests, 12 authorization tests, 3 SQL Server Testcontainers repository tests, 4 application-service tests and 3 domain tests. The Angular application has 19 passing tests, and both the backend Release build and Angular production build pass.

Eight Playwright E2E flows are implemented for list, filtering and pagination, detail, create, edit, transition, Manager cancellation and conflict recovery. Their current result is 0 passed, 0 failed and 8 explicitly skipped because the required Entra E2E base URL, role-specific storage-state files and deterministic fixture IDs are unavailable.

The project demonstrates a verified delivery path from domain rules and SQL Server persistence through protected APIs, generated client contracts and Angular user workflows.

### [[Order Management API](https://github.com/JinyanShao/order-management-api)](https://github.com/JinyanShao/order-management-api)

A backend for processing tenant-isolated orders while protecting inventory consistency under retries and concurrent requests.

It demonstrates multi-tenant isolation, role-based access control, transactional inventory, PostgreSQL row-level locking, idempotency, optimistic concurrency, state transitions, audit logging, request correlation and automated unit, integration and concurrency testing.

### [[Clinical Data Platform](https://github.com/JinyanShao/clinical-data-platform)](https://github.com/JinyanShao/clinical-data-platform)

A controlled ingestion and processing platform for study-scoped healthcare and research data.

It demonstrates Python backend engineering, CSV and FHIR-oriented validation, provenance, auditability, idempotent imports, controlled access, asynchronous processing, structured logging and health checks without claiming production medical compliance.

## Engineering priorities

* Translating operational workflows into explicit domain rules

* Protecting data integrity through validation, transactions and concurrency control

* Designing APIs with predictable authorization and failure contracts

* Testing behavior across domain, application, persistence and delivery boundaries

* Keeping verified implementation separate from future roadmap work

## Current status

* Based in Fribourg, Switzerland

* Swiss Permit B — authorised to work in Switzerland

* AWS Certified Developer – Associate, valid from September 2025 to September 2028

* Starting the BSc in Computer Science and Communication Systems at HEIA-FR in September 2026

* French: approximately B1

* Seeking a role as a Student Software Engineer, Junior Software Engineer, Application Developer, Junior .NET Developer or Application Support Engineer

* QA Automation remains an additional application direction

* Approximately 40% availability by default, with around 40%–60% potentially discussable once the final HEIA-FR timetable is confirmed

* Open to French-speaking and bilingual teams in Fribourg, Bern, Lausanne, Neuchâtel and Biel/Bienne where the commute is practical

[Personal website](https://jinyanshao.ch) · [LinkedIn](https://www.linkedin.com/in/jinyanshao) · [Email](mailto:jinyanshao@proton.me)
