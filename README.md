# Hi, I'm Sathyadeva Vemula 👋

<p align="center">
  <b>Data Engineer • Analytics Engineer • AI Automation Builder</b>
</p>

<p align="center">
  Building production-grade data platforms and intelligent automation systems across
  <b>Snowflake, Databricks, dbt, Azure, Python, and AI workflows.</b>
</p>

<p align="center">

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge\&logo=snowflake\&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge\&logo=databricks\&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge\&logo=dbt\&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge\&logo=microsoftazure\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge\&logo=apachespark\&logoColor=white)

![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge\&logo=apacheairflow\&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge\&logo=apachekafka\&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge\&logo=n8n\&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge\&logo=openai\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge\&logo=postgresql\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge\&logo=azuredevops\&logoColor=white)

</p>

---

## 👨‍💻 About Me

I'm a **Data Engineer and Analyst with 4+ years of experience** building production data platforms across **investment research, foodservice distribution, supply chain, and enterprise analytics**.

My work sits across the complete data lifecycle:

**Ingestion → Transformation → Data Quality → Governance → Analytics → AI Automation**

At **Morningstar**, I build Snowflake and dbt pipelines supporting Managed Investment Data and Direct Platform products, processing **40M+ financial records daily** while contributing to approximately **$150K in annual Snowflake compute savings**.

At **US Foods**, I helped build a Databricks-based analytics platform spanning procurement, inventory, fulfillment, and distribution—reducing critical pipeline runtimes from **4+ hours to under 90 minutes** and replacing fragmented spreadsheet reporting with governed analytics products.

Alongside data engineering, I build **AI-powered business automation systems** using **n8n, OpenAI APIs, PostgreSQL, REST APIs, webhooks, Docker, and human-in-the-loop workflow patterns**.

I enjoy engineering systems that are not only technically scalable, but also make analytics and business operations **faster, more reliable, and easier to trust**.

---

## 📊 Selected Impact

| Area                              |                         Impact |
| --------------------------------- | -----------------------------: |
| Financial records processed       |                 **40M+ daily** |
| Snowflake compute savings         |            **~$150K annually** |
| Snowflake partition scans         |             **60%+ reduction** |
| US Foods pipeline runtime         |          **4+ hrs → <90 mins** |
| Data quality coverage             |             **30+ dbt models** |
| Suspect records quarantined       |                **~3,000/week** |
| Production Airflow schedules      |      **12 critical pipelines** |
| Power BI dashboards built         |         **10+ at Morningstar** |
| Legacy Excel reports consolidated | **12 → 2 governed dashboards** |
| Business KPIs standardized        |                **80+ metrics** |
| Legacy data profiled              |                  **80M+ rows** |
| SQL validation framework          |   **40+ automated test cases** |

---

# 💼 Professional Experience

## Morningstar

### Data Engineer — Managed Investment Data (MID), Direct Platform

**Oct 2024 – Present | Chicago, IL**

* Designed and deployed **Snowflake + dbt ELT pipelines** using a Bronze-Silver-Gold architecture for fund portfolio, NAV, holdings, security master, and investment data.

* Built the core **Silver transformation layer using dbt incremental models**, replacing expensive full-table processing with record-level merge strategies.

* Support pipelines processing **40M+ financial records per day** feeding Morningstar Direct Platform products.

* Contributed to approximately **$150K in annual Snowflake compute savings** by right-sizing four XL warehouses and optimizing frequently queried fact tables.

* Added clustering strategies that reduced partition scans by **60%+** on high-volume analytical workloads.

* Implemented **dbt data quality tests across 30+ production models**, including uniqueness, null, accepted-value, and relationship validations.

* Built **Databricks Delta Live Tables pipelines** for semi-structured financial and third-party market data ingestion.

* Manage **12 critical Apache Airflow production schedules**, DAG dependencies, SLA thresholds, and failure alerts.

* Built **10+ Power BI dashboards** with optimized DAX and incremental refresh, reducing average load times from **40+ seconds to under 8 seconds**.

* Built Git-backed **Azure DevOps CI/CD pipelines** for Power BI promotion across development, QA, and production with automated RLS validation gates.

**Stack**

`Snowflake` `dbt` `SQL` `Databricks` `Delta Live Tables` `Apache Airflow` `Power BI` `DAX` `Azure DevOps` `CI/CD`

---

## US Foods

### Data Analytics Engineer — Enterprise Data & Analytics

**Jan 2023 – Oct 2024 | Rosemont, IL**

* Helped design and build a production analytics platform on **Azure Databricks and Delta Lake** supporting procurement, inventory, fulfillment, sales, and distribution operations.

