🛠 Tech Stack
Data Engineering

<p> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white"/> <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white"/> </p>

Database

<p> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/PostGIS-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Amazon%20Redshift-8C4FFF?style=flat-square&logo=amazonredshift&logoColor=white"/> </p>

Cloud & Infrastructure

<p> <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/> <img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white"/> <img src="https://img.shields.io/badge/AWS%20Glue-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> </p>

Tools & Service

<p> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/> <img src="https://img.shields.io/badge/Redash-FF7964?style=flat-square&logo=redash&logoColor=white"/> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/> </p>

<br>

🚀 Projects
⟠ Ethereum Whale Transaction Detection & Anomaly Analysis

대규모 Ethereum 온체인 데이터를 수집·처리하여 이상 거래를 분석하는 End-to-End Data Pipeline

Python Airflow AWS S3 AWS Glue Redshift Redash

Airflow DAG를 활용한 외부 API 데이터 수집 및 AWS S3 적재 자동화
JSON 원시 데이터를 분석에 적합한 Parquet 포맷으로 변환하는 ETL Pipeline 구축
AWS Glue Data Catalog 및 Redshift 기반 분석 데이터 구조 설계
Redash를 활용한 이상 거래 분석 및 시각화
실시간 데이터와 대용량 과거 데이터 수집 파이프라인 분리
데이터 유효성 검사 및 오류 데이터 격리를 통한 Pipeline 안정성 개선
외부 API 장애가 전체 시스템으로 확산되지 않도록 수집/처리 계층 분리

Pipeline

External APIs → Airflow → AWS S3 → AWS Glue → Redshift → Redash

🔗 Repository: YOUR_ETHEREUM_REPOSITORY_URL

## 🎲 Board Game Cafe Data Platform

**보드게임 정보와 카페 보유 게임 데이터를 통합하는 데이터 파이프라인 및 검색 서비스**

> `Python` · `Airflow` · `PostgreSQL` · `REST API` · `Web Crawling`

보드게임 카페마다 분산되어 있는 보유 게임 데이터를 수집하고,
외부 게임 API의 메타데이터와 결합하여 **원하는 게임을 보유한 카페를 검색할 수 있도록 만드는 프로젝트**입니다.

**Key Features**

* 웹 크롤링을 통한 카페별 보유 게임 데이터 수집
* Apache Airflow 기반 주기적 데이터 수집 및 ETL 자동화
* BoardGameGeek API를 활용한 게임 메타데이터 수집
* 서로 다른 데이터 소스의 게임 정보 정규화 및 통합
* PostgreSQL 기반 데이터 저장 구조 설계
* 게임명, 플레이 인원, 난이도 등을 활용한 검색 데이터 구성

**Data Flow**

`Web Crawling / API → Airflow → Data Processing → PostgreSQL → Search Service`

🔗 **Repository:** `https://github.com/cjw1645/boardgame_finder`

---

## 🧊 Icecat Product Data Pipeline

**상품별로 서로 다른 Feature 구조를 처리하는 제품 데이터 수집 파이프라인**

> `Python` · `REST API` · `JSON` · `ETL`

Icecat Product API를 분석하여 제품별 `featuregroups` 데이터를 수집하고
구조화된 형태로 저장하기 위한 데이터 파이프라인을 설계한 프로젝트입니다.

**Key Features**

* Icecat API 응답 구조 분석
* Product ID 기반 상품 데이터 수집
* `featuregroups` 및 Feature 데이터 순회 처리
* 상품별로 달라지는 Feature 구조 처리
* 중복 데이터 식별을 위한 Hash 기반 처리 구조 설계
* 다수 상품 수집을 고려한 확장 가능한 ETL 구조 설계

**Data Flow**

`Product ID → Icecat API → Feature Extraction → Transform → Structured Data`

🔗 **Repository:** `https://github.com/cjw1645/buildflow`

---

<br>

🎯 Engineering Interests

Data Pipeline · ETL / ELT · Workflow Orchestration · Data Modeling · Data Quality · Cloud Data Engineering

<br>
