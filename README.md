## Project's Description
Ingest data from API with <b>Python</b> , store raw data in <b>Google Cloud Storage</b> , build data pipeline with <b>Apache Spark</b> , load data into <b>Google BigQuery</b> then create dashboard with <b>Google Looker Studio</b>

## Data Lake - Google Cloud Storage
1. Create Project
2. Create Bucket (can create with either UI or CLI gsutil)
   - Select data center : I'll choose Singapore.
   - Others settings is default
3. Go in bucket and upload the file (can upload with UI or CLI gsutil or Python SDK)

gsutil documentaion : https://cloud.google.com/storage/docs/gsutil
