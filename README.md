<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Srimathi%20Sekaran&fontSize=50&fontColor=ffffff&fontAlignY=38&desc=Junior%20Data%20Engineer%20%7C%20Python%20%7C%20Cloud%20Data%20Systems&descSize=17&descAlignY=60&descColor=a8d8ea" alt="Srimathi Sekaran — Junior Data Engineer, Python and Cloud Data Systems" width="100%" />

<a href="https://www.linkedin.com/in/srimathi-sekaran-335179274"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:csesrimathi@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/Srimathinithya/portfolio"><img src="https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio repository" /></a>
<a href="https://github.com/Srimathinithya/data-engineering-projects"><img src="https://img.shields.io/badge/Data_Engineering_Projects-203A43?style=for-the-badge&logo=github&logoColor=white" alt="Data engineering projects" /></a>

**Building reliable pipelines, analytical data systems, and Python applications.**

Coimbatore, Tamil Nadu, India

</div>

---

## 👩‍💻 About Me

I'm a **Junior Data Engineer at Aggregate Intelligence India Private Limited**, working on hospitality data pipelines, cloud migrations, and SQL analytics since **October 2025**.

- Built ETL workflows migrating **500+ GB** of hospitality data across AWS S3, Wasabi, PostgreSQL, and MongoDB.
- Automated competitor reporting and refresh workflows, saving **5 hours per week**.
- Applied data quality checks across Airflow- and cron-orchestrated batch workflows, reducing data errors by **50%**.
- Built concurrent API ingestion with Redis deduplication, blocking up to **70% of duplicate payloads** before MongoDB writes.
- Developed a **Credential Management Platform** with role-based approvals and just-in-time PostgreSQL access.

```python
class DataEngineer:
    name = "Srimathi Sekaran"
    role = "Junior Data Engineer"
    company = "Aggregate Intelligence India Private Limited"
    location = "Coimbatore, India"

    focus = [
        "ETL / ELT pipelines and cloud data migration",
        "Data warehousing and SQL analytics",
        "REST API ingestion and FastAPI services",
        "Data quality, orchestration, and observability",
    ]
    ai_toolkit = ["LangChain", "LangGraph", "LlamaIndex", "n8n AI Agents"]
```

## 💼 Experience

### Junior Data Engineer · Aggregate Intelligence India Private Limited
**October 2025 – Present**

- Engineer Python, Pandas, and Apache Spark pipelines for hospitality datasets, including JSON/BSON flattening and REST-based ingestion with FastAPI.
- Build competitor benchmarking reports with CTEs, window functions, and data partitioning.
- Orchestrate distributed batch workflows with Apache Airflow and cron, supported by Docker, execution logging, monitoring, and validation.
- Design PostgreSQL warehousing schemas and use PySpark for distributed transformations and scalable analytical processing.

**Earlier training**

- **Software Testing Trainee · CloudZoo India Softwares:** Stress and load testing to assess scalability and reliability and identify pre-deployment defects.
- **Web Developer Trainee · Gateway Software Solutions:** Interactive HTML, CSS, and JavaScript components with cross-browser compatibility.

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

| Area | Technologies & practices |
| :--- | :--- |
| Languages & libraries | Python, SQL, Java, Pandas, NumPy, PyMongo |
| Data engineering | ETL/ELT, Apache Spark, PySpark, batch processing, Delta Tables, data cleaning and transformation, distributed processing |
| Warehousing & analytics | Data modeling, schema design, partitioning, CTEs, window functions, materialized views |
| Databases & storage | PostgreSQL, MongoDB, MongoDB Atlas, NoSQL, Redis, AWS S3, Wasabi Object Storage |
| APIs & applications | FastAPI, REST API development and integration, automated ingestion, microservices, Pydantic, Next.js |
| Orchestration & DevOps | Apache Airflow, cron scheduling, Docker, Git, pipeline monitoring and alerting, execution logging, data validation |
| AI engineering & LLM systems | LangChain, LangGraph, LlamaIndex, n8n AI Agents |
| ML & MLOps projects | Scikit-learn, MLflow, Statsmodels, ARIMA, Isolation Forest |

## 🚀 Featured Projects

### 🔐 Credential Management Platform

A role-based database access platform built with **FastAPI, Next.js, PostgreSQL, and AWS Secrets Manager**.

