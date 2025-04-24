
# Healthcare Data Analysis and Visualization – Kyrgyz Republic (2009–2023)

## Overview

This project presents a data-driven exploration of healthcare trends in the Kyrgyz Republic from 2009 to 2023. Through comprehensive data analysis and interactive visualizations, we aim to shed light on regional disparities in disease burden, healthcare infrastructure, and workforce distribution. The findings are intended to support informed decision-making by policymakers and stakeholders in the healthcare sector.

## Objectives

- Analyze regional differences in the incidence of key diseases, including Tuberculosis, Hepatitis, Diabetes, and Acute Intestinal Infections.
- Evaluate healthcare infrastructure indicators such as the number of hospital beds and healthcare professionals.
- Explore correlations between healthcare resources and disease outcomes.
- Provide actionable, data-informed recommendations to improve health services across all regions.

## Data Sources

- Official datasets from:
  - [data.gov.kg](https://data.gov.kg/)
  - [stat.gov.kg](https://stat.gov.kg/)
- Aggregated from `med_data.xlsx` and multiple sheets in `data_lists.xlsx`.

## Timeframe

- Data spans from 2009 to 2023, focusing on regional data (excluding national-level aggregates).

## Methodology

### Data Preparation

- Standardized column naming
- Missing value handling
- Filtering to exclude national totals and highlight regional insights

### Analysis Techniques

- **Descriptive Statistics**: Summary metrics including means, medians, and distributions
- **Correlation Analysis**: Assessed relationships between healthcare infrastructure and disease prevalence
- **Trend Analysis**: Evaluated changes in disease burden and resource distribution over time

### Visualization Tools

- Python (Pandas, Matplotlib, Seaborn)
- Plotly for interactive and animated visualizations
- Jupyter Notebook for integration of narrative and code

## Key Visualizations

- Animated bar charts of disease spread across years and regions
- Heatmaps showing correlation matrices
- Scatter plots of resources vs. disease cases
- Histograms and box plots for disease distributions by region
- Pie charts for disease share per year

## Major Findings

- **Healthcare Capacity vs. Population Growth**: Healthcare infrastructure has not kept pace with population increases.
- **Regional Disparities**: Certain regions exhibit significantly higher disease burdens due to sanitation, infrastructure, or reporting inconsistencies.
- **Inconsistent Resource Impact**: More specialists do not always correlate with lower disease incidence, highlighting deeper systemic issues.
- **Fluctuating Disease Trends**: Periodic spikes suggest outbreaks or changes in reporting accuracy.

## Recommendations

1. **Expand Infrastructure**: Increase investment in facilities and staff, especially in underserved regions.
2. **Targeted Public Health Interventions**: Prioritize disease-prone areas with education, vaccination, and sanitation efforts.
3. **Enhanced Surveillance**: Implement robust data systems for real-time health monitoring and rapid response.
4. **Multifaceted Policy Approaches**: Combine medical resource expansion with preventive and educational strategies.

## Team

- **Nurali Bakytbek uulu**: Data Collection, Cleaning, Visualization
- **Bektur Momunov**: Visualization, Presentation
- **Magomed Mukhammedov**: Analysis, Reporting

## Advisor

- **Dr. Remudin Mekuria**

## Repository Contents

- `data_analysis_visualiztion_project_.ipynb`: Complete notebook with analysis and visualizations
- `Data_Analysis_Report.pdf`: Full written report with detailed methodology and findings
- `Analysis of Healthcare Trends.pdf`: Summary presentation for stakeholders
