# BI-360 Power BI Dashboard
# Business Insights 360 Project Report for AtliQ Hardwares
# Project Overiew

AtliQ Hardware has seen rapid growth in recent years. To stay ahed of competitors and make data-driven decisions, the company has implemented data analytics using Power BI for the first time. This project aims to provide insights into various aspects of the business, including Finance, Sales, Marketing, and Supply Chain, addressing stakeholders queries effectively.

# Live Power BI Report Link
# Tech Stacks
# 🔹SQL
# 🔹Power BI Desktop
# 🔹Excel
# 🔹DAX Language
# 🔹DAX Studio (for report optimization)
# 🔹Project Charter File
# 🔹Power BI Service

# Power BI Techniques Learned
🔹Key questions to ask before starting a project.

🔹Creating calculated columns and measures using DAX.

🔹Data modeling best practices.

🔹Using bookmarks to switch between visuals.

🔹Page navigation with buttons for better user experience.

🔹Using the DIVIDE function to prevent division by zero errors.

🔹Creating a date table using M language for time intelligence.

🔹Dynamic titles based on applied filters.

🔹Implementing KPI indicators.

🔹Conditional formatting using icons or background colors in visuals.

🔹Data validation techniques for accurate reporting.

🔹Publishing reports to Power BI Services.

🔹Setting up a personal gateway for auto-refresh.

🔹Power BI App creation and collaboration via workspaces and access permissions.

# Business Terminology
🔹 Gross Price

🔹 Pre-Invoice Deductions

🔹 Post-Invoice Deductions

🔹 Net Invoice Sale

🔹 Gross Margin 

🔹 Net Sale

🔹 Net Profit

🔹 COGS - Cost of Goods Sold

🔹 YTD - Year to Date

🔹 YTG - Year to GO

🔹 Direct Retailers

🔹 Distributors

🔹 Consumers

# Company Background
AtliQ Hardware has grown rapidly in recent years and expanded its operations globally. The company sells computers and accessories via three channels:

# 🔹 Retailers
# 🔹 Direct
# 🔹 Distributors

Recently, AtliQ faced an unexpected loss due to opening a store in America based on intution rather than solid analytics. Competitors already had dedicated analytics teams to make data-driven decisions. AtliQ Hardware has now committed to building its analytics team to gain valuable insights and make informed business decisions in the future.

# Project Kickoff Session
During the project kickoff, it is essential to clarify all aspects of the project, including:

  🔹The objective of building the Power BI dashboard.
	
  🔹Success metrics for the project.

  🔹 Project timeline and deadlines.

  🔹 Stakeholder expections for previews before the final release.

  🔹 Fears or concerns stakeholders have about the project.

  🔹 The purpose of the dashboard and who will be using it.

  🔹 Stakeholder expections and possible risks.

  🔹 Required resources and data for dashboard development.

  🔹 Stakeholder input on dashboard design and views.

# Dataset Understanding
Understanding the dataset is critical for accurate analysis. The dataset contains:

🔹Dimension Table: Static data such as customer and product details.

🔹Fact Table: Transactional data for sales and forecasting.

# Key Tables

🔹dim_customer: Contains customer information accross 27 markets and two platforms (Brick & Mortar, E-commerce).

🔹dim_market: Contains market details across 27 markets, seven sub-zones, and four regions.

🔹 dim_product: Product data across divisions (Peripherals, PC, Networking, etc.).

🔹 fact_forecast_monthly: Forecasting customer demand to improve satisfaction and reduce warehouse costs.

🔹  fact_sales_monthly: Sales data, structured similarly to the forecast table, but with actual sales values.

🔹  freight_cost: Travel and other costs per market.

🔹  gross_price: Gross prices by product code.

🔹  manufacturing_cost: Manufacturing costs by product and year.

🔹  pre_invoice_deductions: Pre-invoice deductions percentage for customers.

🔹  post_invoice_deductions: Post-invoice deductions and additional deductions.

# Importing Data into Power BI
 The dataset is sourced from a MySQL database. The data is imported into Power BI by providing the   database access credentials.

# Data Modeling
Data modeling forms the foundation of the Power BI report. Poor data modeling can negatively impact report performance. In this project, we followed the Snowflake Data Modeling Method to ensure efficiency and scalability




