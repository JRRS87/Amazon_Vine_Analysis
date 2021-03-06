# Amazon_Vine_Analysis

## Analysis Overview

This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.

## Resources

- Data Source: Amazon Review datasets, Video Games Review dataset
- Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS

## Results

### Total number of reviews

- Vine reviews

94


- Non-Vine reviews

40471


### Total number of 5-star reviews

- Vine reviews

48


- Non-Vine reviews

15663

### Percentage of 5-star reviews

- Vine reviews

51.0638298723404


- Non-Vine reviews

38.701786464381904

## Summary

51% of the reviews in the Vine program were 5 stars reviews and the percentage in the non-Vine reviews is only 39%. This describes a positivity for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.