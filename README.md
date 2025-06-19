# Power-Bi-Projects
This repository contains data and dashboards created using Power Bi.
## Tools & Technologies:
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Source Data (CSV/Excel)

## 1. Bank Loan Insights Report
### Bank Loan Approval & Risk Insights Dashboard
This Power BI dashboard analyzes key metrics related to bank loan applications including approval rates, default risk, customer demographics, and loan types. It supports banking teams in optimizing approval strategies and understanding risk profiles.

## Key Features:
- KPI Cards: Total Applications, Approved Loans, Rejected Loans, Default Rate
- Customer Segmentation: Loan analysis by gender, marital status, credit history
- Loan Status Breakdown: Visuals showing approved vs. rejected by category
- Income vs. Loan Amount: Scatterplots for risk analysis
- Filters: Gender, Education, Credit History, Property Area

## Data Model:
- Single or multi-table model depending on dataset
- Columns: ApplicantIncome, CoapplicantIncome, LoanAmount, Credit_History, etc.
- Cleaned using Power Query and transformed into measures with DAX

## Business Use Cases:
- Identify high-risk applicant segments
- Improve loan approval prediction with data-driven logic
- Track overall approval/rejection patterns
- Compare loan status across income groups and credit history

   
## 2. Blinkit Analysis Report
This Power BI dashboard offers an end-to-end analysis of Blinkit's sales operations, focusing on product demand, delivery metrics, and order trends. It helps stakeholders optimize supply chain efficiency, product performance, and regional sales strategies.

## Key Features:
- KPI Cards: Total Orders, Revenue, Average Delivery Time, Product Count
- Order Trend Analysis: Line and bar charts tracking daily/weekly orders
- Product Demand: Most and least sold products, quantity trends
- Delivery Efficiency: Avg. delivery duration by region, order fulfillment rate
- Top Cities & Warehouses: City-wise order count and revenue contribution
- Time Filters: Year, Quarter, Month slicers for time-based analysis

## Data Model:
- Fact Table: Order Transactions
- Dimension Tables: Product, Customer, Location, Time
- Relationships: Star schema with proper cardinality
- Calculated Measures: DAX formulas for delivery time, profitability, daily average

   
## 3. Customer Churn Analysis Report
This dashboard analyzes customer behavior to identify churn patterns and retention drivers. It enables marketing and customer service teams to make data-backed decisions to reduce churn and improve customer satisfaction.

## Key Features:
- KPI Cards: Total Customers, Churn Rate, Active vs. Churned Customers
- Demographics Analysis: Churn by Gender, Age, Tenure
- Service Usage: Correlation of churn with service subscription (Internet, Tech Support, etc.)
- Payment Behavior: Monthly Charges vs. Churn Likelihood
- Churn Heatmaps & Trend Lines: Time-based churn rate visualization
- Slicers: Filters for Contract Type, Payment Method, Internet Service

## Data Model:
- Fact Table: Customer Activity / Churn Status
- Dimensions: Customer Profile, Services, Contracts, Payment Method
- Calculated Columns: Tenure groupings, Churn probability flags
- Measures: Churn Rate %, Active Base, ARPU (Average Revenue Per User)
   
## 4. Sales Analysis Report
This Power BI dashboard provides a comprehensive overview of sales performance across different regions, products, and time periods. It helps business stakeholders identify trends, top-performing categories, sales growth, and regional performance to support strategic decision-making.

## Key Features:
- KPI Cards: Total Sales, Profit, Quantity Sold, Avg. Discount
- Regional Analysis: Map and bar charts showing sales by region and state
- Category & Sub-Category Performance: Product-wise sales breakdown
- Time-Series Analysis: Sales trends across months/years
- Profitability Overview: Profit margins and high/low-profit segments
- Filters: Slicers for Region, Category, Time Period, etc.

## Data Model:
- Fact Table: Sales Data
- Dimension Tables: Customer, Product, Region, Date
- Relationships: Star schema with 1-to-many between dimension and fact tables

## Business Use Cases:
- Identify high-performing regions and products
- Monitor sales KPIs over time
- Enable cross-filtering for targeted business insights
- Support quarterly and yearly sales reporting










