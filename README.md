# DP-700-Microsoft-Fabric-Data-Engineer-Associate
# DP-700 — Microsoft Fabric Data Engineer Associate
### Sequential Study Guide · Microsoft Learn Official Materials · Updated April 2026
> **Pass score:** 700/1000 · **3 equal domains (30–35% each)** · **Intermediate level**

---

## Exam Overview

As a Fabric Data Engineer, you should have subject matter expertise with data loading patterns, data architectures, and orchestration processes. This exam tests your ability to:

- Ingest and transform data
- Secure and manage an analytics solution
- Monitor and optimize an analytics solution

You should be skilled at manipulating and transforming data by using SQL, PySpark, and KQL, and will work closely with analytics engineers, architects, analysts, and administrators.

### Prerequisites — What you need before starting

| | |
|---|---|
| 🔹 | Experience with SQL, PySpark, or Kusto Query Language (KQL) |
| 🔹 | Background in data extraction, transformation, and loading (ETL) |
| 🔹 | Familiarity with data architectures and orchestration processes |
| 🔹 | Experience with enterprise-scale data analytics solutions |

---

## Exam Weight Distribution

| Domain | Topic | Weight |
|--------|--------|--------|
| **Domain 1** | Implement and manage an analytics solution | 30–35% |
| **Domain 2** | Ingest and transform data | 30–35% |
| **Domain 3** | Monitor and optimize an analytics solution | 30–35% |

---

## Step 1 — Foundations: Get started with Microsoft Fabric

**Level:** Beginner · **10 modules** · Start here even if you have some Fabric experience.
**URL:** `learn.microsoft.com/training/paths/get-started-fabric/`

| Module | What you learn |
|--------|---------------|
| **Intro to end-to-end analytics** | Overview of the Fabric platform: what it is, how it works, and its end-to-end analytics capabilities across all workloads. |
| **Get started with lakehouses** | Lakehouse architecture: combines data lake storage flexibility with data warehouse analytics on a single SaaS platform. |
| **Use Apache Spark** | Spark clusters in Fabric for large-scale data processing and analysis within a lakehouse. |
| **Work with Delta Lake tables** | Delta format tables for ACID transactions, time travel, and advanced analytics patterns in the lakehouse. |
| **Orchestrate with pipelines** | Data Factory pipelines for orchestrating data ingestion and transformation tasks. |
| **Ingest with Dataflows Gen2** | Power Query Online for visual, no-code multi-step data ingestion and transformation. |
| **Get started with data warehouses** | Relational data warehouses in Fabric using T-SQL for structured analytics workloads. |
| **Real-Time Intelligence intro** | Ingesting, querying, and processing real-time data streams using KQL and Eventhouse. |
| **Data Science in Fabric** | Managing notebooks, experiments, and ML models within the Fabric ecosystem. |
| **Administer Fabric environment** | Configure features and manage access as an administrator on the SaaS platform. |

---

## Step 2 — Implement a Lakehouse with Microsoft Fabric

**Level:** Intermediate · **7 modules** · Prerequisite: Step 1 complete.
**URL:** `learn.microsoft.com/training/paths/implement-lakehouse-microsoft-fabric/`

| Module | What you learn |
|--------|---------------|
| **Intro to end-to-end analytics** | Revisit Fabric architecture from an implementation lens; understand workload integration. |
| **Get started with lakehouses** | Create and manage lakehouses; understand storage layers and SQL analytics endpoints. |
| **Use Apache Spark** | Process and analyze data at scale using Spark notebooks with PySpark. |
| **Work with Delta Lake tables** | Build reliable, queryable Delta tables; use V-Order compaction and time travel. |
| **Ingest with Dataflows Gen2** | Visually ingest and transform multi-source data into the lakehouse using Power Query. |
| **Orchestrate processes & pipelines** | Build pipelines with triggers, parameters, and dynamic expressions for orchestration. |
| **Medallion architecture design** | Organize data across Bronze → Silver → Gold layers for optimized, incremental analytics. |

---

## Step 3 — Ingest Data with Microsoft Fabric

**Level:** Intermediate · **6 modules** · Prerequisite: Steps 1–2 complete.
**URL:** `learn.microsoft.com/training/paths/ingest-data-with-microsoft-fabric/`

| Module | What you learn |
|--------|---------------|
| **Dataflows Gen2** | Multi-step visual ingestion and transformation using Power Query Online; schedule and publish. |
| **Pipelines & orchestration** | Design full and incremental load pipelines; implement event-based triggers and scheduling. |
| **Apache Spark in Fabric** | PySpark for large-scale batch transformation, aggregation, denormalization, and deduplication. |
| **Real-Time Intelligence intro** | Ingest and query streaming data using KQL, Eventhouse, and Real-Time hub. |
| **Real-time Eventstreams** | No-code ingestion and transformation of real-time events from multiple sources with routing. |
| **Work with Eventhouse** | Scalable store for real-time data; KQL queries, windowing functions, and OneLake shortcuts. |

---

## Step 4 — Manage a Microsoft Fabric Environment

**Level:** Intermediate · **4 modules** · Prerequisite: Steps 1–3 complete.
**URL:** `learn.microsoft.com/training/paths/manage-microsoft-fabric-environment/`

| Module | What you learn |
|--------|---------------|
| **CI/CD in Microsoft Fabric** | Git integration and deployment pipelines for version control, database projects, and lifecycle management. |
| **Monitor Fabric activities** | Monitoring Hub, configure alerts, and Activator for detecting patterns in streaming data. |
| **Secure data access** | Multi-layer security: workspace, item, row, column, object, folder/file, and OneLake security. |
| **Administer Fabric environment** | Configure tenant settings, manage capacity, domains, workspace settings, and audit logs. |

