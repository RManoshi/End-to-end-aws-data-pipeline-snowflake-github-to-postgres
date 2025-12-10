# End-to-end-aws-data-pipeline-snowflake-github-to-postgres
End-to-end AWS data pipeline ingesting Snowflake and GitHub data into S3, transforming with AWS Glue, loading into PostgreSQL (RDS), and validating via Tableau.

This repository demonstrates an end-to-end AWS data engineering pipeline that ingests data from multiple sources, processes it using AWS services, and loads it into PostgreSQL for analytics and visualization.

The primary focus of this project is **data engineering** — ingestion, storage, transformation, security, and orchestration.

---

## 📌 Project Architecture (High Level)

- GitHub (CSV data via GitHub Actions) → Amazon S3
- Snowflake sample database → Amazon S3 (raw layer)
- Amazon S3 (raw → curated) using AWS Glue
- Amazon S3 (curated) → Amazon RDS PostgreSQL
- PostgreSQL → Tableau (for validation & basic visualization)

---


