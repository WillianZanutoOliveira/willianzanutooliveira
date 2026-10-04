<div align="center">

# Willian Zanuto

### Senior .NET Software Engineer

**Distributed Systems · Software Architecture · Event-Driven Architecture · Cloud · Modernization**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Willian%20Zanuto-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/willian-zanuto-34a531b6)
[![ProcedeAuto](https://img.shields.io/badge/ProcedeAuto-Product%20Engineering-111827)](https://procedeauto.com.br/)
[![Português](https://img.shields.io/badge/README-Portugu%C3%AAs-374151)](./README.md)

![.NET 10](https://img.shields.io/badge/.NET-10-512BD4?logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-Messaging-FF6600?logo=rabbitmq&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?logo=kubernetes&logoColor=white)

</div>

---

Software engineer with **13+ years in Technology** and **9+ years in software development**, focused on building, integrating and modernizing enterprise systems.

I currently work as a **Senior .NET Developer at NAVA – Technology for Business** and as a **Partner & Software Engineer at ProcedeAuto**, combining hands-on engineering, integrations, messaging, operations, product and architectural evolution.

> I focus on building software that is **maintainable, reliable, observable and evolvable**, balancing engineering quality with real business needs.

**Quick navigation:** [Flagship project](#-flagship-engineering-project) · [Evidence](#-engineering-evidence) · [Public projects](#-selected-public-projects) · [Case studies](#-architecture--product-engineering) · [Contact](#-contact)

---

## ⭐ Flagship engineering project

### [Distributed Commerce Platform](https://github.com/WillianZanutoOliveira/distributed-commerce-platform)

[![CI](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/actions/workflows/ci.yml)
![Services](https://img.shields.io/badge/Services-4-2563EB)
![Databases](https://img.shields.io/badge/PostgreSQL%20DBs-3-4169E1)
![Events](https://img.shields.io/badge/Integration%20Events-5-7C3AED)
![Docker](https://img.shields.io/badge/Docker%20Images-4-2496ED)

A **.NET 10 distributed systems reference platform** created to demonstrate production-minded engineering decisions.

**Clean Architecture · RabbitMQ · MassTransit · Event-Driven Architecture · PostgreSQL · Transactional Outbox/Inbox · Idempotency · Eventual Consistency · OpenTelemetry · Docker · Kubernetes · CI/CD**

The implemented flow coordinates **Orders, Inventory, Payments and Notifications** through asynchronous messaging, database-per-service boundaries, retries, duplicate protection, health checks, observability and architecture documentation.

[**Architecture**](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/blob/main/docs/architecture.md) ·
[**5-minute Recruiter Walkthrough**](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/blob/main/docs/recruiter-guide.md) ·
[**ADRs**](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/tree/main/docs/adr) ·
[**Kubernetes**](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/tree/main/deploy/k8s) ·
[**CI**](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/actions/workflows/ci.yml)

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

**Core stack:** C# · .NET 10 · ASP.NET Core · EF Core · RabbitMQ · MassTransit · PostgreSQL · SQL Server · Azure DevOps · AWS · Docker · Kubernetes · OpenTelemetry

---

## 🚀 Selected public projects

### [Golden Raspberry Awards API](https://github.com/WillianZanutoOliveira/ApiWebFilme)

[![CI](https://github.com/WillianZanutoOliveira/ApiWebFilme/actions/workflows/ci.yml/badge.svg)](https://github.com/WillianZanutoOliveira/ApiWebFilme/actions/workflows/ci.yml)
![.NET](https://img.shields.io/badge/.NET-10-512BD4?logo=dotnet&logoColor=white)
![Tests](https://img.shields.io/badge/Tests-NUnit-22C55E)
![Docker](https://img.shields.io/badge/Docker-Enabled-2496ED?logo=docker&logoColor=white)

Modernized **.NET 10** REST API with isolated and tested business rules, startup data seeding, side-effect-free GET behavior, EF Core/SQLite, Problem Details, health checks, Docker and CI with coverage.

[Architecture](https://github.com/WillianZanutoOliveira/ApiWebFilme/blob/master/docs/architecture.md) ·
[ADRs](https://github.com/WillianZanutoOliveira/ApiWebFilme/tree/master/docs/adr) ·
[CI](https://github.com/WillianZanutoOliveira/ApiWebFilme/actions/workflows/ci.yml)

### [Central Pessoa API](https://github.com/WillianZanutoOliveira/ApiCentralPessoa)

[![CI](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/actions/workflows/ci.yml/badge.svg)](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/actions/workflows/ci.yml)
![.NET](https://img.shields.io/badge/.NET-10-512BD4?logo=dotnet&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-EF%20Core-4479A1?logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker%20Compose-Enabled-2496ED?logo=docker&logoColor=white)

**.NET 10** REST API with EF Core/MySQL, secure external configuration, validation, Problem Details, centralized exception handling, health checks, automated tests and Docker Compose.

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

➡️ [Open Engineering Portfolio](./portfolio/README.md)

---

<details>
<summary><strong>✅ Engineering approach</strong></summary>

<br>

Across public projects I try to make not only the final result visible, but also **how engineering decisions are made and validated**:

- meaningful changes through branches and pull requests;
- CI validating builds, tests and containers before merge;
- automated tests and code coverage;
- ADRs documenting decisions and trade-offs;
- secure configuration without committed credentials;
- architecture documentation;
- Docker and Kubernetes examples;
- troubleshooting CI failures before integration.

</details>

<details>
<summary><strong>💼 End-to-end perspective</strong></summary>

<br>

My background includes technical support, systems analysis and software development. This gives me a broader perspective that includes code, operations, users, integrations and business processes.

My experience includes **digitizing manual workflows, web/mobile applications, system integrations, legacy modernization, troubleshooting, automation and translating business needs into software**.

</details>

---

## 📫 Contact

**LinkedIn:** https://www.linkedin.com/in/willian-zanuto-34a531b6  
**ProcedeAuto:** https://procedeauto.com.br/