* Built ingestion pipelines across **5 operational source systems** using Bronze-Silver-Gold data architecture.

* Developed reusable and parameterized **Azure Data Factory ingestion templates**, reducing new source onboarding from **2–3 engineering days to approximately half a day**.

* Built a **Kafka + Spark Streaming pipeline** for Warehouse Management System inventory events, enabling intraday stock movement visibility.

* Applied partitioning and Spark caching strategies to resolve shuffle-heavy workloads and reduce production pipeline runtime from **4+ hours to under 90 minutes**.

* Implemented **Great Expectations** checks across 15+ ingestion jobs for schema drift, null violations, referential integrity, and business-rule validation.

* Quarantined approximately **3,000 suspect records per week** before they reached downstream inventory and fulfillment reporting.

* Implemented **Azure DevOps CI/CD** for Databricks notebooks and pipelines with environment-specific configuration and automated rollback controls.

* Reduced production incidents from **2–3 per month to near zero** through automated validation and deployment practices.

* Consolidated **12 separately maintained Excel reports into 2 certified Power BI dashboards** backed by governed semantic models and Row-Level Security.

* Built a standardized business metrics dictionary covering **80+ KPIs** across purchasing, fulfillment, inventory, and distribution.

**Stack**

`Azure Databricks` `Delta Lake` `PySpark` `Azure Data Factory` `ADLS Gen2` `Apache Kafka` `Spark Streaming` `Great Expectations` `Power BI` `Azure DevOps`

---

## Cognizant Technology Solutions

### Data Analyst

**Aug 2021 – Aug 2022 | Hyderabad, India**

* Built **Azure Data Factory pipelines** to ingest transactional data from multiple databases into ADLS Gen2.

* Developed PySpark notebooks in Databricks for profiling, cleansing, and standardizing raw enterprise datasets.

* Profiled and cleaned **80M+ rows across 5 legacy datasets**, resolving duplicate keys, schema inconsistencies, and malformed records.

* Built **IBM DataStage ETL jobs** for IBM DB2 source systems and optimized long-running extraction queries through indexing and SQL restructuring.

* Developed a reusable **SQL data validation framework with 40+ test cases** covering nulls, referential integrity, reconciliation, and business rules.

* Rebuilt **5 legacy SSRS reports in Power BI**, correcting recurring business-logic discrepancies and reducing reporting delivery from 3 days to same day.

* Partnered with onshore analysts to translate business requirements into SQL specifications and reduce downstream UAT rework.

**Stack**

`Azure Data Factory` `ADLS Gen2` `Databricks` `PySpark` `Spark SQL` `IBM DataStage` `IBM DB2` `SQL` `SSRS` `Power BI`

---

# 🤖 Featured AI Project

## AI Revenue Intelligence & Sales Operations Automation Platform

Built an **event-driven AI sales and revenue automation platform** designed to automate repetitive work across the customer lifecycle while preserving human review where it matters.

### Architecture

```text
Lead Capture
      ↓
Lead Validation
      ↓
PostgreSQL
      ↓
AI Qualification
      ↓
Personalized Outreach
      ↓
Gmail API
      ↓
Customer Response
      ↓
AI Intent + Objection Classification
      ↓
Structured JSON
      ↓
Workflow Routing
      ↓
Meeting / Follow-up / Human Review
      ↓
Revenue Analytics
```

### What it does

* Captures lead events through **REST APIs and webhooks**
* Validates and stores lead information in **PostgreSQL**
* Generates personalized customer outreach
* Sends communication through **Gmail API**
* Extracts only the newest customer response
* Uses AI to classify **intent and objections**
* Converts unstructured responses into structured JSON
* Routes opportunities through event-driven workflows
* Maintains persistent workflow state
* Tracks lifecycle stages from lead → meeting → proposal → payment → onboarding
* Supports retry logic, idempotency, OAuth controls, and error handling
* Uses approval gates for sensitive or low-confidence actions
* Creates an auditable layer for funnel and operational analytics

### Analytics Layer

Designed the platform to support metrics including:

* Lead conversion rate
* Response rate
* Meeting conversion
* Sales cycle time
* Follow-up effectiveness
* Human-intervention rate
* Lead-source performance
* Funnel-stage conversion

**Stack**

`n8n` `OpenAI API` `PostgreSQL` `Gmail API` `Docker` `REST APIs` `Webhooks` `JSON` `Prompt Engineering` `Event-Driven Workflows`

---

# 🚀 Data Engineering Projects

## SEC Financial Data Pipeline & Investment Analytics Platform

