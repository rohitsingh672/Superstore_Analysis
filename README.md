# Alfido Tech Sales Performance Analysis

## Project Overview

This project analyzes Alfido Tech's sales performance across regions, product categories, and time periods. The objective is to uncover business insights, identify top and underperforming products, detect seasonal trends, and provide actionable recommendations to improve sales performance.

## Business Objective

* Analyze sales trends over time.
* Evaluate regional and category-wise performance.
* Identify best-selling and low-performing products.
* Measure key business KPIs.
* Discover seasonality patterns.
* Recommend strategies to improve revenue and profitability.

---

## Dataset Description

The dataset contains sales transaction records with information such as:

* Order ID
* Order Date
* Ship Date
* Customer Information
* Product Information
* Category & Sub-Category
* Region
* Sales Revenue
* Profit
* Quantity
* Discount

---

## Data Cleaning & Preparation

### Steps Performed

1. Imported dataset using Pandas.
2. Converted date columns to datetime format.
3. Removed duplicate records based on Order ID and Product ID.
4. Handled missing values.
5. Created additional features:

   * Year
   * Quarter
   * Month
   * Month Number
   * Days to Ship
6. Standardized column names and data types.
7. Verified data quality and consistency.

---

## Key Performance Indicators (KPIs)

### Revenue

Total Sales generated.

Formula:

Revenue = Sum(Sales)

### Profit Margin

Profit Margin (%) = (Profit / Sales) × 100

### Average Order Value (AOV)

AOV = Total Sales / Number of Orders

### Total Orders

Count of unique Order IDs.

### Average Shipping Time

Average Shipping Time = Mean(Days to Ship)

### Category Contribution

Percentage contribution of each category to total sales.

---

## Exploratory Data Analysis

### Time-Based Analysis

* Monthly Sales Trend
* Quarterly Sales Trend
* Yearly Sales Trend
* Seasonal Performance Analysis

### Regional Analysis

* Sales by Region
* Profit by Region
* Top Performing Regions
* Underperforming Regions

### Product Analysis

* Top 10 Products by Sales
* Top 10 Products by Profit
* Bottom 10 Products by Profit
* Category-wise Performance
* Sub-Category Analysis

---

## Visualizations

The project includes:

### Sales Trend Charts

* Monthly Revenue Trend
* Quarterly Revenue Trend
* Year-over-Year Growth

### Regional Performance Charts

* Revenue by Region
* Profit by Region

### Product Performance Charts

* Top Products by Sales
* Top Products by Profit
* Bottom Products by Profit

### Category Analysis

* Category-wise Revenue Distribution
* Sub-Category Profitability

### Operational Metrics

* Average Shipping Time
* Shipping Performance by Region

---

## Key Insights

### Best Performing Areas

* Technology category contributes the highest revenue.
* West region generates the maximum sales.
* Certain products consistently deliver high profits.

### Improvement Areas

* Some sub-categories generate revenue but produce low profit margins.
* High discounts negatively impact profitability.
* Certain regions show lower customer engagement and sales.

### Seasonality

* Sales typically peak during festive and year-end periods.
* Some months consistently outperform others.
* Seasonal demand patterns can guide inventory planning.

---

## Recommendations

### 1. Optimize Discount Strategy

Reduce excessive discounting on low-margin products to improve profitability.

### 2. Focus on High-Profit Products

Increase marketing efforts for products with strong profit margins.

### 3. Improve Regional Targeting

Allocate additional marketing resources to underperforming regions.

### 4. Enhance Inventory Planning

Use seasonal trends to maintain optimal stock levels during peak demand periods.

### 5. Expand Successful Categories

Invest more in high-performing categories and introduce complementary products.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Power BI (Optional Dashboard)

---

## Project Structure

sales-performance-analysis/

│

├── data/

│ └── superstore_final_dataset.csv

│

├── notebooks/

│ └── Sales_Analysis.ipynb

│

├── visualizations/

│ ├── sales_trend.png

│ ├── regional_performance.png

│ └── product_analysis.png

│

├── reports/

│ └── insights_report.pdf

│

├── README.md

│

└── requirements.txt

---

## Expected Outcomes

* Improved understanding of sales performance.
* Identification of revenue growth opportunities.
* Better inventory and marketing decisions.
* Increased profitability through data-driven recommendations.

---

## Author

Rohit Rajput

Aspiring Data Analyst | Python | SQL | Power BI | Data Visualization
