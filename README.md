# Product-Price-Analysis-and-Visualization

## Overview
The **Product Price Analysis and Visualization** project is a Python-based data analysis tool that enables users to upload product datasets (in CSV or Excel format), automatically clean and analyze the data, and generate multiple types of visualizations.  
It demonstrates how raw product data can be transformed into meaningful insights using **Pandas**, **NumPy**, and **Matplotlib**.

---

## Features

### Data Input
- Accepts both `.csv` and `.xlsx` file formats.
- Compatible with datasets containing columns such as `Product`, `Price`, `Rating`, and `Category`.

### Data Cleaning
- Automatically removes special characters and currency symbols (₹, $, commas, etc.).
- Converts text-based price data to numeric format.
- Handles missing values and duplicate records.
- Standardizes column names for consistency.

### Data Analysis
- Computes essential statistics such as average, minimum, and maximum price.
- Calculates correlation between price and rating.
- Provides descriptive statistics for all numerical columns.

### Data Visualization
Users can select one or more chart types to visualize insights:
- **Bar Chart**: Compare product prices.
- **Scatter Plot**: Analyze the relationship between price and rating.
- **Histogram**: Display price distribution.
- **Pie Chart**: Show top products by price share.
- **Line Chart**: Present price trends across products.
- **Box Plot**: Detect outliers in product pricing.
- **Area Chart**: Visualize overall pricing patterns.
- **Count Plot**: Show product count by category (if available).

### Output
- The cleaned dataset is automatically saved as `cleaned_product_data.csv`.
- Visualization results are displayed directly within the Python environment.

---

## Tech Stack

| Component | Technology |
|------------|-------------|
| Programming Language | Python 3.x |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib |
| File Support | CSV, Excel |

--
