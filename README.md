# Chicago Building Permit Analysis

## Overview
This project explores building permit activity across Chicago using Python and pandas. The analysis examines permit types, construction activity by geographic area, yearly and monthly trends, review categories, reported project costs, and cost outliers.

The project uses Chicago building permit records dating from 2006 through February 2026.

## Tools & Technologies
- Python
- pandas
- Matplotlib
- Jupyter Notebook

## Analysis
The notebook explores several aspects of Chicago's building permit data:

- **Permit Types:** Identified the five most frequently issued permit types.
- **Yearly Trends:** Compared permit activity in 2020 and 2026, accounting for the fact that 2026 data only extended through February.
- **Geographic Patterns:** Identified wards and community areas with the highest permit activity.
- **Monthly Trends:** Compared renovation and alteration permits by month in 2025 and 2026.
- **Permit Status:** Examined approved, pending, and under-review references in 2025 work descriptions.
- **Reported Costs:** Compared median and mean reported project costs across review types.
- **Combined Categories:** Identified the most frequent combinations of community area, review type, and permit type.
- **Outlier Detection:** Used the interquartile range (IQR) method to identify unusually high or low reported project costs within community areas.

## Key Findings
- Express permits were the most common permit type.
- Chicago's 42nd Ward had the highest permit activity in the dataset.
- The Loop (Community Area 32) had the highest number of permits among Chicago's community areas.
- April had the highest number of renovation/alteration permits in 2025.
- Direct Developer Services had the highest median reported project cost among the review types examined.
- The Loop's most frequent combination of community area, review type, and permit type was an express permit.
- The IQR analysis identified unusually high reported costs, including several extreme values that may warrant further investigation.

## Files
- `project3JT.ipynb` — Jupyter Notebook containing the analysis, code, outputs, and visualizations.

## Skills Demonstrated
Data cleaning and preprocessing, datetime conversion, filtering, grouping and aggregation, exploratory data analysis, statistical outlier detection, and data visualization.

## Notes
This project was completed as part of coursework and received a score of 100%. The 2026 permit data was only available through February at the time of analysis, so comparisons with complete years should be interpreted with that limitation in mind. Reported-cost outliers may reflect unusual records or data-quality issues and should not automatically be interpreted as actual project costs.
