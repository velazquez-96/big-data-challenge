# Cloud ETL

This activity is focused first, on performing a ETL process completely in the cloud and upload a DataFrame to an RDS instance. And second, on using PySpark to perform a statistical analysis of selected data. There are two files in ths activity centered in different tasks:

1. Create DataFrames to match production-ready tables from two big Amazon customer review datasets.
2. Analyze whether reviews from Amazon's Vine program are trustworthy. 

For the first part the following activities are made:

* Use the schemata to create tables in your RDS database.

* Using Google Colaboratory two datasets from the list at [review dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) are **extracted** , one into each notebook.

* **Transform** the dataset to fit the tables in the [schema file](Schema.sql) created

* **Load** the DataFrames that correspond to tables into an RDS instance.

And for the second part the following activities are made:

* Investigate whether Vine reviews are free of bias. 
* Use PySpark to analyze the data.

## Features

* Cloud ETL
* Use of Pyspark
* Create a PostgreSQL DB Instance and connecting to a Database on a PostgreSQL DB Instance 

## Built with 

* Google Colaboratory
* AWS
* PostgreSQL

## Outcomes

* [Report](amazon_analysis.md) containing findings and analysis of Amazon's Vine program

* Transformed and loaded tables into an RDS instance


