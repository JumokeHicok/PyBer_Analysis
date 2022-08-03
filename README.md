# PyBer_Analysis

## Project Overview
The CEO of PyBer, a ride_sharing app company, would like the following tasks completed using the city_data and ride_data datasets.

1. Summarize the ride-sharing data by city type.
2. Create a multi-line graph showing the weekly fares by city type.
3. Summarize the differences by city type and how the differences can be used for decision making.

## Resources
- Data Source: city_data.csv and ride_data.csv
- Software: Python 3.9.12, Jupyter Notebook 6.4.8

## Results
After completing the analysis we can see that:

- Total Rides = 125 for Rural, 625 for Suburban, and 1,625 for Urban  
- Total Drivers = 78 for Rural, 490 for Suburban, and 2,405 for Urban
- Total Fares = \$4,327.93 for Rural, \$19,356.33 for Suburban, and \$39,854.38 for Urban
- Average Fare per Ride = \$34.62 for Rural, \$30.97 for Suburban, and \$24.53 for Urban
- Average Fare per Driver = \$55.49 for Rural, \$39.50 for Suburban, and \$16.57 for Urban

![Summary by City Type](/analysis/summary_by_city_type.png)

- Total Fare by City Type:

![Total Fare by City Type](/analysis/total_fare_by_city_type.png)


## Challenge Summary
One way this analysis can be used for decision making is by reviewing which city types have too many drivers.  Urban cities appear to have too many drivers which could be the reason for the lower average fare per driver and possibly the lower average fare per ride due to over supply. 

Another way this data can be used for decision making is by reviewing which city types have too few drivers.  Rural cities could be losing out on fares if they don't have enough drivers to support the business.

A third way this data could be used for decision making is by comparing how fares for the three city types compare on a weekly basis.  For example, suburban fares went up towards the end of April while urban and rural fares went down.  It could be useful to figure out why for planning purposes.