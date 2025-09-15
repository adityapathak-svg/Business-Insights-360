# 📊 BI-360 Power BI Dashboard  
### Business Insights 360 Project Report for **AtliQ Hardwares**  

---

## 🚀 Project Overview  
AtliQ Hardware has seen rapid growth in recent years. To stay ahead of competitors and make data-driven decisions, the company has implemented **Power BI** for the first time.  

This project provides insights into **Finance, Sales, Marketing, and Supply Chain**, addressing stakeholders’ queries effectively.  

---

## 🔗 Live Power BI Report Link  
*(Add your link here)*  

---

## 🛠️ Tech Stacks  
- SQL  
- Power BI Desktop  
- Excel  
- DAX Language  
- DAX Studio (for report optimization)  
- Project Charter File  
- Power BI Service  

---

## 📚 Power BI Techniques Learned  
- Key questions to ask before starting a project  
- Creating calculated columns and measures using DAX  
- Data modeling best practices  
- Using bookmarks to switch between visuals  
- Page navigation with buttons for better UX  
- Using the **DIVIDE** function to prevent division by zero errors  
- Creating a date table using **M language** for time intelligence  
- Dynamic titles based on applied filters  
- Implementing KPI indicators  
- Conditional formatting (icons/background colors)  
- Data validation techniques for accurate reporting  
- Publishing reports to Power BI Services  
- Setting up a personal gateway for auto-refresh  
- Power BI App creation & collaboration via workspaces and permissions  

---

## 🏷️ Business Terminology  
- Gross Price  
- Pre-Invoice Deductions  
- Post-Invoice Deductions  
- Net Invoice Sale  
- Gross Margin  
- Net Sale  
- Net Profit  
- COGS – Cost of Goods Sold  
- YTD – Year to Date  
- YTG – Year to Go  
- Direct Retailers  
- Distributors  
- Consumers  

---

## 🏢 Company Background  
AtliQ Hardware has grown rapidly and expanded globally. It sells computers and accessories via:  
- Retailers  
- Direct  
- Distributors  

Recently, AtliQ faced a loss due to opening a store in America based on intuition rather than analytics, while competitors had dedicated data teams. To avoid repeating this, AtliQ has committed to building an analytics team to make **data-driven decisions**.  

---

## 📝 Project Kickoff Session  
Key clarifications during the kickoff:  
- Objective of building the Power BI dashboard  
- Success metrics for the project  
- Timeline & deadlines  
- Stakeholder expectations (previews before release)  
- Risks, fears, or concerns from stakeholders  
- Dashboard purpose and target users  
- Required resources and data  
- Input on design and views  

---

## 📂 Dataset Understanding  
The dataset includes:  
- **Dimension Table** → Static data (customers, products)  
- **Fact Table** → Transactional data (sales, forecasting)  

### 🔑 Key Tables  
- **dim_customer** → Customer info across 27 markets & 2 platforms (Brick & Mortar, E-commerce)  
- **dim_market** → Market details (27 markets, 7 sub-zones, 4 regions)  
- **dim_product** → Product data across divisions (Peripherals, PC, Networking, etc.)  
- **fact_forecast_monthly** → Forecasting customer demand (improve satisfaction, reduce warehouse costs)  
- **fact_sales_monthly** → Actual sales data, structured like forecast table  
- **freight_cost** → Travel & market-wise costs  
- **gross_price** → Product-wise gross prices  
- **manufacturing_cost** → Yearly product manufacturing costs  
- **pre_invoice_deductions** → Pre-invoice deduction % for customers  
- **post_invoice_deductions** → Post-invoice & additional deductions  

---

## 🗄️ Importing Data into Power BI  
- Data is sourced from a **MySQL database**  
- Imported into Power BI via database access credentials  

---

## 🧩 Data Modeling  
Data modeling is the **foundation of the Power BI report**. Poor modeling = poor performance.  
This project uses the **Snowflake Data Modeling Method** for efficiency & scalability.  

---
✨ *End of Report*  
