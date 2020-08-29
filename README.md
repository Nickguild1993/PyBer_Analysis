# **PyBer Analysis**


## Overview of the Analysis

The purpose of this analysis was to further flesh out the three defined market types that PyBer operates in- Suburban, Urban, and Rural cities.  Specifically, we wanted to examine how **fares** in each of those above three mentioned areas fluctuate throughout the year (the data we had was for Q1 of 2019).  By better understanding how Pyber's business is doing in each of those areas of operation, *over time*, they can better understand both where they can look to improve, like by increasing customer engagement for individuals residing in urban areas, but also, *when* is the most efficient time of the year to look increase their presence, based on the data we produced.  PyBer will be better able to understand how their business changes over time, and be able to make future predictions based on the fluctuations shown in each of the three types of cities.



## Results Section:

### Line Chart
![Alt_text](https://github.com/Nickguild1993/PyBer_Analysis/blob/master/Resources/pyber_fare_city_type_linechart.png)

- As seen above, there are varying levels of change in the amount of fares earned over time for all three city types during the first quarter of 2019.  While the amount of fares earned for each type seem to be indepedent of each other, there are certain times when the fares for the three city types behave similarily.  For example, there is a spike during the later half of Feburary- just before the beginning of March, in which the total fares for all three city types noticeably went up (both Urban and Suburban experience their highest peak for Q1 during this time). Following this spoke, all three types then see their fares decline going into the first week of march, with each type subsequently rebounding to different degrees during the first week in march.

 - Janaury is the slowest month for all three types, with the fares for each type seemingly building up slowly as the warmer spring climate approaches and people go out more. Pyber's rural operation is only one that leads into january with any positive momentum- as both Urban and Suburban experience their fare nadir during the leadup to Janaury before defrosting.
 
 - April is interesting, with both Rural and Urban fares coming into the month strong.  Instead of both continuing on the same upward trend however, Rural area fares rapdily dive after reaching their quarterly high on April 1st, then see a more steady decline that seems to eventually even out as the month progresses. Urban cities behave differently after having that pre-April surge in common with their Rural counterparts.  Instead of an immediate decline like Rural areas, fares from Urban cities continue to go up for the first week of April, then begin trending downward during the second week of the month, with the at first gradual decline becoming more sharp during the latter half of April.  Fares for Suburban cities behave very differently during April than both Rural and Urban cities.  Fares for Suburbs come into april on a downward trend, get noticeably worse during the first week of the month, before rebounding to a level not seen since the end of Febuary in the second week, before holding steady for the rest of April.
 
### DataFrame
![Alt_text](https://github.com/Nickguild1993/PyBer_Analysis/blob/master/Resources/pyber_summary_df.png)

- It's very clear from the above DataFrame that **Urban areas** are where most of PyBer's business takes place.  The amount of drivers that operate in Urban areas is more than *6 times* the amount in Suburban and Rural areas combined.   While Urban does have the lowest average fare per trip at $24.53 (compared to $30.97 for Suburban and $34.62 for Rural areas) the sheer volume of trips- with more than 68% of all PyBer trips occuring in Urban areas, more than compensates for that.  

- Looking at average fare per driver, Rural areas are the most profitable for the drivers, with each driver receiving $55.49 on average.  There are of course, a couple of caveats that should be acknowledged with that figure.  Firstly, we don't know the average *distance* of each trip.  However, given that we do know that those trips originate in Rural communities, it is likely that they're longer trips than those that orginate in both Suburban and Urban areas simply because Rural areas are more remote, meaning that a greater distance must be traveled to reach a destination, which causes the trip fare to increase.  Secondly, without knowing the average time between when a customer books a trip and when that car arrives, we don't know if the low number of drivers in Rural areas (78 active in Q1) is more a result of low demand on behalf of the consumer, or a low supply of available drivers. Knowing that would help us understand if the high amount the average driver makes is at least partially attributable to some form of surge pricing, which would happen if the demand for trips is higher than the supply of drivers can accommodate.

## Executive Summary and Suggestions: 

While it's hard to give recommendations without knowing Pyber's market share, desired focal points, engagement budget, etc. for each of the three areas, we do have some general suggestions.  

### Suggestions
- Incentivize both existing drivers and new drivers to work in Rural areas.  Those cities had only 78 active drivers for 125 trips (1.6 trips per driver) during Q1 of 2019, which in addition to those areas being more spread out due to their inherent remoteness, could very well mean that the average wait time might be appreciably higher for rural customers looking for rides vis-a-vis those looking to hail a ride in Urban and Suburban areas, both of which have a much lower ratio of rides to drivers. So, if you increased the amount of drivers operating in those rural areas, you could both reduce the wait time for customers, who in turn would be less likely to either look for alternative modes of transportation or cancel their rides outright because of said wait time.  Additionally, the rural market may not be nearly as saturated as the Urban and to a lesser extent the Suburban markets likely are because those Rural cities are likely underserved when it comes to ride sharing services due to both their remoteness and smaller populations of driver candidates.

- Roll out a promotional campaign to PyBer users during Janaury.  Because January is a slow month across all three city types, you wouldn't even need to sort users by zipcode or another method, which makes it much easier since you can just target all existing/new users.  Perhaps something like $10 off your first ride in January and then $5 off for any subsequent rides for the rest of the month.

- Increase advertising building up to, and during, the 3rd week of Feburary.  This week is a highwater mark for all three city types, so increasing PyBer's advertising presence against other ride hailing companies during this peak time could yield a higher market share not only for that week, but for the future as well, assuming that user's preference of ride sharing companies is sticky over time.
