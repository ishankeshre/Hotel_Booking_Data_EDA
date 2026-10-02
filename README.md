
# Hotel Harmony – Booking Data EDA

## Overview
This project explores hotel booking data to understand booking patterns, cancellations, guest behavior, room preferences, and pricing trends across City Hotels and Resort Hotels. The analysis uses Python to identify patterns that can support better operational and revenue management decisions.

## Requirements
- Python 3.x
- Jupyter Notebook

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Preparation
- Started with 119,390 booking records and 32 columns.
- Replaced placeholder NULL values in agent and company fields.
- Filled missing children values with zero.
- Converted reservation status dates into datetime format.
- Removed duplicate records, resulting in 87,396 rows.

## Analysis
The analysis focused on:
- Booking distribution by hotel type.
- Cancellation rates and seasonal patterns.
- Lead time and its relationship with cancellations.
- Average Daily Rate (ADR) by hotel type and market segment.
- Guest countries and distribution channels.
- Stay duration for repeat and new guests.
- Room type preferences.
- Special requests, parking requirements, and booking changes.
- ADR trends across years and arrival months.

## Key Insights
- The cleaned dataset contains 87,396 bookings.
- A total of 24,025 bookings were canceled, representing approximately 27.5% of the dataset.
- Average booking lead time is approximately 79.89 days.
- August is the most common arrival month.
- Portugal (PRT) is the most frequently recorded guest country.
- City Hotels have an average ADR of 110.99, compared with 99.03 for Resort Hotels.
- Cancellation rates are approximately 30.0% for City Hotels and 23.5% for Resort Hotels.
- August has the highest total ADR among arrival months in this analysis.

## Challenges
- Handling placeholder NULL values and duplicate records.
- Comparing booking behavior across different hotel types and market segments.
- Understanding seasonal patterns in cancellations and pricing.
- Interpreting relationships between variables without assuming causation.

## Recommendations
- Review cancellation patterns by lead time, hotel type, and season when planning booking policies.
- Consider hotel-specific ADR trends when evaluating pricing strategies.
- Use seasonal booking patterns to support staffing and resource planning.
- Further investigate cancellation drivers using statistical models and validated analysis.

## Conclusion
This project demonstrates how exploratory data analysis can reveal meaningful patterns in hotel bookings, cancellations, seasonality, and pricing. The findings provide a foundation for deeper analysis of customer behavior and revenue management.
