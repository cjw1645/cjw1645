<div align="center">

# cjw1645

### Data Engineer

`Data Pipeline` · `ETL` · `Data Engineering`

<br>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>

</div>

<br>

## 🛠 Tech Stack

### Data Engineering

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white"/>
</p>

### Database & Storage

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostGIS-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Amazon%20Redshift-8C4FFF?style=flat-square&logo=amazonredshift&logoColor=white"/>
</p>

### Cloud & Infrastructure

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS%20Glue-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
</p>

### Tools & Services

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redash-FF7964?style=flat-square&logo=redash&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
</p>

<br>

## 🚀 Projects

### ⟠ Ethereum Whale Transaction Detection & Anomaly Analysis

> An end-to-end data pipeline for collecting, processing, and analyzing large-scale Ethereum on-chain data to identify anomalous transactions.

`Python` `Airflow` `AWS S3` `AWS Glue` `Redshift` `Redash`

* Automated data ingestion from multiple external APIs to **Amazon S3** using Apache Airflow DAGs
* Built an ETL pipeline to transform raw JSON data into analytics-optimized **Parquet** format
* Designed an analytical data architecture using **AWS Glue Data Catalog and Amazon Redshift**
* Built visualization dashboards with **Redash** to analyze anomalous transaction patterns
* Separated real-time and historical batch workloads to prevent external API failures from affecting the entire pipeline
* Introduced a data validation layer to isolate malformed records before downstream processing
* Decoupled data ingestion and processing stages to improve pipeline resilience and fault isolation

**Architecture**

`External APIs → Airflow → Amazon S3 → AWS Glue → Redshift → Redash`

🔗 **Repository:** `https://github.com/DE6-TEAM6-Mars/ProjectMars`

---

### 🎲 Board Game Cafe Finder

> A location-aware AI service that helps users find nearby board game cafes with the games they want to play.

`Python` `Airflow` `PostgreSQL` `PostGIS` `pgvector` `Gemini API` `Docker`

* Built an Airflow-based ETL pipeline to periodically collect and normalize store and inventory data from multiple offline board game cafe chains
* Implemented geospatial search using **PostgreSQL and PostGIS** to identify stores within a user's search radius
* Designed a **hybrid RAG architecture** combining semantic vector search with geospatial filtering
* Normalized inconsistent game names across multiple data sources to improve entity matching
* Ensured pipeline idempotency through deduplication, composite keys, and database upserts
* Separated static master data from frequently changing inventory data to optimize collection schedules
* Decoupled external LLM dependencies from internal database and UI logic to maintain testability during API failures

**Architecture**

`Web Crawling → Airflow → PostgreSQL / PostGIS → pgvector → RAG → Streamlit`

🔗 **Repository:** `https://github.com/cjw1645/boardgame_finder`

---

### 🧊 Icecat Product Data Pipeline

> A data pipeline for collecting and structuring heterogeneous product feature data from the Icecat API.

`Python` `REST API` `JSON` `ETL`

* Collected product data based on Icecat Product IDs
* Parsed nested `featuregroups` to extract structured product features
* Designed processing logic to handle heterogeneous feature structures across different product categories
* Implemented a strategy for identifying and handling duplicate records
* Designed the ETL workflow with scalability for large-scale product collection in mind

**Architecture**

`Product ID → Icecat API → Extract → Transform → Structured Data`

🔗 **Repository:** `https://github.com/cjw1645/buildflow`

<br>

## 🎯 Engineering Interests

`Data Pipelines` · `ETL / ELT` · `Workflow Orchestration` · `Data Modeling` · `Data Quality` · `Cloud Data Engineering`

<br>
