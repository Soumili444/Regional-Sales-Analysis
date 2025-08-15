📊 USA Regional Sales Analysis
🗂️ Project Summary

This Exploratory Data Analysis (EDA) notebook examines Acme Co.’s 2014–2018 USA sales dataset to uncover actionable business insights.

Key steps:

Data Profiling & Cleaning – Verified schema, fixed missing budgets, corrected data types.

Univariate & Bivariate Analysis – Explored revenue, margin, unit price, and segmented by product, channel, and region.

Trend & Seasonality Analysis – Tracked monthly/yearly sales patterns and identified recurring peaks and troughs.

Outlier Detection – Highlighted unusually high or low transactions in revenue and unit price.

Correlation & Segmentation – Measured relationships between metrics and grouped customers by revenue vs. profit margin.

❓ Problem Statement

Analyze Acme Co.’s 2014–2018 sales data to:

Identify revenue and profit drivers across products, channels, and regions.

Uncover seasonal trends and outliers.

Compare actual performance vs. budgets.

Recommend strategies for pricing, promotions, and market expansion to achieve sustainable growth and lower concentration risk.

📂 Dataset

The dataset contains:
Timeframe: 2014–2018
Metrics: Revenue, profit margin, unit price, budget
Dimensions: Product, channel, region, customer segment

🛠️ Tech Stack

Language: Python 3

Libraries:
  -pandas – data manipulation & cleaning
  -numpy – Numerical computations.
  -matplotlib.pyplot – Static data visualizations.
  -matplotlib.ticker.FuncFormatter – Custom number formatting in Matplotlib charts.
  -seaborn – Statistical and aesthetic data visualization.

  📈 Key Insights

Seasonality & Trends

  -Clear Q4 sales spikes observed each year, especially in December, driven by holiday demand.
  -Noticeable sales dip in Q2 2016, possibly linked to channel strategy changes.

Regional Performance

  -West region consistently delivers the highest revenue and profit margins.
  -Central region shows stable but lower revenue, suggesting potential for targeted marketing.

Channel Analysis

  -Retail channel contributes the largest share of total revenue.
  -Online sales show a steady year-on-year growth trend, hinting at a digital shift.

Product Insights

  -High-margin products are concentrated in specific categories sold heavily in the West.
  -Certain low-margin products dominate the volume but contribute little to profit.

Outlier Detection

  -Identified transactions with abnormally high unit prices — possible pricing errors or special one-off deals.
  -Several low-revenue transactions from the same region/channel suggest inefficiencies.
  
Budget vs. Actual Performance
  
  -Budget targets were consistently met or exceeded in most years, except 2016.
  -Significant overperformance in 2017, especially in the Retail channel.
