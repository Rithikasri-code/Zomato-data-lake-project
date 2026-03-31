# Zomato Data Lake Project

An end-to-end data pipeline built on Google Cloud Platform that ingests, processes, and analyzes Zomato restaurant data at scale. This project was designed to explore how modern data lake architectures work in practice, using real-world tools like Apache Spark and BigQuery.

## What This Project Does

Raw Zomato datasets are uploaded to Google Cloud Storage, processed and cleaned using PySpark, and finally loaded into BigQuery where they can be queried for analytics and reporting. The pipeline is designed to be scalable and can be connected to BI tools like Looker Studio for visualization.

## Architecture

The data flows through three stages. First, raw CSV files (orders and restaurant data) land in a Cloud Storage bucket. From there, a PySpark job handles the cleaning and transformation, outputting structured data into a processed zone. That processed data is then loaded into BigQuery, where it becomes available for analytical queries.

## Tools and Technologies

- **Cloud Platform:** Google Cloud Platform (GCP)
- **Storage:** Google Cloud Storage (GCS)
- **Processing:** Apache Spark (PySpark) via Dataproc
- **Data Warehouse:** BigQuery
- **Visualization:** Looker Studio / Power BI
- **Language:** Python

## Project Structure
```
Zomato-DataLake-Project/
├── data/
│   ├── raw/                    # Raw Zomato CSV files
│   └── processed/              # Cleaned data ready for BigQuery
├── scripts/
│   ├── ingestion_spark.py      # Reads raw data from GCS into Spark
│   ├── transform_spark.py      # Cleaning and transformation logic
│   └── load_to_bigquery.py     # Loads final output into BigQuery
├── notebooks/
│   └── zomato_etl.ipynb        # Full PySpark ETL walkthrough
├── requirements.txt
└── README.md
```

## Setup

Clone the repository and install the dependencies:
```
git clone https://github.com/Rithikasri-code/Zomato-data-lake-project.git
cd Zomato-data-lake-project
pip install -r requirements.txt
```

You will also need a GCP project with Cloud Storage, Dataproc, and BigQuery enabled. Make sure your service account has the appropriate permissions before running the ingestion script.

## Author

Rithika Sri
rithikasri739@gmail.com
[LinkedIn](https://www.linkedin.com/in/rithika-sri-p-585b59328)

## License

This project is licensed under the MIT License.


