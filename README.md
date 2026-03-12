# 📊 Business Insights 360 – Power BI Analytics Project

🔗 **Live Dashboard:**  
https://app.powerbi.com/view?r=eyJrIjoiODIzOWQ1MDAtODc0ZC00ZTZjLTgwNWQtN2M1ZDEyZjgwNjUyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

---

# 🌟 Project Overview

AtliQ Hardware is a global hardware manufacturer that sells computers and accessories across multiple markets. As the company expanded internationally, leadership required a **centralized analytics platform** to track business performance across finance, sales, marketing, supply chain, and executive divisions.

This project builds a **Business Insights 360 dashboard using Power BI**, transforming raw operational data into an interactive decision-support system for stakeholders.

The dashboard enables different business teams to:

- Track revenue and profitability  
- Monitor customer and product performance  
- Evaluate marketing and regional performance  
- Analyze forecast accuracy and supply chain efficiency  
- Provide executives with a high-level business overview  

This project demonstrates how **large-scale business data can be transformed into actionable insights using Power BI and DAX.**

---

# 🏢 Business Problem

AtliQ Hardware previously relied heavily on **Excel-based reporting and manual analysis**, which created several challenges:

- Limited visibility across global markets  
- Difficulty identifying top and underperforming products  
- Lack of real-time insights for decision making  
- Poor coordination across departments  
- Inefficient forecasting and supply chain planning  

The objective of this project is to create a **centralized analytics dashboard** that allows stakeholders to quickly understand business performance and make **data-driven decisions**.

---

# 💻 Tech Stack

The following tools and technologies were used:

- **SQL** – Data extraction and preprocessing  
- **Power BI Desktop** – Dashboard development  
- **Power Query** – Data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – Business calculations and KPIs  
- **DAX Studio** – Query optimization and performance tuning  
- **Excel** – Data validation and initial exploration  

---

# 🛠️ Power BI Features Implemented

This dashboard leverages several advanced Power BI features:

- Data transformation using **Power Query**
- **Snowflake data modeling** for optimized relationships
- Creation of **business measures using DAX**
- **Dynamic titles** responding to slicer selections
- **Conditional formatting** for KPI indicators
- **Bookmarks and navigation buttons** for smooth report navigation
- **Drill-through pages** for deeper insights
- **Custom tooltips** for contextual information
- **Date table creation using M language**
- **Data validation techniques** to ensure accuracy

---

# 📂 Dataset Overview

The project uses two datasets provided as part of the business analytics simulation.

## Database 1: gdb041

This dataset contains **core transactional and dimensional data.**

### dim_customer

- Contains customer information  
- **75 unique customers across 27 markets**  
- Customer channels:
  - Retailers
  - Distributors
  - Direct Sales
- Platforms include **Brick & Mortar and E-commerce**

### dim_market

Market classification organized into:

- **4 regions:** APAC, EU, LATAM, NAN  
- **7 sub-zones**

### dim_product

Product information including divisions and categories.

Product divisions include:

- **P&A** – Peripherals & Accessories  
- **PC** – Notebooks & Desktops  
- **N&S** – Networking & Storage  

### fact_sales_monthly

- Monthly sales transactions  
- Includes product, customer, and sales quantity information  

### fact_forecast_monthly

- Monthly demand forecasts  
- Used to evaluate **forecast accuracy** and support supply chain planning  

---

## Database 2: gdb056

This dataset contains **cost and pricing related data.**

### freight_cost

- Logistics and freight expenses by market and fiscal year  

### gross_price

- Product gross price by fiscal year  

### manufacturing_cost

- Manufacturing cost per product by year  

### pre_invoice_deductions

- Trade discounts applied before invoicing  

### post_invoice_deductions

- Discounts and claims applied after invoicing  

---

# 🗂️ Data Model

The Power BI model follows a **Snowflake Schema**, ensuring efficient querying and optimized performance.

The model connects:

- Sales transactions  
- Customer data  
- Product information  
- Market segmentation  
- Pricing and cost tables  

This structure enables **cross-functional analysis across finance, sales, marketing, and supply chain teams.**

---

# 💡 Dashboard Overview

The dashboard provides a **360° analytical view of AtliQ Hardware’s business performance** across multiple functional areas.

---

# 🏠 Home View

The Home page acts as a **central navigation hub** for the entire report.

Users can navigate to different business views including:

- Finance  
- Sales  
- Marketing  
- Supply Chain  
- Executive  

This design improves accessibility and makes the dashboard easier for stakeholders to explore.

---

# 💰 Finance View

The Finance dashboard focuses on **financial performance and profitability analysis.**

Key elements include:

- Profit & Loss statement breakdown  
- Net Sales trends over time  
- Gross Margin analysis  
- Top and bottom performing customers  
- Top and bottom performing products  

This view helps finance teams **monitor revenue drivers and cost structures.**

---

# 📈 Sales View

The Sales dashboard focuses on **customer and product sales performance.**

Key metrics include:

- Net Sales  
- Gross Margin %  
- Sales by customer  
- Sales by product  
- Unit economics and deductions  

Sales managers can identify:

- High-value customers  
- Revenue-driving products  
- Sales trends across markets  

---

# 📊 Marketing View

The Marketing dashboard analyzes **market and regional performance.**

Insights include:

- Sales performance by region  
- Market-wise revenue trends  
- Customer segmentation  
- Product performance across markets  
- Gross Margin % and Net Profit % by segment  

This allows marketing teams to understand **which markets and segments drive business growth.**

---

# 🚚 Supply Chain View

The Supply Chain dashboard evaluates **forecast accuracy and operational efficiency.**

Key metrics include:

- Forecast Accuracy  
- Net Error  
- Absolute Error  
- Monthly demand forecasting trends  

This helps supply chain teams:

- Improve demand forecasting  
- Reduce stock imbalances  
- Optimize procurement planning  

---

# 👔 Executive View

The Executive dashboard provides a **high-level overview of business performance.**

Key insights include:

- Revenue by division  
- Revenue by channel  
- Sales by top customers  
- Sales by top products  

Executives can quickly evaluate **overall business health and performance trends.**

---

# 🚀 Project Outcome

This project demonstrates how **large-scale business data can be transformed into actionable insights using Power BI.**

Key outcomes include:

- Converting **1.5M+ rows of raw data** into an interactive analytics dashboard  
- Creating a **single source of truth for business performance**  
- Enabling cross-functional analytics across departments  
- Supporting leadership with **data-driven decision making**

The dashboard empowers:

### Finance Teams
→ Monitor profitability and financial trends  

### Sales Teams
→ Identify key customers and products driving revenue  

### Marketing Teams
→ Understand regional and market performance  

### Supply Chain Teams
→ Improve demand forecasting and operational planning  

### Executives
→ Track overall business performance quickly and efficiently  

---

# 📬 Contact

If you'd like to connect or discuss this project:

**LinkedIn:** www.linkedin.com/in/tamil-eniyan-a7116a171
**Email:** umayalini64@gmail.com
