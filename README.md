# YouTube Analysis on AWS Data Engineering Project

**Overview**

This project implements an end-to-end YouTube video analysis pipeline leveraging key AWS services such as S3, Lambda, and Athena. The goal is to process and analyze YouTube data to derive insights that support data-driven decision-making and trend forecasting.

**Architecture**
![Architecture Diagram](https://github.com/rohankodavalla/Youtube-Analysis-AWS/raw/latest_branch/architecture.jpeg)

-------------------------------------------------------------------------------------------------------------------------------------------------

**Key Features**:
- **Automated Data Extraction**: Efficiently retrieves YouTube video data and stores it in Amazon S3 for further processing.
- **Serverless Data Processing**: Uses AWS Lambda to transform raw data into structured formats, reducing manual intervention.
- **Advanced Analytics**: Leverages AWS Athena to query data directly from S3, enabling fast, interactive analysis.
- **Scalable Design**: The architecture is designed to scale as the volume of YouTube video data increases, utilizing cloud-native technologies.

This project aims to securely manage, streamline, and analyze the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

-------------------------------------------------------------------------------------------------------------------------------------------------

**Project Obejectives**:
1. **Data Ingestion**: Design an efficient pipeline to collect YouTube video data from multiple sources.
2. **ETL Process**: Implement an ETL system to transform raw data into a consumable format for analytics.
3. **Data Lake**: Use Amazon S3 as a centralized repository to store and manage large datasets.
4. **Scalability**: Ensure the system can handle increasing data volumes with minimal performance degradation.
5. **Cloud-Based Architecture**: Leverage AWS for scalable, serverless processing and storage solutions.
6. **Business Intelligence**: Build a reporting system to visualize and extract actionable insights from the data.

-------------------------------------------------------------------------------------------------------------------------------------------------

**AWS Services used**:
1. Amazon S3: Scalable object storage service that ensures high availability and durability of stored data.
2. AWS IAM: Manages secure access to AWS resources, ensuring proper permissions are in place.
3. Amazon QuickSight: A fully managed business intelligence service to build interactive dashboards and visualizations.
4. AWS Glue: Serverless data integration service that simplifies the discovery, preparation, and combination of data for analysis.
5. AWS Lambda: Runs code without the need to provision or manage servers, enabling cost-effective serverless computing.
6. AWS Athena: Query service for S3 that allows direct querying of data using SQL, without the need to load data into a database.

-------------------------------------------------------------------------------------------------------------------------------------------------

**Dataset Used**
The dataset used in this project is sourced from Kaggle and contains CSV files with statistics of daily trending YouTube videos. The data includes video title, channel title, publication time, tags, views, likes, dislikes, description, and comment count. This dataset spans multiple regions and provides insights into video trends across various countries.

Link to Kaggle Dataset-
https://www.kaggle.com/datasets/datasnaek/youtube-new

