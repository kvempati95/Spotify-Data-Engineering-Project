![image](https://github.com/kvempati95/Spotify-Data-Engineering-Project/assets/143650052/f66b5102-ddc4-4a3a-9d40-eeba9fe2900f)# Spotify-Data-Engineering-Project

## Introduction
In this project, we will build an ETL (Extract, Transform, Load) pipeline using the Spotify API on AWS. The pipeline will retrieve data from the Spotify API, transform it to the desired format, and then load it to the AWS Data Store.

## Architecture Diagram
![image](https://github.com/kvempati95/Spotify-Data-Engineering-Project/assets/143650052/2035babd-faef-4cf2-86ee-8dfb706007cb)

## About Dataset/API
This API contains information about music artists, albums, and songs - Spotify API

## Services Used
**Amazon S3 (Simple Storage Service):** Scalable object storage for storing and retrieving any amount of data from anywhere on the web, commonly used for large media files, data backups, and static website files.
**AWS Lambda:** Serverless computing service allowing execution of code in response to events like changes in S3, DynamoDB, or other AWS services, without managing servers.

**Amazon CloudWatch:** Monitoring service for AWS resources and applications, used to collect and track metrics, monitor log files, and set alarms.

**Glue Crawler:** Fully managed service for automatically crawling data sources, identifying data formats, and inferring schemas to create an AWS Glue Data Catalog.

**AWS Glue Data Catalog**: Fully managed service created by Glue Crawler, automatically identifying data formats and inferring schemas to create a catalog that integrates with other AWS services like Athena.

**Amazon Athena:** Interactive query service for analyzing data in Amazon S3 using standard SQL, can utilize the Glue Catalog or other S3 buckets for analysis.
