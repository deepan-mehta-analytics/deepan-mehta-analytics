<p align="center">
  <img src="Linkedin-Banner-3.png" alt="Deepan Mehta Banner" width="650"/>
</p>
<hr style="border: 1px solid #2f2f2f;">


## 👋 Hi, I'm Deepan Mehta

> *"When learning meets data, growth becomes measurable and inevitable."*

> **Data Analytics | Data Engineering | AI Systems**
>
> Building end-to-end data solutions across ETL, analytics, and machine learning.
>
> **Current Project:** 🚲 [Bike Demand ML System](https://github.com/deepan-mehta-analytics/bike-demand-ml-system) — 4-city Random Forest inference API live on **GCP Cloud Run** (v4.4.0); RMSE accuracy gates in CI, cost-audit alerting via Slack, Cloud Logging + Prometheus metrics; companion [R Shiny dashboard](https://github.com/deepan-mehta-analytics/bike-demand-prediction) with live GBFS + weather feeds across 6 cities — next: drift monitoring pipeline (v4.5.0)

---

## 🌟 About Me

I'm a data-driven professional passionate about applying **AI, Data Engineering and Analytics** to improve **Business, Learning and Development (L&D)** outcomes.

After a successful career in **Aviation training and Airport operations**, I've transitioned toward **data engineering and data analytics**, where I can apply analytical methods to solve learning and business problems.

I build data-driven solutions covering:

- AI/ML Engineering — end-to-end training pipelines, inference APIs, and production cloud deployment
- Cloud Data Engineering — GCP Cloud Run, Artifact Registry, BigQuery; containerised CI/CD
- Observability — structured JSON logging (Cloud Logging), Prometheus metrics endpoints
- ETL pipelines and data workflows
- Exploratory data analysis and visualization
- Predictive modelling using Python and R
- Analytics dashboards and reporting systems (R Shiny, Tableau, Looker Studio)

---

## 🧠 Core Competencies

**Programming & Analysis:**

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![BigQuery](https://img.shields.io/badge/-BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white)
![Excel](https://img.shields.io/badge/-Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

**ML Engineering & APIs:**

![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/-Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

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

---

## 💼 Featured Projects

| Project | Description | Tools |
|---------|-------------|-------|
| 🏗️ [Sales Data Pipeline (ETL)](https://github.com/deepan-mehta-analytics/sales-data-pipeline) | Built a production-grade ETL pipeline using Medallion architecture (Bronze/Silver/Gold) to transform raw sales data into validated, analytics-ready datasets with automated data quality checks, feature engineering, and CI/CD workflows. | Python, Pandas, DuckDB, Docker, GitHub Actions |
| 🚲 [Bike Demand Prediction System](https://github.com/deepan-mehta-analytics/bike-demand-prediction) | Built a 6-city live demand dashboard integrating OpenWeather forecasts, GBFS live station data, and a FastAPI ML backend. Features UC1 fleet rebalancing alerts and UC2 rider demand scores across Seoul, London, NYC, DC, Paris, and Chicago. | R, Shiny, httr, Leaflet, GBFS, FastAPI (backend), Docker, GitHub Actions |
| ⚙️ [Bike Demand ML System](https://github.com/deepan-mehta-analytics/bike-demand-ml-system) | Production ML inference API live on **GCP Cloud Run** (v4.4.0). Trains 4-city Random Forest models (Seoul, London, NYC, DC); models baked into Docker image at build time. CI auto-publishes to GHCR + Artifact Registry and redeploys on merge via `gcloud run deploy`. RMSE accuracy gates in CI, cost-audit alerting via Slack, structured JSON logging → Cloud Logging, Prometheus `/metrics` endpoint. | Python, FastAPI, scikit-learn, Pydantic, Docker, GCP Cloud Run, Prometheus, GitHub Actions |
| 🧑‍💼 Financial Portfolio Analytics *(repo coming soon)* | Designing and developing a modular financial analytics platform for tracking and evaluating stock portfolios, integrating data pipelines, performance metrics, and API-driven insights within a scalable backend architecture. | Python, Pandas, FastAPI, LLM Integration |
| 🎓 Corporate Training Analytics Platform | Refactor->Re-write -> full-stack training records and analytics system to manage multi-course training programmes, featuring a unified data model, role-based admin dashboard, KPI tracking, event/result management, and reporting abstraction. | Java, SQL, Data Modeling, KPI Analytics, Role-Based Access |

---

## 📊 Architecture: Sales Data Pipeline

> Medallion ETL — raw sales CSV to analytics-ready datasets, served via FastAPI and containerised for GHCR release.

```mermaid
flowchart TD
    A["📂 Raw Sales CSV"] --> B["🥉 Bronze Layer\nIngestion + Pydantic validation"]
    B --> C["🥈 Silver Layer\nCleaning · Dedup · Feature engineering"]
    C --> D["🥇 Gold Layer\nAnalytics-ready Parquet + KPI aggregations"]
    D --> E["🦆 DuckDB\nIn-process analytical queries"]
    E --> F["⚡ FastAPI REST API"]
    F --> G["🐳 Docker → GHCR\nMulti-stage build · CI publish on tag"]
    H["✅ GitHub Actions\nLint · Test · Coverage · Release"] --> G
```

---

## 🎓 Certifications

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
