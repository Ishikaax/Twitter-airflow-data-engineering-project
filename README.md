# Twitter-airflow-data-engineering-project

This project demonstrates a data pipeline built using Python and Apache Airflow to extract, transform, and load (ETL) data from Twitter's API. The pipeline is deployed on an AWS EC2 instance, with data stored in Amazon S3. The key steps include:

Twitter Data Extraction: Connecting to the Twitter API using OAuth to retrieve tweet information like username, tweet text, likes, retweets, and creation date. The extracted data is processed using Python and Pandas.
Data Transformation: The extracted tweet data is transformed into a structured format (CSV) using Pandas.
Data Storage: The processed data is stored in an Amazon S3 bucket, ensuring scalability and persistence.
Apache Airflow: Airflow is used to automate and schedule the entire ETL process. A Directed Acyclic Graph (DAG) is set up to define the workflow, with Python operators handling task execution.
This project showcases the integration of Twitter API, Python, AWS (EC2, S3), and Airflow for building an efficient and scalable data pipeline.
