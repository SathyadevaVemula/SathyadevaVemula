# Hi, I'm Sathyadeva Vemula

![Snowflake](https://img.shields.io/badge/Snowflake-56B9EB?style=flat&logo=snowflake&logoColor=white)
![Azure Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-EDA32D?style=flat&logo=powerbi&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

<p align="center">
  <b>Data Engineer with 4+ years building production pipelines on Snowflake, dbt, and Azure Databricks</b>
</p>

---

## About Me

Data engineer with 4+ years of production experience across financial data and enterprise supply chain platforms. I build data infrastructure that analytics teams can rely on without needing engineering involved in every step.

At **Morningstar**, I design and maintain ELT pipelines processing 40M+ daily financial records on Snowflake and dbt, and identified $150K in annual compute savings through systematic warehouse profiling and right-sizing. At **US Foods**, I built the company's retail analytics platform from scratch on Azure Databricks, replacing a fragmented Excel reporting environment with governed, production-grade data products across purchasing, inventory, and sales operations.

I work across the full data stack: batch and real-time ingestion with ADF, Kafka, and Spark Streaming; layered transformation with dbt and Delta Live Tables; data quality with Great Expectations and dbt tests; governance through Unity Catalog and RBAC; and reporting delivery through CI/CD-deployed Power BI pipelines.

---

## Impact

| Metric | Result |
|---|---|
| Daily records processed in production | 40M+ |
| Annual Snowflake compute savings identified | $150K |
| Pipeline runtime reduction (US Foods) | 4+ hours to under 90 minutes |
| Suspect records quarantined weekly | 3,000+ |
| Pipeline reliability | 99%+ |
| Analyst onboarding time reduction | 2 weeks to 3 days |

---

## Work Experience

**Data Engineer — Morningstar** `Oct 2024 – Present`

Part of a 5-person data engineering team serving equity research, fixed income, and fund data product lines for 30+ analysts. Built Snowflake and dbt ELT pipelines processing 40M+ daily records. Replaced full-table scans with is_incremental() merge logic, cutting daily transformation runtime from 3+ hours to under 45 minutes. Implemented dbt tests across 30+ core models. Managed 12 production pipeline schedules in Apache Airflow. Built 10+ Power BI dashboards and established Git-backed CI/CD deployment pipelines in Azure DevOps. Mentored 2 junior engineers on dbt model structure and Snowflake optimization patterns.

`Snowflake` `dbt` `Delta Live Tables` `Apache Airflow` `Unity Catalog` `Power BI` `Azure DevOps`

---

**Data Analytics Engineer — US Foods** `Jan 2023 – Oct 2024`

Part of a 4-person analytics engineering team at one of the largest US food distributors. Built the company's retail analytics platform from scratch on Azure Databricks and Delta Lake, covering ingestion from 5 operational source systems through Bronze-Silver-Gold layers to 7 Power BI dashboards. Built a Kafka-based real-time ingestion stream for WMS inventory events using Spark Streaming, giving procurement intraday stock visibility for the first time. Implemented Great Expectations data quality checks across 15+ ingestion jobs. Reduced production incidents from 2-3 per month to near zero through CI/CD automation.

`Azure Databricks` `Delta Lake` `Apache Kafka` `Spark Streaming` `Great Expectations` `dbt` `ADF` `ADLS Gen2`

---

**Data Analyst — Cognizant Technology Solutions** `Aug 2021 – Aug 2022`

Part of an 8-member offshore delivery team supporting a North American retail client's migration from on-premises SQL Server to Azure. Built ADF ingestion pipelines and PySpark notebooks to profile and standardize 80M+ rows across 5 legacy datasets before loading into Snowflake. Built a SQL validation framework with 40+ test cases adopted as team-wide standards.

`PySpark` `ADF` `ADLS Gen2` `Snowflake` `Power BI` `SQL`

---

## Academic Projects

**SEC Financial Data Pipeline and Investment Analytics Platform**

Ingested raw XBRL-tagged financial filings from the SEC EDGAR company_facts API across 500+ publicly traded companies into a Bronze Delta Lake layer on ADLS Gen2. Wrote PySpark to parse and normalize financial fields across 3-4M fact records, resolving inconsistent tagging conventions across filers. Built dbt incremental models using filing date as the watermark for quarter-over-quarter growth rates and trailing twelve-month rolling metrics at the Gold layer. Connected to a Power BI semantic model covering 20 quarters of financials per company with DAX measures for trend analysis and sector benchmarking.

`SEC EDGAR API` `Delta Lake` `PySpark` `dbt` `ADLS Gen2` `Power BI` `DAX`

---

**Hospital Readmission Risk Analytics — CMS Medicare Data**

Ingested 5 annual releases of CMS Hospital Compare data from data.cms.gov into a Bronze layer with intake metadata, covering readmission rates, complication measures, and HCAHPS scores across 4,000+ hospitals nationwide. Resolved schema drift across 5 annual CMS releases in PySpark, standardizing all hospital identifiers to the CMS Certification Number as the stable join key. Handled three distinct CMS suppression types in the Silver transformation, each requiring a different null treatment strategy. Built dbt Gold layer models joining readmission rates against CMS national benchmarks and delivered a Power BI dashboard with geospatial mapping and five-year trend views across roughly 400K measure-hospital-year records.

`CMS data.gov` `PySpark` `dbt` `Delta Lake` `Power BI` `Geospatial`

---

**Chicago Transit Authority Operational Analytics Lakehouse**

Ingested 40M+ historical CTA rail records from the Chicago Data Portal and real-time bus event feeds from the CTA Bus Tracker API into a Bronze Delta Lake layer using Auto Loader on Azure Databricks. Resolved three recurring data quality issues in PySpark: missing stop sequences on rerouted trips, duplicate records from API retries during service disruptions, and timezone mismatches between UTC API timestamps and local service schedules. Built a Gold aggregation layer with daily and weekly route-level ridership patterns, applying Z-ordering on station ID and service date for fast filtered reads. Delivered a Power BI reporting layer with Row-Level Security by service district.

`Auto Loader` `Azure Databricks` `Delta Lake` `PySpark` `Z-Ordering` `Power BI` `RLS`

---

**FlowSync HR — HR Analytics Platform**

Built an HR analytics platform on Databricks ingesting engagement scores, workload signals, and sentiment data through automated Python pipelines. Designed Delta Lake table architecture to support historical trend analysis across HR dimensions. Built a Power BI reporting layer with micro-survey KPIs and sentiment dashboards with automated refresh pipelines. Finalist in the Base44 $10K Challenge.

`Databricks` `Delta Lake` `Python` `Power BI`

---

## Tech Stack

**Languages:** Python, PySpark, Spark SQL, T-SQL, Snowflake SQL, DAX

**Data Platforms:** Snowflake, Azure Databricks, Delta Lake, ADLS Gen2, Azure Synapse

**Ingestion and Streaming:** Azure Data Factory, Apache Kafka, Spark Streaming, Auto Loader

**Orchestration:** Apache Airflow, Databricks Workflows, Azure Data Factory

**Modeling and Transformation:** dbt, Delta Live Tables, SCD Type I/II, Star Schema, ELT/ETL

**Data Quality:** Great Expectations, dbt Tests, Schema Validation, Unity Catalog

**BI and Reporting:** Power BI, DAX, Power Query, SSRS, Semantic Model Design

**DevOps and Governance:** Azure DevOps, GitHub Actions, CI/CD, Git, Unity Catalog, Microsoft Purview, RBAC

---

## Certifications

- Coursera / IBM: Data Visualization using Python, Advanced SQL for Data Engineering
- Snowflake: Snowflake for Data Engineering
- Microsoft: Power BI Data Analyst, Azure Fundamentals (AZ-900)
- Databricks: Lakehouse Fundamentals
- dbt Labs: dbt Fundamentals
- Smart India Hackathon 2020 Finalist — Ministry of Women and Child Development, Government of India

---

## Currently Focused On

- Apache Iceberg and open table format interoperability
- Advanced dbt testing patterns and data contracts
- DataOps and observability at scale
- Machine learning integration with data engineering pipelines

---

## Connect

- Email: sathyadeva.vemula@gmail.com
- LinkedIn: https://www.linkedin.com/in/sathyadeva-vemula/
- Portfolio: https://sathyadevavemula.github.io/

---

When I'm not building data platforms, I'm hiking or picking up a new sport. Always optimizing something, even outside of work.
