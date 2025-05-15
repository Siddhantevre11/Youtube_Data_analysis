# Youtube_Data_analysis

we have a client, who wants to run ads for his product on social media and he chose YouTube

He wants to find answers to these questions

Find top categories of videos people watch on YouTube
What factors affect how popular a YouTube video will be?

Why YouTube?

YouTube is the 2nd most visited website after Google

![image](https://github.com/Siddhantevre11/Youtube_Data_analysis/assets/114145391/ff415bb4-3af6-471b-8136-9323fd81aa75)


Our goal and success criteria

Data Ingestion — Build a mechanism to ingest data from different sources
ETL System — We are getting data in raw format, transforming this data into the proper format
Data lake — We will be getting data from multiple sources so we need centralized repo to store them
Scalability — As the size of our data increases, we need to make sure our system scales with it
Cloud — We can’t process huge amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
Reporting — Build a dashboard to get answers to the question we asked earlier

Our Architecture Diagram For This Project

![image](https://github.com/Siddhantevre11/Youtube_Data_analysis/assets/114145391/31e06eab-9d1c-438f-8285-070d126f4ebf)

Services we will be using

Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance. Users may save and retrieve any quantity of data using Amazon S3 at any time and from any location.


AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely. One can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources. It is a feature of AWS with no additional charge.


QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud. It is the first BI service to offer pay-per-session pricing, where you only pay when your users access their dashboards or reports, making it cost-effective for large-scale deployments. It can connect to various sources like Redshift, S3, Dynamo, RDS, files like JSON, text, CSV, TSV, Jira, Salesforce, and on-premises oracle SQL-server.


AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development. It runs Spark/Python code without managing Infrastructure at a nominal cost. You pay only during the run time of the job. Also, you pay storage costs for Data Catalog objects. Tables may be added to the AWS Glue Data Catalog using a crawler. The majority of AWS Glue users employ this strategy. In a single run, a crawler can crawl numerous data repositories. The crawler adds or modifies one or more tables in your Data Catalog after it’s finished.


AWS Lambda: Lambda is a computing service that allows programmers to run code without having to create or manage servers. Lambda executes the code on high-availability computing infrastructure and manages all aspects of it, including server and operating system maintenance, capacity provisioning and automated scaling, code monitoring, and logging. Lambda allows you to run code for almost any form of application or backend service.


AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3. It is serverless and supports many data formats e.g CSV, JSON, ORC, Parquet, and AVRO.


Dataset Description

This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations.

Two data files:

Region-contains video information from different regions
Category-Contains information about different categories of videos
