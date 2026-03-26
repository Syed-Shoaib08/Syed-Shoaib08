<h1 align="center">Hi, I'm Shoaib Syed</h1>
<h3 align="center">Senior Data Engineer | Azure • GCP • Microsoft Fabric • Power BI</h3>

---

## About Me

Senior Data Engineer with 5+ years of experience designing and delivering production-grade data platforms across **healthcare** and **financial services** domains. Specialized in cloud-native architectures on **Microsoft Azure** and **Google Cloud Platform**, with deep expertise in real-time streaming, Medallion Architecture, distributed computing, and enterprise BI.

Proven track record architecting scalable ETL/ELT pipelines processing terabytes of structured and unstructured data using Azure Data Factory, Databricks, Synapse Analytics, Microsoft Fabric, and GCP BigQuery. Extensive experience with data warehousing, Delta Lake, Apache Spark, and multi-cloud platform engineering.


---

## Professional Experience

**Senior Data Engineer — Healthcare Domain**
- Architected multi-cloud data platform processing clinical data monthly across Azure Data Lake Storage Gen2, Synapse Analytics, and Databricks
- Engineered production ETL/ELT pipelines using Azure Data Factory and Python processing Epic, Cerner, and HL7 clinical feeds
- Designed Medallion Architecture on Azure Data Lake with Delta Lake format, ACID transactions, and schema enforcement
- Built real-time streaming pipelines using Azure Event Hubs and Databricks Structured Streaming for patient monitoring
- Developed data governance framework using Azure Purview for data cataloging, lineage tracking, and HIPAA-compliant access controls
- Implemented change data capture using Azure Data Factory mapping data flows and Delta Lake merge operations
- Built CI/CD pipelines using Azure DevOps with YAML-based workflows for automated deployment of Data Factory pipelines and Databricks notebooks
- Delivered interactive Power BI reports and dashboards for clinical operations providing insights on patient flow, resource utilization, and quality metrics

**Senior Data Engineer — Financial Services Domain**
- Designed and modernized legacy financial systems migrating 35+ ETL workflows to hybrid cloud architecture across Azure and AWS
- Engineered scalable data pipelines using Azure Data Factory and AWS Glue processing millions of financial transactions daily
- Built distributed computing solutions using Azure Databricks and AWS EMR Spark clusters for large-scale mortgage data processing
- Developed real-time fraud detection pipelines using Apache Kafka and Azure Event Hubs processing mortgage applications at high throughput
- Implemented data warehousing on Azure Synapse Analytics and AWS Redshift with conformed dimensions supporting loan servicing analytics
- Built comprehensive data quality framework implementing 120+ validation rules with configurable thresholds
- Implemented NoSQL solutions using Azure Cosmos DB and AWS DynamoDB for customer profile data at scale
- Developed Apache Airflow DAGs orchestrating complex cross-cloud workflows with SLA monitoring and retry logic

**Data Engineer — Financial & Robotics Domain**
- Built end-to-end streaming ETL pipelines using Azure Event Hubs, Apache Beam on GCP Dataflow, and Apache Kafka
- Designed data warehouse on AWS Redshift and Azure Synapse Analytics with star schema for robotics telemetry analytics
- Implemented real-time anomaly detection using GCP Pub/Sub, Azure Event Hubs, and AWS Kinesis with sub-second latency
- Built data lake on Azure Data Lake Storage Gen2, AWS S3, and GCP Cloud Storage implementing Medallion Architecture with lifecycle management

---

## Tech Stack

**Cloud Platforms**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)

**Data Engineering**

![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-000000?style=flat-square&logo=microsoft&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-003366?style=flat-square&logo=databricks&logoColor=white)
![Azure Data Factory](https://img.shields.io/badge/ADF-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Synapse Analytics](https://img.shields.io/badge/Synapse-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![ADLS Gen2](https://img.shields.io/badge/ADLS_Gen2-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

**Languages & Tools**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D4?style=flat-square&logo=azure-devops&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Domains**

Healthcare Data Engineering — Clinical data platforms, HIPAA-compliant pipelines, patient monitoring systems

Financial Services Data Engineering — Mortgage processing, fraud detection, transaction analytics

---

## Featured Projects

### Real-Time ICU Patient Monitoring Platform
> Azure • Microsoft Fabric • ADLS Gen2 • Python • Power BI • Delta Lake

End-to-end healthcare data engineering platform built on **Medallion Architecture** (Bronze/Silver/Gold). Simulates real-time ICU patient vital signs, applies a **NEWS-based clinical risk scoring engine** across six vital parameters, and delivers live operational insights via a Power BI dashboard hosted on Microsoft Fabric with Direct Lake connectivity.

**Key highlights:**
- Automated daily pipeline orchestrated via Microsoft Fabric — 4 notebooks executing in sequence
- Partition-aware processing — reads only latest datetime partition preventing historical data accumulation
- Microsecond timestamp enforcement for full Microsoft Fabric Spark compatibility
- Silver layer full overwrite pattern ensuring deterministic Gold aggregations
- Power BI Direct Lake mode — zero-copy querying over Delta tables, no import or refresh overhead
- Clinical conditional formatting aligned to NEWS threshold standards
