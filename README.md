# Zomato-data-lake-project
End-to-end Zomato Data Lake built on Google Cloud Platform using Spark, BigQuery, and Cloud Storage for scalable analytics.
#gcp #spark #bigquery #datalake #dataengineering #zomato

# 🍴 Zomato Data Lake Project using Apache Spark, GCS, and BigQuery

An end-to-end data lake built using **Google Cloud Platform**, **Apache Spark**, and **BigQuery** to process, clean, and analyze Zomato restaurant data efficiently at scale.

---

## 🧩 Project Overview

The project demonstrates how to design a **data lake architecture** where raw Zomato datasets are ingested into **Google Cloud Storage (GCS)**, processed using **Apache Spark**, and loaded into **BigQuery** for analytical queries and reporting.

---

## 🏗️ Architecture

[Zomato Dataset]
↓
[Google Cloud Storage - Raw Zone]
↓
[Apache Spark on Dataproc / PySpark]
↓
[Transformed Data - Processed Zone]
↓
[BigQuery - Analytics Layer]


---

## ⚙️ Tools & Technologies

| Category | Tool |
|-----------|------|
| Cloud Platform | Google Cloud Platform (GCP) |
| Storage | Google Cloud Storage (GCS) |
| Processing | Apache Spark (PySpark) |
| Data Warehouse | BigQuery |
| Visualization | Looker Studio / Power BI |
| Language | Python |

---

## 📂 Project Structure

Zomato-DataLake-Project/
│
├── data/
│ ├── raw/ # Raw Zomato dataset (CSV)
│ ├── processed/ # Transformed data ready for BigQuery
│
├── scripts/
│ ├── ingestion_spark.py # Ingest data from GCS to Spark
│ ├── transform_spark.py # Data cleaning and transformation
│ ├── load_to_bigquery.py # Load final data into BigQuery
│
├── notebooks/
│ ├── zomato_etl.ipynb # End-to-end PySpark ETL notebook
│
├── requirements.txt
├── README.md
└── LICENSE


---

## 🚀 Key Features

- ✅ Data ingestion from **Google Cloud Storage**
- ✅ Transformation & cleaning using **PySpark**
- ✅ Analytical data loaded into **BigQuery**
- ✅ Scalable & serverless data pipeline
- ✅ Ready for BI tools like **Looker Studio**

---

## 🧰 Setup Instructions

### 1️⃣ Clone this repository
```bash
git clone https://github.com/yourusername/Zomato-data-lake-project.git
cd Zomato-data-lake-project

👩‍💻 Author

Rithika Sri
📧 rithikasri739@gmail.com

🌐 linkedIn - https://www.linkedin.com/in/rithika-sri-p-585b59328?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

📜 License

Licensed under the MIT License.


