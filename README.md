# Worst-Performing-NYC-Subway-Lines-in-2023-Through-Comprehensive-EDA

# Project Overview
This project conducts a comprehensive Exploratory Data Analysis (EDA) of New York City's subway system performance in 2023. The aim is to identify the worst-performing subway lines by analyzing data related to:
- Customer Journey Metrics: Extra platform and train time.
- Train Delays: Number, categories and subcategories of delays.
- Major Incidents: Large-scale disruptions affecting 50+ trains.
Through this analysis, I provide insights that can help improve transit efficiency and give riders a better understanding of the system's challenges.

## Project Overview
The NYC subway system serves millions of passengers daily, but it also faces significant operational challenges. This project examines ridership patterns, delays, incidents, and other performance metrics across different subway lines to determine the worst-performing lines in 2023.

## Datasets
The analysis is based on three publicly available datasets from [data.ny.gov](https://data.ny.gov):
- **MTA Subway Major Incidents**: Tracking major incidents that delay 50+ trains.
- **MTA Subway Trains Delayed**: Recording delays and their causes.
- **MTA Subway Customer Journey-Focused Metrics**: Tracking ridership, additional platform time (APT), additional train time (ATT), etc.

## Methodology
1. **Data Cleaning and Preparation**: Loaded datasets, cleaned data by removing unnecessary columns, and merged them to facilitate comprehensive analysis.
2. **Normalization**: Adjusted delay and incident counts per 1,000 passengers to compare performance across different subway lines fairly.
3. **EDA**: Explored various metrics to understand delay and incidents patterns, additional platform and train times, and performance across different subway lines.
4. **Visualization**: Developed custom plotting functions to visualize data and better communicate trends and findings.

## Key Insights
1. **Seasonal Variations and Ridership Patterns**: 
   - Peak ridership occurred in October (147M passengers), while the highest delays and incidents occurred in December (36681 delays and 56 incidents).
   - Factors such as weather, holidays, and operational stress contributed to delays more than passenger volume.

2. **Subway Lines Performance**:
   - The busiest lines (6, 1, 7, F) didn’t have the worst delay rates. Lines like the N Line exhibited high delays despite moderate ridership.
   - Shuttle lines (S 42nd, S Fkln) performed well due to simpler operations, but S Rock stood out with the highest delays per 1,000 passengers (3.43).

3. **Delays and Incidents**:
   - The N Line had the most delays and incidents, while lines like the E and 2 showed high incidents with fewer delays, proving that delays and incidents don’t always correlate directly.

4. **Operational Metrics**:
   - **APT**: The B (1.73 min), M (1.72 min), and C (1.66 min) Lines had the highest platform wait times.
   - **ATT**: The A (0.82 min), B (0.79 min), and D (0.79 min) Lines experienced the longest onboard delays.
   - Over 20% of passengers on the D, B, and Q Lines experienced significant delays.

5. **Top Categories of Delays**:
   - **Infrastructure & Equipment** (31%) was the top delay cause, peaking in September.
   - **Police & Medical** delays (26.1%) peaked in December, likely due to holiday-related issues.
   - **Planned Right of Way (ROW) Work** (25.2%) saw a spike in November.

6. **Worst-Performing Lines**:
   - **D, N, A, B, and E** Lines were the bottom five in 2023.
   - The D and N Lines experienced significant operational inefficiencies, scoring two points lower than the third worst line - a considerable difference that highlights just how poorly these lines performed in comparison to the rest.

## Recommendations
1. **Prepare for Seasonal Disruptions**: Increase staffing, adjust schedules, and improve communication during high-disruption periods.
2. **Enhance Operational Efficiency**: Conduct operational reviews and apply best practices from high-performing lines.
3. **Improve Incident and Delay Management**: Customize response strategies for each line and invest in security, maintenance, and infrastructure to reduce incidents and delays.
4. **Optimize Schedules and Increase Train Frequency**: Increase train frequency and adjust schedules to reduce APT and ATT on lines like B, M, and C.
5. **Invest in Infrastructure and Maintenance**: Prioritize upgrades in infrastructure and equipment to address the largest contributor to delays and better coordinate ROW work.
6. **Enhance Security and Emergency Response**: Increase police presence and improve emergency protocols to handle incidents more effectively.
7. **Promote Public Awareness and Safety**: Launch safety campaigns to educate passengers on emergency protocols and prevent unauthorized track access by installing platform barriers.
8. **Enhance Communication with Passengers**: Provide clear and timely updates on delays, service changes, and wait times through multiple channels. Listen to feedback.
9. **Leverage Data for Informed Decision-Making**: Use data analytics to continuously monitor performance, identify trends, and allocate resources more effectively.
10. **Focus on Worst-Performing Lines**: Implement comprehensive improvements across operations, scheduling, planned maintenance work, safety and infrastructure.
