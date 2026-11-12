## Hi, I'm Youssef 👋

**.NET Backend Developer · ASP.NET Core · REST APIs & System Integrations · Dynamics 365 CE / Dataverse**

I build backend services and connect business systems. For 2+ years I've worked on **production** platforms built with ASP.NET Core and Microsoft Dynamics 365 / Dataverse: Dataverse plugins, REST APIs, integration services between CRM and external systems, and the performance work that keeps them fast.

📍 Egypt (UTC+2), with working hours that overlap Europe and the Gulf · 💼 open to **freelance, contract and full-time** roles

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Youssef%20Mohammed-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/youssef-mohamed-15801b215)
[![Portfolio](https://img.shields.io/badge/Portfolio-youssefmohammed.com-222?logo=googlechrome&logoColor=white)](https://youssefmohammed.com)

---

### ⭐ Featured project

**[ERP Sync Connector](https://github.com/ucciefmhmd/erp-sync-connector)**: a .NET 10 integration service that keeps ERP data in sync and delivers sales orders **without duplicates**, even when the ERP times out or loses responses.

- Clean Architecture, keyset-paged change feeds with transactional checkpoints, and a transactional outbox with idempotency keys and reconciliation
- Polly resilience, scoped API keys, rate limiting, RFC 9457 errors, Serilog and trace ids
- 71 tests with about 73% coverage in CI, Docker, Codespaces, an architecture guide and 5 ADRs · [v1.0.0](https://github.com/ucciefmhmd/erp-sync-connector/releases/tag/v1.0.0)

**[Dataverse Plugins Showcase](https://github.com/ucciefmhmd/dataverse-plugins-showcase)**: C# Dataverse plugins and a Custom API on standard tables: contact data quality, a credit-limit guard using a FetchXML aggregate, and a credit-summary Custom API. Business rules are kept out of the SDK, plugins are thin, errors are traced safely, and 58 tests run the plugins through `IPlugin.Execute`.

### What I work on

| Area | In practice |
|---|---|
| **Dynamics 365 CE / Dataverse** | C# plugins and Custom Workflow Activities, Power Automate, FetchXML / QueryExpression, data model, security roles, forms, views and business rules |
| **Integrations** | ASP.NET Core integration services between Dataverse and external systems over OAuth 2.0 / OpenID Connect, webhooks and Azure Service Bus; retries, batching and idempotency |
| **Backend APIs** | ASP.NET Core Web APIs with EF Core and SQL Server, Clean Architecture, CQRS / MediatR, validation, JWT and role-based authorisation |
| **Performance** | Request-level timing of CRM calls, then removing round-trips, narrowing column sets, paging FetchXML and caching slow lookups |
| **Front end, when needed** | Angular, TypeScript, Blazor |

### Highlights from production work

<sub>Client names are left out on purpose; this work lives in private repositories.</sub>

- **Integration service, built from scratch:** an ASP.NET Core service between Dataverse, an OpenID Connect identity provider and external systems, using OAuth 2.0, webhooks and Azure Service Bus.
- **CRM performance:** added timing for every CRM call behind an API request, then used it to remove unnecessary round-trips and slow queries.
- **Reliability fix:** a bulk update kept failing on an external API's HTTP 429 limit. Caching, retries with backoff and batching made it finish reliably.
- **Dataverse plugin layer** for a licensing and service-request portal: schedule generation, status-transition guards, recalculated totals and notifications.

### Other projects

| Project | What it is |
|---|---|
| LMS Platform <sub>(private repositories, in development)</sub> | A learning management system: .NET 10 REST API split into Api, Application, Infrastructure and Persistence projects, EF Core + SQL Server, JWT with refresh-token rotation; Angular student and staff portals in English and Arabic |
| [Examination-Exam](https://github.com/ucciefmhmd/Examination-Exam) | SQL Server exam system: role-based procedures, views, triggers, automatic grading (team project) |
| [Clinical-Management-System](https://github.com/ucciefmhmd/Clinical-Management-System) | C# Windows Forms clinic app on EF Core (team project) |

### Tech

**Backend:** C# · .NET · ASP.NET Core · EF Core · SQL Server · REST · SignalR
**Microsoft platform:** Dynamics 365 CE · Dataverse · Power Automate · Azure Service Bus · Microsoft Entra ID
**Practices:** Clean Architecture · CQRS · automated testing (xUnit) · CI/CD (GitHub Actions, Azure DevOps) · Docker
**Front end:** Angular · TypeScript · Blazor
