<div align="center">

<img src="./assets/header.gif" width="100%" alt="Srimathi Sekaran — Engineering data into impact. Data engineering, Python, and cloud systems." />

# Hi, I’m Srimathi Sekaran

**Junior Data Engineer · Python Developer · Cloud Data Systems**

I build data pipelines for pricing analysis and use machine learning and computer vision to match hotel listings.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-d4f680?style=for-the-badge&logo=linkedin&logoColor=101311)](https://www.linkedin.com/in/srimathi-sekaran-335179274)
[![Email](https://img.shields.io/badge/Email-d4f680?style=for-the-badge&logo=gmail&logoColor=101311)](mailto:csesrimathi@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-252f23?style=for-the-badge&logo=github&logoColor=d4f680)](https://srimathinithya.github.io/portfolio/)
[![Projects](https://img.shields.io/badge/Explore_my_projects-252f23?style=for-the-badge&logo=github&logoColor=d4f680)](https://github.com/Srimathinithya/data-engineering-projects)

**Coimbatore, India** · **Aggregate Intelligence India Private Limited**

</div>

---

## Recent work

**Hotel record and image matching.** I worked on matching listings from different providers to the same hotel. A histogram gradient boosting model scores candidate records, and uncertain matches go to human review. I built an OpenCV tool that uses SHA-256 to spot identical files and SIFT features with RANSAC to verify matches between cropped or resized photos.

**Self-storage pricing.** I worked on comparing similar units at nearby facilities. Accounting for promotions such as a free first month makes it possible to compare effective rates across stores. I also updated PostgreSQL refresh logic to preserve prior-day summaries for price and inventory comparisons.

**Rental car delivery.** I added validation and heartbeat logging to a Python delivery pipeline and automated cleanup of expired data. I also corrected backup error handling so Airflow marks the task as failed when the underlying script fails.

## Public repositories

| Repository | What to look for |
| --- | --- |
| [Data engineering projects](https://github.com/Srimathinithya/data-engineering-projects) | Examples covering ingestion, warehouse design, monitoring, and pricing analytics. |
| [Concurrent API ingestion](https://github.com/Srimathinithya/data-engineering-projects/tree/master/10-advanced-realtime-ingestion) | Pydantic validates incoming records, Redis checks for duplicates, and MongoDB handles bulk writes. |
| [Competitor price analytics](https://github.com/Srimathinithya/data-engineering-projects/tree/master/04-competitor-price-analytics) | PostgreSQL queries and reporting views for comparing prices and tracking volatility. |
| [Credential management system](https://github.com/Srimathinithya/credential_management_system) | A FastAPI and PostgreSQL project for requesting, approving, and expiring temporary database access. |

## Tools I use

- **Data engineering** — Python, SQL, pandas, Apache Spark, Apache Airflow
- **Matching and image analysis** — scikit-learn, OpenCV, SIFT, RANSAC
- **Storage and backend development** — PostgreSQL, MongoDB, Redis, AWS S3, FastAPI

## Experience

**Aggregate Intelligence** · Coimbatore, India  
Junior Data Engineer since June 2026. Previously a data engineering intern from October 2025 to June 2026.
