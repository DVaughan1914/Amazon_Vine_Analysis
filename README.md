# Amazon_Vine_Analysis

# Analysis Overview

  This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
I focused on the US reviews for video games


# Results

# Total number of reviews
![vine_reviews](https://user-images.githubusercontent.com/100040621/174656022-1d145ae7-494b-4e54-9d88-c111b49ec4fd.png)

![Non-Vine Reviews](https://user-images.githubusercontent.com/100040621/174656045-8df7625f-59d3-4a0e-8d2a-a3105355fa89.png)



# Total number of 5-star reviews
![vine reviews 2](https://user-images.githubusercontent.com/100040621/174656096-0c9d033d-f9df-43e1-8713-e1aa6cdc3c03.png)

![non vine reviews 2](https://user-images.githubusercontent.com/100040621/174656122-5cc40ea3-389c-4b42-bf12-95e63dc1b73a.png)


# Percentage of 5-star reviews
![Vine Reviews 3](https://user-images.githubusercontent.com/100040621/174656188-b3c87b59-7277-4367-92ee-a632f38604b2.png)

![Non Vine reviews 3](https://user-images.githubusercontent.com/100040621/174656252-88f96a82-2244-4b07-afa1-4d3063da090a.png)






# Summary

51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
