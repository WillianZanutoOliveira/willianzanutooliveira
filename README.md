# Willian Zanuto

[🇺🇸 English](./README.en.md)

### Senior .NET Software Engineer
**C# · .NET 10 · ASP.NET Core · RabbitMQ · Distributed Systems · Software Architecture · Cloud · Modernização**

Desenvolvedor de software com **13+ anos de trajetória em Tecnologia** e **9+ anos em desenvolvimento**, atuando na construção, integração e modernização de sistemas corporativos.

Atualmente sou **Desenvolvedor .NET Sênior na NAVA – Technology for Business** e **Sócio & Software Engineer na ProcedeAuto**. Minha experiência combina desenvolvimento hands-on, integrações, mensageria, operação, produto e evolução arquitetural.

Busco construir software **manutenível, confiável, observável e evolutivo**, equilibrando decisões técnicas com necessidades reais do negócio.

[LinkedIn](https://www.linkedin.com/in/willian-zanuto-34a531b6) · [ProcedeAuto](https://procedeauto.com.br/) · [Engineering Portfolio](./portfolio/README.md)

---

## ⭐ Projeto técnico em destaque

### [Distributed Commerce Platform](https://github.com/WillianZanutoOliveira/distributed-commerce-platform)

[![CI](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/actions/workflows/ci.yml)

Plataforma de referência em **.NET 10** criada para demonstrar decisões de engenharia relevantes em ambientes distribuídos.

**Clean Architecture · RabbitMQ · MassTransit · Event-Driven Architecture · PostgreSQL · Transactional Outbox/Inbox · Idempotência · Eventual Consistency · OpenTelemetry · Docker · Kubernetes · CI/CD**

O fluxo implementa uma jornada distribuída de pedidos entre **Orders, Inventory, Payments e Notifications**, com banco por serviço, mensagens assíncronas, retries, proteção contra duplicidade, health checks, observabilidade e documentação arquitetural.

[Architecture](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/blob/main/docs/architecture.md) ·
[5-minute Recruiter Walkthrough](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/blob/main/docs/recruiter-guide.md) ·
[ADRs](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/tree/main/docs/adr) ·
[Kubernetes](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/tree/main/deploy/k8s) ·
[CI](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/actions/workflows/ci.yml)

**4 serviços · 3 bancos PostgreSQL independentes · 5 integration events · CI validando 4 imagens Docker**

> O objetivo deste projeto não é demonstrar quantidade de código, mas decisões sobre **consistência distribuída, confiabilidade de mensagens, desacoplamento, observabilidade e operação**.

---

## 🎯 Evidências de engenharia

| Sinal | Evidência pública |
| --- | --- |
| **Arquitetura distribuída** | Orders, Inventory, Payments e Notifications como serviços independentes |
| **Mensageria confiável** | RabbitMQ/MassTransit com Outbox/Inbox, retries e idempotência |
| **Ownership de dados** | PostgreSQL por serviço, sem compartilhamento de tabelas entre bounded contexts |
| **Consistência** | Fluxo assíncrono com estados `Pending`, `Completed`, `InventoryRejected` e `PaymentFailed` |
| **Observabilidade** | OpenTelemetry, métricas, traces e health checks |
| **Entrega** | GitHub Actions com build, testes, coverage e build das quatro imagens Docker |

➡️ [Ver o walkthrough técnico de 5 minutos](https://github.com/WillianZanutoOliveira/distributed-commerce-platform/blob/main/docs/recruiter-guide.md)

**Stack principal:** C# · .NET 10 · ASP.NET Core · EF Core · RabbitMQ · MassTransit · PostgreSQL · SQL Server · Azure DevOps · AWS · Docker · Kubernetes · OpenTelemetry

---

## 🚀 Outros projetos públicos

### [Golden Raspberry Awards API](https://github.com/WillianZanutoOliveira/ApiWebFilme)

[![CI](https://github.com/WillianZanutoOliveira/ApiWebFilme/actions/workflows/ci.yml/badge.svg)](https://github.com/WillianZanutoOliveira/ApiWebFilme/actions/workflows/ci.yml)

API REST modernizada para **.NET 10**, com regra de negócio isolada e testada, seed no startup, GET sem efeitos colaterais, EF Core/SQLite, Problem Details, health check, Docker e CI com cobertura.

**.NET 10 · ASP.NET Core · EF Core · NUnit · Docker · GitHub Actions**

[Architecture](https://github.com/WillianZanutoOliveira/ApiWebFilme/blob/master/docs/architecture.md) ·
[ADRs](https://github.com/WillianZanutoOliveira/ApiWebFilme/tree/master/docs/adr) ·
[CI](https://github.com/WillianZanutoOliveira/ApiWebFilme/actions/workflows/ci.yml)

### [Central Pessoa API](https://github.com/WillianZanutoOliveira/ApiCentralPessoa)

[![CI](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/actions/workflows/ci.yml/badge.svg)](https://github.com/WillianZanutoOliveira/ApiCentralPessoa/actions/workflows/ci.yml)

API em **.NET 10** com EF Core/MySQL, configuração segura, validação, Problem Details, tratamento centralizado de exceções, health check, testes automatizados e Docker Compose.

**.NET 10 · ASP.NET Core · EF Core · MySQL · NUnit · Docker Compose · CI/CD**

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

---

## ✅ Como trabalho engenharia

Nos projetos públicos procuro tornar verificável não apenas o resultado final, mas **o processo de engenharia**:

- mudanças relevantes por branch e Pull Request;
- CI validando build, testes e containers antes do merge;
- testes automatizados e code coverage;
- ADRs registrando decisões e trade-offs;
- configuração segura sem credenciais versionadas;
- documentação de arquitetura;
- Docker e exemplos Kubernetes;
- troubleshooting de falhas de CI antes da integração.

---

## 💼 Visão de ponta a ponta

Minha trajetória passou por suporte técnico, análise de sistemas e desenvolvimento. Isso me trouxe uma visão que vai além do código e inclui operação, usuários, integrações e processos de negócio.

Tenho experiência com **digitalização de processos manuais, aplicações web/mobile, integrações entre sistemas, modernização de legado, troubleshooting, automação e tradução de necessidades de negócio em software**.

---

## 📫 Contato

**LinkedIn:** https://www.linkedin.com/in/willian-zanuto-34a531b6  
**ProcedeAuto:** https://procedeauto.com.br/

> Interesse em desafios onde desenvolvimento hands-on, arquitetura e visão de produto precisem trabalhar juntos para gerar impacto real no negócio.
