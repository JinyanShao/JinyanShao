# Jinyan Shao

**Business application engineer building reliable systems with .NET, Angular and cloud-delivery foundations.**

Based in Fribourg, Switzerland, I design operational software around explicit domain rules, transactional data, access control, testing and maintainable delivery pipelines.

My commercial background includes Python-based backend development, API integration, SQL data processing and workflow automation. My public engineering portfolio extends that foundation through evidence-based projects using C#, .NET 8, ASP.NET Core, Angular, FastAPI, PostgreSQL, SQL Server, Docker, GitHub Actions and cloud-delivery foundations.

## Current focus

I am building [[Helvetic Operations Platform](https://github.com/JinyanShao/helvetic-operations-platform)](https://github.com/JinyanShao/helvetic-operations-platform), an enterprise Web application for coordinating work orders across multiple operational sites.

The application gives dispatchers and operations managers a controlled workflow for creating, updating, prioritising, transitioning and cancelling work orders while preserving domain rules, access controls, audit history and concurrent-update safety.

Its verified implementation currently demonstrates:

* C# domain modelling with a guarded Work Order lifecycle
* .NET 8 and ASP.NET Core Minimal APIs
* Application-service and Work Order-specific repository boundaries
* EF Core 8 persistence with SQL Server and official migrations
* SQL Server `rowversion` optimistic concurrency
* Atomic audit-event persistence
* FluentValidation and standards-based Problem Details responses
* Server-side pagination, filtering and allowlisted sorting
* Microsoft Entra ID / MSAL authorization code integration with role-based access
* A generated NSwag TypeScript client with deterministic drift checking
* Angular 22 list, detail, create, edit, transition, cancellation and conflict-recovery workflows
* Automated backend, integration, authorization, persistence, service, domain and Angular tests

The repository also contains Docker delivery assets, GitHub Actions validation and an Azure Bicep infrastructure baseline. Production Azure deployment, Key Vault, private endpoints, production observability and live authenticated Entra E2E execution remain explicitly documented roadmap work.

## Featured engineering work

### [Helvetic Operations Platform](https://github.com/JinyanShao/helvetic-operations-platform)

A multi-site work-order management Web application designed to help dispatchers and operations managers control operational work, identify SLA risk, preserve audit history and handle concurrent updates safely.

[[Repository](https://github.com/JinyanShao/helvetic-operations-platform)](https://github.com/JinyanShao/helvetic-operations-platform)

Verified engineering evidence includes 30 passing backend tests: 8 API integration tests, 12 authorization tests, 3 SQL Server Testcontainers repository tests, 4 application-service tests and 3 domain tests. The Angular application has 19 passing tests, and both the backend Release build and Angular production build pass.

Eight Playwright E2E flows have been implemented for list, filtering and pagination, detail, create, edit, transition, Manager cancellation and conflict recovery. Their current result is 0 passed, 0 failed and 8 explicitly skipped because the required Entra E2E base URL, role-specific storage-state files and deterministic fixture IDs are not currently available. The flows must not be described as executed successfully.

The application covers the complete verified Work Order path from domain rules and SQL Server persistence through protected APIs, generated client contracts and Angular user workflows.

### [[Order Management API](https://github.com/JinyanShao/order-management-api)](https://github.com/JinyanShao/order-management-api)

A backend for processing tenant-isolated orders while protecting inventory consistency under retries and concurrent requests.

It demonstrates multi-tenant isolation, role-based access control, transactional inventory, PostgreSQL row-level locking, idempotency, optimistic concurrency, state transitions, audit logging and automated concurrency testing.

### [[Clinical Data Platform](https://github.com/JinyanShao/clinical-data-platform)](https://github.com/JinyanShao/clinical-data-platform)

A controlled ingestion and processing platform for study-scoped healthcare and research data.

It demonstrates Python backend engineering, CSV and FHIR-oriented validation, provenance, auditability, idempotent imports, controlled access, asynchronous processing and structured operational diagnostics without claiming production medical compliance.

## Engineering priorities

* Turning operational workflows into explicit domain rules

* Protecting data integrity across validation, transactions and concurrent updates

* Designing APIs with predictable authorization and failure contracts

* Testing business behavior across domain, application, persistence and delivery boundaries

* Documenting verified implementation separately from future roadmap work

## Current status

- Based in Fribourg, Switzerland
- Swiss Permit B — authorised to work in Switzerland
- AWS Certified Developer – Associate
- Starting the BSc in Computer Science and Communication Systems at HEIA-FR in September 2026
- Seeking an approximately 40% role as a Student Software Engineer, Junior Software Engineer, Application Developer, Junior .NET Developer or Application Support Engineer; QA Automation remains an additional application direction.
- Approximately 40% availability by default, with around 40%–60% potentially discussable once the final HEIA-FR timetable is confirmed.
- Open to French-speaking and bilingual teams within practical public-transport distance from Fribourg

[Personal website](https://jinyanshao.ch) · [LinkedIn](https://www.linkedin.com/in/jinyanshao) · [Email](mailto:jinyanshao@proton.me)
