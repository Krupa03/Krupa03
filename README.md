# Hi, I'm Krupa 👋 

**Data Engineer** based in India — building end-to-end data pipelines, high-throughput real-time streaming infrastructure, and optimized cloud data warehouses using Python, SQL, Kafka, dbt, and PySpark.

📍 **Availability**: Open to global remote contract/full-time opportunities (USD/EUR) and on-site roles in Ireland (Critical Skills Employment Permit eligible for Data Engineering shortage list) or Dubai.

---

## 🛠 Tech Stack

- **Languages**: Python (Pandas, NumPy, SQLAlchemy), SQL (PostgreSQL, MySQL, BigQuery, Spark SQL), PL/pgSQL
- **Data Engineering**: Apache Kafka, PySpark, dbt, Apache Airflow, TimescaleDB, HDFS, ETL/ELT Systems
- **Cloud & DevOps**: AWS (S3), Google Cloud (BigQuery, GCS, Looker Studio), Azure, Terraform (IaC), Docker, GitHub Actions, Git, Bash
- **AI & Data Products**: LangChain, ChromaDB, Vector Databases, Claude/LLM API Integration, Streamlit

---

## 📂 Featured Production Architectures

### 🏎 [Real-Time Sales Pipeline](https://github.com/Krupa03/realtime-sales-pipeline)
End-to-end event streaming pipeline simulating production-scale transactional retail flow.
- **Infrastructure**: Python mock producer → Apache Kafka broker → PySpark Structured Streaming engine.
- **Storage & Viz**: High-velocity data ingested into TimescaleDB hypertables, serving a live 3-panel Grafana monitoring dashboard with a 30s auto-refresh rate.
- **Scale**: Successfully processed over $368K in transaction volume, handling peaks of 110 orders/minute.

### 🛡 [Automated Data Quality Checker](https://github.com/Krupa03/data-quality-checker)
Defensive engineering CLI tool enforcing data contract and schema validity across a Kimball star-schema data warehouse.
- **Testing**: Built a comprehensive 7-test suite via Pytest covering null values, duplicates, referential integrity, freshness, and structural schema drift.
- **DevOps**: Automated execution via a GitHub Actions CI/CD workflow validating code quality on every push. Infrastructure fully provisioned as code using Terraform.
- **Problem Solved**: Caught and patched a crucial cross-platform timezone processing bug (Windows/IST vs UTC environments) before deployment.

### ⚡ [E-Commerce ELT Pipeline](https://github.com/Krupa03/ecommerce-elt-pipeline)
Production-grade analytical warehouse build handling transactional e-commerce ingestion and modeling.
- **Orchestration**: Apache Airflow dynamically manages daily ingestion cycles into Google BigQuery raw layers.
- **Modeling**: dbt handles transformations across 3 structural layers (staging → intermediate → analytics marts) utilizing incremental model configurations.
- **Result**: Successfully executed 16 consecutive historical DAG runs, mapping business metrics for 99K+ orders.

### 🤖 [RAG Document Chatbot](https://github.com/Krupa03/rag-document-chatbot)
Multi-turn intelligent context retrieval engine running entirely on localized infrastructure.
- **Ingestion**: PDF processing pipelines utilize semantic chunking and generate localized vector embeddings.
- **Storage**: Vector profiles mapped into a 73-chunk ChromaDB vector store optimized for retrieval latency.
- **Execution**: LangChain framework couples historical conversational memory with precise source-citation output, deployed locally via Ollama and a Streamlit UI.

---

## 💼 Core Technical Experience

**Data Analyst Intern** | Native Engineering *(Oct 2025 – Dec 2025)*
- Designed custom SQL extraction scripts utilizing window functions and complex multi-table joins to feed Tableau dashboards.
- Automated recurring manual data pulls into programmatic Python pipelines, saving weekly engineering overhead.
- Engineered automated data cleansing rules (deduplication, schema matching, validation) to clean incoming financial data.

**Data Analyst Intern** | Acespritech Solutions *(Dec 2022 – Feb 2023)*
- Built live Power BI and Tableau tracking interfaces to monitor operational infrastructure metrics and ticketing queues.
- Wrote PowerShell and Python automation scripts to aggregate server performance metadata before database ingestion.

---

## 🎓 Education & Credentials

- **P.G. Diploma in Big Data Solution Architecture** – Conestoga College, Canada
- **Master of Engineering (M.E.) in Computer Engineering** – Gujarat Technological University
- **Bachelor of Engineering (B.E.) in Computer Engineering** – Gujarat Technological University
