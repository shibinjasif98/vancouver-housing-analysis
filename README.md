# Vancouver Housing Affordability Analysis

## Project Overview
This project analyzes housing affordability in Vancouver by comparing average rental prices with median income over time.  
The goal is to understand whether rent growth has outpaced income growth and to quantify affordability pressure using the rent-to-income ratio.

The analysis focuses on Vancouver Census Metropolitan Area (CMA) from 2019 to 2023.

---

## Key Questions Answered
- Is housing affordable relative to income in Vancouver?
- How has housing affordability changed over time?
- Is rent growth or income growth driving affordability issues?
- When did affordability deterioration accelerate most?

---

## Key Insights
- Vancouver renters have exceeded the commonly recommended **30% affordability threshold** throughout the entire period.
- Affordability briefly improved during 2020 but deteriorated sharply after 2021.
- Rental prices increased significantly faster than median income, driving sustained affordability stress.
- By 2023, rent-to-income ratios approached **60%**, indicating severe affordability pressure.

---

## Data Sources
- **Statistics Canada**
  - Average rental prices (quarterly)
  - Median income (annual)

All data was cleaned, transformed, and aligned into a quarterly time series before analysis.

---

## Methodology
1. Cleaned and merged rent and income datasets using Python.
2. Converted income data to monthly values for comparability.
3. Calculated rent-to-income ratio as a key affordability metric.
4. Built a Power BI dashboard to visualize trends and drivers.
5. Applied a 30% affordability benchmark for interpretation.

---

## Dashboard Overview
The Power BI dashboard includes:
- Rent-to-Income Ratio trend with affordability threshold
- Average quarterly rent trend
- Median income trend
- Contextual assumptions and limitations

The dashboard provides an executive-level overview of housing affordability dynamics in Vancouver.

---

## Assumptions & Limitations
- Median income is assumed constant within each year due to annual reporting.
- Rental prices represent market averages across unit types in Vancouver CMA.
- Utility costs, taxes, and household size are not included.
- Analysis is limited to 2019–2023 due to data availability.
- The 30% affordability threshold is used as a general guideline, not a strict rule.

---

## Tools & Skills Demonstrated
- Python (Pandas, data cleaning, transformations)
- Power BI (DAX measures, dashboard design, storytelling)
- Git & GitHub (version control, project structuring)
- Data analysis & visualization
- Business-oriented insight communication

---

## Project Structure
Vancouver_housing_analysis/
│
├── data/
│ ├── raw/
│ └── processed/
│
├── notebooks/
│ └── 04_affordability_analysis.ipynb
│
├── dashboards/
│ └── housing_affordability_vancouver.pbix
│
└── README.md