# 📊 Power BI Inflation Analysis

A _data analysis and visualization project_ using _Power BI_ to explore and interpret _inflation trends_ over time.  
This project transforms raw economic data into _interactive dashboards_ that help understand how inflation impacts different sectors, regions, and time periods.

---

## 🧭 Table of Contents

1. [Project Overview](#project-overview)
2. [Objectives](#objectives)
3. [Data Sources & Preparation](#data-sources--preparation)
4. [Methodology & Analysis](#methodology--analysis)
5. [Dashboard Structure & Visuals](#dashboard-structure--visuals)
6. [How to Use / Reproduce](#how-to-usereproduce)
7. [Key Insights & Findings](#key-insights--findings)
8. [Future Enhancements](#future-enhancements)
9. [Folder & File Structure](#folder--file-structure)
10. [Technologies & Tools](#technologies--tools)
11. [Final Output](#final-output)

---

## 🧩 Project Overview

Inflation plays a crucial role in economic stability and consumer behavior.  
This Power BI project analyzes _historical inflation data_ to identify _patterns, trends, and insights_ that can aid decision-making for policymakers, businesses, and individuals.

The dashboard provides an _interactive interface_ to visualize inflation rates over different time periods, across regions and sectors, highlighting the underlying causes and effects.

---

## 🎯 Objectives

- Analyze and visualize inflation trends over time
- Compare inflation rates across regions or economic categories
- Identify periods of significant inflationary or deflationary pressure
- Enable dynamic data exploration using filters and slicers
- Provide data-driven insights to support decision-making

---

## 🗂 Data Sources & Preparation

> (Note: Update these based on your actual dataset)

_Primary Data Source:_

- Consumer Price Index (CPI) or Inflation data from government portals, World Bank, or IMF

_Supplementary Data (if used):_

- GDP growth data, commodity price data, sectoral indices, etc.

_Data Cleaning & Transformation Steps:_

- Removed missing or duplicate entries
- Standardized date formats
- Converted nominal values into percentage changes
- Calculated Month-over-Month (MoM) and Year-over-Year (YoY) inflation rates
- Derived rolling averages for smoothing volatility

---

## 🔍 Methodology & Analysis

1. _Data Collection_

   - Collected multi-year inflation data across various parameters.

2. _Data Preprocessing_

   - Cleaned and normalized the dataset to ensure consistent formats.

3. _Computation_

   - Calculated average inflation rate, price index, and variance per time frame.

4. _Visualization_

   - Designed dynamic visuals such as line charts, bar graphs, and KPI cards.

5. _Analysis_
   - Identified inflation spikes, trends, and correlations with key macroeconomic factors.

---

## 📈 Dashboard Structure & Visuals

| Dashboard Page          | Description                                                   |
| ----------------------- | ------------------------------------------------------------- |
| _Overview Page_         | Shows key metrics (average inflation, CPI trends, YoY change) |
| _Trend Analysis_        | Line charts for month-wise/year-wise inflation patterns       |
| _Category Comparison_   | Sector-wise inflation comparison using bar charts             |
| _Geographical Insights_ | Map visuals for country or region-level inflation             |
| _Interactive Filters_   | Slicers for year, sector, or timeframe selection              |
| _Summary Page_          | Key takeaways, highest inflation periods, volatility insights |

---

## 🧠 Key Insights & Findings

(You can modify based on your dataset output)

- Inflation peaked between _2020–2022_ due to supply chain disruptions and global events.
- _Food and Energy sectors_ showed the highest price volatility.
- _Post-2023_, inflation rates began stabilizing across most regions.
- Average inflation rate over the study period: _X%_
- The data reveals strong correlation between _fuel prices and CPI movements_.

---

## ⚙ How to Use / Reproduce

1. _Clone the repository_
   ```bash
   git clone https://github.com/R-ayush/Power-BI-Inflation-Analysis-Journeying-Through-Global-Economic-Terrain.git
   cd Power-BI-Inflation-Analysis-Journeying-Through-Global-Economic-Terrain
   ```
2. _Open the Power BI file_

- Launch Power BI Desktop
- Open Inflation_Analysis.pbix (or equivalent file)

3. _Connect/refresh data_

- Update file paths if needed
- Refresh data source to fetch the latest data

4. _Explore_

- Use interactive filters and slicers to explore the data
- Hover over charts for detailed tooltips and insights

## 🧾 Folder & File Structure

PowerBI_InflationAnalysis/
│
├── data/ # Raw and cleaned datasets
├── reports/ # Exported reports or visuals
├── screenshots/ # Dashboard preview images
├── Inflation_Analysis.pbix # Main Power BI project file
└── README.md # Project documentation

## 🧰 Technologies & Tools

- Power BI Desktop — Dashboard development
- Microsoft Excel / CSV — Data preparation
- DAX & Power Query — Data modeling and calculations
- Data Visualization Techniques — KPIs, charts, cards, maps
