# Vendor Performance Analysis (End-to-End Data Analytics Project)

### This project analyzes vendor performance data (~2GB dataset) to uncover actionable business insights. The goal was to identify top vendors, underperforming vendors, geographic trends, and profit margins, and provide strategic recommendations for improving sales and operational efficiency.

#### The project combines:

-SQL for data extraction and transformation

-Python (EDA) for exploratory analysis and visualization

-Power BI (with DAX) for interactive dashboards and KPIs

#### Problem Statement

The company relied heavily on a few key vendors but lacked a clear understanding of:

Which vendors drive the most sales & profit

Where inefficiencies (slow turnover, unsold capital) exist

How geographic distribution impacts performance

What strategies can improve low-performing vendors without reducing profitability

### Approach

1. Data Preparation

Imported and processed a 2GB raw dataset with multiple vendor tables.

Cleaned missing values, removed duplicates, and standardized vendor names.

Performed SQL joins and aggregations to merge multiple data sources.


2. Exploratory Data Analysis (EDA)

Used Pandas, Matplotlib, Seaborn to explore sales, purchases, and profit distributions.

Identified outliers, sales trends, and vendor contribution percentages.

Built 20+ Python visualizations to support early findings.


3. Dashboard Development (Power BI)

Designed an interactive Power BI dashboard with:
 KPIs: Total Sales, Total Purchases, Gross Profit, Profit Margin, Unsold Capital
 DAX measures to calculate turnover ratios, purchase contributions, and margins
Vendor contribution breakdown (top vs low performers)
Geographic map showing vendors across the world
Visuals in doughnut charts, bar graphs, and performance metrics


4. Insights & Recommendations

Identified 68M sales from a single vendor (Diageo North America Inc.) → high dependency risk.

Unsold Capital of $4.18M indicated inefficiencies in inventory turnover.

Profit Margin of 44.22% showed strong opportunities to optimize low-performing vendors.

Recommended pricing re-evaluation, vendor diversification, inventory optimization, and marketing strategies.

### Key Findings

Top 10 vendors contributed 70%+ of total sales.

Low-performing vendors had <35% stock turnover.

Dependency on a single vendor accounted for 24.81% of sales.

Optimizing inventory could reduce unsold capital by $4M+.


#### Conclusion

This project demonstrates the end-to-end analytics workflow: from raw SQL queries → EDA in Python → visualization in Power BI → actionable recommendations.

By implementing the strategies identified, businesses can achieve:
Sustainable profitability
Reduced vendor dependency risk
Improved inventory efficiency
Stronger decision-making with data-driven insights

Tech Stack

SQL (Joins, Aggregations, Data Cleaning)

Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn)

Power BI (Interactive Dashboard, DAX Calculations, KPIs, Maps)

Dashboard Preview
https://drive.google.com/file/d/1oRkIuEt85IcbVgVLPnc6lHfkoGm0aJqK/view?usp=sharing
