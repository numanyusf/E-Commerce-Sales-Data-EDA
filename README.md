# Sales Dataset Analysis

## Overview

This notebook provides a brief overview of the sales dataset contained in the "data-2.csv" file. The dataset includes information about various sales transactions, such as InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country.

### Data Columns and Descriptions

| Column       | Description                                      |
|--------------|--------------------------------------------------|
| InvoiceNo    | A unique identifier for each sales transaction. |
| StockCode    | Code associated with the stock or product.      |
| Description  | Description of the product sold.                 |
| Quantity     | The quantity of the product sold in each transaction. |
| InvoiceDate  | The date and time when the transaction took place. |
| UnitPrice    | The price of a single unit of the product.      |
| CustomerID   | The unique identifier for the customer.         |
| Country      | The country where the customer is located.      |

## Exploratory Data Analysis (EDA)

The analysis includes the following steps:

1. Data Import and Overview
   - Importing the dataset and checking its basic information.

2. Numeric and Object Data Description
   - Describing the numeric and object values of the dataset.

3. Duplicate Records
   - Identifying and removing duplicate records from the dataset.

4. Missing Values
   - Analyzing and visualizing missing values in the dataset.

5. Data Cleaning
   - Handling missing values and removing records with negative quantities.

6. Data Distribution
   - Plotting the distribution of selected numeric columns.

7. Correlation Analysis
   - Creating a heatmap to check the correlation between numeric columns.

8. Creating Additional Columns
   - Adding new columns such as 'Sales', 'Hour', 'Day', 'Date', 'Month', and 'Year'.

9. Sales Analysis
   - Analyzing total sales for each hour, day, month, and year.

10. Top and Bottom Sold Products
    - Identifying and visualizing the top 20 and bottom 20 sold products.

11. Sales by Country
    - Analyzing sales and visualizing the top 10 countries by sales.

12. Statistical Tests
    - Conducting t-test, Pearson correlation, and ANOVA to derive insights.

## Conclusion

This readme provides an in-depth analysis of the sales dataset, offering insights into sales trends, popular products, and country-wise performance. The visualizations and statistical tests enhance our understanding of the dataset, supporting informed decision-making related to sales strategies and customer behavior.
