# YouTube Trends Data Analytics

## Overview

The project aims to securely manage, streamline and perform analysis on the structured and semi-structured YouTube videos data based on the video categories, trending metrics and insights. By leveraging Amazon Web Services, it aims to uncover patterns in viewer behavior, content performance and channel growth.

## Project Goals
1. Data Ingestion — Build a mechanism to ingest data from different sources.
2. ETL System — Since data is acquired in raw format, it should be transformed into the proper format.
3. Data lake — As data is acquired from from multiple sources, a repository needs to be centralized inorder to store them.
4. Scalability — As the size of the data increases, we must make sure the system scales with it.
5. Cloud — It is difficult to process vast amounts of data on the local computer so we need to use the cloud and for this project we use Amazon Web Services(AWS).
6. Reporting — Build a dashboard to get answers to the questions we want to know.

## Services Used
1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security and performance.
2. AWS IAM: This is an identity and access management service which enables us to manage access to AWS services and resources securely.
3. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
4. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
5. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
6. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

## Project Flow Idea
1. Data Ingestion: Collected data from different sources ingested into an S3 bucket.
2. ETL System: Transformed raw (JSON and CSV) data into a usable format using AWS Glue.
3. Data Lake: Stored large volumes of data in a centralized repository using Amazon S3.
4. Cloud Infrastructure: Efficiently managed and processed data using AWS services such as AWS Lambda, S3, AWS Glue, and Athena.
5. Access Management and Data Security: Utilized AWS Identity and Access Management (IAM) and data encryption to ensure data/service security.
6. Reporting: Provided insights through an interactive dashboard using Amazon QuickSight.

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
<img src="architecture.jpeg">
