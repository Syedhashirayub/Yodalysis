# Data Engineering Yodalysis Project by Syed Hashir

## Overview

This project aims to securely manage, streamline, and analyse the structured and semi-structured YouTube video data based on the video categories and trending metrics.

## Architecture Diagram
<img src="architecture.jpeg">

## Project Goals
1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
6. Reporting — Build a dashboard to get answers to the question we asked earlier

## Services we will be using
1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS IAM: This is nothing but identity and access management that enables us to securely manage access to AWS services and resources.
3. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
4. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
5. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
6. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

![Screenshot 2023-11-07 at 10 03 14 AM](https://github.com/Syedhashirayub/Yodalysis/assets/100124377/358a4023-2674-4342-8459-7619bd205e08)

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on popular YouTube videos over the covers daily. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. Video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new




