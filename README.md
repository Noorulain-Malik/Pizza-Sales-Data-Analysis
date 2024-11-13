# Pizza-Sales-Data-Analysis
This project analyzes pizza sales data, including data cleaning, central tendency analysis, and hypothesis testing on weekday vs. weekend sales
# Pizza Sales Data Analysis Project

### Overview
This project analyzes pizza sales data to explore sales patterns, central tendencies, and the impact of certain factors (like the day of the week) on pizza sales. Key objectives include exploring data types, conducting data cleaning, analyzing central tendencies, and performing hypothesis testing.

### Table of Contents
1. [Project Details](#project-details)
2. [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
3. [Analysis](#analysis)
4. [Hypothesis Testing](#hypothesis-testing)
5. [Results and Insights](#results-and-insights)
6. [Technologies Used](#technologies-used)
7. [Presentation](#presentation)
### Project Details

- **Dataset**: Pizza sales data was explored for various fields, like pizza type, size, and quantity. An ER diagram was created to categorize data types and establish relationships between fields (e.g., `Pizza_type_id`, `Quantity`, `Size`).
- **Objective**: The goal was to analyze pizza sales patterns, identify pricing trends based on pizza size, and investigate any outliers in the data.

### Data Cleaning and Preprocessing

The following steps were undertaken:
- **Header Formatting**: Freezing top rows and aligning fields.
- **Field Consistency**: Ensuring `Pizza_type_id` and `Pizza_id` values are standardized.
- **Formatting**: Converting relevant fields to appropriate number or currency formats.

### Analysis

- **Central Tendency and Distribution**:
  - **Objective**: To understand the average price per pizza size. Analysis revealed that larger sizes, especially XXL, are significantly more expensive.
  - **Outlier Detection**: Price increase from XL to XXL sizes was inconsistent, suggesting potential outliers. Mean, median, and mode were used to check for anomalies.

### Hypothesis Testing

- **Hypothesis**: Testing whether pizza sales differ between weekdays and weekends.
  - **Null Hypothesis (H0)**: No difference in average pizzas sold on weekdays vs. weekends.
  - **Alternative Hypothesis (H1)**: A difference exists in average pizzas sold on weekdays vs. weekends.
  - **Results**: The t-test showed a p-value of 0.6649, which is greater than 0.05, so we failed to reject the null hypothesis. There was no significant difference in sales across weekdays and weekends.

### Results and Insights

- **Pizza Size & Price**: Larger pizzas are generally more expensive, with XXL sizes significantly higher in price. Some inconsistencies in pricing trends suggest potential outliers.
- **Sales Patterns**: Sales patterns did not vary significantly between weekdays and weekends, supporting the hypothesis of consistent sales.

### Technologies Used
- **Python**: Data cleaning, analysis, and statistical tests.
- **Excel**: Initial data exploration.
- **PowerPoint**: For presentation and visualization of findings.

### Presentation
The presentation includes a step-by-step walkthrough of the analysis and findings. Access the presentation file [here](path/to/Introduction-to-Data-Analytics-and-Statistical-Analysis-1.pptx) to view visualizations, hypothesis testing results, and conclusions.

