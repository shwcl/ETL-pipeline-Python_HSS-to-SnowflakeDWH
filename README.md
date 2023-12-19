# Data Engineering Project
## Project Description
This project implemented an ETL pipeline to load 120000+ rows of data of from an Home Subscriber Server (HSS) stored in semi-structred format to a Snowflake data warehouse.

## Background
The company launched an LTE service to the public and the Analytics Team wanted to understand the penetration of LTE subscribers in several areas, analyze the growth pattern of this customer base and gather other useful insights. 
After discussing requirements with the Analytics Team, it was destablished that the required data was stored on a Home Subscriber Server (HSS) in log files in semi-structed format. So we proposed to develop a data pipeline to parse and load the data to the Snowflake data warehouse


## Objective
To build an ETL pipeline to load data of LTE subscribers stored on an Home Subscriber Server (HSS) to the Snowflake data warehouse.
<br></br>

MY ROLE

My role as a Data Engineer was to provide the Data Analysis team with the specific data they required. 
The source data was stored in semi-structured format on a Home Subscriber Server (HSS), which generates and stores location-state data on LTE-enabled mobile subscribers.
<br></br>

WHAT I DID

I built an ETL pipeline to load 120000+ rows of location-state data of LTE subscribers from an HSS to the client's DWH. The source data was stored in log files in semi-structured format.
<br></br>

DEVELOPMENT PROCESS

Steps:

1.	Create a staging table and a destination table on Snowflake DWH

2.	Develop a script a Python script to do the following:
	- Extract semi-structured data from the switch to a text file
	- Parse the data in the text file and output the result to a CSV file
	- Load the data from the CSV file to the staging table on Snowflake

3.	Create an ETL job in Pentaho Data Integration to transform data in staging table using SQL and load to the destination table
<br></br>

TOOLS USED

Python, SQL, Pentaho Data Integration and Snowflake DWH
<br></br>

SUMMARY OF PROJECT’S SUCCESS

The reporting done by the client using analysis-ready data delivered by the data pipeline I developed led to or significantly contributed to the company re-introducing the specific service to the public a couple years later with the aim of expanding its customer base.

 
