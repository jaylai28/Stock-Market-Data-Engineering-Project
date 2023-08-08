# Stock-Market-Data-Engineering-Project-Using-Kafka
This is an End-To-End Data Engineering Project, focusing on Real-Time Stock Market Data processing through the utilisation of Kafka. The data ingestion process begins with a CSV file, which subsequently undergoes a transformation into JSON format through Apache Kafka and Python. The JSON data is then seamlessly deposited into an AWS S3 bucket, creating a centralised repository.

AWS Glue Crawler then organizes and crawls the data from the S3 bucket and creates a table in AWS Athena, for detailed analysis. This comprehensive process showcases the journey from data ingestion and transformation to storage and analysis.


# Architecture
![Architecture](https://github.com/jaylai28/Stock-Market-Data-Engineering-Project/assets/69461406/87b0a6c5-f3f0-420f-bc7d-ca8055033a9c)



# Technologies Used
- Programming Language - Python
- Amazon Web Service (AWS)
- Apache Kafka

1. S3 (Simple Storage Service)
2. Athena
3. SQL
4. Glue Crawler
5. Glue Catalog
6. EC2
