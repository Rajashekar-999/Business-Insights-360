# Business-Insights-360

**Project Overview**

AtliQ is a rapidly growing hardware company that sells a wide range of products across multiple countries. Their sales channels include retail outlets, direct-to-customer platforms, and distributor networks—both online and offline. To support their growth and enable data-driven decision-making, AtliQ has initiated the development of a comprehensive data analytics solution.

Live Dashboard – [Click to View](https://app.powerbi.com/links/5Bn1-JhyfB?ctid=c6e549b3-5f45-4032-aae9-d4244dc5b2c4&pbi_source=linkShare&bookmarkGuid=c576ca5e-4835-4ae3-8597-b87d4b2a04f1)

Presentation PPT – [Click to View](https://www.linkedin.com/posts/raja-shekarg_bi360-project-presentation-activity-7274649532846477313-5l6J?utm_source=share&utm_medium=member_desktop&rcm=ACoAADON-YgB0EgIZ2-cObDPZEcM5V_FVS6sis4)

**Technology Stack**

SQL

Power BI

Excel

DAX Studio

PowerPoint

M Language (Power Query)

DAX Language

**Domain Knowledge**

Data Analytics & Warehousing

Data Cataloging

OLTP & OLAP Systems

Star Schema & Snowflake Schema

Fiscal Year (FY), Year to Date (YTD), Year to Go (YTG)

Sales Metrics: Gross Sales, Pre/Post-Invoice Deductions, Net Sales

Cost Metrics: Manufacturing & Freight Costs, COGS

Profitability: Gross Margin, Net Profit, Margin Percentages

Sales & Forecast Analysis: Sales Quantity, Forecast Accuracy, Net & Absolute Errors

**Data Import to Power BI**

Data is sourced from a MySQL database and imported into Power BI using secure access credentials.

Database: gdb041

**Dimension Tables:**

dim_customer

dim_market

dim_product

Fact Tables:

fact_forecast_monthly

fact_sales_monthly

Database: gdb056

Cost Tables:

freight_cost

gross_price

manufacturing_cost

pre_invoice_deductions

post_invoice_deductions

**Data Model:**

Snowflake Schema

![Data Model (SnowFlake Schema)](https://github.com/user-attachments/assets/97dc7fd5-0722-494b-8508-8646057fb861)


**Project Workflow**

**Planning & Scoping**

Defined project goals, timelines, key stakeholders, and scope boundaries.

**Project Charter**

Documented objectives, stakeholders, expectations, success criteria, timelines, and strategies to manage scope creep.

**Data Collection & Exploration**

Collected datasets and created a date table using M Language in Power Query.

**Project Management & Communication**

Maintained consistent communication with stakeholders, asked critical questions, and delivered actionable insights on time.

**Data Loading**

Imported datasets into Power BI and conducted initial data validation.

**Data Transformation**

Cleaned and reshaped data using Power Query transformations.

**Data Modeling**

Created relationships, calculated columns, and structured data using best practices.

**Measure Development**

Used DAX to build key measures and calculations for analytical insights.

**Report Development**

Developed focused views for Finance, Sales, Market, and Supply Chain analysis.

**Dashboard Design**

Designed an intuitive interface with navigation buttons, dynamic titles, KPIs, and conditional formatting for visual benchmarking.

**Data Validation & Testing**

Built a User Acceptance Testing (UAT) report to validate data accuracy and performance.

**Stakeholder Feedback Implementation**

- Incorporated feedback by enabling:

- Dynamic targets

- What-if parameters

- Slicer-based measures

- Bookmarks for seamless navigation

- Tooltips for detailed trend analysis

**Executive Dashboard Creation**

Consolidated all views and KPIs into an executive-level dashboard.

**Deployment & Sharing**

Published reports to Power BI Service for secure access and collaboration.

**Automated Data Refresh**

Configured data gateways for scheduled refreshes to ensure up-to-date insights.


