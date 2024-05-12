# Diwali Sales Data Analysis

## Overview
This project aims to analyze Diwali sales data to understand various trends and patterns among customers. The dataset used contains information about customer demographics, purchase behavior, and product details.

## Dataset
The dataset used for analysis is stored in a CSV file named `Diwali Sales Data.csv`. It includes the following columns:

- `User_ID`: Unique identifier for each user.
- `Cust_name`: Name of the customer.
- `Product_ID`: Unique identifier for each product.
- `Gender`: Gender of the customer (Male/Female).
- `Age Group`: Age group of the customer.
- `Age`: Age of the customer.
- `Marital_Status`: Marital status of the customer (0 - Single, 1 - Married).
- `State`: State of the customer.
- `Zone`: Geographical zone.
- `Occupation`: Occupation of the customer.
- `Product_Category`: Category of the purchased product.
- `Orders`: Number of orders made by the customer.
- `Amount`: Amount spent by the customer.

## Libraries Used
- `numpy`: For numerical computations.
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For data visualization.
- `seaborn`: For enhanced data visualization.

## Analysis Steps
1. **Data Cleaning and Preprocessing**:
   - Removed irrelevant or empty columns.
   - Handled missing values by dropping rows with null values.
   - Adjusted data types for better analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed various aspects of the data such as gender distribution, age distribution, state-wise sales, marital status, occupation, and product categories.
   - Created visualizations including bar charts and histograms to understand trends and patterns.

3. **Insights and Conclusion**:
   - Identified key trends such as the dominance of female customers, preference for specific age groups, popular states for sales, and preferred product categories.
   - Concluded with insights about the target demographic and their preferences.

## Files
- `Diwali Sales Data.csv`: The dataset used for analysis.
- `Diwali_Sales_Data_Analysis.ipynb`: Jupyter Notebook containing the Python code for data analysis.

## Conclusion
The analysis provides valuable insights into the purchasing behavior of customers during Diwali sales. Understanding these patterns can help businesses tailor their marketing strategies and product offerings to target specific demographics more effectively.

