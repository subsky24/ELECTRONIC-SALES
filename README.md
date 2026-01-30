# ELECTRONIC-SALES
PROJECT TITLE

Sales Performance & Profitability Analysis Dashboard

📌 PROJECT DESCRIPTION

This project analyzes an Electronic Sales dataset to evaluate overall sales performance, growth trends, and profitability across time, channels, products, and regions.

The objective was to move beyond raw sales figures and uncover:

How sales are evolving year-to-date and year-over-year

Which products, channels, and regions drive profit

Where growth metrics are distorted due to data structure

How management can improve pricing, assortment, and regional strategy

The final deliverable is an interactive Power BI dashboard designed for executive decision-making, with clear KPIs, trend analysis, and insight panels.

🛠 TOOLS USED

Microsoft Power BI

Power Query (ETL & data cleaning)

DAX (Time intelligence & KPIs)

Data modeling

Interactive visuals & dashboard design

Excel (initial data inspection)

🎯 BUSINESS QUESTIONS ADDRESSED

Overall Performance

What are total sales, year-to-date sales, YoY growth, and profit margin?

How has sales performance evolved over time?

Time-Based Analysis

How do sales trend monthly and quarterly?

Which quarters and months contribute most to YTD performance?

How does current performance compare to the same period last year?

Channel Performance

Which sales channel generates the most revenue and profit?

Are differences in performance driven by volume or margin?

How does YoY growth vary across channels?

Product Performance

Which product categories are top and bottom performers?

How do sales and profit differ across product categories?

Why do some products show high growth but low sales?

Regional (Zone) Performance

Which regions are most profitable?

Where are margins strongest and weakest?

How do regional YoY trends differ?

🔧 POWER QUERY (ETL) MODIFICATIONS

The following transformations were applied to ensure data quality and analytical accuracy:

Converted Order Date to proper Date format

Removed duplicates and handled missing values

Standardized column names for consistency

Ensured numeric fields (Sales, Profit, Quantity, Cost) were correctly typed

Created clean, analysis-ready tables for:

Sales

Products

Channels

Zones

Validated data ranges to avoid incorrect time intelligence results

🧮 DAX MEASURES USED
Core Measures

Total Sales

![image-URL](https://github.com/subsky24/ELECTRONIC-SALES/blob/main/IMAGES/Screenshot%20(328).png?raw=true)

Total Profit

![image-URL](https://github.com/subsky24/ELECTRONIC-SALES/blob/main/IMAGES/Screenshot%20(322).png?raw=true)


Total Order Quantity

Profit Margin %

Time Intelligence Measures

Sales YTD

![image-URL](https://github.com/subsky24/ELECTRONIC-SALES/blob/main/IMAGES/Screenshot%20(327).png?raw=true)

Sales MTD

![image-URL](https://github.com/subsky24/ELECTRONIC-SALES/blob/main/IMAGES/Screenshot%20(324).png?raw=true)

Sales QTD

![image-URL](https://github.com/subsky24/ELECTRONIC-SALES/blob/main/IMAGES/Screenshot%20(325).png?raw=true)

Sales SPLY (Same Period Last Year)

![image-URL](https://github.com/subsky24/ELECTRONIC-SALES/blob/main/IMAGES/Screenshot%20(326).png?raw=true)

YoY Variance

YoY Variance %

Sales Last Month

![image-URL](https://github.com/subsky24/ELECTRONIC-SALES/blob/main/IMAGES/Screenshot%20(323).png?raw=true)

Supporting Measures

Dynamic variance color logic (positive = green, negative = red)

Context-aware calculations using CALCULATE

Proper use of date context with a dedicated Date Table

These measures enabled accurate trend comparison and avoided misleading growth interpretations.

📈 KEY INSIGHTS & FINDINGS
Time & Growth Insights

Sales show steady month-over-month growth, with later months contributing the highest YTD sales.

Q4 was the strongest quarter in 2013, while Q2 led performance in 2012 and 2014.

YoY variance appears negative in later years due to base-year distortion, caused by partial sales data starting late in 2011.

Channel Insights

The Store channel generates the highest sales and absolute profit.

All channels maintain similar profit margins, indicating consistent pricing and cost control.

Differences in channel performance are volume-driven rather than margin-driven.

Catalog channel shows the largest YoY decline, signaling reduced relevance or reach.

Product Insights

Computers are the top-performing product category by both sales and profit.

Music, Movies, and Audio are the weakest in sales.

Audio shows high YoY growth percentages but low absolute sales, indicating growth from a small base rather than true scale.

Regional (Zone) Insights

South East records the highest Sales YTD and strongest profit margin.

North Central also demonstrates high profit-to-sales efficiency.

FCT underperforms in both Sales YTD and YoY growth, suggesting structural or demand challenges.

Regional differences have a greater impact on profitability than channel differences.

💡 BUSINESS RECOMMENDATIONS
1️⃣ SKU Optimization in Store Channel

Focus store inventory on high-performing SKUs such as Computers and Camcorders.

Reduce shelf space for consistently low-performing categories.

2️⃣ Price & Cost Review

Conduct targeted cost reviews in underperforming regions (e.g., FCT).

Identify logistics or operational inefficiencies impacting margins.

3️⃣ Margin Normalization Strategy

Since margins are similar across channels, prioritize volume expansion rather than aggressive repricing.

Protect margin consistency while scaling sales.

4️⃣ Targeted Regional Pilots

Use South East and North Central as pilot regions for:

New product launches

Promotional campaigns

Apply successful strategies selectively to weaker regions.

5️⃣ Growth Interpretation Discipline

Avoid over-reliance on YoY % alone.

Always evaluate growth metrics alongside absolute sales values to prevent misinterpretation.

![image_URL](https://github.com/subsky24/ELECTRONIC-SALES/blob/main/IMAGES/Screenshot%20(301).png)
![image URL](https://github.com/subsky24/ELECTRONIC-SALES/blob/main/IMAGES/Screenshot%20(297).png?raw=true)