Built an investment analytics pipeline using public **SEC EDGAR XBRL financial data**.

* Ingested company facts for **500+ publicly traded companies**
* Processed approximately **3–4M financial fact records**
* Landed raw records into a Bronze Delta Lake layer on ADLS Gen2
* Used PySpark to standardize fields such as revenue, EPS, and debt ratios
* Built incremental dbt models using filing date as the processing watermark
* Calculated quarter-over-quarter growth and trailing-twelve-month metrics
* Created a Gold analytical layer
* Connected the model to Power BI
* Built DAX measures supporting sector benchmarking and approximately **20 quarters of company financial history**

**Stack**

`SEC EDGAR API` `XBRL` `Azure Databricks` `Delta Lake` `ADLS Gen2` `PySpark` `dbt` `Power BI` `DAX`

---

## Chicago Transit Authority Operational Analytics Lakehouse

Built a lakehouse for historical and real-time public transportation analytics.

* Ingested historical CTA rail data and real-time bus event feeds
* Used **Databricks Auto Loader** for scalable Bronze-layer ingestion
* Resolved duplicate records generated by API retries
* Corrected UTC/local timezone inconsistencies
* Built route-level ridership and station peak-load aggregations
* Applied **Z-Ordering** to improve filtered analytical workloads
* Built a Power BI reporting layer
* Implemented **Row-Level Security**
* Scheduled production processing through Databricks Workflows

**Stack**

`Azure Databricks` `Auto Loader` `Delta Lake` `PySpark` `Databricks Workflows` `Power BI` `RLS`

---

# 🛠️ Technical Stack

### Languages & Query

`Python` `PySpark` `SQL` `Snowflake SQL` `T-SQL` `Spark SQL` `DAX` `Power Query`

### Cloud & Data Platforms

`Snowflake AI Data Cloud` `Azure Databricks` `Microsoft Azure` `Delta Lake` `ADLS Gen2` `Azure Synapse Analytics`

### Data Engineering

`Azure Data Factory` `Apache Airflow` `Apache Kafka` `Spark Streaming` `Databricks Delta Live Tables` `Auto Loader`

### Transformation & Modeling

`dbt` `ELT` `ETL` `Medallion Architecture` `Star Schema` `SCD Type I/II` `OBT` `Kimball Dimensional Modeling`

### Data Quality & Governance

`Great Expectations` `dbt Tests` `Unity Catalog` `Data Lineage` `RBAC` `Schema Validation`

### AI & Automation

`n8n` `OpenAI API` `Prompt Engineering` `RAG Agents` `REST APIs` `Webhooks` `Gmail API` `PostgreSQL` `Docker` `Event-Driven Workflows` `Workflow State Management`

### Business Intelligence

`Power BI` `DAX` `Power Query` `Incremental Refresh` `Row-Level Security` `SSRS` `Semantic Modeling`

### DevOps

`Azure DevOps` `Git` `CI/CD` `GitHub` `GitHub Copilot`

### Enterprise ETL

`IBM DataStage` `IBM DB2`

---

# 🧠 What I Like Building

I'm particularly interested in systems where **Data Engineering and AI meet**:

* Production-grade ELT/ETL platforms
* Lakehouse and warehouse architectures
* Reliable batch and streaming pipelines
* Analytics-ready semantic layers
* Automated data quality and governance
* AI-powered workflow automation
* Event-driven business processes
* Structured extraction from unstructured information
* RAG and data-aware AI systems
* Human-in-the-loop AI workflows
* Decision-support platforms
* Observable and auditable AI automation

The goal isn't just to add AI to a workflow.

It's to build systems where **good data, reliable engineering, automation, and AI work together in production.**

---

# 🎓 Education

### Wright State University

**Master of Science in Computer Science**
Dayton, Ohio | Aug 2022 – Apr 2024
**GPA: 3.5 / 4.0**

### Jawaharlal Nehru Technological University

**Bachelor of Technology in Information Technology**
Hyderabad, India | Jul 2018 – May 2022
**GPA: 8.31 / 10**

---

# 🌐 Connect With Me

<p align="left">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sathyadeva_Vemula-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/sathyadeva-vemula/)

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit_Site-000000?style=for-the-badge\&logo=githubpages\&logoColor=white)](https://sathyadevavemula.github.io/)

[![Email](https://img.shields.io/badge/Email-sathyadeva.vemula%40gmail.com-EA4335?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:sathyadeva.vemula@gmail.com)

</p>

---

<p align="center">
  <b>Data Engineering × Analytics × AI Automation</b>
</p>

<p align="center">
  Building reliable data foundations — then making them intelligent.
</p>
