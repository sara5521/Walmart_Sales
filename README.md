# Walmart Sales Data Analysis

This repository contains an analysis of Walmart sales data, focusing on understanding the factors that influence sales performance. The analysis aims to provide insights into seasonal trends, the impact of external factors like holidays, and how various store locations perform over time.

## Project Overview

The objective of this project is to analyze Walmart's sales data to identify patterns and factors that contribute to changes in sales. By leveraging data analysis techniques, the project aims to offer actionable insights that can help optimize sales strategies.

## Dataset

- **Source**: The dataset used in this analysis is publicly available on [Kaggle](https://www.kaggle.com/).
- **Description**: The dataset contains historical sales data for 45 Walmart stores located in different regions. It includes information on store sales, holiday markdown events, temperature, fuel prices, Consumer Price Index (CPI), and unemployment rate.

### Key Columns

- `Store`: The store number.
- `Date`: The week of sales.
- `Weekly_Sales`: Sales for the given store and date.
- `Holiday_Flag`: Indicates whether the week is a special holiday week (1) or not (0).
- `Temperature`: Average weekly temperature.
- `Fuel_Price`: Cost of fuel in the region.
- `CPI`: Consumer Price Index.
- `Unemployment`: The unemployment rate in the region.

## Analysis Objectives

1. **Analyze Sales Trends Over Time**:
   - Identify general trends and seasonal fluctuations in weekly sales.

2. **Impact of Holidays on Sales**:
   - Assess how major holidays such as Thanksgiving, Christmas, and the Super Bowl affect sales.

3. **Regional Performance**:
   - Compare the sales performance of different Walmart stores and regions.

4. **Correlation Analysis**:
   - Examine how external factors like temperature, fuel prices, CPI, and unemployment impact sales.

5. **Predictive Modeling**:
   - Develop predictive models to forecast future sales based on historical data and external factors.

## Tools and Libraries Used

- **Python**: The programming language used for data analysis.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For predictive modeling and machine learning.

## How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sara5521/Walmart_Sales.git
