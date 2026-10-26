<img src="./assets/header.svg" alt="Samuel Wanjohi, Software & AI Engineer at Microsoft" width="100%">

<p align="center">
  <a href="https://www.linkedin.com/in/samuelwanjohi"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:sam.wanjohi94@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hi-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="./CV.md"><img src="https://img.shields.io/badge/CV-Read_it-7B6CFF?style=for-the-badge&logo=readthedocs&logoColor=white" alt="CV"></a>
  <a href="https://github.com/OData"><img src="https://img.shields.io/badge/OData-Team_member-E8590C?style=for-the-badge&logo=github&logoColor=white" alt="OData"></a>
</p>

### I work on the open-source .NET libraries that power OData APIs, including Microsoft Graph, and I build AI agents that make engineers faster.

Most of my day job is making APIs **faster, safer and easier to ship**: profiling hot paths in a JSON reader, closing resource-exhaustion holes before attackers find them, and running releases for packages used across the .NET ecosystem. The rest is building **documentation-grounded AI agents** that turn incidents, docs and tribal knowledge into answers and pull requests.

Before Microsoft, I helped scale **M-PESA**, one of the world's largest mobile-money platforms, to **2,600+ transactions per second**.

---

## 🧭 By the numbers

<table>
  <tr>
    <td align="center" width="25%"><h2>340+</h2><sub>commits to <a href="https://github.com/OData/odata.net">odata.net</a> &amp; <a href="https://github.com/OData/AspNetCoreOData">AspNetCoreOData</a> since 2024</sub></td>
    <td align="center" width="25%"><h2>100+</h2><sub>pull requests merged across the OData .NET stack</sub></td>
    <td align="center" width="25%"><h2>8 h → 9 min</h2><sub>M-PESA upgrade downtime, cut on platforms built for 99.99% availability</sub></td>
    <td align="center" width="25%"><h2>60%</h2><sub>less manual processing from privacy-telemetry ETL pipelines</sub></td>
  </tr>
</table>

<p align="center">
  <a href="https://www.nuget.org/packages/Microsoft.OData.Core"><img src="https://img.shields.io/nuget/dt/Microsoft.OData.Core?label=Microsoft.OData.Core%20downloads&style=flat-square&color=512BD4" alt="Microsoft.OData.Core downloads"></a>
  <a href="https://www.nuget.org/packages/Microsoft.AspNetCore.OData"><img src="https://img.shields.io/nuget/dt/Microsoft.AspNetCore.OData?label=Microsoft.AspNetCore.OData%20downloads&style=flat-square&color=512BD4" alt="Microsoft.AspNetCore.OData downloads"></a>
</p>
<p align="center"><sub>Live download counts of packages I help build and release.</sub></p>

## 🔬 Open-source work I'm proud of

<details open>
<summary><b>🛡️ Security hardening</b>: closing denial-of-service and data-exposure paths in ASP.NET Core OData</summary>

- [Bounded `MaxReceivedMessageSize` default](https://github.com/OData/AspNetCoreOData/pull/1574) to stop unbounded allocation (CWE-770)
- [Property restrictions and query limits for `$apply` / `$compute`](https://github.com/OData/AspNetCoreOData/pull/1594)
- [Configurable timeout for `matchesPattern`](https://github.com/OData/AspNetCoreOData/pull/1593) to defuse regex-based slowdowns
- [Opt-in diagnostic logging for query-validation failures](https://github.com/OData/AspNetCoreOData/pull/1592)
- Fixes for paging bypass via `Prefer: maxpagesize=0` (CWE-1284), nested `Delta<T>` allow-lists, and EDM-boundary checks for open types
</details>

<details open>
<summary><b>⚡ Performance</b>: fewer allocations on the hottest paths</summary>

- [Vectorized whitespace skipping in the JSON reader](https://github.com/OData/odata.net/pull/3381)
- [Avoid double string allocation in `JsonReader`](https://github.com/OData/odata.net/pull/3416) and `ReadOnlySpan`/`ReadOnlyMemory` refactors
- [`ODataNullValue` singleton](https://github.com/OData/odata.net/pull/3284) to remove repeated allocations
- [Built-in `Encoding.CreateTranscodingStream`](https://github.com/OData/odata.net/pull/3403) replacing a custom stream
</details>

<details>
<summary><b>🧱 Modernizing the API surface</b>: moving OData onto modern .NET</summary>

- Replace `Edm.Date` / `Edm.TimeOfDay` with `System.DateOnly` / `System.TimeOnly` in [ODL](https://github.com/OData/odata.net/pull/3408) and [ASP.NET Core OData](https://github.com/OData/AspNetCoreOData/pull/1541) for the 10.x line
- [Async APIs for `CsdlWriter` and `SchemaWriter`](https://github.com/OData/odata.net/pull/3006)
- [`ShouldReadPropertyAsStream` API](https://github.com/OData/odata.net/pull/3477) for streaming with property annotations
- [Enums as keys in the OData client](https://github.com/OData/odata.net/pull/3013), plus `IAsyncEnumerable` support and `TryValidate` for query options
</details>

<details>
<summary><b>🚀 Release engineering</b>: shipping 7.x, 8.x, 9.x and the 10.0 previews</summary>

- Drove version releases across four supported major lines
- Built nightly vs. release publishing modes, internal feed publishing and symbol pushing
- Automated stable OData dependency updates and package-version validation in CI
- Adopted NuGet Central Package Management; ported large legacy test suites to modern E2E tests
</details>

## 🤖 What else I build

| | |
|---|---|
| **AI agents & RAG** | Documentation-grounded agents and reusable skills that answer engineering questions, turn incidents into work items, plan implementations and check PRs, with human review gates for security and breaking changes. |
| **Platform self-service** | Azure DevOps automation for pipeline permissions and repo migration using workload identity federation, ownership checks, dry-run mode and full audit trails. |
| **API reliability** | Schema-contract and workload compatibility validation for Microsoft Graph onboarding, backed by telemetry, monitors and alerts. |
| **Payments at scale** | M-PESA Payment Gateway and API upgrades connecting banks, SACCOs, fintechs and merchants. |

## 🛠️ Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=cs,dotnet,py,ts,js,java,azure,react,nodejs,postgres,mysql,mongodb,git,linux,nginx,vscode&perline=16" alt="Tech stack">
</p>

![OData](https://img.shields.io/badge/OData-E8590C?style=flat-square)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs-412991?style=flat-square&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6E40C9?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![Azure Functions](https://img.shields.io/badge/Azure_Functions-0062AD?style=flat-square&logo=azurefunctions&logoColor=white)
![Data Factory](https://img.shields.io/badge/Data_Factory-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Kusto](https://img.shields.io/badge/Kusto-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Cosmos DB](https://img.shields.io/badge/Cosmos_DB-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

## 🗺️ The journey

```mermaid
timeline
    2018 : Microsoft AppFactory intern
         : Mawingu Networks, IoT and billing
    2019 : Techno Brain, Microsoft Engineering Center
         : Privacy telemetry pipelines
    2022 : Safaricom, M-PESA
         : 2,600+ TPS payment platform
    2024 : Microsoft
         : OData, Microsoft Graph, AI agents
```

🎓 **BSc Microprocessor Technology & Instrumentation**, University of Nairobi

## 💬 Let's talk about

C# performance · API design · OData · security hardening · building AI agents that people actually use · or the best cycling routes around Nairobi 🚴

<p align="center"><a href="./CV.md"><b>📄 Read the full CV →</b></a></p>
