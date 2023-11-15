# Customer Segmentation Analysis

## Project Overview

This project aims to analyze and segment customer data from the Mall_Customers.csv dataset. The goal is to identify patterns and insights that can be used to better understand customer behavior and inform marketing strategies.

## Data Exploration

The data analysis process involved several steps:

1. **Data Import and Overview:** The data was imported into a Pandas DataFrame and examined using head(), shape(), and describe() methods to gain a basic understanding of the dataset.

2. **Data Distribution:** The distributions of key variables like Annual Income (k$), Age, and Spending Score (1-100) were explored using Seaborn's displot() function to visualize the spread of the data.

3. **Gender Analysis:** The number of customers in each gender category was visualized using a bar chart. The relationship between age and gender was further explored using a boxplot to compare the age distribution across genders.

4. **Income-Age-Spending Relationships:** Scatter plots were used to visualize the relationships between age and annual income, age and spending score, and annual income and spending score to identify any correlations or patterns.

5. **Age Distribution by Range:** The number of customers in different age ranges was visualized using a bar chart to understand the age distribution of the customer base.

6. **Spending Score Distribution by Range:** The number of customers in different spending score ranges was visualized using a bar chart, broken down by gender, to identify any spending patterns among different genders.

7. **Annual Income Distribution by Range:** The number of customers in different annual income ranges was visualized using a bar chart, broken down by age group, to analyze the distribution of income across different age groups.

## Cluster Analysis

To identify groups of customers with similar characteristics, K-means clustering was applied to the data. The optimal number of clusters was determined using the elbow method, which involves calculating the WCSS (Within Cluster Sum of Squares) for different values of k and identifying the point where the WCSS starts to decrease sharply.

## Results

The data analysis revealed several insights about the customer base:

* Customers are predominantly in the 26-35 age range.
* Spending scores tend to increase with age.
* There is a positive correlation between annual income and spending score.
* Female customers are more likely to have higher spending scores than male customers.
* There are five distinct customer segments based on their annual income and spending score profiles.

## Conclusions

The customer segmentation analysis provides valuable insights into the characteristics and behavior of different customer groups. These insights can be used to inform marketing strategies, tailor product recommendations, and enhance customer engagement.

## Future Work

Further analysis could include exploring the relationships between customer demographics, purchase history, and product preferences. Additionally, machine learning techniques could be employed to develop predictive models for customer behavior and identify potential churn risks.
