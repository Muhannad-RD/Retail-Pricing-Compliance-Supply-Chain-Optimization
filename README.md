# Retail Pricing Compliance & Supply Chain Optimization

## Project Overview
This project presents a **Business Intelligence & Supply Chain Analytics** solution for the Retail FMCG & Personal Care domain. By building a complete ETL pipeline and a multi-dimensional data model, the system tracks retail pricing compliance, flags unauthorized discount variations, and optimizes wholesale distribution to prevent supply chain whiplash and critical stockouts.

## Business Intelligence Dashboard
The interactive Power BI dashboard provides a holistic view of financial and logistics performance, allowing Brand Managers to track the margin squeeze, detect compliance anomalies, and isolate underperforming retail channels via cross-filtered temporal and regional views.

> <img width="2156" height="1161" alt="Retail Dashboard Overview" src="Figure 1.png" />
> *Figure 1: Retail Pricing Compliance & Supply Chain Optimization Dashboard*

## Technical Stack
* **Data Modeling:** Star Schema (Fact and Dimension Tables with 1:N Relationships).
* **Data Processing & ETL:** Power Query (Advanced Data Cleansing, Schema Enforcement, Null Handling, and Data Serialization).
* **Calculations:** DAX (Advanced Measures for Dynamic Margins, Retail/Brand Profit Variances, Price Compliance %, and Months of Coverage [MOC]).
* **Visualization:** Power BI Desktop / Power BI Service.
* **Reporting:** Comprehensive Technical & Analytical Business Report in PDF.

## Strategic Insights
* **The Profitability Paradox:** Identified key digital retailers sacrificing their own margins via aggressive, unauthorized discounting to drive consumer volume, threatening long-term brand equity.
* **The Margin Squeeze:** Isolated specific high-velocity SKUs where aggressive retail price cutting directly caused severe wholesale demand spikes, leading to inventory depletion.
* **Supply Chain Whiplash:** Unplanned promotional spikes frequently caused retail purchasing orders to fail, creating an immediate need for synchronized forecasting to stabilize the Months of Coverage (MOC).

## Repository Contents
* `Dashboard.pbix` - Power BI Dashboard Interactive Source File.
* `Retail Pricing Compliance Supply Chain Optimization.pdf` - Final Professional Technical & Analytical Report.
* `Dashboards.pdf` - Static Export & Design Layout of the Power BI Pages.
* `Sales_Generated_Realistic.csv` - Synthesized transactional sales dataset capturing wholesale (Sell-in) and consumer (Sell-out) metrics.
* `Promo_Summary_Cleaned.csv` - Daily web-scraped retail price compliance and promo tracking dataset.

## Author
* **Hassan Al-Hadidi**

* **Bassam Al-Nakhli**

* **Muhannad Al-Raddadi**

## License
This project is licensed under the **MIT License**.
