# Engineering Portfolio

This section brings together **architecture case studies, product-engineering work and public code** that demonstrate how I approach software beyond feature implementation.

The goal is to make technical decisions, trade-offs, quality practices and product context visible without exposing proprietary source code, credentials or sensitive implementation details.

## Architecture & product case studies

### [B2B/B2C SaaS Orders Platform](./pedidos-saas-case-study.md)

Architecture case study for a multi-organization commercial platform built around modern .NET, PostgreSQL, Vue, security, payments, observability and automated testing.

**Highlights:** .NET 10 · ASP.NET Core · PostgreSQL · Vue 3 · Multi-tenancy · CI/CD · OpenTelemetry · Testcontainers

### [ProcedeAuto — Vehicle Information Automation](./procedeauto-case-study.md)

Product-engineering case study about digitizing and automating vehicle-information workflows, integrating software, external data sources and customer-facing automation.

**Highlights:** Product Engineering · APIs · Integrations · Automation · Digital Workflows · Production Ownership

---

## Public engineering projects

### [Distributed Commerce Platform](https://github.com/WillianZanutoOliveira/distributed-commerce-platform)

Public reference platform focused on senior-level distributed-system concerns:

- Clean Architecture;
- RabbitMQ / MassTransit;
- event-driven service collaboration;
- database-per-service PostgreSQL;
- transactional outbox/inbox;
- idempotent consumers;
- eventual consistency and retries;
- OpenTelemetry;
- Docker / Docker Compose;
- Kubernetes deployment examples;
- automated tests, coverage and CI container validation.

Useful links:
[Architecture](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/blob/main/docs/architecture.md) ·
[ADRs](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/tree/main/docs/adr) ·
[Kubernetes](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/tree/main/deploy/k8s) ·
[CI](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/actions/workflows/ci.yml)

### [Golden Raspberry Awards API](https://github.com/WillianZanutoOliveira/ApiWebFilme)

Public .NET 10 API showing:

- business-rule separation;
- unit and integration tests;
- EF Core / SQLite;
- Problem Details and health checks;
- Docker;
- CI with code coverage;
- ADRs and architecture documentation.

Useful links:
[Architecture](https://github.com/WillianZanutoOliveira/ApiWebFilme/blob/master/docs/architecture.md) ·
[ADR 0001](https://github.com/WillianZanutoOliveira/ApiWebFilme/blob/master/docs/adr/0001-modernize-to-dotnet-10.md) ·
[ADR 0002](https://github.com/WillianZanutoOliveira/ApiWebFilme/blob/master/docs/adr/0002-consecutive-award-intervals.md) ·
[CI](https://github.com/WillianZanutoOliveira/ApiWebFilme/actions/workflows/ci.yml)

### [Central Pessoa API](https://github.com/WillianZanutoOliveira/ApiCentralPessoa)

Public .NET 10 API showing:

- EF Core / MySQL;
- secure external configuration;
- validation and Problem Details;
- centralized exception handling;
- health checks;
- NUnit tests and coverage;
- Docker / Docker Compose;
- GitHub Actions;
- security and architecture documentation.

Useful links:
[Architecture](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/blob/master/docs/architecture.md) ·
[ADR 0001](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/blob/master/docs/adr/0001-modernize-to-dotnet-10.md) ·
[Security](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/blob/master/SECURITY.md) ·
[CI](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/actions/workflows/ci.yml)

---

## What I want this portfolio to show

My objective is not to present a large number of repositories. I prefer to expose a smaller set of projects where recruiters and engineers can inspect evidence of:

- architectural reasoning;
- incremental modernization;
- automated quality gates;
- tests and operational concerns;
- secure configuration;
- integration and product thinking;
- documentation of technical decisions.

> Proprietary projects are represented through sanitized case studies. Production code, credentials, provider details and sensitive implementation information are intentionally omitted.
