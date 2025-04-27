# ✈️ Flight Data Analysis and Visualization

## Overview
In this project, I performed an exploratory data analysis (EDA) on a large U.S. domestic flights dataset.  
The goal was to clean the data, uncover trends, and visualize key insights about flight delays, airline performance, airport traffic, and flight patterns.

## Process
- **Data Cleaning**:
  - Handled missing values (e.g., replaced missing delay values with 0, dropped rows missing both arrival and departure times).
  - Dropped irrelevant or poorly documented columns.
  - Filtered out airports without proper IATA codes.

- **Exploratory Analysis**:
  - Analyzed arrival and departure delays.
  - Studied flight counts by month, day of week, and hour of the day.
  - Compared airlines based on flight counts and delay performance.
  - Examined relationships between flight distance and delays.
  - Investigated airport traffic through heatmaps using Folium.

- **Visualizations**:
  - Histograms of delays.
  - Bar charts of monthly and daily flight counts.
  - Scatter plots of airport activity vs. average delays.
  - Heatmaps showing flight traffic density across the U.S.

## Key Findings
- Flights rarely depart early but often arrive earlier than scheduled.
- Departure delays are highest during late-night hours (11 PM – 4 AM), possibly due to staffing or operational challenges.
- Flight volumes are stable across months, but weekends (especially Saturdays) see fewer flights.
- Southwest Airlines (WN) dominates domestic traffic with relatively low delays, while Spirit (NK) and Frontier (F9) perform poorly.
- No strong relationship between flight distance and delay.
- Major hubs like Los Angeles see significant traffic, and flight patterns suggest most trips are round-trips.

## Conclusion
Flight delays seem to be more influenced by operational factors and time of day rather than distance or seasonality.  
While major airports handle high traffic relatively well, late-night operations show room for improvement.  
Overall, this analysis gives a strong foundation for understanding U.S. domestic flight behavior.
