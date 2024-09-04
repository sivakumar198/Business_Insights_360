# Business Insights 360

## Project Overview

AtliQ Hardware, a rapidly growing company in the tech industry, has embarked on its first data analytics initiative using Power BI. The goal is to leverage data to outpace competitors and enhance decision-making across finance, sales, marketing, and supply chain management. This project aims to address stakeholders' questions and provide actionable insights to drive the company's strategic decisions.

I developed this project following the Codebasics Power BI Course and have applied various Power BI techniques to deliver comprehensive insights.

## Tech Stack

- **SQL**
- **Power BI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for report optimization)
- **Power BI Services**

## Key Techniques Learned

- Defining project objectives and success criteria
- Creating calculated columns and measures using DAX
- Data modeling best practices
- Utilizing bookmarks and page navigation
- Implementing dynamic titles and KPIs
- Conditional formatting and data validation
- Publishing and managing reports in Power BI Services
- Setting up personal gateways and Power BI Apps

## Business Terminology

- **Gross Price**
- **Pre-Invoice Deductions**
- **Post-Invoice Deductions**
- **Net Invoice Sale**
- **Gross Margin**
- **Net Sales**
- **Net Profit**
- **COGS** (Cost of Goods Sold)
- **YTD** (Year to Date)
- **YTG** (Year to Go)
- **Direct**
- **Retailer**
- **Distributors**
- **Consumer**

## Company Background

AltiQ Hardware has seen significant global expansion, selling computer hardware and accessories through various channels:

- **Retailers**
- **Direct Sales**
- **Distributors**

Despite its growth, the company faced unexpected losses in the American market. In response, AltiQ Hardware is building its analytics team to better compete and make informed decisions based on data-driven insights.

## Project Kick-Off

Before starting the dashboard, consider these questions:

- What is the objective of the Power BI dashboard?
- How will the project's success be measured?
- What is the project's deadline?
- Are stakeholders expecting a preview before the final release?
- What are stakeholders' hopes and concerns regarding the project?
- Who will use the dashboard, and for what purposes?
- What are the expectations for the project's completion?
- What resources and data are needed?
- Are there specific design inputs from stakeholders?

## Dataset Overview

### Dimension Tables

- **dim_customer**: Contains details of customers and markets.
- **dim_market**: Provides market, sub-zone, and regional information.
- **dim_product**: Includes product divisions, categories, and variants.

### Fact Tables

- **fact_forecast_monthly**: Contains customer demand forecasts to aid in inventory management.
- **fact_sales_monthly**: Records actual sales quantities.

### Additional Tables

- **freight_cost**: Details travel and other costs for each market.
- **gross_price**: Records product gross prices.
- **manufacturing_cost**: Lists manufacturing costs by product and year.
- **pre_invoice_deductions**: Shows pre-invoice deduction percentages.
- **post_invoice_deductions**: Provides post-invoice deduction details.

## Importing Data into Power BI

Data from a MySQL database is imported into Power BI by providing the necessary database access credentials.

## Data Modeling

Data modeling is crucial for report performance. This project utilizes the Snowflake Schema for data modeling. Adhering to good data modeling practices ensures efficient and effective report generation.

## Overall Report

