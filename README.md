# Amazon_Vine_Analysis
## Overview
Amazon Vine program analysis is a designed to determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
This project focused on the US major appliance data reviews.

## Resources Used 
* **Source Data:** Amazon review dataset (US major applicance)
* **Tools:** Google Colab Notebook, PostgresSQL, pgAdmin and AWS

## Results:
* Total Paid Review Vs Unppaid Reviews - The dataframes filtered for Vine == 'Y' & Vine = 'N'
[PaidVsUnpaid](images/PaidVsUnpaid.PNG)




