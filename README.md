# Youtube_Data_analysis
The Insights we are trying to encover here are-

What are the most-watched video categories on YouTube, and how can I align my ads with trending content to maximize visibility?

What key factors influence a video’s popularity on YouTube (e.g., views, engagement, duration), and how can I leverage these insights to optimize my ad targeting and performance?

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

Amazon S3


AWS IAM 


QuickSight 

AWS Glue 


AWS Lambda 


AWS Athena 

Dataset Description

This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations.

Two data files:

Region-contains video information from different regions
Category-Contains information about different categories of videos
