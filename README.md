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

_Primary dataset (included in this repository):_

- `Project Executable Files/Dataset/global_inflation_data.csv`  
  Annual average inflation (consumer prices) by country, with one column per year from 1980–2024.

_Columns (simplified):_

- `country_name` – country or economy name  
- `indicator_name` – description of the metric  
- `1980` … `2024` – annual average inflation rate (%)

_If you use this data outside this project, please add the appropriate citation for the original provider (for example, official statistics portals, IMF, or World Bank)._ 

_Typical data preparation steps used for this report include:_

- Handling missing or inconsistent values
- Standardizing numeric and date formats
- Reshaping the data where needed for analysis
- Creating derived measures (such as averages, growth, and volatility) inside Power BI using DAX

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

### Project phases and repository mapping

- **Project Initialization and Planning Phase/** – problem statement, scope definition, and planning artefacts.
- **Data Collection and Preprocessing Phase/** – data discovery, collection, and cleaning/transformation artefacts.
- **Data Visualization/** – exploratory charts and visual experiments used before finalizing the report.
- **Dashboard/** – dashboard layout ideas and design references.
- **Report/** – `Report Design Template.pdf` describing the final report layout and design.
- **Project Executable Files/** – final Power BI report file and the dataset used by the model.
- **Project Documentation and Demonstration/** – `Project Documentation.pdf` and `Project Demonstration.mp4` with the final explanation and walkthrough.

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

   - Launch Power BI Desktop.
   - Open `Project Executable Files/PowerBIInflationAnalysis.pbix`.

3. _Check or update the data source path_

- Ensure the data source points to `Project Executable Files/Dataset/global_inflation_data.csv`.
- If you moved the project, go to **Transform data ▸ Data source settings** in Power BI and update the file path.
- Click **Refresh** to load the data.

4. _Explore the dashboard_

- Use interactive filters and slicers to explore the data.
- Hover over charts for detailed tooltips and insights.
- Switch between pages to view different perspectives (overview, trends, comparisons, etc.).

5. _If you don’t have Power BI Desktop_

- Open `Project Documentation and Demonstration/Project Documentation.pdf` for a static overview of the report.
- Play `Project Documentation and Demonstration/Project Demonstration.mp4` to watch a recorded walkthrough of the dashboard.

## 🧾 Folder & File Structure
```
Power-BI-Inflation-Analysis-Journeying-Through-Global-Economic-Terrain/
│
├── Project Initialization and Planning Phase/          # Problem statement, scope, and planning artefacts
├── Data Collection and Preprocessing Phase/           # Data collection, cleaning, and transformation artefacts
├── Data Visualization/                               # Exploratory visualizations and design experiments
├── Dashboard/                                        # Dashboard layout and design references
├── Report/
│   └── Report Design Template.pdf                    # Report layout and design reference
├── Project Executable Files/
│   ├── PowerBIInflationAnalysis.pbix                 # Main Power BI report file
│   └── Dataset/
│       └── global_inflation_data.csv                 # Historical annual average inflation by country (1980–2024)
├── Project Documentation and Demonstration/
│   ├── Project Documentation.pdf                     # Detailed project documentation
│   └── Project Demonstration.mp4                     # Video walkthrough of the dashboard
└── README.md                                         # Project overview and usage instructions
```

## 🧰 Technologies & Tools

- Power BI Desktop — Dashboard development
- Microsoft Excel / CSV — Data preparation
- DAX & Power Query — Data modeling and calculations
- Data Visualization Techniques — KPIs, charts, cards, maps

## Final Output

- `Project Executable Files/PowerBIInflationAnalysis.pbix` – interactive Power BI report.
- `Project Documentation and Demonstration/Project Documentation.pdf` – detailed written documentation.
- `Project Documentation and Demonstration/Project Demonstration.mp4` – recorded walkthrough of the dashboard.
