# Jinyan Shao

**Business application engineer building reliable systems with .NET, Angular and cloud-delivery foundations.**

Based in Fribourg, Switzerland, I design operational software around explicit domain rules, transactional data, access control, testing and maintainable delivery pipelines.

My commercial background includes Python-based backend development, API integration, SQL data processing and workflow automation. My public engineering portfolio extends that foundation through production-oriented work with FastAPI, PostgreSQL, Docker, GitHub Actions and AWS concepts.

## Current focus

I am applying my existing backend and business-application experience to the Microsoft ecosystem through a working end-to-end project:

- Guarded Work Order lifecycle rules, application services and a Work Order-specific repository boundary
- EF Core 8 persistence with SQL Server, official migrations, `rowversion` optimistic concurrency and atomic audit events
- ASP.NET Core Minimal APIs with FluentValidation, Problem Details, server-side pagination, filtering and allowlisted sorting
- Microsoft Entra ID / MSAL authorization code flow and role-based access
- Generated NSwag TypeScript client with drift checking
- Angular 22 list, detail, create, edit, transition, cancellation, conflict-recovery and role-aware workflows
- Automated backend, integration, authorization, repository, service, domain and Angular tests

The repository also includes Docker images, GitHub Actions validation and an Azure Bicep infrastructure baseline. Production Azure deployment, Key Vault, private endpoints, production observability and a live authenticated Entra E2E environment remain roadmap work.

## Featured engineering work

### [Helvetic Operations Platform](https://github.com/JinyanShao/helvetic-operations-platform)

A multi-site operations control tower built as an end-to-end enterprise application using C#, ASP.NET Core, EF Core 8, SQL Server, Angular 22 and strict TypeScript.

Verified results: 30 backend tests passed—8/8 API integration, 12/12 authorization, 3/3 Testcontainers repository, 4/4 service and 3/3 domain tests—plus 19 Angular tests. The backend Release build and Angular production build passed.

Eight Playwright E2E flows are implemented: 0 passed, 0 failed and 8 explicitly skipped because the Entra E2E base URL, role storage-state files and deterministic fixture IDs are unavailable. These flows remain implemented but require the roadmap's live authenticated Entra E2E environment to execute.

### [Order Management API](https://github.com/JinyanShao/order-management-api)

A multi-tenant business backend with role-based access control, transactional inventory, concurrency control, idempotency, audit logging and automated tests.

### [Clinical Data Platform](https://github.com/JinyanShao/clinical-data-platform)

A FHIR-oriented ingestion platform focused on validation, provenance, controlled access and asynchronous workflows.

## What I care about

- Turning operational workflows into clear domain models
- Reliable APIs, data integrity and observable failure modes
- Tests that protect business rules rather than implementation details
- Documentation that separates shipped behavior from roadmap work

## Current status

- Based in Fribourg, Switzerland
- Swiss Permit B — authorised to work in Switzerland
- AWS Certified Developer – Associate
- Starting the BSc in Computer Science and Communication Systems at HEIA-FR in September 2026
- Seeking an approximately 40% role as a Student Software Engineer, Junior Software Engineer, Application Developer, Junior .NET Developer or Application Support Engineer; QA Automation is an additional application direction.
- Open to French-speaking and bilingual teams within practical public-transport distance from Fribourg

[Personal website](https://jinyanshao.ch) · [LinkedIn](https://www.linkedin.com/in/jinyanshao) · [Email](mailto:jinyanshao@proton.me)
