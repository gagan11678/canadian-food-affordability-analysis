# The Hunger Games: An Analysis on Canadian Food Affordability

### Project Overview:

**"The Hunger Games"** is a comprehensive data analysis project that explores the intersection of food affordability, income inequality, population growth, and food insecurity across Canada. Using publicly available datasets from Statistics Canada, we evaluated how rising food prices, stagnant wages, and socio-economic policy decisions have impacted Canadian households from 2017–2024.

The project involved extensive data wrangling, regression analysis, visualization using Tableau, and the development of insights that highlight critical trends and disparities in food access.

### Key Questions Addressed:

What does a healthy diet cost in Canada in 2024?

How do food prices correlate with population growth?

Which income brackets are most affected by food inflation?

How much do households spend on food relative to their earnings?

Which provinces experience the highest rates of food insecurity?

### 📂 Datasets Used

All datasets were sourced from Statistics Canada, including:

Canadian Income Survey (CIS): 2017–2021

Monthly Average Retail Food Prices

Detailed Food Spending by Region and Province

Quarterly Population Estimates

### Data Wrangling Highlights

Consolidated 5 years of CIS data into a uniform schema using pandas

Merged CIS with food spending to create a holistic view of household economics

Standardized product units (per kg/L) for accurate food price comparisons

Categorized food items by type (meat, dairy, grains, etc.) for cost calculation

### Analysis Techniques

Linear regression to correlate population growth with food price index (R² = 0.92)

Comparative analysis of income brackets vs food spending

Provincial-level mapping of food insecurity rates and income levels

Cost modeling of vegetarian vs non-vegetarian diets per Canada Food Guide

### Tools & Technologies

Python (Pandas, NumPy) for data cleaning and processing

Tableau for data visualization and dashboards

Excel for intermediate preprocessing and exploratory analysis

GitHub for version control and documentation

### 📈 Key Insights

A healthy non-vegetarian diet costs ~$6,547/year; vegetarian costs ~$4,822/year

Lower-income Canadians spend up to 30% of income on food

Alberta showed the highest food insecurity rate in 2021 at 20.49%

Ontario and Quebec showed recent declines in average food prices

### Limitations

Latest CIS data available only till 2021
Food pricing dataset may not reflect regional variety and quality
Self-reported food insecurity data could contain inaccuracies

### Tasks Performed

Designed and executed the data pipeline: loading, cleaning, merging, and standardizing datasets from the Canadian Income Survey and other Statistics Canada sources
Created custom functions to categorize and standardize food product data
Led the implementation of regression models and affordability analyses
Developed Tableau visualizations and guided the storytelling direction
Wrote the full report, including introduction, insights, limitations, and conclusions

### Conclusion

This project underscores the growing challenges many Canadians face when it comes to food affordability. Through data storytelling, we shed light on systemic inequalities, regional disparities, and the urgency for policy reforms aimed at reducing food insecurity.

I hope this report serves as both an educational tool and a springboard for continued work in food policy, economics, and social justice in Canada.

