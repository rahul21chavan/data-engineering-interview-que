Real-Time Data Engineering Scenario Questions (General Technical)
1. Data Ingestion Scenarios

Your source system provides a full file every day, but you need to load only new or changed records. How would you design this pipeline?

A large CSV file (200GB) arrives daily in cloud storage. How would you efficiently ingest it?

Source data arrives in multiple formats (CSV, JSON, XML). How would you standardize ingestion?

Files sometimes arrive late or are missing. How would your pipeline handle this?

How would you design a pipeline to ingest data from a REST API every hour?

2. Incremental & CDC Scenarios

How would you implement incremental loading when the source does not have a timestamp column?

How would you detect updated and deleted records between two datasets?

Design a solution for Change Data Capture (CDC) using Delta Lake or SQL.

How would you implement Slowly Changing Dimension (SCD Type 2)?

How would you handle duplicate records during incremental loads?

3. Data Quality & Validation

How would you validate incoming data before loading into the warehouse?

What checks would you implement for data quality in a production pipeline?

If row counts between source and target do not match, how would you troubleshoot?

How would you detect and handle null or invalid values?

How would you design automated data validation reports?

4. Performance Optimization

Your Spark job is taking too long to run. How would you troubleshoot?

A join operation is causing performance issues due to data skew. How would you fix it?

How would you optimize a slow SQL query?

A Delta table has millions of small files. How would you optimize it?

How would you decide when to cache data in Spark?

5. Pipeline Failure & Monitoring

Your ETL job failed in production. What steps would you take to investigate?

How would you design retry and alert mechanisms?

How would you implement logging in a data pipeline?

How would you ensure pipeline idempotency (safe re-runs)?

How would you monitor pipeline health and SLA?

6. Data Modeling & Architecture

How would you design a data lake architecture (Bronze, Silver, Gold)?

When would you use a data warehouse vs a data lake?

How would you design a schema for large transactional data?

How would you partition large datasets?

How would you handle schema changes in production?

7. Real-Time & Streaming

How would you design a real-time data pipeline?

How would you handle late-arriving events in streaming?

How would you ensure exactly-once processing?

How would you handle streaming job failures?

When would you choose batch vs streaming?

8. Cloud & Storage Scenarios

How would you design a scalable data lake on AWS/Azure?

How would you securely store sensitive data?

How would you optimize cloud storage costs?

How would you move large on-prem data to the cloud?

How would you manage access control for data?

9. Collaboration & Production Scenarios

How would you handle a requirement change after deployment?

How do you manage version control for data pipelines?

How would you promote code from dev to prod?

How would you design a reusable ETL framework?

How would you document data pipelines for other teams?

10. Business Problem Scenarios

A dashboard is showing incorrect numbers. How would you debug?

Users report data is delayed. How would you investigate?

How would you design a daily sales aggregation pipeline?

How would you handle high-volume event data (millions per hour)?

How would you design a pipeline for near real-time analytics?
