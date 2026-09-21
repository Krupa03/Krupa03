# Hi, I'm Krupa 👋

Data Engineer and Analytics Engineer based in India — building end-to-end ELT pipelines, Lakehouse architectures, and real-time streaming systems using Python, SQL, dbt, Airflow, Kafka, PySpark, and Databricks.

📍 **Availability:** Open to sponsored relocation (Ireland CSEP · EU Blue Card eligible — IT shortage occupation) and global remote roles (USD/EUR). Target markets: Ireland · Poland · Germany · Austria · Remote.

---

## 🛠 Tech Stack

| Category | Tools |
|---|---|
| **Data Engineering** | Apache Airflow · Apache Kafka · PySpark · dbt · Spark SQL · ETL/ELT |
| **Cloud & Lakehouse** | Databricks (Unity Catalog · Serverless · Workflows) · Delta Lake · Google Cloud (BigQuery, GCS) · AWS (S3) · Azure (ADF, ADLS) |
| **Languages** | Python (Pandas, NumPy, SQLAlchemy) · SQL (PostgreSQL, MySQL, BigQuery, Spark SQL) · PL/pgSQL |
| **IaC & DevOps** | Terraform · Docker · GitHub Actions CI/CD · Git |
| **Warehouses** | BigQuery · Snowflake · PostgreSQL · TimescaleDB |
| **Visualisation** | Tableau · Power BI · Grafana · Looker Studio |
| **AI & Data Products** | LangChain · ChromaDB · Streamlit · Claude/LLM API |

---

## 📂 Production Projects

### 🏦 [Fintech ELT Pipeline](https://github.com/Krupa03/fintech-elt-pipeline)
**Databricks Serverless · Delta Lake · Unity Catalog · PySpark · dbt · Python · SQL**

End-to-end fraud-detection ELT pipeline on the IEEE-CIS dataset (590K+ transactions).

- PySpark ingests raw CSVs into Delta Lake raw tables via Unity Catalog Volume
- dbt runs 5 models across staging → intermediate → mart layers surfacing daily fraud rates, risk-scored transactions, and multi-factor fraud signals
- 6 dbt tests enforcing uniqueness, not-null, and accepted value constraints
- Databricks Workflow orchestrates the full pipeline — 2 dependency-chained tasks, **4m 26s end-to-end**

---

### ⚡ [E-Commerce ELT Pipeline](https://github.com/Krupa03/ecommerce-elt-pipeline)
**Airflow · dbt · BigQuery · Docker**

Production-grade analytical warehouse on 99.4K Brazilian Olist orders.

- Airflow 2.8.1 orchestrates daily ingestion into BigQuery raw layer
- dbt transforms across staging → intermediate → mart layers surfacing **R$16.4M in customer LTV**
- Incremental models, schema tests, full data lineage documentation
- **16 consecutive successful DAG runs**, each completing under 6 minutes

---

### 🚀 [Real-Time Sales Pipeline](https://github.com/Krupa03/realtime-sales-pipeline)
**Kafka · PySpark · TimescaleDB · Grafana · Docker Compose**

End-to-end real-time streaming pipeline simulating production-scale event flow.

- Python/Faker producer → Kafka → PySpark Structured Streaming → TimescaleDB hypertables
- Live 3-panel Grafana dashboard with 30s auto-refresh
- **$368,919 simulated transaction volume** peaking at **110 orders/minute**
- Full stack containerised via Docker Compose

---

### 🏗 [Lakehouse & Streaming Architecture](https://github.com/Krupa03/data-engineering-15-day-sprint)
**Databricks · Delta Lake · Snowflake · PySpark · Kafka · dbt**

Lakehouse and streaming architecture study covering production patterns.

- Bronze/Silver/Gold Medallion architecture on Databricks — Auto Loader, MERGE upserts, Time Travel
- Snowflake pipeline: virtual warehouses, Snowpipe, Streams & Tasks for CDC, zero-copy cloning for dev/prod isolation
- Kafka + Spark Structured Streaming integration
- All patterns documented across 15 committed modules

---

### 🛡 [Data Quality CLI Tool](https://github.com/Krupa03/data-quality-checker)
**Python · AWS S3 · Terraform · GitHub Actions · DuckDB · pytest**

Defensive engineering CLI enforcing data contracts across a Kimball star-schema warehouse.

- Automated checks for nulls, duplicates, referential integrity, freshness, and schema drift
- Terraform provisions AWS S3 infrastructure as code (tested against LocalStack)
- GitHub Actions CI/CD runs lint, pytest suite (7 tests, all passing), and terraform validate on every push
- Caught and fixed a cross-platform timezone bug in freshness-check logic — verified on UTC sandbox and live IST machine

---

### 🤖 [RAG Document Chatbot](https://github.com/Krupa03/rag-document-chatbot)
**LangChain · ChromaDB · Ollama · HuggingFace · Streamlit**

Fully local multi-turn document Q&A system.

- PDF ingestion → 500-token semantic chunking → 73 chunks in ChromaDB vector store
- LangChain retrieval chain (top-3 chunks per query) with source citations and multi-turn memory
- Streamlit UI with configurable parameters, runs via Ollama — zero external API dependency
- Sub-2-second response time across 50+ page documents

---

## 💼 Experience

**Data Analyst Intern | Native Engineering** *(Oct 2025 – Dec 2025)*
- Gathered reporting requirements from managers and business analysts, translating business needs into SQL extraction logic and Tableau dashboard outputs
- Defined data quality standards and cleaning rules — deduplication, null handling, ID reconciliation using Python (Pandas) and SQL
- Automated the weekly reporting cycle with Python post-processing, replacing 3+ hours of manual work per week

**Data Analyst Intern | Acespritech Solutions Pvt Ltd** *(Dec 2022 – Feb 2023)*
- Liaised with operations and finance stakeholders to gather KPI requirements, delivering 3 Power BI and Tableau dashboards reviewed weekly by the team
- Extracted and transformed data from 4 relational source tables using SQL — mapped raw IT operations data to structured reporting schemas

---

## 🎓 Education

- **Post-Graduate Diploma** in Big Data Solution Architecture — Conestoga College, Canada (2023) · GPA 3.75
- **Master of Engineering** in Computer Engineering — Gujarat Technological University (2020)
- **Bachelor of Engineering** in Computer Engineering — Gujarat Technological University (2018)

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Krupa%20Parmar-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/krupa-parmar-a7996210a/)

Open to Data Engineer and Analytics Engineer roles — Ireland (CSEP) · Poland · Germany · Austria · Remote (USD/EUR). DMs open.
