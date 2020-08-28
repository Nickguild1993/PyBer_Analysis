# PyBer_Analysis
Work for Module #5

## Overview of the analysis: Explain the purpose of the new analysis.

The purpose of this analysis was to further flesh out the three defined market types that PyBer operates in- Suburban, Urban, and Rural cities.  Specifically, we wanted to examine how **fares** in each of those above three mentioned areas fluctuate throughout the year.  By better understanding how Pyber's business is doing in each of the three types of locations that they operate in *over time*, they can better understand both where they can look to improve, like increasing customer engagement for individuals residing in urban areas via social media, but also, *when* is the most efficient time of the year to look increase their presence, based on the data we produced.



## Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

![Alt_text](https://github.com/Nickguild1993/PyBer_Analysis/blob/master/Resources/pyber_fare_city_type_linechart.png)

As seen above, there are slight changes in the amount of fares earned over time for all three city types during the first quarter of 2019.  While the amount of fares earned for each type seem to be indepedent of each other, there are certain times when the fare amount for the three city types behave similarily.  For example, there is a spoke during the later half of Feburary- just before the beginning of March, in which the total fares for all three city types noticeably goes up (both Urban and Suburban experience their peak for Q1 during this time). All three types then see their fares decline going into the first week of march, with each type subsequently rebounding during the first week in march.

 - Janaury is the slowest month for all three types, with the fares for each type seemingly building up slowly as the warmer spring climate approaches and people go out more.
 
 - April is interesting, with both Rural and Urban area fare amounts coming into the month strong.  Instead of continuing on the same trend however, Rural area fares rapdily dive after reaching their quarterly high on April 1st then see a more steady decline that seems to eventually even out as the month continues. Urban cities behave differently after having a pre-April surge in common with Rural cities.  Instead of an immediate decline like Rural areas, Urban cities continue to see their fares go up for the first week of April, then begin trending downward during the second week of the month, with the gradual decline becoming more sharp during the second half of April.  Fares for Suburban cities behave very differently during April than eithr of their Rural and Urban counterparts.  Fares for Suburbs come into april on a downward trend, get noticeably worse during the first week of the month, before rebounding to a level not seen since the end of Febuary in the second week, and then holding steady for the rest of April.



![Alt_text](https://github.com/Nickguild1993/PyBer_Analysis/blob/master/Resources/pyber_summary_df.png)

It's very clear from the above DataFrame that **Urban areas** are where most of PyBer's business takes place.  The amount of drivers that operate in Urban areas is more than *6 times* the amount in Suburban and Rural areas combined.   While Urban does have the lowest average fare per trip at $24.53 (compared to $30.97 for Suburban and $34.62 for Rural areas) the sheer volume of trips- with more than 68% of all PyBer trips occuring in Urban areas, more than compensates for that.  

## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

While it's hard to give recommendations without knowing Pyber's market share, desired focal points, engagement budget, etc. for each of the three areas, we do have some general suggestions.  

- Incentivize both existing drivers and new drivers to work in Rural areas.  Those cities had only 78 active drivers for 125 trips (1.6 trips per driver) during Q1 of 2019, which in addition to those areas being more spread out due to their inherent remoteness, leads us to conclude that the average wait time must be appreciably higher for customers looking for rides vis-a-vis those looking to hail a ride in Urban and Suburban areas, both of which have a much lower ratio of rides to drivers. So, if you increased the amount of drivers operating in those rural areas, you could both reduce the wait time for customers, who in turn would be less likely to either look for alternative modes of transportation or cancel their rides because of said wait time.  Additionally, the rural market may not be nearly as capped out as the Urban and to a lesser extent the Suburban markets likely are because those Rural cities are likely underserved when it comes to ride sharing services.

- Roll out a promotional campaign to PyBer users during Janaury.  Because January is a slow month across all three city types, you wouldn't even need to sort users by zipcode or another method, which makes it much easier since you can just target all existing/new users.  Perhaps something like $10 off your first ride in January and then $5 off any subsequent rides for the rest of the month.

- Increase advertising building up to, and during, the 3rd week of Feburary.  This week is a highwater mark for all three city types, so increasing PyBer's advertising presence against other ride hailing companies during this peak time could yield a higher market share not only for that week, but for the future as well, assuming that user's preference of ride sharing companies is sticky over time.
