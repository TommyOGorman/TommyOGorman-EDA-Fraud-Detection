# TommyOGorman-EDA-Fraud-Detection
Exploratory Data Analysis of motor insurance fraud using R and Quarto.

This project explores a dataset of motor insurance claims to identify potential fraud indicators using Exploratory Data Analysis (EDA) techniques.

The goal is to uncover behavioural, demographic, cost-based, and geographic patterns associated with fraudulent claims, which can support future predictive modelling and operational fraud prevention strategies.

## Project Highlights

- **Data Cleaning**: Standardised formats and resolved inconsistencies to prepare the dataset for analysis.
- **Feature Engineering**: Created new variables such as `carpool`, `age_group`, `high_cost`, and one-hot encoded `routing_area` to reveal deeper fraud patterns.
- **Visual Analysis**: Developed targeted ggplot2 charts to examine fraud trends by cost, region, car occupancy, age group, and repeated names.
- **Pattern Detection**: Identified repeated individuals, geographic hotspots, and cost anomalies linked to potential organised fraud.

## Files Included

- `eda_fraud_report.qmd` – Quarto report with full code and analysis.
- `TommyOGorman_EDA_Fraud_Report.pdf` – Final rendered version of the report.
- `eda_fraud_script.R` – Standalone R script for key data preparation and plotting.
- `.png` visualisations – Exported plots included in the Quarto report for layout compatibility.
- `data.csv` – Input dataset (if shared).

## Key Insights

- Shared trips and multiple passengers strongly correlate with fraud.
- Fraud is concentrated in specific routing areas (e.g. THAMES, SHANNON).
- Most fraud claims come from drivers aged 25–65, with none reported for 65+.
- Repeated names across claims may indicate organised activity.

## Tools Used

- **R** with `tidyverse`, `ggplot2`, `skimr`, `recipes`, `corrplot`
- **Quarto** for report generation
- **RStudio**

## 👤 Author

Tommy O’Gorman  
MSc Business Analytics – TUS  
LinkedIn: https://www.linkedin.com/in/tommy-o-gorman-63909b124/
