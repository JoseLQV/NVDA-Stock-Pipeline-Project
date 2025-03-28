
# NVDA Stock Data Pipeline  
*End-to-End ETL Pipeline for Yahoo Finance Data*  

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Airflow](https://img.shields.io/badge/Apache_Airflow-2.6+-orange)
![Postgres](https://img.shields.io/badge/Postgres-15+-blue)
![Spark](https://img.shields.io/badge/Apache_Spark-3.5+-red)

## 📌 Overview  
Automated pipeline to extract, transform, and analyze NVIDIA (NVDA) stock data from Yahoo Finance, featuring:  
- **ETL Automation**: Apache Airflow DAGs for scheduled data workflows.  
- **Scalable Storage**: Postgres (structured data) + Minio (S3-compatible raw storage).  
- **Analytics**: Spark for transformations and Metabase for visualization.  

## 🛠️ Tech Stack  
- **Orchestration**: Apache Airflow (Astro CLI for local dev)  
- **Infrastructure**: Docker, Postgres, Minio  
- **Processing**: PySpark  
- **Visualization**: Metabase  



