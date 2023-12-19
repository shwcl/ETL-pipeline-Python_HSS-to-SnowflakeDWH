# Data Engineering Project
## Project Description
This project implemented an ETL pipeline to load 120000+ rows of data of from an Home Subscriber Server (HSS) stored in semi-structred format to a Snowflake data warehouse.
<br></br>

## Background
The company launched an LTE service to the public and the Analytics Team wanted to understand the penetration of LTE subscribers in several areas, analyze the growth pattern of this customer base and gather other useful insights. 
After discussing requirements with the Analytics Team, it was destablished that the required data was stored on a Home Subscriber Server (HSS) in log files in semi-structed format. So we proposed to develop a data pipeline to parse and load the data to the Snowflake data warehouse on a scheduled basis.
<br></br>

## Objective
To build an ETL pipeline to load data of LTE subscribers stored on an Home Subscriber Server (HSS) to the Snowflake data warehouse.
<br></br>


## data Architecture Diagram
![HSS_Snowflake_ETL](https://github.com/shwcl/ETL-pipeline-Python_HSS-to-SnowflakeDWH/assets/52106536/09e3b7a1-cc01-425b-81f3-31e2fb8d69d3)
<br></br>

## Pentaho Data Integration ETL Job
![pentaho_ETL_image1](https://github.com/shwcl/ETL-pipeline-Python_HSS-to-SnowflakeDWH/assets/52106536/ee581452-8664-401f-b4c6-c8b45d4083ab)
<br></br>

## Development Process
Steps:

1. Create a staging table and a destination table on Snowflake DWH

2. Develop a script a Python script to do the following:
   - Extract semi-structured data from the HSS to a text file
   - Parse the data in the text file and output the result to a CSV file
   - Load the data from the CSV file to the staging table on Snowflake

4. Create an ETL job in Pentaho Data Integration to transform data in staging table using SQL and load the data to a destination table
<br></br>


## Tools Used
Python, SQL, Pentaho Data Integration and Snowflake DWH
<br></br>

## Impact
The reporting done by the client using analysis-ready data delivered by the data pipeline I developed led to or significantly contributed to the company re-introducing the specific service to the public a couple years later with the aim of expanding its customer base.

 
