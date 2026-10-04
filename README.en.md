# Willian Zanuto

[🇧🇷 Português](./README.md)

### Senior .NET Software Engineer
**C# · .NET 10 · ASP.NET Core · RabbitMQ · Distributed Systems · Software Architecture · Cloud · Modernization**

Software engineer with **13+ years in Technology** and **9+ years in software development**, focused on building, integrating and modernizing enterprise systems.

I currently work as a **Senior .NET Developer at NAVA – Technology for Business** and as a **Partner & Software Engineer at ProcedeAuto**, combining hands-on engineering, integrations, messaging, operations, product and architectural evolution.

I focus on building software that is **maintainable, reliable, observable and evolvable**, balancing engineering quality with real business needs.

[LinkedIn](https://www.linkedin.com/in/willian-zanuto-34a531b6) · [ProcedeAuto](https://procedeauto.com.br/) · [Engineering Portfolio](./portfolio/README.md)

---

## ⭐ Flagship engineering project

### [Distributed Commerce Platform](https://github.com/WillianZanutoOliveira/distributed-commerce-platform)

[![CI](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/actions/workflows/ci.yml)

A **.NET 10 distributed systems reference platform** created to demonstrate production-minded engineering decisions.

**Clean Architecture · RabbitMQ · MassTransit · Event-Driven Architecture · PostgreSQL · Transactional Outbox/Inbox · Idempotency · Eventual Consistency · OpenTelemetry · Docker · Kubernetes · CI/CD**

The implemented flow coordinates **Orders, Inventory, Payments and Notifications** through asynchronous messages, database-per-service boundaries, retries, duplicate protection, health checks, observability and architecture documentation.

[Architecture](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/blob/main/docs/architecture.md) ·
[5-minute Recruiter Walkthrough](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/blob/main/docs/recruiter-guide.md) ·
[ADRs](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/tree/main/docs/adr) ·
[Kubernetes](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/tree/main/deploy/k8s) ·
[CI](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/actions/workflows/ci.yml)

**4 services · 3 independent PostgreSQL databases · 5 integration events · CI validating 4 Docker images**

> The goal is not to showcase code volume, but decisions around **distributed consistency, message reliability, decoupling, observability and operations**.

---

## 🎯 Engineering evidence

| Signal | Public evidence |
| --- | --- |
| **Distributed architecture** | Orders, Inventory, Payments and Notifications as independent services |
| **Reliable messaging** | RabbitMQ/MassTransit with Outbox/Inbox, retries and idempotency |
| **Data ownership** | Database-per-service PostgreSQL boundaries with no cross-service table access |
| **Consistency model** | Asynchronous flow through `Pending`, `Completed`, `InventoryRejected` and `PaymentFailed` states |
| **Observability** | OpenTelemetry traces, metrics and health checks |
| **Delivery** | GitHub Actions running build, tests, coverage and four Docker image builds |

➡️ [Open the 5-minute engineering walkthrough](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/blob/main/docs/recruiter-guide.md)

**Core stack:** C# · .NET 10 · ASP.NET Core · EF Core · RabbitMQ · MassTransit · PostgreSQL · SQL Server · Azure DevOps · AWS · Docker · Kubernetes · OpenTelemetry

---

## 🚀 Other public projects

### [Golden Raspberry Awards API](https://github.com/WillianZanutoOliveira/ApiWebFilme)

[![CI](https://github.com/WillianZanutoOliveira/ApiWebFilme/actions/workflows/ci.yml/badge.svg)](https://github.com/WillianZanutoOliveira/ApiWebFilme/actions/workflows/ci.yml)

Modernized **.NET 10** REST API with isolated and tested business rules, startup data seeding, side-effect-free GET behavior, EF Core/SQLite, Problem Details, health checks, Docker and CI with coverage.

**.NET 10 · ASP.NET Core · EF Core · NUnit · Docker · GitHub Actions**

[Architecture](https://github.com/WillianZanutoOliveira/ApiWebFilme/blob/master/docs/architecture.md) ·
[ADRs](https://github.com/WillianZanutoOliveira/ApiWebFilme/tree/master/docs/adr) ·
[CI](https://github.com/WillianZanutoOliveira/ApiWebFilme/actions/workflows/ci.yml)

### [Central Pessoa API](https://github.com/WillianZanutoOliveira/ApiCentralPessoa)

[![CI](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/actions/workflows/ci.yml/badge.svg)](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/actions/workflows/ci.yml)

**.NET 10** REST API with EF Core/MySQL, secure external configuration, validation, Problem Details, centralized exception handling, health checks, automated tests and Docker Compose.

**.NET 10 · ASP.NET Core · EF Core · MySQL · NUnit · Docker Compose · CI/CD**

[Architecture](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/blob/master/docs/architecture.md) ·
[ADR](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/blob/master/docs/adr/0001-modernize-to-dotnet-10.md) ·
[Security](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/blob/master/SECURITY.md) ·
[CI](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/actions/workflows/ci.yml)

---

## 🏗️ Architecture & Product Engineering

### [B2B/B2C SaaS Orders Platform — Architecture Case Study](./portfolio/pedidos-saas-case-study.md)

Sanitized case study of a private multi-organization SaaS platform focused on tenant isolation, authorization, security, payments, observability and delivery quality.

**.NET 10 · ASP.NET Core · PostgreSQL · Vue 3 · Multi-tenancy · MFA · Testcontainers · OpenTelemetry · GitHub Actions**

### [ProcedeAuto — Vehicle Information Automation](./portfolio/procedeauto-case-study.md)

Product-engineering case study focused on workflow digitalization, automation, external integrations and continuous evolution of a real business solution.

**Product Engineering · APIs · Integrations · Automation · Digital Workflows · Reliability**

---

## ✅ Engineering approach

Across public projects I try to make not only the final result visible, but also **how engineering decisions are made and validated**:

- meaningful changes through branches and pull requests;
- CI validating builds, tests and containers before merge;
- automated tests and code coverage;
- ADRs documenting decisions and trade-offs;
- secure configuration without committed credentials;
- architecture documentation;
- Docker and Kubernetes examples;
- troubleshooting CI failures before integration.

---

## 💼 End-to-end perspective

My background includes technical support, systems analysis and software development. This gives me a broader perspective that includes code, operations, users, integrations and business processes.

My experience includes **digitizing manual workflows, web/mobile applications, system integrations, legacy modernization, troubleshooting, automation and translating business needs into software**.

---

## 📫 Contact

**LinkedIn:** https://www.linkedin.com/in/willian-zanuto-34a531b6  
**ProcedeAuto:** https://procedeauto.com.br/
