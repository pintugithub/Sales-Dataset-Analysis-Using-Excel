# Supermarket Sales Analysis  
**BUS708 – Statistics and Data Analysis**  
**Student ID**: XXX  
**University**: XXX

## Project Overview

This project presents an in-depth statistical analysis of a supermarket sales dataset to uncover patterns in customer behavior, financial performance, and satisfaction levels. The analysis aims to determine whether customer type (Member vs. Normal) influences satisfaction and to evaluate the relationship between Cost of Goods Sold (COGS) and Gross Income.

## Dataset Description

**File**: `supermarket_sales.xlsx`  
The dataset consists of transactional records from a fictional supermarket chain across three city branches. It includes:

- **Transaction Details**: Invoice ID, Date, Branch, City  
- **Customer Info**: Customer Type, Gender  
- **Purchase Data**: Product Line, Unit Price, Quantity, Tax, Total, COGS, Gross Income  
- **Customer Feedback**: Rating (satisfaction), Payment Method

This rich dataset supports financial, behavioral, and satisfaction-based analysis.

## Key Analyses

### Descriptive Statistics

- **Average Unit Price**: 55.67  
- **Average Quantity**: 5.51  
- **Mean Gross Income**: 15.38  
- **Customer Rating Mean**: 6.97 (on a scale of 1–10)

### Visual Insights

- Members spent a total of **$164,223.44**, slightly more than **$158,743.31** spent by Normal customers.
- Indicates potential purchasing power linked with membership.

### Regression Analysis

- A linear regression model of **COGS → Gross Income** yielded:
  - **R² = 1.0** (perfect correlation)
  - **p-value = 0**, indicating the model is statistically significant
  - Suggests COGS can precisely predict Gross Income

### Correlation Analysis

- **COGS and Gross Income**: Perfect positive correlation (**r = 1.0**)  
- **Ratings and Financials**: Weak negative correlation (~ **r = -0.0364**)

### Hypothesis Testing

- **Null Hypothesis**: No difference in satisfaction between Members and Normals  
- **p-value = 0.7179**  
- Conclusion: No statistically significant difference in customer satisfaction based on membership status

##  Key Insights

- **COGS strongly influences profitability** – managing costs can directly enhance gross income.
- **Membership does not significantly impact satisfaction**, suggesting benefits should be more experience-driven.
- Strategy should focus on improving the customer journey and product offerings for all segments.

## Tools & Techniques

- Microsoft Excel  
- Regression Analysis  
- Correlation Analysis  
- Two-sample Hypothesis Testing  
- Visuals: Bar Charts, Scatter Plots



*This project was completed as part of the BUS708 Statistics and Data Analysis module and reflects academic work submitted for assessment.*
