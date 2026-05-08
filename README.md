# Retail Sales & Product Intelligence Dashboard

## Project Overview

This project focuses on analyzing retail grocery sales and product nutritional data using Python and Power BI. The objective of the project is to uncover meaningful business insights related to sales performance, customer purchasing behavior, profitability, product trends, and nutritional characteristics.

The project combines Exploratory Data Analysis (EDA), data preprocessing, visualization, and dashboard development to support data-driven business decision-making.

The analysis was performed using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn, while Power BI was used to build interactive dashboards and visual storytelling components.

---

# Problem Statement

Retail businesses generate large volumes of sales and product-related data every day. However, extracting actionable insights from this data can be difficult without proper analysis and visualization.

The goal of this project is to:

- Analyze sales performance and profitability
- Understand customer purchasing behavior
- Identify high-performing and low-performing product categories
- Detect seasonal and regional sales trends
- Analyze nutritional characteristics of products
- Provide business recommendations using data-driven insights

---

# Datasets Used

## 1. Retail Sales Dataset

The retail sales dataset contains information related to:

- Orders
- Sales
- Profit
- Customers
- Product categories
- Regions
- Discounts
- Order dates

## 2. Menu Nutrition Dataset

The menu dataset contains nutritional information such as:

- Calories
- Fat
- Sugar
- Protein
- Sodium
- Serving size
- Product categories

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI
- GitHub

---

# Data Cleaning and Preprocessing

The datasets were cleaned and transformed using Python before importing into Power BI.

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Standardized column names
- Converted date columns into datetime format
- Corrected inconsistent data formats
- Created additional analytical columns
- Checked data types and outliers

### Feature Engineering Performed

New columns created include:

- Profit Margin
- Sales Category
- Month
- Quarter
- Year
- Healthy Product Indicator
- Calorie Level

These additional features improved dashboard analysis and business interpretation.

---

# Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to identify trends, patterns, and business opportunities.

## Retail Sales Analysis

The following analyses were conducted:

- Monthly sales trend analysis
- Quarterly performance analysis
- Region-wise sales and profit analysis
- Category and sub-category performance
- Discount impact on profitability
- Customer purchasing behavior
- Profit margin analysis

## Customer Analysis

Customer behavior analysis included:

- Top customers by sales
- Customer contribution analysis
- High-value customer identification
- Purchase pattern analysis

## Nutritional Product Analysis

Nutritional analysis included:

- Calories distribution
- Healthy vs unhealthy product comparison
- Sugar and fat analysis
- Nutrient correlation analysis
- Product health categorization

---

# Dashboard Features

The Power BI dashboard was designed to provide interactive and business-focused insights.

## KPI Cards

The dashboard includes:

- Total Sales
- Total Profit
- Profit Margin %
- Total Orders
- Total Customers
- Average Sales
- Healthy Product Percentage

## Interactive Filters

Users can filter the dashboard using:

- Region
- Category
- Month
- Quarter
- Product Type
- Customer Segment

## Visualizations Used

The dashboard contains:

- Line Charts
- Bar Charts
- Stacked Charts
- Scatter Plots
- Heatmaps
- Treemaps
- Donut Charts
- KPI Cards

---

# Time Series Analysis

Time series analysis was performed to study sales trends over time.

Key findings include:

- Seasonal fluctuations in sales
- Monthly growth trends
- High-performing sales periods
- Revenue spikes during certain quarters

The analysis helped identify patterns useful for forecasting and strategic planning.

---

# Customer and Product Analysis

Customer analysis showed that a small percentage of customers contributed significantly to overall revenue.

Product analysis revealed:

- High-performing product categories
- Low-profit product groups
- Sales concentration across selected categories
- Nutritional characteristics of products

The combination of retail and nutritional analysis provided a broader understanding of product performance and customer behavior.

---

# Key Insights

The following major insights were discovered during the analysis:

- Sales showed clear seasonal patterns during specific months.
- Certain regions generated high sales but lower profitability.
- Heavy discounting negatively impacted overall profit margins.
- A small group of customers contributed a large share of total sales.
- Some product categories generated strong revenue despite low margins.
- High-calorie products represented a significant portion of product sales.
- Healthy products formed a smaller percentage of total products.

---

# Business Recommendations

Based on the analysis, the following recommendations were made:

## 1. Optimize Discount Strategies

Excessive discounting reduced profitability in several categories. Businesses should optimize discount levels to balance sales growth and profit margins.

## 2. Expand Healthy Product Offerings

The analysis showed an opportunity to increase healthier product options to target health-conscious consumers.

## 3. Improve Inventory Planning

High-performing product categories should receive better inventory allocation to prevent stock shortages.

## 4. Focus on High-Value Customers

Customer retention strategies and loyalty programs should target high-value customers to improve repeat purchases.

## 5. Regional Pricing Optimization

Regions with high sales but low profit margins require pricing and operational review.

---

# Dashboard Preview

## Executive Dashboard

(Add dashboard screenshot here)

## Sales Analysis Dashboard

(Add dashboard screenshot here)

## Nutritional Analysis Dashboard

(Add dashboard screenshot here)

---

# Project Structure

Retail-Analytics-Project/
│
├── data/
│   ├── retail_cleaned.csv
│   └── menu_cleaned.csv
│
├── notebooks/
│   └── eda_analysis.ipynb
│
├── dashboard/
│   └── Retail_Analytics_Dashboard.pbix
│
├── images/
│   └── dashboard_preview.png
│
└── README.md

---

# How to Run the Project

1. Clone the repository
2. Open the Jupyter Notebook
3. Run the Python EDA notebook
4. Open the Power BI (.pbix) file
5. Refresh the dataset connections if required

---

# Future Improvements

Future enhancements that can be added to this project include:

- Machine learning sales forecasting
- Customer segmentation models
- Real-time sales dashboard integration
- Recommendation systems
- Cloud deployment of dashboards

---

# Conclusion

This project demonstrates how Python and Power BI can be combined to perform industry-level retail analytics and product intelligence analysis.

The dashboard provides valuable business insights related to sales performance, profitability, customer behavior, and product nutrition. The project highlights the importance of data-driven decision-making in modern retail businesses.
