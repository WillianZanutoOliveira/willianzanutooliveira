<div align="center">

# Willian Zanuto

### Senior .NET Software Engineer

**Distributed Systems · Software Architecture · Event-Driven Architecture · Cloud · Modernização**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Willian%20Zanuto-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/willian-zanuto-34a531b6)
[![ProcedeAuto](https://img.shields.io/badge/ProcedeAuto-Product%20Engineering-111827)](https://procedeauto.com.br/)
[![English](https://img.shields.io/badge/README-English-374151)](./README.en.md)

![.NET 10](https://img.shields.io/badge/.NET-10-512BD4?logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-Messaging-FF6600?logo=rabbitmq&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?logo=kubernetes&logoColor=white)

</div>

---

Desenvolvedor de software com **13+ anos de trajetória em Tecnologia** e **9+ anos em desenvolvimento**, atuando na construção, integração e modernização de sistemas corporativos.

Atualmente sou **Desenvolvedor .NET Sênior na NAVA – Technology for Business** e **Sócio & Software Engineer na ProcedeAuto**. Minha experiência combina desenvolvimento hands-on, integrações, mensageria, operação, produto e evolução arquitetural.

> Meu foco é construir software **manutenível, confiável, observável e evolutivo**, equilibrando engenharia e necessidades reais do negócio.

**Navegação rápida:** [Projeto principal](#-projeto-técnico-em-destaque) · [Evidências](#-evidências-de-engenharia) · [Projetos públicos](#-projetos-públicos-selecionados) · [Cases](#-arquitetura--product-engineering) · [Contato](#-contato)

---

## ⭐ Projeto técnico em destaque

### [Distributed Commerce Platform](https://github.com/WillianZanutoOliveira/distributed-commerce-platform)

[![CI](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/actions/workflows/ci.yml)
![Services](https://img.shields.io/badge/Services-4-2563EB)
![Databases](https://img.shields.io/badge/PostgreSQL%20DBs-3-4169E1)
![Events](https://img.shields.io/badge/Integration%20Events-5-7C3AED)
![Docker](https://img.shields.io/badge/Docker%20Images-4-2496ED)

Plataforma de referência em **.NET 10** criada para demonstrar decisões de engenharia relevantes em ambientes distribuídos.

**Clean Architecture · RabbitMQ · MassTransit · Event-Driven Architecture · PostgreSQL · Transactional Outbox/Inbox · Idempotência · Eventual Consistency · OpenTelemetry · Docker · Kubernetes · CI/CD**

O fluxo implementa uma jornada distribuída entre **Orders, Inventory, Payments e Notifications**, com banco por serviço, mensagens assíncronas, retries, proteção contra duplicidade, health checks, observabilidade e documentação arquitetural.

[**Architecture**](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/blob/main/docs/architecture.md) ·
[**5-minute Recruiter Walkthrough**](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/blob/main/docs/recruiter-guide.md) ·
[**ADRs**](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/tree/main/docs/adr) ·
[**Kubernetes**](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/tree/main/deploy/k8s) ·
[**CI**](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/actions/workflows/ci.yml)

---

## 🎯 Evidências de engenharia

| Sinal | Evidência pública |
| --- | --- |
| **Arquitetura distribuída** | Orders, Inventory, Payments e Notifications como serviços independentes |
| **Mensageria confiável** | RabbitMQ/MassTransit com Outbox/Inbox, retries e idempotência |
| **Ownership de dados** | PostgreSQL por serviço, sem compartilhamento de tabelas entre bounded contexts |
| **Consistência** | Fluxo assíncrono com estados `Pending`, `Completed`, `InventoryRejected` e `PaymentFailed` |
| **Observabilidade** | OpenTelemetry, métricas, traces e health checks |
| **Entrega** | GitHub Actions com build, testes, coverage e build de quatro imagens Docker |

**Stack principal:** C# · .NET 10 · ASP.NET Core · EF Core · RabbitMQ · MassTransit · PostgreSQL · SQL Server · Azure DevOps · AWS · Docker · Kubernetes · OpenTelemetry

---

## 🚀 Projetos públicos selecionados

### [Golden Raspberry Awards API](https://github.com/WillianZanutoOliveira/ApiWebFilme)

[![CI](https://github.com/WillianZanutoOliveira/ApiWebFilme/actions/workflows/ci.yml/badge.svg)](https://github.com/WillianZanutoOliveira/ApiWebFilme/actions/workflows/ci.yml)
![.NET](https://img.shields.io/badge/.NET-10-512BD4?logo=dotnet&logoColor=white)
![Tests](https://img.shields.io/badge/Tests-NUnit-22C55E)
![Docker](https://img.shields.io/badge/Docker-Enabled-2496ED?logo=docker&logoColor=white)

API REST modernizada para **.NET 10**, com regra de negócio isolada e testada, seed no startup, GET sem efeitos colaterais, EF Core/SQLite, Problem Details, health check, Docker e CI com cobertura.

[Architecture](https://github.com/WillianZanutoOliveira/ApiWebFilme/blob/master/docs/architecture.md) ·
[ADRs](https://github.com/WillianZanutoOliveira/ApiWebFilme/tree/master/docs/adr) ·
[CI](https://github.com/WillianZanutoOliveira/ApiWebFilme/actions/workflows/ci.yml)

### [Central Pessoa API](https://github.com/WillianZanutoOliveira/ApiCentralPessoa)

[![CI](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/actions/workflows/ci.yml/badge.svg)](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/actions/workflows/ci.yml)
![.NET](https://img.shields.io/badge/.NET-10-512BD4?logo=dotnet&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-EF%20Core-4479A1?logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker%20Compose-Enabled-2496ED?logo=docker&logoColor=white)

API em **.NET 10** com EF Core/MySQL, configuração segura, validação, Problem Details, tratamento centralizado de exceções, health check, testes automatizados e Docker Compose.

[Architecture](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/blob/master/docs/architecture.md) ·
[ADR](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/blob/master/docs/adr/0001-modernize-to-dotnet-10.md) ·
[Security](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/blob/master/SECURITY.md) ·
[CI](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/actions/workflows/ci.yml)

---

## 🏗️ Arquitetura & Product Engineering

### [B2B/B2C SaaS Orders Platform — Architecture Case Study](./portfolio/pedidos-saas-case-study.md)

Case sanitizado de uma plataforma SaaS privada multi-organização, com foco em isolamento de tenant, autorização, segurança, pagamentos, observabilidade e qualidade de entrega.

**.NET 10 · ASP.NET Core · PostgreSQL · Vue 3 · Multi-tenancy · MFA · Testcontainers · OpenTelemetry · GitHub Actions**

### [ProcedeAuto — Vehicle Information Automation](./portfolio/procedeauto-case-study.md)

Case de engenharia de produto sobre digitalização de processos, automação, integrações com fontes externas e evolução de uma solução utilizada em contexto real de negócio.

**Product Engineering · APIs · Integrations · Automation · Digital Workflows · Reliability**

➡️ [Abrir Engineering Portfolio](./portfolio/README.md)

---

<details>
<summary><strong>✅ Como trabalho engenharia</strong></summary>

<br>

Nos projetos públicos procuro tornar verificável não apenas o resultado final, mas também **o processo de engenharia**:

- mudanças relevantes por branch e Pull Request;
- CI validando build, testes e containers antes do merge;
- testes automatizados e code coverage;
- ADRs registrando decisões e trade-offs;
- configuração segura sem credenciais versionadas;
- documentação de arquitetura;
- Docker e exemplos Kubernetes;
- troubleshooting de falhas de CI antes da integração.

</details>

<details>
<summary><strong>💼 Visão de ponta a ponta</strong></summary>

<br>

Minha trajetória passou por suporte técnico, análise de sistemas e desenvolvimento. Isso me trouxe uma visão que vai além do código e inclui operação, usuários, integrações e processos de negócio.

Tenho experiência com **digitalização de processos manuais, aplicações web/mobile, integrações entre sistemas, modernização de legado, troubleshooting, automação e tradução de necessidades de negócio em software**.

</details>

---

## 📫 Contato

**LinkedIn:** https://www.linkedin.com/in/willian-zanuto-34a531b6  
**ProcedeAuto:** https://procedeauto.com.br/

> Interesse em desafios onde desenvolvimento hands-on, arquitetura e visão de produto precisem trabalhar juntos para gerar impacto real no negócio.
