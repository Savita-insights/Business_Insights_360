## 📊 Business Insights 360 | Power BI Project
## 📑 Project Overview

AtliQ Hardware, a fast-growing global computer hardware company, wanted to strengthen its market position through data-driven decision making. For the first time, they adopted Power BI to transform raw data into actionable insights across Finance, Sales, Marketing, and Supply Chain.

This project aimed to answer key stakeholder questions, improve profitability, and ensure smarter business moves — especially after recent setbacks caused by intuition-based decisions.

🔗 [Live Report Link]

## 👨‍💻 Tech Stack

- SQL – Data extraction & transformation
- Power BI Desktop – Visualization & reporting
- Excel – Data preparation & validation
- DAX Language – Measures & calculations
- DAX Studio – Performance optimization
- Project Charter File – Governance & scope definition

## 🎓 Power BI Skills Gained

✔ Asking the right business questions before starting a project

✔ Creating calculated columns & DAX measures

✔ Data modeling (Snowflake schema) for optimized performance

✔ Dynamic dashboards using bookmarks, buttons & navigation

✔ Preventing zero-division errors with DIVIDE() function

✔ Building date tables with M language

✔ Dynamic titles & KPI indicators based on filters

✔ Conditional formatting (icons, color scales)

✔ Publishing & collaborating in Power BI Service

✔ Setting up personal gateway for scheduled refresh

✔ Creating & sharing Power BI Apps for stakeholders

## 🌐 GitHub Skills

- Large file handling with GitHub LFS
- File extension tracking for streamlined version control

## 💼 Business Domain Knowledge

- **Finance:** Gross Price, Net Sales, Net Profit, COGS, Margins
- **Sales:** Direct, Retailer, Distributor models
- **Performance Metrics:** YTD, YTG analysis
- **Supply Chain:** Forecasting, Freight, Manufacturing Costs

## 🏬 Company Background

AtliQ Hardware operates globally, selling PCs, accessories, networking & storage solutions through Retail, Direct, and Distributor channels.

⚠️ **Challenge:** Expansion into the U.S. failed due to reliance on surveys & intuition rather than analytics. Competitors with advanced data teams gained an edge.

✅ **Solution:** Build a data analytics system (this project) to drive decisions with evidence-based insights.

## ❓ Stakeholder Kick-Off Questions

- Before dashboard development, we aligned on:
- Objective & success measures
- Timeline & preview expectations
- Stakeholder hopes, fears, and requirements
- End-users & use cases
- Data availability & validation process
- Potential risks during development

**Dimension Tables (Static Data):**

- **dim_customer:** 27 markets (India, USA, Spain…), 75 customers, 2 platforms (Brick & Mortar, E-commerce), 3 channels (Retailer, Direct, Distributor)
- **dim_market:** 27 markets, 7 sub-zones, 4 regions (APAC, EU, NA, LATAM)
- **dim_product:** Divisions (P&A, Peripherals, Accessories, PC, Notebook, Desktop, Networking, Storage), 14 categories, multiple product variants

**Fact Tables (Transactional Data):**

- **fact_forecast_monthly:** Customer demand forecasts → improves satisfaction & reduces storage cost; denormalized by Data Engineering; start-of-month granularity
- **fact_sales_monthly:** Similar to forecast table but includes actual sales quantities

**Additional Tables:**

- **freight_cost:** Travel and logistics costs per market/year
- **gross_price & manufacturing_cost:** Product pricing & manufacturing cost details
- **pre_invoice_deductions & post_invoice_deductions:** Customer-specific deductions by year
  
## 📥 Data Import & Modeling

- Data sourced from MySQL into Power BI

- Applied Snowflake data modeling for scalability & performance

- Created relationships for Finance, Sales, Marketing & Supply Chain analysis

## 🎨 Dashboard Design

**Home View:** Central navigation hub

Finance, Sales, Marketing, Supply Chain, Executive Views – tailored insights for each function

Interactive visuals, drilldowns, KPIs, and trend analysis

## 🎯 Project Outcomes

Enabled data-driven decision making

Answered critical “Why” questions across departments

Improved forecasting, cost management, and profitability

Established a scalable analytics foundation for AtliQ Hardware
