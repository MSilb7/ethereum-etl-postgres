# Ethereum ETL PostgreSQL

### Export Ethereum data from BigQuery to CSV files

- Install gcloud and run `gcloud auth login`
- Run `pip install -r requirements.txt`
- Run `export_ethereum_data_bigquery_to_gcs.sh <your_gcs_bucket>`

### Import data from CSV files to Cloud SQL

TODO: 

Postgres config:

temp_file_limit: 2147483647

Add Cloud SQL service account to the bucket.

Create database.