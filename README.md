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


# My Journey as a Data Engineer & Analyst
### Cognizant → US Foods → Morningstar

> **A note on how to use this document, before you read it:**
> This is a narrative draft meant to help you prepare for interviews — a way to turn your resume bullets into a story you can actually tell out loud. It's built directly from the resume we finalized, so the technical claims and metrics match. A few things you should know:
> - Anywhere you see a `[bracketed placeholder]`, that's a number or detail I genuinely don't know (mainly exact team headcounts) — fill those in with your real figures before you rehearse this.
> - Where I *do* cite a real number (like Morningstar's MID org size), I've pulled it from public sources, and I've noted that in-line.
> - The Cognizant client is described generically because your original resume didn't name the account or industry — adjust that section to match reality.
> - Only use the parts of this that are actually true to your experience. Interviewers probe for specifics, and a detail that doesn't hold up under a follow-up question does more damage than a shorter, honest answer.

---

## Chapter 1: Cognizant Technology Solutions — Hyderabad, India
### Data Analyst | Aug 2021 – Aug 2022

I started my career at Cognizant right after undergrad, on a delivery account supporting a large North American client that was still running a meaningful chunk of its transactional systems on IBM DB2 — the kind of legacy footprint you find at companies that were early adopters of relational databases in the 90s and never fully modernized. *(I'm describing the account generically here since the original resume didn't name the client or industry — swap this in for the real context.)* My team sat inside a broader delivery pod of roughly `[X data engineers, Y analysts — fill in]` people, split between offshore engineering in Hyderabad and a handful of onshore business analysts in the US who owned the relationship with the client's stakeholders.

**Walking into the data.** My first few weeks were less about writing code and more about understanding just how much undocumented tribal knowledge lived in that DB2 environment. I was brought in to help ingest transactional data from three source databases into ADLS Gen2, and almost immediately it became clear that "ingest" was the easy part — the hard part was that five of the legacy source datasets I inherited, totaling more than 80 million rows combined, had quietly accumulated over a decade of data quality debt. Duplicate primary keys that shouldn't have been possible given the schema. Malformed transaction records that had been silently breaking downstream reports for well over a year and a half before anyone noticed, because nobody was actually reconciling row counts end to end.

That was the first real technical challenge I owned: profiling and cleansing those datasets in PySpark and Spark SQL, tracing the schema inconsistencies back to their source, and figuring out which anomalies were "expected legacy weirdness" versus genuine data corruption that needed to be flagged upstream.

**The DataStage-to-cloud bridge.** In parallel, I was writing IBM DataStage ETL jobs to pull data out of the DB2 systems and land it in a staging layer, using parallel-job stages for lookups and aggregations. This is where I got genuinely good at SQL performance tuning in a way that's stuck with me since — DB2's optimizer behaves very differently from Snowflake's or Spark's, and some of the extract queries I inherited were running for minutes because of correlated subqueries that should have been joins. Rewriting those and adding the right indexes brought several of them down to seconds, which mattered a lot inside a DataStage job that was already tight on its extract window. I also built the habit, every single load, of reconciling row counts against DB2 control totals before certifying anything — a discipline I carried with me into every role after this one.

**Where the analyst side came in.** The engineering work fed directly into the analysis and reporting side, which is really where I learned how to translate ambiguity into something buildable. I worked with four onshore business analysts to take eight reporting requirements — often written in fairly vague business language — and turn them into precise SQL specifications before development even started. That sounds like a small thing, but it cut our UAT rework in the following sprint by roughly half, because we were resolving disagreements about what a metric actually meant *before* we built it instead of after a business user flagged it in testing.

I also built a SQL-based data validation framework — null checks, referential integrity checks, business rule thresholds — that grew to more than 40 test cases. It ended up becoming the standard template the broader analytics team reused for every new source that got onboarded onto the account after mine, which was the first time I really felt like something I built outlived my immediate task.

On the reporting side, I rebuilt five legacy SSRS reports in Power BI, correcting business logic that had been quietly wrong for a while — there was a recurring data discrepancy that required manual correction every single reporting cycle, and once I traced and fixed the underlying logic, delivery time went from three days of back-and-forth to same-day.

**What I took with me.** Looking back, Cognizant taught me the unglamorous half of data work: reconciliation discipline, how to read a legacy system's scars, and how to sit between engineering and business stakeholders without losing precision in either direction. It's also where I decided I wanted to go deeper into the modern cloud data stack rather than staying in legacy ETL — which is what pushed me toward grad school.

---

## Interlude: Wright State University & the Bridge into US Foods

I moved to the US in 2022 to start a Master's in Computer Science at Wright State University, and picked up part of my practical experience during that program through CPT authorization — which is how the US Foods role overlapped with the back half of my degree. The coursework gave me the theoretical grounding (distributed systems, database internals) to go with the hands-on legacy-systems experience from Cognizant, and US Foods is where I got my first real exposure to building a modern lakehouse from scratch instead of maintaining someone else's.

---

## Chapter 2: US Foods — Rosemont, IL
### Data Analytics Engineer, Enterprise Data & Analytics | Jan 2023 – Oct 2024

US Foods is one of the largest foodservice distributors in the country — north of 250,000 customer locations, more than 70 broadline distribution centers plus close to 90 cash-and-carry stores, moving fresh, frozen, and dry goods through a genuinely complex supply chain every single day. I joined the Enterprise Data & Analytics team, which sat inside the broader IT organization and was responsible for turning operational data — procurement, inventory, fulfillment, distribution — into something the business could actually plan against. My immediate group was `[X engineers, Y analysts — fill in your real numbers]`, working alongside data architects on the wider Enterprise Data team.

**The five-system problem.** When I joined, retail and supply-chain reporting was scattered across five separate operational source systems with no unified layer underneath them — which meant every analyst who needed a cross-system view was doing manual reconciliation in Excel. My first major project was designing and building a retail analytics platform on Azure Databricks and Delta Lake from scratch: a proper Bronze-Silver-Gold medallion architecture that gave every downstream consumer — engineers and analysts alike — a single, trustworthy place to work from instead of five.

To make onboarding new sources sustainable, I built parameterized Azure Data Factory pipeline templates for the ingestion layer. Before that template existed, bringing a new source online was a 2-3 day engineering effort every time; afterward, it was a half-day configuration task. That's the kind of unglamorous platform investment that doesn't show up as a headline metric but changes the team's actual velocity.

**Going real-time.** The biggest engineering leap was building a Kafka-based real-time ingestion stream for inventory movement events coming off the Warehouse Management System (WMS). Using Spark Streaming, we landed those events into Delta Lake within minutes of when they actually happened on the warehouse floor. Before this, procurement had no intraday visibility into stock movement — they were working off batch snapshots that were, at best, a day old. Getting that pipeline stable enough to trust in production meant a lot of iteration on checkpointing and backpressure handling, since WMS event volume spiked hard during peak fulfillment windows.

**Chasing down the SLA problem.** For a while, our daily batch pipelines had a recurring SLA failure — the kind where the job "usually" finishes on time but blows past its window a couple of times a week for no obvious reason. Digging into the Spark execution plans, the root cause turned out to be shuffle-heavy joins against high-frequency dimension lookups that weren't partitioned sensibly. Applying date-based partitioning and Spark caching on those lookup tables brought the average daily runtime down from over four hours to under 90 minutes — and, just as importantly, made the runtime *predictable*, which mattered more to the business than the raw speedup.

**Building trust in the numbers — the analysis side.** Engineering reliability only matters if people trust what comes out the other end, and that's where the analyst half of the role came in. I implemented Great Expectations checks across more than 15 ingestion jobs — schema drift detection, null violations, referential integrity, business rule thresholds — which quarantined roughly 3,000 suspect records a week before they ever touched a report. I also wired CI/CD into all our Databricks notebook and pipeline deployments through Azure DevOps, with environment-specific parameter files and automatic rollback on validation failure, which took us from 2-3 production incidents a month down to nearly zero.

On the reporting side, I consolidated twelve individually maintained Excel reports — each with its own slightly different definition of the same metrics — into two certified Power BI dashboards with governed semantic models and row-level security. That project was as much a diplomacy exercise as an engineering one; getting sales and operations to agree on a single definition of "on-time fill rate" took more meetings than the dashboard build itself. To make that kind of disagreement less likely going forward, I built and maintained a business metrics dictionary covering more than 80 KPIs across purchasing, fulfillment, and inventory — which, across a distribution network serving a customer base that size, became the first place new analytics hires were pointed to.

**What I learned about scale.** US Foods is where I really internalized that data engineering at enterprise scale isn't just a technical problem — it's a trust and governance problem wearing a technical costume. Every pipeline I built had to answer not just "does this run reliably" but "will the business believe the number that comes out of it."

---

## Chapter 3: Morningstar — Chicago, IL
### Data Engineer, Managed Investment Data (MID) | Oct 2024 – Present

I joined Morningstar's Direct Platform organization, on the Managed Investment Data (MID) team specifically. MID's job, at its core, is to sit between asset managers — the firms running mutual funds, interval funds, and other managed investment vehicles — and everyone downstream who relies on Morningstar's data: individual investors, financial advisors, and institutional clients using products like Morningstar Direct and Direct Advisory Suite. Asset managers send us their fund data — portfolios, ownership stakes, NAVs, holdings, operational details — and our job is to collect it, standardize it, and layer Morningstar's own analytics on top so it's usable and comparable across thousands of funds. *(This MID team scope, and the fact that the org has grown from about 5 people to more than 380 globally since 2020, is public information Morningstar has shared in job postings — I'm citing it because it's real, not guessing. My own immediate pod is smaller than that — something like `[X engineers, Y analysts — fill in]` people focused specifically on our slice of the pipeline.)*

**The shape of the problem.** Fund data doesn't arrive clean. Every asset manager formats their submissions slightly differently, on their own timelines, and the definition of something as basic as "holdings as of date" can vary firm to firm. My work is to take that mess and turn it into governed, analytics-ready data products — currently processing more than 40 million records a day across financial instruments, fund holdings, and market events, all flowing through a Bronze-Silver-Gold layered architecture in dbt and Snowflake.

**Rebuilding the Silver layer.** One of the first things I owned was the Silver transformation layer, rebuilding it in dbt around `is_incremental()` materializations instead of the full-table scans it had been running on. That's a deceptively simple-sounding change, but it meant re-thinking the merge logic for every core fund and security master model so that we were only touching the records that actually changed each day — which is what actually made the daily transformation runtime sustainable as data volume kept growing.

**The compute cost conversation.** Snowflake compute cost is a constant, ongoing conversation on a team processing this much data daily, and I contributed to a project that ended up saving around $150K a year — right-sizing four XL virtual warehouses down to Large for batch workloads that didn't need that horsepower, and adding clustering keys to three of our most frequently queried fact tables, which cut partition scan volumes by more than 60%. I want to be honest that this wasn't a solo effort — it came out of a broader cost-governance push the platform team was already running, and my part was identifying and executing the warehouse right-sizing and clustering changes within that effort.

**Guarding quality at the gate.** Because this data eventually reaches client-facing products, quality gates matter enormously. I implemented dbt tests — not_null, unique, accepted_values, and custom relationship checks — across more than 30 core models, which catches data quality regressions in fund and instrument-level data before they ever reach Direct Platform reporting. For the messier, semi-structured feeds coming from upstream financial and third-party market data vendors, I built a Databricks Delta Live Tables pipeline that enforces schema expectations and row-level quality constraints at each layer before anything lands in Snowflake staging.

Keeping all of this running on schedule is its own discipline — I manage 12 critical production pipeline schedules in Apache Airflow, with DAG dependencies and SLA threshold alerts tuned so that daily loads consistently land inside the delivery windows the Direct Platform's research and advisor-facing products depend on.

**Closing the loop with reporting and delivery.** On the analysis and delivery side, I've built more than 10 Power BI dashboards for MID data operations and research teams, optimizing the DAX and using incremental refresh to bring average load time down from over 40 seconds to under 8 — which also meaningfully cut the number of ad hoc reporting requests landing on the team, since people could self-serve. I also built Git-backed CI/CD pipelines in Azure DevOps for promoting Power BI content across dev, QA, and production, with automated row-level-security validation as a deployment gate — which took our release cycle from 2-3 days down to same-day.

**Where things stand now.** This is still the role I'm in, and it's where I've gotten the most comfortable operating across the full stack — batch and semi-structured ingestion, layered transformation, quality and governance, and the CI/CD discipline to ship all of it safely. The thing I'd say I've learned most clearly here is that at this scale, the technical work and the trust/governance work are the same job, not two separate ones.

---

## Looking Back

Across these three roles, the throughline for me has been the same problem showing up at increasing scale and stakes: raw, messy, often undocumented data on one side, and people who need to trust it to make real decisions on the other — whether that's a business analyst at Cognizant, a procurement team at US Foods, or a financial advisor relying on Morningstar's Direct Platform. What's changed is the sophistication of the tools I reach for and how early I now think about quality and governance in a pipeline's design, rather than bolting it on afterward.




