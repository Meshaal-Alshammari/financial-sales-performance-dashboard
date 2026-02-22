Financial & Sales Performance Dashboard
Built with Power BI | Adventure Works Dataset

Executive Summary
This project presents a comprehensive financial performance dashboard designed to analyze revenue, profitability, cost structure, and sales effectiveness across time, geography, and product dimensions.

The solution integrates a structured data model with DAX-driven KPIs to provide executive-level visibility into business performance and target achievement.

Data Model & Architecture
The dashboard is built using a relational model including:
Fact Table: Sales
Dimension Tables: Date, Product, Region, Reseller, Salesperson
Target Table for performance benchmarking

The model enables:
Time intelligence (Year, Quarter, Month analysis)
Performance comparison vs Targets
Margin and cost tracking
Multi-dimensional slicing (Region, Category, Salesperson)

Business Objectives
Track total sales, cost, and profit trends
Monitor profit margin fluctuations
Compare actual sales vs targets (Variance & Variance %)
Identify high-performing regions and product categories
Analyze quantity contribution by category
Evaluate salesperson performance

Key KPIs Implemented (DAX-Based)
Total Sales
Total Cost
Total Profit
Profit Margin %
Orders Count
Sales vs Target
Variance & Variance %
Country % Contribution
Category-Level Profitability
Time-Based Performance Trends

Key Analytical Insights
Sales exhibit seasonality with noticeable peaks followed by margin compression periods.
The United States dominates revenue contribution compared to other regions.
Clothing and Bikes lead in quantity sold, significantly influencing total revenue.
Certain quarters show declining profit margins due to cost increases.
Target variance analysis highlights underperformance periods followed by recovery cycles.

Technical Implementation
Power BI Data Modeling (Relationships & Star Schema logic)
DAX Measures for financial KPIs
Time Intelligence calculations
Variance & Target comparison logic
Interactive filters (Year, Region)
Multi-page dashboard structure:
Executive Overview
Profit & Cost Analysis
Salesperson Performance
Product-Level Deep Dive

Business Impact
This dashboard demonstrates how raw transactional data can be transformed into structured financial intelligence, enabling:
Early detection of margin erosion
Revenue concentration analysis
Target performance monitoring
Strategic decision support
