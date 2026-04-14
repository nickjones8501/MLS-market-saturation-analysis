# MLS-market-saturation-analysis
A Python-based data analysis exploring the relationship between MLS stadium capacities and city populations to identify market saturation and underserved regions.

# MLS Stadium Capacity vs. City Population Analysis

## Project Overview
This project analyzes Major League Soccer (MLS) teams to determine which franchises have the highest and lowest stadium capacity relative to their city's population. This metric (seats per 100k residents) helps identify which markets might be underserved or where stadium size is disproportionately large for the local population.

## Key Insights
* [cite_start]**Top Market Saturation:** The New York Red Bulls lead the league in seats per 100,000 residents (~171,432), largely due to playing in Harrison, NJ, which has a small local population compared to the stadium size[cite: 51].
* [cite_start]**Underserved Markets:** Large metro areas like Los Angeles (LAFC) and Chicago (Chicago Fire FC) have the lowest seats per 100k residents (under 1,000), suggesting high demand relative to available supply[cite: 54].

## Data Sources
- [cite_start]`mls.csv`: Contains team names, stadium names, and capacities[cite: 17].
- [cite_start]`mls_city_population_estimates.csv`: Contains 2024 population estimates for the respective cities[cite: 19].

## Tools Used
- [cite_start]**Python (Pandas/NumPy):** For data cleaning and merging datasets[cite: 2, 3, 25].
- [cite_start]**Seaborn/Matplotlib:** For creating the final comparative visualization[cite: 4, 5, 59].
