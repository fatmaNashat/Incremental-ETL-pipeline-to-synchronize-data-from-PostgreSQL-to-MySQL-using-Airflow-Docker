<img width="1536" height="1024" alt="ChatGPT Image Nov 5, 2025, 08_51_03 AM" src="https://github.com/user-attachments/assets/20149c06-f35e-4f22-8657-62d4f75f3bf2" />


Incremental ETL Pipeline with Apache Airflow

This project demonstrates a production-style ETL workflow using Apache Airflow to incrementally synchronize data from PostgreSQL to MySQL.

Key Features

Timestamp-based incremental extraction (last_update)

Idempotent upsert logic in MySQL

Airflow Variables for persistent state tracking

Task orchestration using PythonOperators

Fully containerized environment using Docker

Tech Stack

-Apache Airflow

-PostgreSQL

-MySQL

-Python

-Docker

Use Case

Efficiently process only new or updated records, reducing load, improving performance, and ensuring reliable data synchronization.
