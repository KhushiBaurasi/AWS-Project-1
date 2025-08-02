# 📺 MediaStream Analytics

A real-time analytics pipeline for tracking **viewership logs**, **ad revenue**, and **user engagement** using AWS and Snowflake. Designed with a **Lambda Architecture** for real-time + batch processing.

---

## 🚀 Project Summary

MediaStream Analytics enables media companies to track **audience behavior** and **monetization metrics** with scalable AWS cloud services and Snowflake.

- 🌊 Real-time ingestion from CSV logs into Snowflake and S3
- ❄️ Snowflake-powered dashboards for revenue and viewer insights
- 🧊 Iceberg format support for efficient batch queries using Glue

---

## 🧰 Tech Stack

| Service | Role |
|--------|------|
| **AWS EC2** | Hosts Python script to stream CSV logs |
| **Amazon Kinesis** | Real-time ingestion pipeline |
| **Apache Spark on EMR** | Structured streaming and transformations |
| **Amazon S3** | Raw and processed data storage |
| **AWS Glue** | ETL and batch Iceberg table creation |
| **Snowflake** | Cloud Data Warehouse for analytics |
| **Apache Iceberg** | Enables large-scale batch analytics |
| **Power BI / Quicksight** | Visual reporting and dashboards |

---

## 🗂️ Architecture Overview


