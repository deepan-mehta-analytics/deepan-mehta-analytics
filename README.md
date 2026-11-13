<p align="center">
 
</p>
<hr style="border: 1px solid #2f2f2f;">


## 👋 Hi, I'm Deepan Mehta

*"When learning meets data, growth becomes measurable and inevitable."*

**Applied AI Engineer | Forward Deployed Engineer | Data Analytics | Data Engineering | AI Systems**

As a **Forward Deployed Engineer** my role is to provide AI backed solutions to legacy Enterprise Systems across **ANY TECH STACK as needed by clients.**

**It could be Google Cloud, Databricks, AWS, Snowflake, Agentic solutions and more.**  

Building end-to-end AI solutions across ETL, analytics, machine learning and AI engineering

**Current Projects:**

- 🛡️ [Databricks Fraud Detection](https://github.com/deepan-mehta-analytics/databricks-fraud-detection) — **streaming fraud pipeline on the Databricks lakehouse**
  - **Auto Loader** replays 6M PaySim mobile-money transactions into a **Unity Catalog** medallion layout, with duplicate, late, schema-change and malformed-data scenarios each proven by SQL checks
  - A **Lakeflow declarative pipeline** of materialized views builds Silver with data-quality expectations, a quarantine shelf, duplicate removal and leak-free point-in-time velocity features
  - A gradient-boosted fraud model tracked in **MLflow** and versioned in the **Unity Catalog model registry** scores every new payment after each load, catching 405 of 822 frauds at a 50-alerts-per-hour review budget vs 352 for the best simple rule
  - A **Databricks SQL** task turns scores into an append-only alert log and a case table, governed by **Unity Catalog** groups, row filters, column masks and a tag-based (ABAC) policy, with manager-only access proven on a second real user
  - Two **AI/BI dashboards** generated from Python monitor the model's live results, data freshness and job health from **system tables**, each viewer's own access rules applied, with one colour theme, sliders, click-to-filter and drill-through
  - **Alerting emails** from job notifications and two SQL-alert health checks run by the job tell engineers when a run fails or data falls behind, worded so nobody mistakes them for fraud news
  - Jobs, pipeline, dashboards and alerts deployed as code via **Databricks Asset Bundles**
  - **Verified end to end on Databricks Free Edition (v0.6.0)**, 251 tests in CI
  - **Next:** **model monitoring** with drift-triggered retraining (v0.7.0)

- 🖱️ [AWS Clickstream Analytics](https://github.com/deepan-mehta-analytics/aws-clickstream-analytics) — **serverless clickstream analytics lake on AWS** turning **165,474 real web clicks** into product and funnel insight
  - **Lambda ingest → S3 Bronze/Silver/Gold → AWS Glue (PySpark) → Glue Data Catalog → Athena**, with **quality gates that quarantine bad rows instead of dropping them** and a **Gold star schema** for BI
  - The whole stack is **infrastructure as code (AWS SAM)** with **encryption, concurrency, timeout and query-scan cost guardrails enforced by tests**
  - **Deployed and verified on AWS (Mumbai, v0.1.0)**: Athena's counts **matched the source on every check**, **job bookmarks** processed only new data, and the stack was **torn down the same day** at a **measured cost of about ₹3.33**
  - 221 tests in CI
  - **Next:** **Apache Iceberg Silver tables** with schema evolution and a **verified data erasure across every layer** (built and tested, AWS run in progress), then streaming and Redshift

- 🏗️ [Sales Data Pipeline](https://github.com/deepan-mehta-analytics/sales-data-pipeline) — **production-grade Medallion (Bronze → Silver → Gold) ETL pipeline** with automated data quality gates, feature engineering, and an embedded **DuckDB** analytical store
  - Orchestrated via a self-hosted **Apache Airflow** DAG (9 independently retryable tasks) syncing into a partitioned/clustered **BigQuery** cloud warehouse, live-verified end-to-end against real GCP infrastructure
  - **FastAPI** query layer published to **GHCR**
  - Watermark-based **incremental load** (insert-only CDC) now live, 160 tests enforced in CI
  - **Next:** MLflow/W&B run tracking (v2.0)

---

## 🌟 About Me

I'm a data-driven professional passionate about applying **AI, Data Engineering and Analytics** to improve **Business, Learning and Development (L&D)** outcomes.

After a successful career in **Aviation training and Airport operations**, I've transitioned toward **AI Engineering, data engineering and data analytics**, where I can apply analytical methods to solve learning and business problems.

I build data-driven solutions covering:

- AI/ML Engineering — end-to-end training pipelines, inference APIs, and production cloud deployment
- Cloud Data Engineering — GCP Cloud Run, Artifact Registry, BigQuery; containerised CI/CD
- Lakehouse Data Engineering — Databricks Auto Loader, Spark Structured Streaming, Lakeflow Declarative Pipelines, Delta Lake, Databricks SQL, Asset Bundles
- Lakehouse monitoring — AI/BI dashboards built as code, job and pipeline health from Databricks system tables, per-viewer access rules, alerting emails from job notifications and SQL-alert health checks
- Lakehouse governance and ML — Unity Catalog grants, row filters, column masks and tag-based (ABAC) policies; MLflow with the Unity Catalog model registry
- Snowflake Data Cloud — Snowpipe continuous ingestion, Dynamic Tables and native Semantic Views; Cortex Agents/Analyst for governed natural-language analytics, Cortex Search for RAG, and Cortex Code for AI-assisted pipeline building
- Observability — structured JSON logging (Cloud Logging), Prometheus metrics endpoints
- ETL pipelines and data workflows
- Exploratory data analysis and visualization
- Predictive modelling using Python and R
- Analytics dashboards and reporting systems (R Shiny, Tableau, Looker Studio)

---

## 🧠 Core Competencies

**Programming & Analysis:**

![Python](https://img.shields.io/badge/-python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![pandas](https://img.shields.io/badge/-pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![BigQuery](https://img.shields.io/badge/-BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white)
![Excel](https://img.shields.io/badge/-Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

**ML Engineering & APIs:**

![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![pytest](https://img.shields.io/badge/-pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Ruff](https://img.shields.io/badge/-Ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/-Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Anthropic](https://img.shields.io/badge/-Anthropic_SDK-blueviolet?style=for-the-badge)

**Visualization & Reporting:**

![Tableau](https://img.shields.io/badge/-Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Looker Studio](https://img.shields.io/badge/-Looker%20Studio-4285F4?style=for-the-badge&logo=googleanalytics&logoColor=white)
![ggplot2](https://img.shields.io/badge/-ggplot2-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Shiny](https://img.shields.io/badge/-Shiny-276DC3?style=for-the-badge&logo=r&logoColor=white)

**Cloud Data Engineering:**

![Google Cloud](https://img.shields.io/badge/-Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/-BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white)
![Cloud Run](https://img.shields.io/badge/-Cloud%20Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Vertex AI](https://img.shields.io/badge/-Vertex%20AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Artifact Registry](https://img.shields.io/badge/-Artifact%20Registry-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/-Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Pub/Sub](https://img.shields.io/badge/-Pub%2FSub-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Dataflow](https://img.shields.io/badge/-Dataflow-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Apache Beam](https://img.shields.io/badge/-Apache%20Beam-FF6F00?style=for-the-badge&logo=apache&logoColor=white)
![Dataform](https://img.shields.io/badge/-Dataform-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Dataplex](https://img.shields.io/badge/-Dataplex-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![BigLake](https://img.shields.io/badge/-BigLake-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

**Lakehouse & Streaming (Databricks):**

![Databricks](https://img.shields.io/badge/-Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/-Spark%20Structured%20Streaming-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Auto Loader](https://img.shields.io/badge/-Auto%20Loader-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/-Delta%20Lake-00ADD4?style=for-the-badge)
![Unity Catalog](https://img.shields.io/badge/-Unity%20Catalog-1B3139?style=for-the-badge&logo=databricks&logoColor=white)
![Asset Bundles](https://img.shields.io/badge/-Asset%20Bundles-1B3139?style=for-the-badge&logo=databricks&logoColor=white)
![Lakeflow Pipelines](https://img.shields.io/badge/-Lakeflow%20Pipelines-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Databricks SQL](https://img.shields.io/badge/-Databricks%20SQL-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![AI/BI Dashboards](https://img.shields.io/badge/-AI%2FBI%20Dashboards-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![SQL Alerts](https://img.shields.io/badge/-SQL%20Alerts-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)

**AWS Data Engineering:**

![AWS](https://img.shields.io/badge/-AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Amazon S3](https://img.shields.io/badge/-Amazon%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/-AWS%20Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![AWS Glue](https://img.shields.io/badge/-AWS%20Glue-8C4FFF?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Glue Data Catalog](https://img.shields.io/badge/-Glue%20Data%20Catalog-8C4FFF?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Amazon Athena](https://img.shields.io/badge/-Amazon%20Athena-8C4FFF?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![PySpark](https://img.shields.io/badge/-PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Apache Parquet](https://img.shields.io/badge/-Apache%20Parquet-50ABF1?style=for-the-badge&logo=apacheparquet&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/-Apache%20Iceberg-4E8EE9?style=for-the-badge&logo=apache&logoColor=white)
![AWS SAM](https://img.shields.io/badge/-AWS%20SAM-FF4F8B?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![CloudFormation](https://img.shields.io/badge/-CloudFormation-FF4F8B?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![cfn-lint](https://img.shields.io/badge/-cfn--lint-FF4F8B?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)

**Data Warehousing & Cortex AI:**

![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Snowpipe](https://img.shields.io/badge/-Snowpipe-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Dynamic Tables](https://img.shields.io/badge/-Dynamic%20Tables-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Semantic Views](https://img.shields.io/badge/-Semantic%20Views-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Cortex AI](https://img.shields.io/badge/-Cortex%20AI-6E56CF?style=for-the-badge&logo=snowflake&logoColor=white)
![Cortex Search](https://img.shields.io/badge/-Cortex%20Search-6E56CF?style=for-the-badge&logo=snowflake&logoColor=white)
![Cortex Analyst](https://img.shields.io/badge/-Cortex%20Analyst-6E56CF?style=for-the-badge&logo=snowflake&logoColor=white)
![Cortex Agents](https://img.shields.io/badge/-Cortex%20Agents-6E56CF?style=for-the-badge&logo=snowflake&logoColor=white)
![Cortex Code](https://img.shields.io/badge/-Cortex%20Code-6E56CF?style=for-the-badge&logo=snowflake&logoColor=white)
![Snowflake CoWork](https://img.shields.io/badge/-Snowflake%20CoWork-6E56CF?style=for-the-badge&logo=snowflake&logoColor=white)

---
## ❄️ Snowflake Northstar Badges
**9 verified credentials · Issued by Snowflake**

<p align="left">
<a href="https://developerbadges.snowflake.com/a2e44f0f-e82b-41be-a48c-ad01ce5fd1ba">
  <img src="https://api.accredible.com/v1/frontend/credential_website_embed_image/badge/197357265"
       width="154"
       alt="Building Intelligent Data Application with Snowflake">
</a>
<a href="https://developerbadges.snowflake.com/8a2d878d-a3ac-434a-bb96-276e7cd8caa6">
  <img src="https://api.accredible.com/v1/frontend/credential_website_embed_image/badge/197357135"
       width="167"
       alt="Accelerate AI Development: Building AI Applications with Snowflake Cortex: RAG, Text-to-SQL &amp; CoCo">
</a>
<a href="https://developerbadges.snowflake.com/61240fa4-7eb0-4942-a4ca-818d87759592">
  <img src="https://api.accredible.com/v1/frontend/credential_website_embed_image/badge/189650778"
       width="174"
       alt="From Zero to Agents: Building End-To-End Data Pipelines for an AI Agent">
</a>
<a href="https://developerbadges.snowflake.com/fa443254-ddb7-4c0c-be05-c8b51643ca2e">
  <img src="https://api.accredible.com/v1/frontend/credential_website_embed_image/badge/189650110"
       width="169"
       alt="Northstar - Data Ingestion, Transformation, and Delivery with Snowflake">
</a>
<a href="https://developerbadges.snowflake.com/f5d91b83-916f-4a92-bacb-8193671f49be">
  <img src="https://api.accredible.com/v1/frontend/credential_website_embed_image/badge/197357383"
       width="156"
       alt="Northstar - Build an Automated Data Pipeline with Snowpipe">
</a>
</p>

<p align="left">
<a href="https://developerbadges.snowflake.com/profile/supernovasurfersolutions/wallet"><img src="https://img.shields.io/badge/All_9_Snowflake_Credentials-View_Wallet-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" alt="All 9 Snowflake credentials: view the credential wallet"></a>
</p>

---

## 💼 Featured Projects

<table>
<tr><th align="left">Project</th><th align="left">Description</th><th align="left">Tools</th></tr>
<tr>
<td valign="top">

🛡️ [Databricks Fraud Detection](https://github.com/deepan-mehta-analytics/databricks-fraud-detection)<br>`v0.6.0`<br>in progress

</td>
<td valign="top">

**Streaming fraud-detection pipeline on the Databricks lakehouse**, built in verified phases. Auto Loader replays 6.36M PaySim mobile-money transactions as hourly JSON Lines files into a Unity Catalog medallion layout, with schema hints, `addNewColumns` evolution, rescued data and an exactly-once checkpoint. Duplicate, late, schema-change and malformed-data scenarios are each **staged and proven by SQL checks**.

A Lakeflow declarative pipeline then builds Silver: data-quality expectations with a quarantine shelf, first-arrival dedup, and **seven point-in-time velocity features** on the receiving ("mule") account that use earlier hours only.

A scikit-learn gradient-boosted model, tracked in MLflow and versioned in the Unity Catalog model registry with **champion/challenger aliases**, scores every new payment in a job step after Silver and **logs each decision with its model version and inputs**.

Jobs, pipeline, dashboards and alerts **ship as code** via Databricks Asset Bundles.

**Verified end to end on Databricks Free Edition (v0.1.0–v0.3.0):** 5,987,427 Bronze rows **reconcile exactly** to 5,987,412 clean + 5 rejected + 10 duplicates, features match an independent reference model, and on a held-out period of 822 frauds **the model catches 405 at 50 alerts per hour** (PR-AUC 0.346) vs 352 for flagging the largest payments, with the cost of late fraud labels measured.

**Gold and governance (v0.4.0):** a Databricks SQL task writes an append-only alert log (top 50 per hour, never re-ranked) and a case table with verdicts, and 3,268 alerts and 412 closed cases **match an independent calculator exactly**.

Unity Catalog groups, per-table grants, a row filter and column masks give **managers closed cases only with account names redacted**, proven on a second real user along with `REVOKE`, and a tag-based (ABAC) policy is shown working on Free Edition.

<details><summary>More</summary>

**Monitoring (v0.5.0):** a SQL task rebuilds six plain views after every load, and two AI/BI dashboards generated from Python show the model's live results, data freshness and job health from system tables, with one colour theme, sliders, click-to-filter and drill-through to a single job run; on a 59-hour test run **every number matched an independent calculation**, and a manager sees the same totals with open cases and engineering pages withheld.

**Alerting (v0.6.0, latest):** the job emails the deploying engineer when a run fails or passes 30 minutes, and two SQL-alert health checks (stages behind, rejected rows) end every run with Run if: All done, emailing "System health check" messages that open by saying no payment needs review; a run made to fail on purpose **still ran both checks and sent its failure email**, with no data moved. **251 tests in CI, total cost ₹0.**

**Next:** model monitoring with drift-triggered retraining (v0.7.0), then a live demo window (v1.0.0).

</details>

</td>
<td valign="top">

• Python<br>• SQL<br>• **Databricks**<br>• **Auto Loader**<br>• **Lakeflow Declarative Pipelines**<br>• **Spark Structured Streaming**<br>• **Delta Lake**<br>• **Unity Catalog**<br>• **Databricks SQL**<br>• **MLflow**<br>• **AI/BI dashboards**<br>• **SQL alerts**<br>• scikit-learn<br>• Asset Bundles<br>• pytest<br>• GitHub Actions<br>• Kafka *(production option)*

</td>
</tr>
<tr>
<td valign="top">

🖱️ [AWS Clickstream Analytics](https://github.com/deepan-mehta-analytics/aws-clickstream-analytics)<br>`v0.1.0`<br>in progress

</td>
<td valign="top">

**Serverless clickstream analytics lake on AWS** that turns raw web clicks into answers a retailer can act on: daily traffic, browse-depth funnel, and which products make visitors leave. Built on **real data** (165,474 clicks, 24,026 visits from an online clothing shop).

A serverless Lambda ingest verifies every file (MD5 checksum, retry budget) and lands it by month in S3 Bronze; an AWS Glue PySpark job with job bookmarks builds Silver (hard quality rules **quarantine bad rows with a reason, never silently drop them**) and a Gold star schema with **rerun-safe (idempotent) writes**; 13 Glue Catalog tables with partition projection serve Athena.

The entire stack is **infrastructure as code (AWS SAM + CloudFormation)** with **enterprise guardrails enforced in CI**: private encrypted buckets, reserved concurrency, job timeouts and an Athena 1 GB scan cutoff.

**Spark reconciles row-for-row with the source on all 165,474 clicks**; architecture decisions recorded as ADRs, every tier cost-modelled before deployment.

<details><summary>More</summary>

**Status: core lake deployed and verified on AWS Mumbai (v0.1.0)** through a reviewed CloudFormation change set: Glue runs of about 2.5 minutes each, Athena counts **matched the source on all 4 checks**, the second run read only the new month (job bookmarks), and a verified teardown left nothing running. **Measured AWS bill for the run: about ₹3.33**, against a ₹12 estimate.

**In progress: Apache Iceberg v2 Silver tables** written by Glue and created by Athena, with schema evolution without rewriting data and **one visit erased from Bronze, Silver and Gold** so time travel can no longer reach it (built and tested in CI with 221 tests, AWS run in progress). Then Kinesis/Firehose streaming and Redshift Serverless.

</details>

</td>
<td valign="top">

• Python<br>• **PySpark**<br>• **AWS Lambda**<br>• **Amazon S3**<br>• **AWS Glue**<br>• **Glue Data Catalog**<br>• **Amazon Athena**<br>• **Apache Iceberg**<br>• **AWS SAM / CloudFormation**<br>• Parquet<br>• DuckDB<br>• pytest<br>• GitHub Actions<br>• KMS · AWS Organizations *(production options)*

</td>
</tr>
<tr>
<td valign="top">

🏗️ [Sales Data Pipeline (ETL)](https://github.com/deepan-mehta-analytics/sales-data-pipeline)<br>`v1.2.2`<br>released

</td>
<td valign="top">

Built a production-grade ETL pipeline using **Medallion architecture (Bronze/Silver/Gold)** to transform raw sales data into validated, analytics-ready datasets with **automated data quality checks**, feature engineering, and CI/CD workflows.

Orchestrated via a self-hosted Apache Airflow DAG (**9 independently retryable tasks**) alongside the existing GitHub Actions cron, syncing into a partitioned/clustered BigQuery cloud warehouse — **live-verified end-to-end**, with watermark-based **incremental load** (insert-only CDC) now replacing full-dataset reprocessing on every run.

Runs end to end on the real Superstore dataset (**9,994 rows**) in about **617 ms**, with 90 tests at v1.0.0. **v1.2.2** adds a FastAPI query layer published to GHCR as a Docker image.

</td>
<td valign="top">

• Python<br>• Pandas<br>• DuckDB<br>• **Apache Airflow**<br>• **Google BigQuery**<br>• Docker<br>• GitHub Actions

</td>
</tr>
<tr>
<td valign="top">

⚡ [GridPulse — GCP Data Platform](https://github.com/deepan-mehta-analytics/gridpulse-gcp)<br>Phase 1<br>in progress

</td>
<td valign="top">

**Bitemporal** GCP data platform built to cover the **Google Cloud Professional Data Engineer exam guide v4.2** end-to-end with runnable code, not notes — every settlement price keeps `event_time`, `published_at`, and `settlement_run` as separate dimensions so **nothing is ever overwritten**, and any past belief state is reconstructable via as-of queries.

Runs entirely on **free-tier services and local emulators** (Pub/Sub, MinIO, Airflow, Spark) via Docker Compose, with real GCP reserved for short, **budget-capped demo windows**.

**Phase 1 in progress:** the Elexon BMRS REST collector, Avro-enforced Pub/Sub, Apache Beam windowing pipeline, and DLQ replay are all **built, tested, and verified end-to-end** against live local services.

<details><summary>More</summary>

**18 tests** across contract, integration and unit suites cover ingestion to Bronze.

</details>

</td>
<td valign="top">

• Python<br>• **Terraform**<br>• Docker<br>• **Apache Beam**<br>• Pub/Sub<br>• **Airflow**<br>• BigQuery<br>• GitHub Actions

</td>
</tr>
<tr>
<td valign="top">

🧾 [Snowflake Cortex AI — AP Invoice Intelligence](https://github.com/deepan-mehta-analytics/snowflake-cortex-ai)<br>`v1.1.0`<br>released

</td>
<td valign="top">

**Multi-source accounts-payable pipeline** running entirely inside Snowflake: Dynamic Tables conform **invoices from SAP, Oracle, Baan, and Workday** into a native Semantic View per documented business rules; a Cortex Agent (Analyst text-to-SQL, Cortex Search and two tested stored-procedure tools for exact totals and BR-004 review status) answers natural-language questions, scored on a 21-question golden set by native Cortex Agent Evaluations (LLM judge) in GitHub Actions — **a drop below the recorded baseline fails the build** (main run: 0.97 answer correctness, 0.95 logical consistency).

Four synthetic source tables (**50 invoices, 3 currencies**); **90 tests** in CI and **38/38 grant checks** pass after every deploy.

A wrong total the v1.0.0 eval caught is now fixed and proven, and **every amount in an answer is checked against what the tools returned**.

"Overdue" is measured at a fixed reporting date, the account is rebuilt by a **re-runnable deploy with a grant check**, and the live results are preserved in the repo.

<details><summary>More</summary>

The agent was published to **Claude through a Snowflake-managed MCP server** over OAuth as a least-privilege user (removed 2026-11-03 ahead of the trial end), and a BR-004 data-quality guardrail (Data Metric Function, review queue, email alert) flags invoices over USD 500,000 at the invoice-date FX rate. **Ran live on Snowflake through v1.1.0 until the trial ended on 2026-11-11.**

</details>

</td>
<td valign="top">

• **Snowflake**<br>• SQL<br>• **Dynamic Tables**<br>• **Cortex Analyst**<br>• **Cortex Agents**<br>• **Cortex Search**<br>• **MCP**<br>• GitHub Actions<br>• Python<br>• Openflow *(production option)*<br>• Snowflake Intelligence *(production option)*

</td>
</tr>
<tr>
<td valign="top">

🚲 [Bike Demand Prediction System](https://github.com/deepan-mehta-analytics/bike-demand-prediction)<br>`v1.7.0`<br>released

</td>
<td valign="top">

Built a **6-city live demand dashboard** integrating OpenWeather forecasts, GBFS live station data, and a FastAPI ML backend.

Features **UC1 fleet rebalancing alerts and UC2 rider demand scores** across Seoul, London, NYC, DC, Paris, and Chicago.

Began as an IBM Applied Data Science capstone and grew over six releases. City-native data (Seoul **35,063 rows**, Paris 17,539, Chicago 32,720); best model **R² 0.730 / RMSE 333.89 bikes/hr, a 39% gain over baseline**.

<details><summary>More</summary>

**78 tests / 120 assertions** run in CI, and the live station stream was moved from Dataflow to Cloud Run + Scheduler at **zero free-tier cost**.

</details>

</td>
<td valign="top">

• **R**<br>• **Shiny**<br>• httr<br>• Leaflet<br>• GBFS<br>• FastAPI (backend)<br>• **Docker**<br>• GitHub Actions

</td>
</tr>
<tr>
<td valign="top">

⚙️ [Bike Demand ML System](https://github.com/deepan-mehta-analytics/bike-demand-ml-system)<br>`v4.5.0`<br>live

</td>
<td valign="top">

**Production ML inference API** live on **GCP Cloud Run** (v4.5.0).

Trains **6-city Random Forest models** (Seoul, London, NYC, DC, Paris, Chicago); models baked into Docker image at build time.

CI auto-publishes to GHCR + Artifact Registry and redeploys on merge via `gcloud run deploy`. **RMSE accuracy gates in CI**, cost-audit alerting via Slack, structured JSON logging → Cloud Logging, Prometheus `/metrics` endpoint.

<details><summary>More</summary>

Weekly **Vertex AI** retraining with an **MLflow** registry and a **3% RMSE promotion gate** (switched off June 2026, portfolio mode). A data-quality gate dropping anomalous Paris 2022 data cut RMSE **23.30 → 20.51**. **66 pytest tests** in CI.

</details>

</td>
<td valign="top">

• Python<br>• FastAPI<br>• scikit-learn<br>• Pydantic<br>• Docker<br>• **GCP Cloud Run**<br>• Prometheus<br>• GitHub Actions<br>• API Gateway + Cloud Armor *(production option)*

</td>
</tr>
<tr>
<td valign="top">

🏠 [StayOps — Rental Ops Console](https://github.com/deepan-mehta-analytics/stayops)<br>`v4.0.1`<br>live

</td>
<td valign="top">

Multi-channel booking reconciliation engine and **AI-assisted ops console** for short/mid-term rental operators.

Ingests bookings from CSV and Google Sheets (**idempotent SHA-256 dedup**), **detects 4 conflict types automatically** (duplicates, double-bookings, pricing anomalies, gap nights), and surfaces live KPI dashboards and SQL reports — built end-to-end with Claude Code on Next.js 16 + Supabase.

Seeded with about **86 bookings across 4 properties**; **27 Vitest tests** run in CI.

<details><summary>More</summary>

**Phase 2 shipped (v2.0.0):** a Claude tool-calling agent reads each flagged conflict, streams its reasoning and **proposes a resolution with a 0–100 confidence score** that the operator accepts or dismisses; Vercel Cron runs nightly turnover tasks and a weekly AI ops report with optional Slack delivery. Since then: a public landing page with PostHog funnel tracking (v3.0.0), Supabase Auth with row-level security on all 7 tables (v4.0.0) and a Next.js security patch (v4.0.1). **Live on Vercel.** Next: Playwright end-to-end tests (v4.1.0).

</details>

</td>
<td valign="top">

• TypeScript<br>• **Next.js 16**<br>• Drizzle ORM<br>• **Supabase**<br>• shadcn/ui<br>• Anthropic SDK<br>• Vercel<br>• PostHog

</td>
</tr>
<tr>
<td valign="top">

🎓 Corporate Training Analytics Platform<br>private<br>in progress

</td>
<td valign="top">

Refactor->Re-write -> **full-stack training records and analytics system** to manage multi-course training programmes, featuring a **unified data model**, role-based admin dashboard, KPI tracking, event/result management, and reporting abstraction.

**From a monolith:** the original desktop app was JavaFX 8 on a NetBeans/Ant build: 17 Java classes (about 5,300 lines) with SQL and business logic inside the screen controllers, 58 JAR files copied by hand, and a Windows `.exe` tied to machine-specific Java paths.

**To current tech:** a ground-up rewrite on **Java 21 + JavaFX 21 with Maven**, with configuration moved to environment variables and ignored local files, and the code split into auth, controllers, models, reporting and a 40-class admin module (83 classes, about 13,400 lines).

A redesigned **v2 MySQL schema (21 tables)** built around course families, course types, training events and results, with **a scripted migration from the legacy database** and synthetic demo data (96 people, 30 training events, 181 results) on a local Docker MySQL.

Role-based login with a first-login password change, **access scoping by course family and site**, an optional admin audit log, KPI snapshots and monthly trends, CSV exports, and a **reporting-engine abstraction** that adds JasperReports PDF templates alongside the legacy report engine.

<details><summary>More</summary>

**311 JUnit 5 test methods** across 59 test files; the MySQL driver was upgraded to clear a high-severity CVE (CVE-2023-22102), and a git hygiene checklist covers secrets, database dumps and third-party binaries.

**Status: private, work in progress.** The Maven build compiles; admin modularization, screen modernization and Windows packaging are next.

</details>

</td>
<td valign="top">

• Java<br>• SQL<br>• **Data Modeling**<br>• **KPI Analytics**<br>• Role-Based Access<br>• **JavaFX 21**<br>• **Maven**<br>• **MySQL**<br>• JasperReports<br>• Docker<br>• JUnit 5<br>• Apache Superset *(planned)*<br>• Power BI Embedded *(production option)*

</td>
</tr>
<tr>
<td valign="top">

🏷️ [AI Expense Text Classification](https://github.com/deepan-mehta-analytics/ai-expense-classification)<br>`v1.0.0`<br>released

</td>
<td valign="top">

**NLP pipeline** classifying a real-world, anonymized FY23 expense ledger into Services/Equipment/Material — built against a documented PRD, with **no pre-existing category labels** to learn from.

**267 expense remarks hand-labelled** against a documented rubric; 6 unit tests.

Compares TF-IDF + classical ML (**94.4% accuracy, 0.93 macro F1** — selected) against a zero-shot transformer baseline, backed by a documented labeling rubric, 5-fold cross-validation, and an auto-generated executive summary. **v1.0.0 shipped.**

</td>
<td valign="top">

• Python<br>• scikit-learn<br>• **TF-IDF**<br>• Hugging Face Transformers<br>• Jupyter<br>• pytest

</td>
</tr>
</table>

---

## 📊 Architecture: Databricks Fraud Detection — Current & Roadmap

<!-- Simplified from the databricks-fraud-detection README (Architecture + Roadmap), synced at v0.6.0. Re-sync on each release. -->

> A streaming fraud pipeline on the Databricks lakehouse: hourly mobile-money payments flow through a Unity Catalog medallion layout, get scored by a registered model, and become reviewable alerts, with monitoring, alerting emails and governance built in.

```mermaid
flowchart TD
    subgraph Src["📥 Data Source"]
        CSV["PaySim mobile money<br/>6.36M transactions<br/>743 hourly files"]
    end

    subgraph Ing["🥉 Bronze ✅ Auto Loader"]
        REL["Hourly replay<br/>duplicate · late<br/>schema-change<br/>malformed rows"]
        BR["bronze_transactions<br/>append-only Delta"]
    end

    subgraph Sil["🥈 Silver ✅ Lakeflow"]
        CHK["Quality expectations<br/>quarantine shelf"]
        FEAT["Clean, de-duplicated<br/>leak-free features"]
    end

    subgraph ML["🤖 Model ✅ MLflow"]
        TR["Gradient-boosted<br/>UC model registry<br/>@champion"]
        SC["Scores every load<br/>405 of 822 frauds<br/>at 50 alerts/hour<br/>vs 352 best rule"]
    end

    subgraph Gold["🥇 Gold ✅ Databricks SQL"]
        AL["Append-only alerts<br/>case table · verdicts"]
    end

    GOV{{"🔐 Unity Catalog<br/>groups · row filters<br/>masks · ABAC"}}

    subgraph Mon["📊 Monitoring ✅ Built"]
        DASH["2 AI/BI dashboards<br/>model · freshness<br/>job health"]
        EM["Alerting emails<br/>job failures<br/>2 health checks"]
    end

    subgraph Drift["📈 Model monitoring 🔜"]
        DR["Drift detection<br/>auto-retraining<br/>next: v0.7.0"]
    end

    subgraph Demo["🚀 Live demo 🔜"]
        LV["Time-boxed live run<br/>scripted teardown<br/>planned: v1.0.0"]
    end

    CSV --> REL
    REL --> BR
    BR --> CHK
    CHK --> FEAT
    FEAT --> TR
    FEAT --> SC
    TR --> SC
    SC --> AL
    AL --> DASH
    AL --> EM
    GOV -.-> AL
    GOV -.-> DASH
    Mon --> Drift
    Drift --> Demo
```

*Deployed as code via Databricks Asset Bundles · verified end to end on Databricks Free Edition (v0.6.0) · 251 tests in CI.*

---

## 🎓 Certifications
- Currently enrolled in IIT Delhi — Advanced Certification: Forward Deployed Engineer
- Google Data Analytics Professional Certificate
- IBM Data Analytics Professional Certificate with Excel & R

---

My mission is to bridge **Data Engineering and Learning** — using data to make learning, Business Analysis and training more effective.

---

## 📫 Contact

📍 Mumbai, India<br>
📧 [deepanmehta@live.com](mailto:deepanmehta@live.com)<br>
🔗 [LinkedIn](https://www.linkedin.com/in/d-mehta-054519341/)<br>
💼 [GitHub Projects](https://github.com/deepan-mehta-analytics?tab=repositories)

---

> *"When learning meets data, growth becomes measurable and inevitable."*