- Separate **user, admin, and super-admin** workspaces.
- Access requests tied to a specific **process and server target**, with database roles assigned during approval.
- **Just-in-time PostgreSQL users**, one-time password display, and automatic access revocation on expiry.
- Credential-package management with audit and rotation history for access tracking.

### 🔄 Data Engineering & Ingestion

| Project | What it does | Core stack |
| :--- | :--- | :--- |
| [Cloud Data Migration & ETL Platform](https://github.com/Srimathinithya/data-engineering-projects/tree/master/01-cloud-data-migration-etl) | Multi-stage migration of 500+ GB of hospitality data across cloud storage and databases, using partitioning, schema validation, and delta loads. | Python, Spark, PostgreSQL, MongoDB, AWS S3, Wasabi |
| [Real-Time API Ingestion Pipeline](https://github.com/Srimathinithya/data-engineering-projects/tree/master/02-realtime-api-ingestion) | Paginated REST ingestion normalizing 15+ JSON schemas into MongoDB, with automated hourly refreshes. | Python, PyMongo, Pandas, cron |
| [Advanced Real-Time Ingestion](https://github.com/Srimathinithya/data-engineering-projects/tree/master/10-advanced-realtime-ingestion) | Concurrent producer-consumer ingestion with Pydantic validation and Redis caching, blocking up to 70% of duplicate payloads before bulk upserts. | Python, Redis, MongoDB, Pydantic, Docker |
| [Student Data Management Platform](https://github.com/Srimathinithya/data-engineering-projects/tree/master/05-student-data-platform) | FastAPI and MongoDB CRUD platform with indexed queries and Spark bulk ingestion. | FastAPI, MongoDB, Spark, Docker |

### 📊 Data Warehousing & SQL Analytics

| Project | What it does | Core stack |
| :--- | :--- | :--- |
| [Attendance Data Warehouse](https://github.com/Srimathinithya/data-engineering-projects/tree/master/03-attendance-data-warehouse) | Spark batch processing and partitioned warehouse reporting for 1,000+ student records, reducing report generation from hours to minutes. | Spark, PostgreSQL, SQL, star schema |
| [Competitor Price Volatility Analytics](https://github.com/Srimathinithya/data-engineering-projects/tree/master/04-competitor-price-analytics) | Pricing benchmarks and volatility scorecards with reusable SQL views and automated email reports. | PostgreSQL, CTEs, window functions, Pandas, SMTP |

### 🔭 Observability, Machine Learning & MLOps

| Project | What it does | Core stack |
| :--- | :--- | :--- |
| [ETL Monitoring & Alerting System](https://github.com/Srimathinithya/data-engineering-projects/tree/master/06-etl-monitoring-alerting) | Pipeline checks for schema drift, row counts, and execution timing, with automated failure alerts. | Python, logging, SMTP, Pandas |
| [AIOps Predictive Maintenance](https://github.com/Srimathinithya/data-engineering-projects/tree/master/07-aiops-predictive-maintenance) | Unsupervised anomaly detection on machine telemetry using Isolation Forest. | Scikit-learn, Pandas, PostgreSQL |
| [Sales Forecasting API](https://github.com/Srimathinithya/data-engineering-projects/tree/master/09-sales-forecasting-analytics) | ARIMA forecasting serving 30-day predictions through FastAPI; integration into planning reduced inventory discrepancies by 30%. | FastAPI, Statsmodels, PostgreSQL, Docker |
| [Customer Satisfaction MLOps](https://github.com/Srimathinithya/data-engineering-projects/tree/master/08-customer-satisfaction-mlops) | Random Forest classification with MLflow experiment logging, metric tracking, and model registry management. | MLflow, Scikit-learn, Pandas, Git |

Explore the code and setup guides in my [data-engineering-projects repository](https://github.com/Srimathinithya/data-engineering-projects).

## 📊 GitHub Activity

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Srimathinithya&show_icons=true&theme=tokyonight&hide_border=true" alt="Srimathi's public GitHub statistics" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Srimathinithya&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Languages used across public GitHub repositories" />

</div>

## 📫 Let's Connect

| Channel | Link |
| :--- | :--- |
| LinkedIn | [Srimathi Sekaran](https://www.linkedin.com/in/srimathi-sekaran-335179274) |
| Email | [csesrimathi@gmail.com](mailto:csesrimathi@gmail.com) |
| GitHub | [Srimathinithya](https://github.com/Srimathinithya) |
| Portfolio source | [portfolio](https://github.com/Srimathinithya/portfolio) |

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" alt="" width="100%" />
</div>
