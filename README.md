# Pizza Sales Analysis Project

This project is a comprehensive analysis of pizza sales data using Python. The analysis covers data cleaning, exploration, visualization, and generation of insights into sales trends, customer preferences, and revenue distribution. The results are exported to an Excel file for further use.

## Table of Contents
- [Overview](#overview)
- [Project Features](#project-features)
- [Installation](#installation)
- [Dataset Description](#dataset-description)
- [Key Analysis and Insights](#key-analysis-and-insights)
- [Visualizations](#visualizations)
- [Output Files](#output-files)
- [Technologies Used](#technologies-used)

## Overview
The goal of this project is to analyze pizza sales data to derive meaningful insights such as sales trends, category-wise sales distribution, and revenue contribution during specific periods (e.g., Christmas season). The analysis is performed on multiple datasets and includes merging, cleaning, and visualization to generate actionable insights.

## Project Features
- Data cleaning (handling missing values and duplicates).
- Exploratory Data Analysis (EDA) with descriptive statistics.
- Visualizations to understand sales trends and revenue distribution.
- Merging multiple datasets for comprehensive analysis.
- Revenue and quantity analysis by category, size, and time period.
- Export of cleaned and analyzed data to an Excel file.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/pizza-sales-analysis.git
   ```

   Navigate to the project directory:

   ```bash
   cd pizza-sales-analysis
    ```
   
    Install the required Python libraries:
    ``` bash
    pip install pandas numpy matplotlib seaborn openpyxl
    ```
    
    Place the datasets (pizza_sales.xlsx, pizza_size.csv, pizza_sales_voucher.xlsx, and pizza_category.csv) in the project directory.
   ## Dataset Description

  The project uses the following datasets:

- pizza_sales.xlsx: Sales details of pizzas including order dates, quantities, and prices.
- pizza_size.csv: Information about pizza sizes.
- pizza_sales_voucher.xlsx: Details of voucher usage in sales.
- pizza_category.csv: Categories of pizzas.

## Key Analysis and Insights
* Sales Trends:

  * Month-wise and week-wise revenue trends.
  * Peak sales periods, such as the Christmas season.

* Revenue Distribution:

  - Distribution of revenue by pizza category and size.
  - Revenue contribution of high-price and low-price pizzas.

* Customer Behavior:

  - Quantity analysis for frequently purchased items.
  - Analysis of the most and least expensive pizzas sold.

## Visualizations
  - Histograms of pizza quantities and unit prices.
  - Pie charts for sales distribution by category and size.
  - Line plots for month-wise and week-wise revenue trends.
  - Box plots for order time distribution across categories and sizes.

## Output Files
The results of the analysis are saved in an Excel file: Pizza_sales_analysis_results.xlsx. The file includes:

  - Merged and cleaned data.
  - Category-wise revenues.
  - Sales trends by month and week.
  - High-price and low-price pizza analyses.
  - Christmas sales insights.

## Technologies Used
- Python: Core programming language for data analysis.
- Libraries:
  - pandas: Data manipulation and analysis.
  - numpy: Numerical computations.
  - matplotlib and seaborn: Data visualization.
  - openpyxl: Writing results to Excel.

## Usage
- Run the Jupyter Notebook to perform the analysis:
  ```
  bash
  jupyter notebook pizza_sales_analysis.ipynb
  ```

- Review the visualizations and insights generated in the notebook.
- Access the exported Excel file (Pizza_sales_analysis_results.xlsx) for detailed analysis results.
