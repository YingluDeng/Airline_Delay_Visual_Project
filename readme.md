# Airline On-Time and Delay Causes Data Analysis and Visualization

## Dataset

The Bureau of Transportation Statistics provides a CSV raw data to 
download. This dataset reports flights in the United States, 
including carriers, arrival and departure delays, and reasons for 
delays, from 2004 to 2019.

Data Resource Page: 
https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp

The Information of each Label Name:

1.year -- The year of the month occured

2.month -- The month for which data was collected

3.carrier -- The airline code

4.carrier_name -- The airline name

5.airport -- The airport code

6.airport_name -- The airport name

7.arr_flights -- # of flights that arrived at the airport

8.arr_del15 -- # of flights that arrived >= 15 minutes late

9.carrier_ct -- # of flights delayed due to the carrier

10.weather_ct -- # of flights delayed due to weather

11.nas_ct -- # of flights delayed due to national air system

12.security_ct -- # of flights delayed due to security

13.late_aircraft_ct -- # flights delayed because a previous flight 
                      using the same aircraft was late
                      
14.arr_cancelled -- # of canceled arrivals

15.arr_diverted -- # of scheduled arrivals that were diverted

16.arr_delay -- Sum of the delay minutes

17.carrier_delay -- Total minutes of delays due to carriers

18.weather_delay -- Total minutes of delays due to weather

19.nas_delay -- Total minutes of delays due to natl. air service

20.security_delay -- Total minutes of delays due to security

21.late_aircraft_delay -- Similar to late_aircraft_ct. The total 
                       minutes of delay due to a previous flight 
                       using the same aircraft arriving late.

## Summary of Findings

In the exploration, I found that there was a positive relationship 
between those flight arrived on time and those flights delayed. 
When there are many flights, the delayed situation would happen 
frequently. Furthermore, when we explore the delayed reason, we 
found that most of the delayed reason is due to previous flight 
arrived late. They use the same aircraft, so it causes the delay.

## Key Insights for Presentation

For the presentation, I focus on presenting the relationship between 
different variables. First, we explore the proportion and count of the 
flight carrier and found that SkyWest Airlines Inc. has 31132 flight 
branches in U.S. Then we focus on the average cancelled flight for each
month. And we found there are two peaks for calcellation flight in 
January and July Seperately. Then we continue exploring the relation
through bivariate method and multivariate method focusing on exploring
the delayed reason and delayed time. 

