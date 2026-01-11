# A/B Test Analysis

This project performs an A/B test analysis to compare user behavior between control and test groups.

## Dataset
The dataset contains the following columns:
- `id` — user identifier
- `group` — experiment group (control or test)
- `segment` — user segment
- `events` — number of events (orders)

## Analysis Steps
- Exploratory data analysis (EDA)
- Visualization of distributions (histograms, box plots)
- Normality check using Shapiro–Wilk test
- Selection of appropriate statistical test
- Mann–Whitney U test for group comparison
- Interpretation of results

## Tools and Libraries
- Python
- pandas
- scipy
- matplotlib

## Conclusion
The analysis revealed a statistically significant difference between the control and test groups, indicating that the tested changes had an impact on user behavior.
