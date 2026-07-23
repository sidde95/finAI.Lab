# Financial Data Lake Platform

## Business Case
1. Stores all financial data centrally.
2. Preserves histrorical market information.
3. Supports analytical and AI model training.
4. Eliminates duplicate datasets.
5. Enables scalable data ingestion.
6. Improves data quality through validation.
7. Provides governed access to data.
8. Supports regulatory and sufit requirements.
9. Supplies clean data to downstream systems.
10. Becomes the organization's financial data foundation.
---

## Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Data Ingestion | Python API and File Ingestion Services |
| Object Storage | MinIO / Amazon S3 |
| File Format | Apache Parquet |
| Table Format | Apache Iceberg |
| Local Data Processing | Polars |
| Distributed Data Processing | Apache Spark |
| SQL Transformations | dbt |
| Local Query Engine | DuckDB |
| Distributed Query Engine | Trino |
| Data Validation | Great Expectations, Pandera |
| Metadata Catalog | OpenMetadata / DataHub |
| Metadata Database | PostgreSQL |
| Data Lineage | OpenLineage, Marquez |
| Monitoring | Prometheus, Grafana |
| Testing | Pytest |
| CI/CD | GitHub Actions |