---

## Step 5 — Complete Exam Skill Checklist (All 3 Domains)

Each domain carries equal weight. Use this as a revision checklist before your exam.

### Domain 1: Implement & Manage an Analytics Solution (30–35%)

**Configure Microsoft Fabric workspace settings**
- Configure Spark workspace settings
- Configure domain workspace settings
- Configure OneLake workspace settings
- Configure Dataflows Gen2 workspace settings

**Implement lifecycle management in Fabric**
- Configure version control (Git integration)
- Implement database projects
- Create and configure deployment pipelines

**Configure security and governance**
- Implement workspace-level access controls
- Implement item-level access controls
- Implement row, column, object, and folder/file-level access controls
- Implement dynamic data masking
- Apply sensitivity labels to items
- Endorse items
- Implement and use Microsoft Fabric audit logs
- Configure and implement OneLake security

**Orchestrate processes**
- Choose between Dataflow Gen2, a pipeline, and a notebook
- Design and implement schedules and event-based triggers
- Implement orchestration patterns with notebooks and pipelines, including parameters and dynamic expressions

---

### Domain 2: Ingest & Transform Data (30–35%)

**Design and implement loading patterns**
- Design and implement full and incremental data loads
- Prepare data for loading into a dimensional model
- Design and implement a loading pattern for streaming data

**Ingest and transform batch data**
- Choose an appropriate data store
- Choose between Dataflows Gen2, notebooks, KQL, and T-SQL for data transformation
- Create and manage OneLake shortcuts
- Implement mirroring
- Ingest data by using pipelines
- Transform data by using PySpark, SQL, and KQL
- Denormalize data
- Group and aggregate data
- Handle duplicate, missing, and late-arriving data

**Ingest and transform streaming data**
- Choose an appropriate streaming engine
- Choose between native tables and OneLake shortcuts in Real-Time Intelligence
- Choose between Query acceleration and standard OneLake shortcuts in RTI
- Process data by using Eventstreams
- Process data by using Spark structured streaming
- Process data by using KQL
- Create windowing functions

---

### Domain 3: Monitor & Optimize an Analytics Solution (30–35%)

**Monitor Fabric items**
- Monitor data ingestion
- Monitor data transformation
- Monitor semantic model refresh
- Configure alerts

**Identify and resolve errors**
- Identify and resolve pipeline errors
- Identify and resolve Dataflow Gen2 errors
- Identify and resolve notebook errors
- Identify and resolve Eventhouse errors
- Identify and resolve Eventstream errors
- Identify and resolve T-SQL errors
- Identify and resolve OneLake shortcut errors

**Optimize performance**
- Optimize a Lakehouse table
- Optimize a pipeline
- Optimize a data warehouse
- Optimize Eventstreams and Eventhouses
- Optimize Spark performance
- Optimize query performance

---

## Step 6 — Key Technologies to Master

| Technology | Key usage in DP-700 |
|------------|---------------------|
| **PySpark** | Batch transforms, large-scale data processing, aggregation, Spark structured streaming for real-time |
| **T-SQL** | Warehouse queries, transformations, row-level & column-level security, performance optimization |
| **KQL** | Real-time queries, Eventhouse analytics, windowing functions, data exploration |
| **Delta Lake** | ACID transactions, time travel, V-Order compaction, medallion architecture (Bronze/Silver/Gold) |
| **Dataflows Gen2** | No-code/low-code visual data ingestion and transformation using Power Query Online |
| **Eventstreams** | Real-time event ingestion, routing, filtering, and transformation from multiple sources |
| **Pipelines** | Orchestration of data movement, scheduling, event triggers, parameters, and dynamic expressions |
| **OneLake** | Unified storage layer; shortcuts, mirroring, folder/file-level security, cross-workspace access |

---

## Exam Preparation Tips

> **Free practice assessment** — available at learn.microsoft.com. Take it before and after studying to measure gaps.

- Each module includes hands-on exercises. Use a free Microsoft Fabric trial to complete labs.
- Score of **700 out of 1000** required to pass. Most questions are scenario-based, not purely factual.
- Exam is typically **45–65 questions**; scenario questions test judgment (e.g., when to use Dataflow Gen2 vs pipeline vs notebook).
- Certification **expires after 1 year** — renew free via an online assessment on Microsoft Learn.
- All three domains carry **equal weight** — do not skip monitoring & optimization.
- Focus on real-world decision-making: choosing tools, troubleshooting errors, and optimizing performance.

---

## Official Resources & Links

| Resource | Link |
|----------|------|
| Exam & certification page | `learn.microsoft.com/credentials/certifications/fabric-data-engineer-associate/` |
| Official study guide | `learn.microsoft.com/credentials/certifications/resources/study-guides/dp-700` |
| Free practice assessment | Search "DP-700 practice assessment" on `learn.microsoft.com` |
| Fabric documentation | `learn.microsoft.com/fabric/` |
| Data Engineering overview | `learn.microsoft.com/fabric/data-engineering/data-engineering-overview` |
| Community forum | `techcommunity.microsoft.com` → Analytics on Azure |
| Exam sandbox (preview UI) | `aka.ms/examdemo` |

---

*This document was generated from official Microsoft Learn materials. Content reflects exam skills measured as of April 20, 2026.*
