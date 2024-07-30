# Formula 1 Historical Data Analysis

## Overview
This project involves exploratory data analysis (EDA) on historical Formula 1 race data, focusing on understanding trends and patterns among teams, drivers, and race characteristics over the years. The dataset includes information on races, dates, winners, cars, laps, and times.

## Key Analyses

### 1. Cumulative Wins Over Time
- **Objective**: Track the progression of cumulative wins for teams and drivers.
- **Visualization**: Line plots show the accumulation of wins, highlighting periods of dominance.
  ![Cumulative Team Wins](charts/cum_teams.png)

  ![Cumulative Driver Wins](charts/cum_drivers.png)
- **Insights**: The data reveals dominant eras for teams like Ferrari in the early 2000s and drivers like Lewis Hamilton in recent years.

### 2. Dominance Periods
- **Objective**: Identify specific periods when teams or drivers were dominant.
- **Visualization**: Time dependent bar plot shows dominant eras for teams and drivers
  ![Dominant Teams](charts/dom_teams.png)
  ![Dominant Drivers](charts/dom_drivers.png)
- **Results**: Notable periods include Ferrari's dominance from 1994 to 2013 and Lewis Hamilton's peak from 2007 to 2021.

### 3. Race Characteristics: Lap Times and Evolution
- **Objective**: Examine the evolution of average lap times in races.
- **Visualization**: Time series of the average lap time over each year shows the trend of speed in the sport
  ![Speed](charts/lap_avg.png)
- **Findings**:
  - A running average of lap times shows improvements in race speeds over time, influenced by technological advancements and changes in regulations.
  - However, lap times in the 1960s became slower due to regulatory changes, including reduced engine capacities and an increased focus on safety.

## Conclusion
The EDA provides a comprehensive overview of historical trends in Formula 1, highlighting key factors that influenced the sport, such as technological advancements, regulatory changes, and team strategies. The analysis also underscores the importance of safety improvements and their impact on race dynamics.

## Future Work
- **Deep Dive into Specific Eras**: More detailed analysis of specific periods or drivers.
- **Comparison of Team Strategies**: Analyzing pit stop strategies, tyre choices, and other tactical decisions.
- **Impact of Technological Changes**: Study how specific technological innovations impacted race outcomes.

## Acknowledgments
This analysis was made possible by the rich historical data available for Formula 1. Special thanks to the contributors who have preserved and shared this data.
