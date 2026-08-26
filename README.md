# Supplement Sales Intelligence and Analysis

## Project Overview

This project focuses on analyzing supplement sales data to identify important business trends and patterns related to revenue, product performance, sales volume, returns, discounts, categories, locations, and sales platforms. Using Python and data visualization techniques, the project transforms raw sales data into meaningful insights that can support better business and sales decisions.

## Objectives

- Analyze overall sales and revenue performance.
- Identify the highest-performing product categories.
- Analyze revenue trends over time.
- Identify the top-performing products based on revenue.
- Compare revenue across different locations and platforms.
- Analyze product return rates across categories.
- Study the relationship between discounts and revenue.
- Analyze correlations between sales-related variables.
- Examine monthly revenue and units sold trends.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

## Dataset

The project uses a weekly expanded supplement sales dataset containing information related to:

- Date
- Product Name
- Category
- Location
- Platform
- Revenue
- Units Sold
- Units Returned
- Price
- Discount

## Data Analysis Performed

### 1. Data Loading and Exploration
- Imported the sales dataset using Pandas.
- Inspected the structure and information of the dataset.
- Checked for missing values and duplicate records.
- Generated descriptive statistics for numerical and categorical variables.

### 2. Revenue and Sales Analysis
Daily sales data was aggregated to analyze:

- Total Revenue
- Total Units Sold
- Total Units Returned

Revenue trends were visualized over time to understand sales performance.

### 3. Category Analysis
Revenue was grouped by product category to identify the categories generating the highest overall revenue.

### 4. Location and Platform Analysis
Revenue was analyzed across different locations and sales platforms to understand where and through which channels the business performs best.

### 5. Product Performance
The top 10 products were identified based on total revenue to highlight the strongest-performing products.

### 6. Return Rate Analysis
A Return Rate metric was created using:

Return Rate = Units Returned / Units Sold

The average return rate was then analyzed across different product categories.

### 7. Discount vs Revenue Analysis
A scatter plot was used to examine the relationship between discount levels and revenue across different categories.

### 8. Correlation Analysis
Correlation analysis was performed on:

- Units Sold
- Price
- Revenue
- Discount
- Units Returned

A correlation heatmap was created to visualize relationships between these variables.

### 9. Monthly Sales Analysis
Monthly data was aggregated to analyze:

- Monthly Revenue
- Monthly Units Sold
- Average Discount
- Monthly Units Returned

Monthly trends were visualized to understand changes in sales performance over time.

## Key Visualizations

The project includes visualizations such as:

- Daily Revenue Trend
- Revenue by Category
- Revenue by Location and Platform
- Top 10 Products by Revenue
- Average Return Rate by Category
- Discount vs Revenue
- Correlation Heatmap
- Revenue Over Time by Category
- Monthly Revenue Trend
- Monthly Units Sold Trend

## Project Workflow

Raw Sales Data
        ↓
Data Loading
        ↓
Data Cleaning & Validation
        ↓
Exploratory Data Analysis
        ↓
Feature Creation
        ↓
Sales & Revenue Analysis
        ↓
Statistical & Correlation Analysis
        ↓
Data Visualization
        ↓
Business Insights

## Business Insights

The analysis helps understand:

- Which product categories contribute the most revenue.
- Which products are the strongest revenue generators.
- How sales performance changes over time.
- Which locations and platforms generate higher revenue.
- Which categories experience higher return rates.
- How discounts are associated with revenue.
- Relationships between price, units sold, revenue, discounts, and returns.
- Monthly changes in revenue and sales volume.

## Author
Vidhi Bali
