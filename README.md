# Automotive Dealer Network Performance Analysis: Python and Tableau
This project simulates a dealership performance analytics workflow inspired by regional OEM operations in the automotive industry. Using a synthesized dataset of 200+ dealers over 12 months, I built a complete analytics pipeline to uncover operational efficiency, customer satisfaction drivers, and revenue trends across service and parts operations.

## The final dashboard:

![dashboard](https://github.com/digitoby/Automotive-Dealer-Network-Performance-Analysis/blob/main/photos/Dashboard%201.png)

## Workflow
### Python (Pandas, NumPy, Matplotlib, Seaborn):
Generated a synthetic dataset simulating 200+ dealers over 12 months, including service and parts revenue, CSI, retention, and warranty claims. Performed data cleaning, preprocessing, and feature engineering to ensure realistic distributions. Conducted exploratory data analysis to identify trends, correlations, and performance patterns across dealers and regions.

### KPI Composite Modeling:
Developed a composite KPI scoring framework incorporating service revenue, parts sales, CSI, and claim rates to benchmark dealers. This scoring system highlights patterns in dealer execution, warranty exposure, customer loyalty, and program effectiveness.

### Data Visualization (Tableau):
Created an interactive dashboard featuring top/bottom dealer rankings, revenue vs. CSI scatterplots, regional performace, and regional warranty claim heatmaps. Enabled clear, actionable insights for improving dealer performance and customer experience.

## Key Insights
- Regional
  - South region showed the best CSI scores and retention rates, but the lowest service revenue.
  - Northeast region showed the best service revenue but the lowest average CSI scores and retention rates.
- Customer Experience and Revenue Performance
  - CSI scores tend to stay consistent throughout the year while parts revenue seems to fluctuate based on season. 1st/2nd quarter shows better parts revenue with 3rd/4th quarter being the worst. I would suggest investigating part durability during winter seasons but also adjust manufacturing to meet seasonal demands.
  - Higher CSI score seams to have a decent correlation with lower service revenue. This would make sense since less need to get servicing means a better performing vehicle, thus higher customer satisfaction.
- Dealer Network Performance Insights
  - Dashboard shows top and bottom performing dealerships, suggesting possible weak spots to cut losses (or improve on) and hot spots to prioritize. Midwest shows most warranty claims during Q3/Q4 exposing potential durability issues specific to this region.

## Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
