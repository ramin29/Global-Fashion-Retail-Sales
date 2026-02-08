# Global-Fashion-Retail-Sales
Analysis of the synthetic dataset which simulates two years of transactional data for a multinational fashion retailer.

## Project Overview

This project analyzes a synthetic transactional dataset simulating two years of sales activity for a multinational fashion retailer operating across multiple countries and cities. The goal is to derive data-driven insights that support strategic decisions in pricing, promotions, product assortment, and store performance.

The dataset represents a real-world retail environment with over 1 million transaction records and a relational structure, making it suitable for end-to-end analytics: data modeling, querying, analysis, and visualization.

## Dataset Description
- Time span: 2 years of transaction-level data
- Scale: 1M+ records, 100+ MB
- Source: Kaggle – Global Fashion Retail Stores Dataset
- Data structure: Multiple related tables
  - Transactions
  - Customers
  - Stores
  - Products
  - Employees
  - Discounts

## Data Modeling & Architecture
- Designed and implemented a star-schema dimensional model
- Built a central fact table (Transactions) containing key sales metrics
- Created dimension tables for customers, products, stores, employees, and discounts
- Defined appropriate primary and foreign keys, data types, and relationships
- Introduced a time/hour key to support temporal analysis and aggregation
- Optimized structure for efficient analytical queries and business intelligence use cases

## Data Cleaning & Preparation
- Assessed data quality using column-level statistics
- Identified and handled missing, inconsistent, and invalid values
- Ensured referential integrity across all linked tables
- Prepared clean, analysis-ready datasets for querying and visualization

## Business Questions Addressed
- When do we experience high and low sales periods and how can this guide pricing and promotional timing?
- Which age ranges are most associated with each product and how can we better target key customer segments?
- Which stores across countries and cities generate the highest sales and transaction volumes by product category?
- How do product categories ( Masculine, Children) perform over time and across countries and where should
resources be reallocated?

## Key Analyses & Insights
- Sales Seasonality: Identified strong seasonal patterns with revenue peaks in March, Fall, and December, and slowdowns during early and mid-year periods
- Customer Segmentation: Found customers aged 18–24 to be the most valuable segment, with strong demand for sportswear and structured apparel
- Geographic Performance: Discovered revenue concentration in major Chinese cities (e.g., Shanghai, Beijing, Guangzhou), while several European markets underperformed
- Product Performance: Determined that Feminine and Masculine categories consistently outperform Children’s products, with Sportswear, Shirts, Pants & Jeans, and Coats & Blazers as top subcategories

## Visualizations
- Time-series charts for sales trends and seasonality
- Bar and distribution charts for customer age and product preferences
- Geographic comparisons for country- and city-level store performance
- Category and subcategory performance dashboards

(All visualizations are included in the project presentation and analysis files.)

## Business Recommendations
- Optimize promotion timing during low-demand periods to maximize revenue impact
- Prioritize younger customer segments (18–24) in marketing and product strategy
- Allocate resources toward top-performing cities and product categories
- Reevaluate underperforming regions and product lines using data-backed evidence

## Tools & Skills Used
- SQL (data modeling, joins, aggregations, analytical queries)
- Dimensional modeling (star schema)
- Data cleaning and validation
- Exploratory data analysis
- Data visualization and business storytelling
