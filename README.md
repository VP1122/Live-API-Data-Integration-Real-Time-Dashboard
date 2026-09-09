# World Indicators Analysis — Power BI Dashboard

## Overview
This Power BI project provides an interactive analysis of global development indicators, covering health spending, GDP growth, internet penetration, trade, poverty reduction, and other socioeconomic metrics across countries and regions. The dashboard enables users to explore relationships between indicators, compare regions, and identify top/bottom performing countries over time.

## Dashboard Preview

**Page 1: World Indicators Analysis**
<img width="608" height="399" alt="dashboard-preview" src="https://github.com/user-attachments/assets/464bcfde-157f-469e-a988-eccd4df1e51c" />

![World Indicators Analysis Dashboard](images/dashboard-preview.png)

The main dashboard page includes the following components:

### Key Metric Cards (Left Panel)
- **Average GDP per Capita** — 18.23K
- **Average Trade Value** — 988.60bn
- **Average Spending on Health (% of GDP)** — 6.70
- **Average GDP Growth (%)** — 2.78
- **% of Land Area under Forest** — 31.48

### Filters
- **Region slicer** — Dropdown filter to view data for a specific region or all regions combined.

### Visuals

| Visual | Description |
|---|---|
| **Average Spending on Health (% of GDP)** | Bar chart comparing average health expenditure across regions (Sub-Saharan Africa, East Asia & Pacific, South Asia, Middle East & North Africa, Latin America, North America, Europe & Central Asia). |
| **Average of Indicator Over Time** | Multi-line time series (2020–2025) tracking indicators such as Forest area, GDP growth, Individuals using the Internet, Mobile cellular subscriptions, Renewable energy consumption, and Unemployment. |
| **Effect of Internet Penetration on Immunization** | Scatter/line chart with a year slider (2016–2025) exploring the relationship between internet penetration and child immunization rates. |
| **Internet Penetration vs Unemployment** | Scatter plot with a year slider (2016–2025) examining correlation between internet usage and unemployment rates. |
| **Relationship Between Various Health Indicators** | Correlation heatmap/matrix visualizing relationships among multiple health-related indicators. |
| **Relationship Between Expenditure and Life Expectancy** | Correlation heatmap/matrix visualizing the relationship between health expenditure and life expectancy. |

### Tables
- **Bottom 10 Countries by Poverty Reduction** — Ranked table listing countries with the least poverty reduction progress (e.g., Malaysia, Russian Federation, Dominican Republic, Jamaica).
- **Top 10 Countries by Poverty Reduction** — Ranked table listing countries with the greatest poverty reduction progress (e.g., Argentina, Czechia, Kazakhstan, Moldova).

## Features
- Interactive **region filtering** applied across all visuals.
- **Time-based sliders** (2016–2025) for trend and relationship exploration.
- **Correlation matrices** to identify strength of relationships between health and economic indicators.
- **KPI cards** summarizing global averages at a glance.
- **Ranked tables** to highlight best and worst performing countries by poverty reduction.

## Data
The dashboard is built on a world development indicators dataset containing metrics such as:
- GDP per capita and GDP growth (%)
- Health expenditure (% of GDP)
- Trade value
- Forest area (% of land area)
- Internet usage and mobile subscriptions
- Renewable energy consumption
- Unemployment rate
- Poverty reduction by country
- Life expectancy and other health indicators

> Note: Update this section with the actual data source(s), file names, and refresh schedule used in your `.pbix` file.

## How to Use
1. Open the `.pbix` file in **Power BI Desktop**.
2. Use the **region** slicer at the top-left to filter the entire report by a specific region or view all regions.
3. Adjust the **year sliders** on the scatter/relationship visuals to explore how indicator relationships evolve over time.
4. Hover over chart elements for tooltips with exact values.
5. Refer to the top and bottom 10 tables to identify countries of interest, then cross-filter other visuals by selecting a country (if cross-filtering is enabled).

## Requirements
- Power BI Desktop (latest version recommended)
- Access to the underlying dataset (CSV/Excel/database source, as configured in Power Query)

## Project Structure
```
├── World_Indicators_Analysis.pbix   # Main Power BI report file
├── data/                            # (optional) Source data files
└── README.md                        # Project documentation
```

## Author / Maintainer
_Add your name, team, or organization here._

## License
_Add license information here, if applicable._
