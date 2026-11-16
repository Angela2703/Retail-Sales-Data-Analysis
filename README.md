# Retail Sales Data Analysis

## Project Overview
This project focuses on Exploratory Data Analysis (EDA) of retail sales transactions from 2022 to 2025 using Python. The objective is to identify sales trends, understand customer purchasing patterns, evaluate product performance, and generate actionable business insights.

## Project Objectives
- Understand the structure and quality of retail sales data.
- Perform data cleaning and exploratory data analysis.
- Analyze monthly and quarterly sales trends.
- Identify customer demographics and purchasing patterns.
- Find the top 10 products by quantity sold.
- Analyze revenue contribution by product category.
- Explore relationships between numerical variables.
- Develop data-driven business recommendations.

## Dataset Description
The dataset contains 18,045 transaction records and 36 columns, covering the period from 2022 to 2025.

**Files included:**
- `Sales_transactions_2022_2025.csv` – Main retail sales dataset.
- `sales_data_dictionary.csv` – Description of dataset columns.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

### 1. Data Inspection and Quality Checks
- Dataset shape and data types
- Missing values and duplicate records
- Descriptive statistics
- Review of unusual values and data inconsistencies

### 2. Sales Trend Analysis
- Monthly sales trends
- Quarterly sales trends
- Identification of high-performing sales periods

### 3. Customer Analysis
- Customer age group distribution
- Gender distribution
- Customer demographic patterns

### 4. Product and Category Analysis
- Top 10 products by quantity sold
- Revenue analysis by product category

### 5. Correlation Analysis
- Correlation matrix
- Heatmap visualization
- Relationships between sales, profit, cost, quantity, and discounts

### 6. Additional Visualization
- Distribution of sales amounts using a histogram and KDE curve

## Key Findings
- The dataset contains 18,045 transactions across 2022–2025.
- Total recorded sales revenue is approximately 8.25 million.
- Electronics is the highest revenue-generating product category, contributing approximately 59.8% of total revenue.
- The fourth quarter recorded the highest sales in each year.
- December 2025 was the highest-performing month in the analyzed period.
- Sales Amount and Profit show a strong positive correlation.
- Sales Amount and Cost Amount show a very strong positive correlation.
- Most customer transactions belong to the 26–45 age groups.

## Business Recommendations
1. Focus on the Electronics category to strengthen revenue performance.
2. Improve inventory planning for frequently purchased products.
3. Use customer segmentation to develop targeted marketing campaigns.
4. Review discount strategies to understand their impact on profitability.
5. Improve data quality checks to ensure more reliable business reporting.

## Project Structure

```text
Retail-Sales-Data-Analysis/
│
├── data/
│   ├── Sales_transactions_2022_2025.csv
│   └── sales_data_dictionary.csv
│
├── Retail_Sales_EDA.ipynb
│
└── README.md
```

## How to Use This Project
1. Clone or download this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:
   `pip install pandas numpy matplotlib seaborn`
4. Open the Jupyter Notebook.
5. Run the analysis cells to explore the retail sales dataset.

## Conclusion
This project demonstrates the use of Python-based exploratory data analysis to understand retail sales performance, customer behavior, and product trends. The findings provide useful insights that can support business decision-making and improve sales and inventory strategies.

---
 
**Domain:** Retail / E-commerce  
**Author:** Angela
