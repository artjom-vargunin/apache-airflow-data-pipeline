# Apache Airflow data pipeline
This is final project on data engineering course aimed to implement a data pipeline by using Apache Airflow. Main pipeline stages are Internet Meme data download, cleansing, enrichment, ingestion and analysis by means of machine learning and queries within Postgres, Mongo and Neo4J database systems.
## Setting up environment
1) `docker-compose up airflow-init`
2) `docker-compose up`
3) open `http://localhost:8080`
4) create postgres connection
    * Name - postgres_default
    * Conn type - postgres
    * Host - localhost
    * Port - 5432
    * Database - airflow
    * Username - airflow
    * Password - airflow
