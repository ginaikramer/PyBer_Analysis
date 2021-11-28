# PyBer_Analysis
## Overview
The purpose of this project is to analyze and visualize PyBer ride share data to improve access to ride-sharing services and determine affordability for underserved neighborhoods. Specifically, this project:
- Summarizes ride-sharing data by three different city types: urban, suburban and rural
- Calculates and visualizes the total weekly fares for each city type
- Summarizes how the data differs by city type
- Provides recommendations based on these differences

The following file was used in building this report: [PyBer Data Analysis](/PyBer_Challenge.ipynb) 

## Results
PyBer ride share data consists of three different city types: urban, suburban and rural. Let's see how the data differed between these three city types. I referenced the following two artifacts when documenting differences and observations:

**1) Summary of Ride Sharing Data by City Type**
![PyBer Analysis by City Type](/analysis/PyBer_Analysis_by_City_Type.png)  

**2)  Weekly fares per City Type between January 1, 2019 and April 28, 2019**
![PyBer Fare Summary](/analysis/PyBer_fare_summary.png)  

### Total Rides:
In our study, there was a total of 2,375 rides. The Urban city type had the most rides of 1,625. Suburban rides were second at 625 rides and Rural rides last at 125 rides. Observations from this data includes: 
- Of total rides:
  - Urban city types had around 68.4% of the drivers
  - Suburban city types had around 26.3% of the drivers
  - Rural city types had around 5.3% them
- Urban city types had
  - 2.5 times more rides than Suburban city types
  - 13.0 times more rides than Rural city types

### Total Drivers:
In our study, there was a total of 2,973 drivers. The Urban city type had the most drivers with 2,405. Suburban drivers were second at 490 drivers and Rural rides last at 78 drivers. Observations from this data includes: 
- Of total drivers
  - Urban city types had around 80.9% of the drivers
  - Suburban city types had around 16.5% of the drivers
  - Rural city types had around 2.6% them
- Urban city types had
  - 4.9 times more drivers than Suburban city types
  - 31.0 times more drivers than Rural city types

### Total Fares:
In our study, there was a total of $63,538.64 made in fares. The Urban city type saw the most fares with $39,854.38. The Suburban city type was second at $19,356.33 and the Rural city type was last at $4,327.93.  
- Of total fares:
  - Urban city types had around 62.7% of fares
  - Suburban city types had around 30.5% of fares
  - Rural city types had around 6.8% of fares
- Urban city types had:
  - 2.1 times more fares than Suburban city types
  - 9.2 times more fares than Rural city types

### Average Fare per Ride:
In our study, the Rural city type had the highest average fare per ride at $34.62 per ride, the Suburban city came in second at $30.97 per ride and the Urban city type came in last at $24.53 per ride. 


### Average Fare per Driver:
In our study, the Rural city type had the highest average fare per driver at $55.49 per driver, the Suburban city came in second at $39.50 per driver and the Urban city type came in last at $16.57 per driver.


### Additional Observations:
I used the data to make an additional calculation and observation. For each city type, I divided the total rides by the total drivers to get the **Average Ride per Driver:**
- Urban city type drivers had an average of 0.7 rides per driver
- Suburban city type drivers had an average of 1.3 rides per driver
- Rural city type drivers had an average of 1.6 rides per driver


## Summary
Based on the results from this analysis, I'd like to provide recommendations to address disparities among the city types. 

If I based my analysis on total fares alone, I may recommend putting more effort into the Urban city type market. However, when looking at the average ride per driver, it's clear that the urban city type market is saturated with drivers. There also seems to be a need for ride shares but not enough drivers in both Rural and Suburban city types.

Therefore, I recommend the following three actions to address disparities among the city types:
1. Perform more research into the Rural city type to determine things such as
   - Is the low number of total rides due to the small number of available drivers or something else such as technology limitations, economics, etc. 
   - Would the demand for rides increase if there were more drivers available in Rural cities? 
   - Breakdown, compare and analyze the data from each Rural city to determine which cities to test out pilot programs
2. Perform more research into the Suburban city type to determine things such as
   - Is the low number of total rides due to the small number of available drivers or something else such as technology limitations, economics, etc. 
   - Would the demand for rides increase if there were more drivers available in Suburban cities? 
   - Breakdown, compare and analyze the data from each Suburban city to determine which cities to test out pilot programs
3. Increase the number of drivers in both Suburban and Rural city types by either:
   - Hiring more drivers in each city type
     - This can potentially increase both supply and demand 
   - Incentivizing drivers in Urban city types to take more fares in both Suburban and Rural city types
     - This can potentially increase both supply and demand
     - This can also potentially provide urban city type drivers with more ride share opportunities and increase their average fare per ride and per driver


