## Project's Description
Ingest data from API with <b>Python</b> , store raw data in <b>Google Cloud Storage</b> , build data pipeline with <b>Apache Spark</b> , load data into <b>Google BigQuery</b> then create dashboard with <b>Google Looker Studio</b>

## Data Lake - Google Cloud Storage
1. Create Project
2. Create Bucket (can create with either UI or CLI gsutil)
   - Select data center : I'll choose Singapore.
   - Others settings is default
3. Go in bucket and upload the file (can upload with UI or CLI gsutil or Python SDK)

gsutil documentaion : https://cloud.google.com/storage/docs/gsutil

## Data Pipeline - Cloud Composer + Apache Airflow + DAGs
We use <b>Cloud Composer</b> as an environment.
1. Go to <b>Cloud Composer</b> in <b>Google Cloud Console</b>
2. Create <b>Cloud Composer 1</b>
   - name an environment
   - Location (nearest from your country) : this case I'll select "us-central1"
   - Machine type : n1-standard-2 (RAM 7.5 GB)
   - Disk Size : 20 GB
   - Image Version : select the latest
   - Python version : 3
