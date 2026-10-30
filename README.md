<img src="github-banner.png" width="100%" />

# 👋 Hi, I'm Bill Walker

## Senior Data Engineer | Microsoft Fabric | Azure Data Factory | Python/PySpark | Delta Lake | Power BI-Ready Data Products

I help modernize legacy SQL Server, SSIS, and Azure Data Factory-style data platforms into governed, production-ready lakehouse solutions using Microsoft Fabric, Python/PySpark, Delta Lake, Azure, Databricks, and Power BI.

---

## 🚀 About Me

I am a Senior Data Engineer with 18+ years of experience designing, building, modernizing, and supporting data platforms across traditional SQL Server environments and modern cloud lakehouse architectures.

My current focus is **legacy-to-lakehouse modernization**: helping teams move from SQL Server, SSIS, stored procedures, manual extracts, and fragmented reporting pipelines into scalable, validated, and business-ready data platforms.

I specialize in:

- Microsoft Fabric lakehouse architecture
- Azure Data Factory and metadata-driven ingestion (control tables, parameterized sources and targets)
- Python, PySpark, Spark SQL, and Delta Lake
- Bronze / Silver / Gold medallion architecture, with raw data preserved and every transformation traceable
- Incremental loading, MERGE/upsert logic, and watermark patterns
- Data validation, run logging, monitoring, rerun-safe design, and production support
- Power BI-ready Gold layers, semantic models, and analytics data products
- Git, CI/CD, Dev/Test/Prod promotion, and deployment discipline

What makes my background valuable is that I understand both sides of the modernization journey:

- the legacy SQL Server / SSIS / database systems many companies still rely on
- the modern Fabric / Azure / Databricks lakehouse platforms they are moving toward

---

## 🧭 My Data Engineering Focus

```text
Source Systems
  ↓
Ingestion Frameworks
  ↓
Bronze Raw Landing
  ↓
Silver Cleansed Data
  ↓
Gold Business Models
  ↓
Power BI Semantic Models
  ↓
Trusted Business Reporting
```

I focus on building data platforms that are not just functional, but production-ready:

- reusable
- observable
- validated
- documented
- rerunnable
- governed
- business-aligned

---

## 🧱 Featured Projects

### 🔹 Microsoft Fabric Modern Data Platform

Flagship Commercial Real Estate data engineering project demonstrating how legacy SQL, API, and file-based pipelines can be modernized into a governed Microsoft Fabric lakehouse architecture.

**Key patterns demonstrated:**

- Multi-source SQL-style, REST API, and file ingestion
- Bronze / Silver / Gold medallion architecture
- Python, pandas, PySpark, Delta Lake, and OneLake patterns
- Configuration-driven validation, quarantine, and deduplication
- Power BI-ready star schema and Direct Lake semantic model
- Governed DAX measures and semantic-model validation
- Dependency-aware orchestration, audit logging, and monitoring
- Automated testing with pytest and GitHub Actions
- Dev/Test/Prod release gates, packaging, and rollback planning

👉 [View Project](https://github.com/billpaulwalker/fabric-modern-data-platform)

---

### 🔹 Python REST API Ingestion Framework → Microsoft Fabric Lakehouse  
**Python + GitHub REST API + PySpark + Delta Lake + OneLake + Fabric Data Pipelines**

Reusable, fault-tolerant ingestion framework that incrementally loads GitHub issues through Bronze and Silver layers. It runs locally (raw JSON, Parquet, SQLite run tracking) and in Microsoft Fabric (OneLake, Delta Lake MERGE, notebook orchestrated by a Data pipeline). Verified in a live Fabric workspace: 2,117 Silver rows, one per issue, no duplicates.

**Key patterns demonstrated:**

- Token auth from environment variables or Azure Key Vault, with no committed secrets
- `Link`-header pagination with a max-page guardrail
- Timestamp-based incremental extraction (`since=`) with a watermark overlap window
- Bounded retries with exponential backoff, `Retry-After` support, and rate-limit-aware handling
- Raw JSON Bronze landing → validation with rejected-record quarantine → Silver Delta `MERGE` on a stable key
- Documented same-timestamp upsert policy, so reruns and replays never duplicate data or roll Silver back
- Checkpoint advanced only after a verified Silver commit; recover mode reprocesses Bronze from failed runs
- Run history with final status and failing stage for every execution (SQLite locally, Delta control tables in Fabric)
- Fabric notebook + Data pipeline, an operations runbook, design decisions, and screenshot evidence
- 63 pytest tests, including simulated failure and recovery scenarios, run by GitHub Actions on Ubuntu and Windows

👉 [View Project](https://github.com/billpaulwalker/python-rest-api-fabric-ingestion)

---

### 🔹 Real-Time Lakehouse Pipeline  
**Databricks + PySpark + Delta Lake**

Streaming-first lakehouse project demonstrating modern distributed data engineering patterns.

**Key patterns demonstrated:**

- Databricks lakehouse architecture
- Structured Streaming
- Delta Lake
- Bronze / Silver / Gold pipeline design
- event-driven ingestion concepts
- checkpointing and schema handling
- PySpark transformations

👉 [View Project](https://github.com/billpaulwalker/databricks-realtime-lakehouse-pipeline)

---

### 🔹 Commercial Real Estate Analytics Engineering Platform  
**dbt + SQL + Dimensional Modeling**

Analytics engineering project focused on clean transformation design, testing, and business-ready data marts.

**Key patterns demonstrated:**

- dbt project structure
- staging, intermediate, and mart layers
- star schema modeling
- SQL transformations
- reusable macros
- data quality tests
- CI/CD integration
- commercial real estate reporting model

👉 [View Project](https://github.com/billpaulwalker/commercial-real-estate-dbt-platform)

---

## ⚙️ Core Tech Stack

**Microsoft & Azure:** Microsoft Fabric (Lakehouse, Warehouse, OneLake) · Azure Data Factory · Azure Synapse Analytics · Azure SQL · ADLS Gen2 · Azure Monitor · Power BI · Direct Lake

**Data Engineering:** Python · PySpark · Spark SQL · SQL / T-SQL · pandas · Delta Lake · Databricks · dbt · REST APIs / JSON

**Production Engineering:** Git · GitHub Actions · CI/CD · pytest · Dev/Test/Prod deployment · logging, monitoring & alerting · data quality checks

**Data Modeling & BI:** dimensional modeling · star schema design · semantic models · reporting data marts

---

## 📌 Current Learning & Build Focus

I am continuing to deepen my hands-on work across:

- Microsoft Fabric production patterns
- Python and PySpark for data engineering
- REST API ingestion frameworks
- Azure Data Factory to Fabric modernization
- Databricks lakehouse engineering
- Power BI semantic model readiness
- Git / Azure DevOps deployment practices

---

## 🤝 Let's Connect

- 💼 LinkedIn: https://linkedin.com/in/billpaulwalker
- 📧 Email: billpaulwalker@gmail.com

---

## ⚡ Professional Philosophy

Modern data engineering is not just about moving data.

It is about building trusted, scalable, observable, and business-ready data platforms that help teams make better decisions.
