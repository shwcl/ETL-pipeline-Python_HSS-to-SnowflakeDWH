# ETL-pipeline-Python_HSS-to-SnowflakeDWH

OBJECTIVE

The client - Guyana Telephone and Telegraph (GTT) - launched an LTE service to the public and they wanted to understand the penetration of LTE subscribers in several areas, analyze the growth pattern of this customer base and gather other useful insights. 
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

 
