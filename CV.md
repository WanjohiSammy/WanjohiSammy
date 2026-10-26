# Samuel Wanjohi

**Senior Software & AI Engineer · Cloud Platforms · Distributed Systems**

📍 Nairobi, Kenya · ✉️ [sam.wanjohi94@gmail.com](mailto:sam.wanjohi94@gmail.com) · 💼 [linkedin.com/in/samuelwanjohi](https://www.linkedin.com/in/samuelwanjohi) · 🐙 [github.com/WanjohiSammy](https://github.com/WanjohiSammy)

---

## Summary

Software and AI engineer with 8+ years of experience building enterprise platforms, high-scale APIs, data pipelines, developer tooling and AI-enabled automation across Microsoft and Safaricom. Current work spans Microsoft Graph onboarding, OData library engineering, security and reliability investigations, Azure DevOps governance, and documentation-grounded AI agents using LLM and RAG patterns.

**Highlights:** 340+ commits and 100+ merged PRs to the open-source [OData .NET](https://github.com/OData) libraries · payment platforms processing **2,600+ transactions per second** · systems designed for **99.99% availability** · **60%** reduction in manual processing.

## Core expertise

| Area | Skills |
|---|---|
| **AI & Agentic Systems** | LLM applications, RAG, AI agents, knowledge grounding, prompt engineering, reusable skills, tool integration, evaluations |
| **Software & APIs** | C#, .NET / ASP.NET Core, OData, REST, OpenAPI, microservices, async programming, design patterns |
| **Cloud & Reliability** | Azure, Azure DevOps, CI/CD, workload identity federation, monitoring, incident diagnosis, security remediation |
| **Data & Analytics** | Python, Azure Data Factory, ETL/ELT, Spark, Kafka, SQL Server, PostgreSQL, Kusto, Cosmos DB, Power BI |

## Open source: OData .NET (2024 – present)

Contributor and release engineer on [odata.net](https://github.com/OData/odata.net) and [AspNetCoreOData](https://github.com/OData/AspNetCoreOData), the libraries behind OData services including Microsoft Graph. **340+ commits, 100+ merged pull requests.**

- **Security hardening:** [bounded message-size defaults (CWE-770)](https://github.com/OData/AspNetCoreOData/pull/1574), [query limits for `$apply`/`$compute`](https://github.com/OData/AspNetCoreOData/pull/1594), [regex evaluation timeouts](https://github.com/OData/AspNetCoreOData/pull/1593), and fixes for paging bypass (CWE-1284) and nested `Delta<T>` allow-lists.
- **Performance:** [vectorized JSON whitespace skipping](https://github.com/OData/odata.net/pull/3381), [fewer string allocations in `JsonReader`](https://github.com/OData/odata.net/pull/3416), `ReadOnlySpan`/`ReadOnlyMemory` refactors, and an [`ODataNullValue` singleton](https://github.com/OData/odata.net/pull/3284).
- **API modernization:** [`DateOnly`/`TimeOnly` replacing `Edm.Date`/`Edm.TimeOfDay`](https://github.com/OData/odata.net/pull/3408) for 10.x, [async CSDL writers](https://github.com/OData/odata.net/pull/3006), [streaming with property annotations](https://github.com/OData/odata.net/pull/3477), `IAsyncEnumerable` support, and `TryValidate` for query options.
- **Release engineering:** shipped releases across the 7.x, 8.x, 9.x and 10.0-preview lines; built nightly vs. release publishing modes, automated dependency updates and package-version validation, and adopted Central Package Management.

## Experience

### Software Engineer II — Microsoft, Nairobi
*May 2024 – Present*

- Drive engineering across **Microsoft Graph onboarding** and **[OData](https://github.com/OData)**, translating security, reliability, release and customer requirements into technical designs, implementation plans, product fixes and operational guidance.
- Design **documentation-grounded AI agents** and reusable agent workflows using LLMs, RAG patterns, prompt engineering, enterprise knowledge sources and tool integrations to improve engineering self-service and knowledge discovery.
- Build and enhance OData libraries and services, including performance and compatibility improvements, release validation, package-version guidance, accessibility remediation and security fixes for supported .NET package lines.
- Investigate schema-contract, API and workload compatibility failures in Microsoft Graph; turn findings into safer validation behavior, telemetry, monitors, alerts and actionable guidance for workload owners.
- Design **Azure DevOps self-service automation** for pipeline permission management and repository-reference repair, using workload identity federation, ownership validation, dry-run controls and auditable execution.
- Create AI-assisted engineering workflows for incident-to-work-item conversion, implementation planning, PR quality checks, dependency updates and issue triage, while preserving human review gates for security and breaking changes.

### Software Engineer — Safaricom PLC, Nairobi
*Feb 2022 – May 2024*

- Contributed to **M-PESA** platform upgrades that reduced upgrade-related service disruption from **8 hours (2018) to 9 minutes (2022)**.
- Supported platform improvements that increased processing capacity to **more than 2,600 transactions per second** while maintaining high reliability and scalability.
- Upgraded the M-PESA Payment Gateway and API ecosystem, supporting secure integrations with banks, financial institutions, mobile-money providers, SACCOs and merchants.
- Participated in architecture planning, performance optimization and change-impact analysis for systems designed for **99.99% availability**.

### Software Development Engineer — Techno Brain Global, Microsoft Engineering Center, Nairobi
*Jun 2019 – Feb 2022*

- Designed and implemented five services for processing and analyzing privacy data in Windows event telemetry across large-scale datasets.
- Built ETL and analytics pipelines with Azure Data Factory, U-SQL, SQL Server and Kusto, **reducing manual processing by 60%**.
- Developed Power BI dashboards for privacy-risk reporting and operational decision-making.
- Led database and API design for a test-scheduling platform using ASP.NET Core Web API, SQL Server and React.

### Software Developer — Mawingu Networks Ltd, Nanyuki
*Dec 2018 – May 2019*

- Built IoT and operational automation integrated with Microsoft Kaizala and backend services for remote monitoring of distributed network devices.
- Delivered billing and customer-service workflow applications that replaced spreadsheet-based processes and improved access to customer and payment information.

### Software Development Intern — Microsoft AppFactory, Nanyuki
*Jun 2018 – Nov 2018*

- Built Azure-hosted backend automation integrating network APIs with Microsoft Kaizala for technician notifications and field operations.
- Developed solutions with Azure App Service and Azure Functions and demonstrated Microsoft 365 adoption scenarios to prospective organizations.

## Selected engineering projects

- **Pipeline Governance Self-Service:** governed Azure DevOps workflows for permission grants and repository migration using federated workload identity, ownership checks, dry-run execution and auditable service-principal writes.
- **OData Reliability and Security:** investigation, remediation, release planning, customer guidance and version-support decisions for [OData .NET](https://github.com/OData/odata.net) and [ASP.NET Core OData](https://github.com/OData/AspNetCoreOData) packages.
- **Graph Onboarding Reliability:** schema and workload compatibility validation, production incident analysis, and automation that reduces onboarding friction and release risk.
- **AI-Assisted Engineering:** reusable Copilot skills and agent workflows for incident-to-work-item repair items, implementation planning, repository automation and documentation-grounded support.

## Technical skills

- **Languages:** C#, Python, TypeScript, JavaScript, Java, SQL
- **AI:** LLMs, RAG, AI agents, agentic workflows, prompt engineering, knowledge-grounded Q&A, AI evaluation, Azure AI tooling, OpenAI, DeepSeek, Ollama
- **Backend & APIs:** ASP.NET Core, .NET, OData, REST, OpenAPI, SOAP, Node.js/Express, microservices, dependency injection, asynchronous programming
- **Cloud & DevOps:** Microsoft Azure, Azure DevOps, CI/CD, Azure Functions, App Service, workload identity federation, Power Automate, Git
- **Data:** Azure Data Factory, ETL/ELT, Spark, Kafka, SQL Server, PostgreSQL, MySQL, Kusto, Cosmos DB, MongoDB, Pandas, NumPy, Power BI
- **Frontend & Ops:** React, HTML, CSS, Bootstrap, IIS, Nginx, Linux/Windows, monitoring, troubleshooting, performance tuning

## Education

**BSc, Microprocessor Technology and Instrumentation** — University of Nairobi, Kenya · *2014 – 2018*

---

<sub>[← Back to my GitHub profile](https://github.com/WanjohiSammy)</sub>
