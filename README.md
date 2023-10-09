# f1-racing-data-engineering-and-analysis
## Overview

This project aims to securely manage, streamline, and perform analysis on the Formula 1 races, drivers, constructors, qualifying, circuits, lap times, pit stops, championships from 1950 till the latest 2023 season.

## Project Goals
1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
6. Reporting — Build a dashboard to get answers to the question we asked earlier

## Services we will be using
1. Data Lake Gen 2: Data Lake Gen 2 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. Data Factory: Data factory is used to ingest the raw data into the azure data lake 2.
3. Azure Databricks:DataBricks is used to process and transform the data.
4. Azure Synapse Analytics:Azure Synapse Analytics is used to gain insights from their data. It provides a serverless environment for data warehousing and big data analytics.

## Dataset Used
The dataset consists of all information on the Formula 1 races, drivers, constructors, qualifying, circuits, lap times, pit stops, championships from 1950 till the latest 2023 season.

https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020

## Architecture Diagram
<img src="architecture.jpg">
