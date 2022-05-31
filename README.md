# Amazon_Vine_Analysis
## Overview of the analysis: Explain the purpose of this analysis.
This analysis is to analyze Amazon reviews written by members of the paid Amazon Vine program to find any favorable reviews from Vine members in my dataset. with this analyzing data for Jennifer to submit to the SellBy stakeholders for their use.

The project analyzed the US VIdeo DVD Dataset from Amazon Vine program (paid reviews) and non-Vine (unpaid reviews).

## Deliverable 1 and 2
- Used PySpark to perform the cloud ETL process to extract the dataset.
- Created an AWS RDS database with tables in pgAdmin.
- Transformed the data into four separate DataFrames.
- Run a query to check the tables have been uploaded in pgAdmin.

- Determine if there is any bias towards reviews that were written as part of the Vine program. 
- Determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.
- Used PySpark and recreate the vine_table.
- Used Pnadas to export the vine_table as a CSV file from pdAdmin.
- Used SQL in pgAdmin from AWS database and export the vine_table
- Created an AWS RDS database with tables in pgAdmin.
- Filtered to create dataframes or tables for each use.
- calculated for all Vine and non-Vine reviews, the total number of reviews, the number of 5-star reviews, and the percentage 5-star reviews

## Results:
![amazone_dataset](https://github.com/msjj622/Amazon_Vine_Analysis/blob/main/results/amazone_dataset.png)

![extracted_dataset](https://github.com/msjj622/Amazon_Vine_Analysis/blob/main/results/extracted_dataset.png)

![products_table](https://github.com/msjj622/Amazon_Vine_Analysis/blob/main/results/products_table.png)

![review_id_table](https://github.com/msjj622/Amazon_Vine_Analysis/blob/main/results/review_id_table.png)

![vine_table](https://github.com/msjj622/Amazon_Vine_Analysis/blob/main/results/vine_table.png)

![helpful_votes](https://github.com/msjj622/Amazon_Vine_Analysis/blob/main/results/helpful_votes.png)

![vine_review_df](https://github.com/msjj622/Amazon_Vine_Analysis/blob/main/results/vine_review_df.png)

![none_review_df](https://github.com/msjj622/Amazon_Vine_Analysis/blob/main/results/none_review_df.png)

![paid_none_paid_five](https://github.com/msjj622/Amazon_Vine_Analysis/blob/main/results/paid_none_paid_five.png)

## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

In summary for US DVD Dataset, the positivity bias is to the non-Vine reviews(unpaid service) than Vine reviews (paid service) with the following data:

none_review five-stars are 78061 and reviews are 151400 which is much higher numbers than paid_five reviews.
