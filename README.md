# Road_Accident_Data_Analysis_Using_PowerBI_SQL
# 🚗 Road Accident Analysis

## 📌 Project Overview
This project aims to analyze road accident data to uncover key factors contributing to accidents, identify patterns, and propose data-driven recommendations for safety improvements. The analysis utilizes statistical methods, SQL, Power BI, and visual dashboards for deep and interactive business insights.

---

## ⚙️ How It Works
- **Data Collection:** Uses public and/or government datasets containing accident records—vehicle type, time, location, cause, and severity.
- **Data Cleaning:** Cleans missing values, removes duplicates, and corrects inconsistencies using SQL and Python (pandas).
- **Exploratory Analysis:** Performs univariate and multivariate statistical explorations to spot trends and distributions.
- **Visualization:** Power BI dashboard for interactive filtering by accident type, regions, vehicle classes, and time periods.
- **Insight Extraction:** SQL queries and custom measures expose accident hotspots, common causes, recurrent time slots, and severity breakdowns.

---

## 🚧 Problems Faced
- **Incomplete Data:** Datasets had missing entries for critical variables like location or vehicle type.
- **Multiple Formats:** Data from different sources required heavy wrangling and standardization.
- **High Cardinality:** Many fields (cities, accident types) caused complexity in grouping and analysis.
- **Outlier Detection:** Found extreme values in accident severity skewing averages.

---

## 🛠️ How These Problems Were Overcome
- Filled missing values using median/mode imputation and explicit tagging.
- Created robust data pipelines to unify formats, dates, and categories.
- Used clustering and aggregation methods in SQL to handle large numbers of distinct values.
- Applied statistical outlier removal (IQR filtering, z-scores) to clean result sets.

---

## 💡 Insights & Findings
- **Accident Hotspots:** Found regions and times with highest accident concentration—urban intersections during evening rush hour.
- **Vehicle Impact:** Two-wheelers and heavy vehicles most prone to severe accidents.
- **Seasonal Patterns:** Accident frequency peaks during monsoon months, indicating weather impact.
- **Major Causes:** Over-speeding and distracted driving top contributors to fatal crashes.
- **Policy Recommendations:** Data supports targeted interventions—speed checks in hotspots, awareness for youth riders, and improved signage.

---

## 🌟 Uniqueness of the Project
- Integrates *multiple data sources* and formats into a single unified insight engine.
- Offers a *dynamic Power BI dashboard* with real-time filtering and region drill-down—rare among GitHub datasets.
- Applies *advanced statistical and machine learning methods* to accident analysis, distinguishing it from simple BI projects.
- Presents actionable recommendations backed by granular, locality-level accident patterns.

---

## 📂 Files
- `road_accident_analysis.pbix`: Power BI Interactive Dashboard
- `road_accident_data.csv` & cleaned datasets: Source and processed data
- `Road_Accident_Analysis_SQL.sql`: Core insight-driving SQL scripts
- `/img/`: Custom icons and background images for dashboard visuals
- `README.md`: Project documentation

---

## 📝 How to Run
1. Clone the repo and download all files.
2. Open dataset (CSV or SQL dump) in local database.
3. Launch Power BI and import `road_accident_analysis.pbix` for visualization.
4. Optional: Use Jupyter/Python scripts for custom analysis.

---

## 🙏 Acknowledgements
- Road accident data from [relevant authority or source].
- Libraries: pandas, SQL, Power BI, matplotlib, seaborn.
- Contributors: [Your Name], [Collaborators].
- ## Preview
![Dashboard](https://github.com/touhiduzzaman-tuhin/Road_Accident_Data_Analysis_Using_PowerBI_SQL/assets/67516167/2010a281-141d-4866-87aa-152efd94ccac)

