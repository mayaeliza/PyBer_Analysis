# PyBer Python Analysis
## Overview of Pyber Analysis
A ride-sharing summary presented in a DataFrame by city type
A summary of total weekly fares for each city type presented in a multiple-line chart 

## Purpose
Use analysis to determine average number of fare, drivers, and riders by type of city, and percentage of total fares, drivers and riders by type of city. This will help Pyber improve access to rideshare services and determine affordability for underserved neighborhoods. 

## Resources
Data Source: Pyber_ride_date.csv, city_data.csv, ride_date.csv
Software: Python 3.9.0, Anaconda 4.9.1, Jupyter Notebook, Pandas 1.2.3

# Results
## How does the data differ by city type? How can those differences can be used by decision-makers at PyBer?
### Summary of Data

<img width="488" alt="pyber_challenge_fig9" src="https://user-images.githubusercontent.com/72039212/114025715-0dfb5680-983b-11eb-9af2-6d92f50ae503.png">

By looking at the summary of Pyber data in Figure 8, rural cities generate the smallest number of total rides, drivers and total fares. However, rural cities are the most expensive with the highest average fare per ride and driver. 

Suburban cities follow rural cities with the median number of total rides, drivers, fares, and average fare per ride and driver.

Urban cities generate the most total rides, rides, drivers, fares, and average fare per ride and driver.

By looking at total fare by city type, rural cities generate the least money, $4,327.93, followed by suburban cities, $19,356.33. Urban cities generate the most money, $39,854.38.

![pyber_challenge_fig8](https://user-images.githubusercontent.com/72039212/114029356-0a69ce80-983f-11eb-9bcf-4bcbc62032ba.png)

                                                                                                                                                      
The line chart further illustrates the total fare by city type and also shows a positive trend for increased total fare over time in urban and suburban cities. For rural cities, there are peaks over time but ultimately there is no discenible positive trend for an increase of total fare over time. Due to rural cities having the lowest number of rides, drivers, and total fares, yet the highest rates for average fares per ride and driver, Pyber should consider increasing accessibility to rural cities. This would bring down the average fare per ride and driver. Pyber could redistribute resources and drivers from suburban and urban cities to these rural cities. They should also consider increasing the average fare in urban cities to generate an ever higher total fare in their most profitable city type. 
