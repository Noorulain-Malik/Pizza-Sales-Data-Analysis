# Pizza-Sales-Data-Analysis
This project analyzes pizza sales data, including data cleaning, central tendency analysis, and hypothesis testing on weekday vs. weekend sales

# Pizza Sales Data Analysis Project

## Overview
This project analyzes pizza sales data with a focus on understanding the relationship between various factors like pizza size, sales patterns by day of the week, and pricing trends. Key objectives include data cleaning, central tendency analysis, hypothesis testing, and presenting findings with visualizations.

## Table of Contents
1. [Project Details]
2. [Data Cleaning and Preprocessing]
3. [Analysis]
4. [Hypothesis Testing]
5. [Results and Insights]
6. [Technologies Used]
7. [Project Presentation]
## Project Details

- **Dataset**: The pizza sales data includes various fields like `Pizza_type_id`, `Quantity`, and `Size`. An **ER Diagram** was created to illustrate relationships between tables, providing a clear structure for the dataset.![ER diagram](https://github.com/user-attachments/assets/769d71a1-58e6-4694-aa2d-d74ac7eced66)

- **Objective**: To analyze how pizza size influences pricing, explore sales patterns, and conduct hypothesis testing on whether weekday and weekend sales are statistically different.

## Data Cleaning and Preprocessing

The following steps were undertaken:
- **Header Formatting**: Freezing top rows and aligning fields to improve readability.
- **Field Consistency**: Ensured consistency in fields like `Pizza_type_id` and `Pizza_id`.
- **Data Formatting**: Converted relevant fields to proper numerical and currency formats.
![Picture1](https://github.com/user-attachments/assets/4f8b74f8-9a32-4457-8a9c-915a104850ef)

## Analysis

- **Central Tendency and Distribution**:
  - **Objective**: To analyze the average pizza price based on size. The results show that larger pizza sizes, especially XXL, are significantly more expensive than smaller ones.
  - **Outliers**: Price increases from XL to XXL were inconsistent, suggesting potential outliers. A comparison of mean, median, and mode was used to detect anomalies.
![Picture2](https://github.com/user-attachments/assets/aafc7c6a-7292-42b2-9db3-ac34ba313de2)
![Picture3](https://github.com/user-attachments/assets/30bba48d-0b1d-4dba-bd18-38ec0e7b76e2)

## Hypothesis Testing

- **Hypothesis**: Testing whether there is a difference in pizza sales between weekdays and weekends.
  - **Null Hypothesis (H0)**: No difference in the average number of pizzas sold on weekdays vs. weekends.
  - **Alternative Hypothesis (H1)**: A difference exists in the average number of pizzas sold on weekdays vs. weekends.
  - **Results**: The t-test showed a p-value of 0.6649, which is greater than 0.05, indicating that we fail to reject the null hypothesis. There is no statistically significant difference between weekday and weekend sales.

## Results and Insights

- **Pizza Size & Price**: Larger pizza sizes tend to have a higher price, with XXL being significantly more expensive.
- **Sales Patterns**: There is no significant difference in sales patterns between weekdays and weekends, as indicated by the hypothesis testing results.

## Technologies Used

- **Lucidchart**: Used for to create ER Diagram
- **Excel**: Used for initial data exploration Statistical Analysis and visualization.
- **PowerPoint**: Used to present findings and visualize the analysis.

## Project Presentation

View the project presentation [here](Pizza-Sales-Data-Analysis.pptx) to see visualizations, hypothesis testing results, and detailed conclusions.

