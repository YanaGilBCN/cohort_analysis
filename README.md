# Cohort Analysis in Python

This repository contains Python code for performing a monthly cohort analysis of subscribers using the retention_rate.csv dataset.

## About Cohort Analysis

Cohort analysis involves breaking down a dataset into related groups, or cohorts, based on shared characteristics or experiences within a defined time-span. In this analysis, we group users by the month of their initial purchase to understand user retention and other metrics.

## Data Source

The analysis is based on the "retention_rate.csv" dataset, which contains information about user purchases, including product details and currency used. Specifically, it contains the following variables:

- cohort_start_date
- order_date
- cohort_size  (redundant, to be dropped)
- cohort_size_at_order_date
- plan
- currency
- cohort_age_months
- retention_rate (redundant, to be dropped)


## Key Questions Addressed

1. **Product Retention:** We analyze which products have higher retention rates among subscribers.
2. **Currency Comparison:** We investigate whether there are any differences in retention rates between subscribers using different currencies.

## Deliverables

- **Charts:** Charts are generated to visualize the cohort analysis results.

## File Structure

- `retention_rate.csv`: The dataset used for the analysis.
- `cohort_analysis.ipynb`: Jupyter Notebook containing Python code for cohort analysis.
- `README.md`: This file providing an overview of the project.

## Instructions

To perform the cohort analysis:

1. Ensure you have Python and Jupyter Notebook installed.
2. Clone this repository to your local machine.
3. Open and run the "cohort_analysis.ipynb" notebook in Jupyter Notebook.
4. Follow the instructions and execute the provided Python code to conduct the analysis.
5. Review the results and charts generated to gain insights into product retention and currency comparison among subscribers.

## References

- [Wikipedia - Cohort Analysis](https://en.wikipedia.org/wiki/Cohort_analysis)

For any questions or inquiries, please [contact me](mailto:yanagi.l@gmail.com).
