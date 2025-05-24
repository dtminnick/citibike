# Citibike Ride-Share Data Analysis
This repository contains a complete analysis pipeline for exploring and visualizing New York City's Citibike ride-share data. The project focuses on identifying trends, usage patterns, and rider behaviors through data preparation, aggregation, and visualization using R.

# Objectives
- Clean and prepare raw Citibike trip data.
- Conduct exploratory analysis to understand usage trends by time, location, and user type.
- Visualize key patterns using base R and `ggplot2`.
- Demonstrate efficient and reproducible workflows using tidyverse tools.

# Data Source
The Citibike trip data used in this analysis was sourced from NYC's publicly available [Citibike data system](https://ride.citibikenyc.com/system-data).

# Tools & Libraries
- `dplyr` – data manipulation
- `lubridate` – date-time parsing and handling
- `ggplot2` – data visualization
- `readr` – efficient data import

# Key Steps in the Analysis
1. **Data Import & Cleaning**  
   Loaded raw trip data and cleaned it to remove inconsistencies, missing values, and outliers.

2. **Feature Engineering**  
   Extracted date-time components such as weekday, hour, and trip duration to enable deeper temporal analysis.

3. **Exploratory Analysis**  
   - Trips by user type (Subscriber vs. Customer)
   - Temporal trends (hourly, daily, monthly patterns)
   - Start and end station frequency
   - Average trip duration by rider type

4. **Visualization**  
   Created clear and informative plots to communicate patterns in the data.
   
# Example Visualizations
- **Hourly Ride Volume by Rider Type**
- **Most Popular Start Stations**
- **Trip Duration Distribution**
- **Rides by Day of Week**

# Results Summary
This analysis reveals distinct usage patterns between subscribers and casual customers. Subscribers tend to use Citibike for commuting during weekday peak hours, while customers are more active during weekends and midday hours, often for leisure. Certain stations and neighborhoods consistently show higher traffic, underscoring key service areas.

# Future Work
- Incorporate weather and event data for predictive modeling.
- Build an interactive Shiny dashboard.
- Perform clustering on station usage to identify hub patterns.
