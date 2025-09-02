# [Project 1 : Marketplace Data Pipeline](https://github.com/JacobLender/Marketplace-Value-Pipeline)
- Built a **daily (~100 listings/day)** pipeline ingesting eBay, Craigslist, personal inventory, and active eBay listings into **Supabase/Postgres**.
- Designed a **raw → clean → summary** model with `dim_date` & `dim_search_terms`, idempotent upserts, and run logging.
- Delivered **Power BI (.pbix)** dashboards: **Process Pipeline**, **This Week’s Flip Opportunities** (pricing, margins, aging), and **Inventory Lifecycle Tracker**.
- Added **GenAI (OpenAI API)** to label Craigslist leads **Good / Medium / Bad** for fast triage.
- Automated with **cron/launchd**; secrets via **.env**; reduced manual sourcing and exposed margin drag (shipping, rushed sales).

# [Project 2 : Sales and Revenue Performance](https://github.com/JacobLender/Sales_Rev_Costs)
* Developed a Python-based data analysis script using Pandas, Matplotlib, and Seaborn to explore weekly sales and revenue trends.
* Connected Salesforce data and automated extraction into Google Sheets for streamlined data access and storage.
* Designed and deployed an interactive Power BI dashboard to enable stakeholders to monitor key sales and revenue KPIs in real time.
* Enabled data-driven decision-making by visualizing performance across time periods, regions, and products.

# [Project 3 : Financial Clarity Dashboard](https://github.com/JacobLender/Financial-Clarity)
* Built a dynamic Power BI dashboard to consolidate financial metrics including cash flow, revenue, expenses, and departmental budgets.
* Automated data pipelines and refresh schedules to replace manual weekly data prep, increasing reporting efficiency.
* Created customized, role-based views to serve executives, finance, and operations teams with targeted insights.
* Enabled tracking of profitability and cash trends, and visualized budget vs. actuals for strategic planning.
* Empowered stakeholders to make faster, data-informed decisions, reducing dependency on spreadsheets for financial reporting.

# [Project 4 : Ecommerce-Insights](https://github.com/JacobLender/Ecommerce-Insights)
* Built a full-stack E-commerce analytics solution combining Power BI dashboards and Python churn modeling to deliver actionable insights on customer behavior and ad performance to inform retention strategy.
* Engineered a churn prediction pipeline using labeled customer behavior data, Random Forest classification, and feature engineering to score churn risk with probability outputs.
* Designed and implemented interactive Power BI dashboards tracking sales KPIs, customer lifecycle segmentation (New, Active, Churned), ad performance (CAC, ROAS, LTV), and reorder patterns using DAX and visual analytics.
* Segmented and ranked customers by churn risk using predictive-generated scores to support targeted retention campaigns and increase customer lifetime value.
* Packaged project with clear documentation and visuals to support portfolio presentation and real-world MVP demonstration for product or marketing decision-makers.


