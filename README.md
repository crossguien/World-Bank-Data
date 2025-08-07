# World Bank Data Overview

This project explores key economic indicators across countries between 2010 and 2025 using World Bank data. 
The aim is to evaluate economic health and investment potential across regions using a custom-built Investment Score.

### Code Description

Merged GDP Growth, Inflation, Unemployment, and Public Debt data from multiple CSV files.
Handled null values and normalized country names for consistent joins.

Created normalized values (0 to 1) for each economic indicator using Min-Max scaling.
Developed a composite Investment Score based on weighted averages:

40% GDP Growth

20% Inflation (inverted)

20% Unemployment (inverted)

20% Debt-to-GDP (inverted)

### Data Visualization

Built visual charts in Python showing economic indicator trends by country.
Tableau dashboards show Investment Scores by region and time trends of key indicators.

### Insights

Developing economies have high growth potential but often face challenges like inflation and high unemployment.
Mature economies show fiscal stability but lower growth rates.
The Investment Score helps rank countries on overall macroeconomic attractiveness for foreign investors.

### Tools Used

Python: pandas, numpy, matplotlib, seaborn
Tableau (for dashboard visualization)
SQL & Python (for raw data prep)

Tableau Dashboard Link: https://public.tableau.com/app/profile/cross.guien/viz/WorldBankData_17529602699510/Story1

World Bank Data Kaggle Link: https://www.kaggle.com/datasets/tanishksharma9905/global-economic-indicators-20102025
