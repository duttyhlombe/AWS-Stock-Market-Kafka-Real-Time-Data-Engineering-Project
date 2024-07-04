# AWS-Stock-Market-Kafka-Real-Time-Data-Engineering-Project

I executed an End-To-End Data Engineering solution for real-time stock market data, leveraging a range of technologies including Python, AWS, Apache Kafka, Glue, Athena, and SQL.

![Architecture (1)](https://github.com/duttyhlombe/AWS-Stock-Market-Kafka-Real-Time-Data-Engineering-Project/assets/124158296/6a6e140f-8ae3-4fc6-90ac-288e1456cf8a)

I thoroughly enjoyed working on this AWS-Stock-Market-Kafka-Real-Time-Data-Engineering-Project during my off-hours, finding satisfaction in designing scalable systems and exploring new technologies.

I incorporated FinTech knowledge to design a system that supports real-time trading algorithms and financial data analysis, focusing on accuracy and performance for market predictions.

Project Execution
Data Ingestion: Utilized Apache Kafka for real-time ingestion of stock market data. Configured Kafka producers to collect live data streams from financial APIs and Kafka consumers to process and analyze this data.

Data Storage: Leveraged AWS S3 for scalable and durable storage of raw stock market data. Implemented data partitioning strategies to manage data efficiently.

Data Processing: Used AWS Glue Crawler to catalog the data and Glue Catalog for schema management. Developed ETL jobs in Glue to clean, transform, and load data for further analysis.

Data Analysis: Employed AWS Athena to run SQL queries on data stored in S3, enabling ad-hoc querying and reporting on stock market trends.

Infrastructure Management: Deployed resources on AWS EC2 and managed Kafka brokers and Zookeeper nodes using OpenJDK Corretto 11.0.23 LTS.


Technologies and Tools
Programming Language: Python
AWS Services: S3 (Simple Storage Service), Athena, Glue Crawler, Glue Catalog, EC2
Apache Kafka: For real-time data streaming
OpenJDK Version: Corretto 11.0.23 (LTS) for Kafka


