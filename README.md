# Uber-Data-Analysis

## Overview
The primary goal of this project is to analyze Uber requet data to uncover insights about peak demand times, common pickup locations, and factors affecting the the efficiency og the ride-hailing service to provide actionable recommendations for improving uber's service in terms of driver allocation and response times.

## Data source
Uber Request Dataset from Kaggle (https://www.kaggle.com/datasets/goyalshalini93/uber-request-data)

## Software Tools
- Python (Data cleaning, analysis, and visualization (Pandas, Matplotlib)
- Power BI (Data Visualization)

## Data Cleaning & Analysis (Python)
- Identify and address missing values.
- analyze trends over time.
- Utilize Python libraries for data visualization.

### Business Question
- Number of Trips for each Status
- What is the distribution of requests based on pickup points
- At any time of the day the number of requests increases
- What is the day with the highest number of requests
- Are there specific time when cancellation are more frequent
- Are there specific days of weeks with higher cancellation
  
 

## Data Visualization
-  Import the cleaned and analyzed data from Python into Power BI
-  Identify key insights from visualization.

## Dashboard
![Uber Dashboard](https://github.com/user-attachments/assets/d7536523-e4a0-41f1-8946-936d94ded388)

## Insights
- Only 42% of the total trips are completed.
- 39% of the trips are canceled due to lack in the cars availability.
- 18% of the trips are cancelled.
- The majority of the trips are completed, but there is a significant proportion of requests that are either cancelled or result in 'No Cars Available'. This indicates potential issues with availability or customer cancellations that need to be addressed.
- The number of requests fluctuates throughout the day with noticeable peaks and troughs. Identifying peak hours can help in better allocation of resources, ensuring more drivers are available during high-demand periods to minimize 'No Cars Available' instances
- There is a higher proportion of 'No Cars Available' and 'Cancelled' requests at the Airport compared to the City. This could be due to higher demand or longer waiting times at the Airport. Improving driver availability at the Airport could help in reducing cancellations and availability issues.
- By analyzing cancellations over different times and days, patterns might emerge indicating specific periods when cancellations spike. This can help in identifying potential issues like traffic congestion, weather conditions, or other factors influencing cancellations.


## Recommendation
- We can focus to make more cars available at the airport.
- Increase the number of available drivers during peak hours, particularly in the evenings and mornings, to meet the high demand for rides.
- Improve driver retention by providing incentives and benefits that encourage them to remain active on the platform during high-demand periods.
- Expand the service coverage to other areas and increase the number of cars available to provide rides during peak hours.




