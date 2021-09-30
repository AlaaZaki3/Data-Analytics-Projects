## Flights 
* can find it through this link http://stat-computing.org/dataexpo/2009/the-data.html

> The flights dataset has a number of features related to airports names and flights, arrive delay and some featurs for delaying reasons.
> Through exploring our data we figure out that:
 * Data gathered over 3 years and 1 month from Nov. 2017 to Nov.2020.
 * Data has null values so we droped it during cleansing it
 * Renaming some columns
 * select particular features and work on them as a new dataframe
 * change types of some columns

## Questions: 
* What are the airports have delays?
* What are the reasons of delays?
* Which month has the most delay?
* What is the number of flights per year?
* What is the month has the late flights? need to track the reason "when" the problem happend
Explore which month over 3 years has late flights
* What's the relationship between arrived late and reasons
* what is the city having the great number of late flights?
* What are late flights per year grouped by month?
- Is the month playing a key role in late flights?
* What is the effect of each reason over months and years


## Summary of Findings

> we found that number of flights during 4 years is equavilant 
> Flights arrived delay during 2018 and 2019 
> the main reason for delaying is aircraft becuase it has a strong relationship and arrive delay
> the second reason is weather
> number of flights during 2020 is less than other years and that's logically according flights stopped during COVID-19
> Due to last visual we have a little number of data points gathered from year 2017

2019 has the most number of flights
then 2018
finally 2020 and that's logical because COVID happend in 2020 as flights stopped

January and December have late flights may be cause of weather


- The number of late flights over 2018 year is: 18885
- The number of late flights over 2019 year is: 19566
- The number of late flights over 2020 year is: 13298
- the percentage of late flights during 2018: 93.43 
- the percentage of delay during 2019:93.47 
- the percentage of delay during 2020:77.15
Here number of late flights are different from year 2018 to 2019 by around 1000 but actually the difference in percentage is not significant in order to total flights in the related year

The highest year has late flights is 2019
But actually the percentage of late flights in 2018 and 2019 are close to the same value
In 2018 and 2019 have the percentage close to 93%
2020 has the less percentage over 3 years



## Key Insights for Presentation

> I focus on flights arrived late and what is the reason of it
* As we see, we found the relationship between arrive delay and late_aircraft_delay so that's the main reason to delay the flights, then nas_delay and last reason is weather delay
* number of flights on january:5196, febraury:10182, march:15573, april:19952, may:24205, june:28992, july:34440, augest:39856, september:44406, october:49140, november:65813, December:55188

* on june 2019 the most late flights occured then october and november on july 2018 the most late flights occured then september and october on october 2020 has a high number of late flights

* Based on last insights we can say that october over 3 years from 2018 to 2020 has the significant problem across three year and want to figure out why this happed and work to solve it

* It's clear from the visaul 2019 has the peak point of late flights

Late aircraft has the main reason for delaying the flihgts
All reasons are decreasing on November, March in 2019
Febraury 2020 has a peak point of late flights
NAS Delay is playing very important role in delay flights
