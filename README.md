# Aviation Risk Analysis Project

## Project Overview

This project aims to analyze aviation risk factors to identify which aircraft are the lowest risk for operation. The analysis investigates trends in aviation accidents, evaluates risk factors related to different aircraft models, and provides actionable recommendations for business stakeholders. The audience for this analysis includes business stakeholders who are non-technical and are involved in decision-making related to aircraft procurement.

### Key Goals:
- Identify trends in aviation accidents over time.
- Analyze risk factors related to different aircraft models.
- Provide actionable recommendations for stakeholders to minimize risks.

## Data Understanding

The dataset used in this analysis includes detailed information on aviation accidents, such as:
- Accident identifiers
- Aircraft make and model
- Weather conditions
- Injury severity and total fatalities
- Aircraft damage categories
- Phases of flight during accidents

The dataset contains 88,889 entries with 31 columns. It includes essential details about each accident, including accident date, location, and severity.

### Data Cleaning:
- Dropped columns with over 30% missing values.
- Imputed missing numeric values with the median and categorical values with the mode.

After cleaning, the dataset contains 22 columns, with no missing values in the relevant columns.

## Data Preparation

To make the data suitable for analysis, a subset of the dataset was selected that focuses on key variables such as aircraft make, model, injury counts, and accident severity. A smaller summary dataset was created for use with Tableau, focusing on manufacturers and accident statistics.

## Data Analysis

### 1. Aviation Accidents Over Time
A time series plot of aviation accidents over the years reveals trends and patterns in accident frequency.

![Aviation Accidents Over Time](path_to_graph)

### 2. Top 10 Aircraft Manufacturers Involved in Accidents
A bar chart of the top 10 aircraft manufacturers by the number of accidents shows which manufacturers have had the most incidents. The Cessna aircraft had the highest number of reported accidents, while Boeing and Mooner showed relatively lower accident rates.

![Top 10 Manufacturers](path_to_graph)

### 3. Aircraft Damage Proportions
A pie chart visualizes the proportion of aircraft damage types, showing the severity of damage in reported accidents.

![Aircraft Damage Proportions](path_to_graph)

### 4. Correlation Between Injury Types
A heatmap was generated to show the correlation between different injury types (fatal, serious, minor, and uninjured), helping identify patterns in injury severity.

![Injury Correlation Heatmap](path_to_graph)

## Key Insights

- **Aircraft with high fatality rates** should be avoided, especially in both private and commercial aviation.
- **Safety for landing and takeoff**: A significant proportion of accidents happen during these phases. Therefore, aircraft models with advanced technologies for these phases should be prioritized.
- **Manufacturers with lower accident rates**: Aircraft from manufacturers like Boeing and Mooner show better safety records, and thus, are recommended for procurement.

## Recommendations

- **Avoid high-risk aircraft**: Focus on aircraft with consistently lower fatality rates.
- **Prioritize aircraft from safer manufacturers**: Focus on Boeing and Mooner, which have shown fewer accidents in the dataset.
- **Invest in landing and takeoff technologies**: Aircraft with advanced braking and stability systems should be prioritized to improve safety during critical flight phases.

## Conclusion

This analysis provides valuable insights into aviation risks and helps stakeholders make informed decisions regarding aircraft acquisition and safety measures. By focusing on lower-risk aircraft and investing in safety technologies, the company can significantly reduce operational risks in aviation.

https://public.tableau.com/app/profile/eric.miriti/viz/EricMuthomi/Dashboard2
---

## Files in the Repository
- `AviationData.csv`: The original dataset of aviation accidents.
- `aviation_risk_analysis.ipynb`: The Jupyter notebook containing the analysis.
- `presentation.pdf`: A PDF of the presentation summarizing the results and insights.
- `tableau_summary_data.csv`: A smaller summary dataset for use in Tableau.

