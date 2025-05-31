# Optimizing Sales Performance and Customer Retention through Data-Driven Insights

---

## 🚀 Project Overview

This project delves into leveraging **data-driven insights** to enhance **sales performance** and improve **customer retention**. By meticulously analyzing key sales metrics and understanding the dynamics of the sales pipeline, we aim to uncover actionable insights that directly contribute to business growth and efficiency.

---

## 📊 Data & Methodology

### Data Sources

Our analysis was built upon data consolidated from four primary tables:
* `account`
* `product`
* `sales_team`
* `sales_pipeline`

### Data Cleaning & Preparation

A critical initial step involved **handling null values** within the datasets. We employed strategies to impute or remove missing data by cross-referencing information available across other related tables, ensuring data integrity.

A fundamental understanding of the business's **sales pipeline** was crucial, which progresses through the following stages: **Prospecting ➡️ Engaging ➡️ Win/Lost**. This sequential flow guided our data preparation to accurately represent the customer journey and conversion points.

### Data Model Creation

To facilitate robust and efficient analysis, we engineered a **star schema** data model. The `sales_pipeline` table was designated as our **fact table**, serving as the central hub for transactional data. The `account`, `product`, and `sales_team` tables were established as **dimension tables**, providing descriptive attributes for the sales transactions.

We established **one-to-many relationships** between the fact and dimension tables, which optimizes query performance and allows for clear analytical pathways.

### DAX Measure Calculations

To derive meaningful insights and create compelling visualizations, we developed several key **DAX (Data Analysis Expressions) measures** within our data model. These custom calculations enabled us to extract specific performance indicators:

* **Number of Deals Lost in Each Stage**: Provides granular visibility into bottlenecks and areas requiring intervention within the sales funnel.
* **Total Revenue Generated**: Tracks the overall financial performance of sales activities.
* **Agent Deal Win Rate**: Assesses the effectiveness and success rate of individual sales team members.
* **Average Deal Size**: Offers insights into the typical value of successfully closed opportunities.

---

## 📈 Key Insights & Findings

Our comprehensive analysis yielded several significant insights, which were visualized and presented in our interactive reports:

1.  **Top 6 Products by Revenue**: Identified the products that contribute most significantly to overall revenue, guiding product strategy and marketing efforts.
2.  **Top 6 Sales Agents by Deals Closed**: Recognized top-performing sales professionals, offering benchmarks for the sales team.
3.  **Sales Funnel Analysis with Conversion Rates**: Provided a detailed breakdown of conversion efficiency at each stage of the sales pipeline. The **overall conversion rate was identified as 48.2%**.
4.  **Lost Deals by Sector**: Revealed that the **Technology** and **Software** sectors accounted for the highest number of lost deals, suggesting potential areas for re-evaluation of sales strategies or product fit within these markets.
5.  **Monthly Revenue Peak**: Pinpointed **June** as the month with the **highest revenue generation**, potentially indicating seasonal trends or successful campaigns during that period.
6.  **Product Performance Comparison**: Noted that while **GTXPro generated the highest revenue**, **GTXBasic achieved the highest number of units sold**, highlighting distinct market positioning and sales volume versus value.

---

## 🛠️ Technologies Used

* **[Specify your ETL tool, e.g., Python (Pandas)]**: For data cleaning and preparation.
* **[Specify your data modeling tool, e.g., Power BI Desktop / SSAS]**: For data modeling and DAX calculations.
* **[Specify your visualization tool, e.g., Power BI / Tableau]**: For report generation and visualization.
