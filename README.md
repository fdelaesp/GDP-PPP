# GDP-PPP

I used ggplot2 for visualizations, and I customized the plots to show trends for both countries, including correlation coefficients. These plots illustrate key relationships between GDP growth and other economic factors, helping to identify patterns or significant shifts in the data.

File Structure
R Markdown File: This file contains all the code for the data fetching, processing, and analysis.
DebtSPNF.csv: This file is used for another part of the analysis, specifically focusing on external debt data.
Plots: I saved all the visualizations in the plots/ directory.
Key Functions
Here’s a brief overview of some of the custom functions I used in the analysis:

count_na: This function calculates the number of missing values for each indicator.
plot_gdp_vs_gcf_combined: This function plots the relationship between GDP per capita (PPP) and Gross Capital Formation (% of GDP) for Panama and Costa Rica.
plot_gdp_vs_poverty_combined: This function creates a similar plot but shows the relationship between GDP per capita (PPP) and Poverty Headcount Ratio.
Data Validation: I also made sure to validate the data by checking for syntactic validity of column names and ensuring that file paths are correct before proceeding with analysis.
