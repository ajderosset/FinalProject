# FinalProject

Car crashes in Raleigh, North Carolina, continue to be a problem as more drivers head back to the road in the wake of the COVID-19 pandemic. 

Crashes in Raleigh occur at all times of day around the city. Crash hotspots are different when comparing nighttime crashes to daytime crashes. Weekends also bring a spike of crashes after midnight and before 5 a.m. Although fewer crashes occur at night, a higher percentage of those crashes are fatal. 

Between Nov. 30, 2021 and Nov. 30, 2023, at least 89 people were killed in car accidents in the Raleigh area. Although this number accounts for 0.4% of all crashes, it is still a significant loss of life, with an average of 44.5 people dying each year in Raleigh as a result of car crashes. 

The most common area for car crashes in Raleigh was Interstate 440, according to my analysis. Over 2,800 crashes occurred on the interstate in the past two years. That’s an average of 3.8 crashes each day on the beltline alone. 

Another high-density crash area is the center of downtown, especially along South Dawson St., Edenton St., and South Blount St. South Dawson St. is part of the U.S. Route 401, also known as Capital Blvd. in Raleigh. 

According to the North Carolina Department of Transportation, the average cost per person for car crashes in Wake County is $2,462, as of 2021. The average annual cost for Wake County is $2,833,377,533, the second highest in the state after Mecklenburg County. Such a high number of crashes takes a physical and financial toll on drivers. 

For daytime drivers hoping to avoid the most dangerous roads, getting around the city efficiently might become difficult, as the interstate and major connecting roads are the sites of most of the crashes. If you do need to use the beltline and want the lowest chance of being in a car crash on a weekday, 10 a.m. is an ideal time to get on the road. Don’t linger, as crashes begin to rise again just after 11 a.m. On the weekends, you will have to be an early bird if you want to beat the crashes, with the lowest number occurring between 4 a.m. and 8:30 a.m. 

Nighttime drivers are four times less likely to be in a car accident than daytime drivers in Raleigh. However, nighttime is not necessarily the safer time to drive. 1.45% of crashes at night resulted in fatalities, compared to 00.2% of crashes during the day which resulted in fatalities, according to my analysis.

For both the nighttime fatality data and the daytime fatality data, about 45% appeared as NA values. I omitted this data from my calculation but because it is such a large percentage of the fatality data it could significantly impact the findings. Most drivers involved in crashes with no fatality data were recorded to be off the roadway. 

At night, crashes tend to be consolidated in the center of the city, in the Glenwood South district, according to my analysis. Glenwood South, which is known as Raleigh’s nightlife hub, is home to a wide variety of bars and restaurants that attract young adults, according to the Downtown Raleigh Alliance. 

Nighttime crashes are also concentrated along Capital Blvd. and Wade Ave., another popular road for leaving the city and getting onto the highway. 

When I analyzed the data, I split it into crashes that occurred at night and during the day. Daytime data included crashes that occurred between 5 a.m. and 8 p.m. Nighttime crashes occurred after 8 p.m. but before 5 a.m. Overnight and early morning crashes were included in the nighttime data because a significant portion occurred on Saturdays and Sundays. I hypothesized that people involved in those crashes were likely heading home after a night out. 

Because there were more hours included in the daytime filtering of the data, it is logical that there were more crashes during the day. In fact, there was an average of 34,190 crashes that took place during the day compared to 4,098 crashes at night over the two-year time span. There were about eight times more crashes that occurred during the day than at night.  

Another thing I was interested in investigating was which car crashes occurred near schools. I hypothesized that schools would be a hotspot because they attract a considerable amount of drivers each day. I especially expected high schools to be hotspots because of their early start times and the concentration of inexperienced drivers at high schools is likely much higher than elsewhere in the city. I was unable to combine these two data into one map. I found, however, that a number of schools are concentrated in the center of the city, like the car crashes.
 
When creating the visualizations for the traffic map, I first narrowed the data to include only data from Raleigh, North Carolina. When I plotted it, I realized that some of the coordinate points fell outside of Raleigh, despite being marked as inside of Raleigh. A large concentration of the dirty data fell within Smithfield. Other dirty data was concentrated along the same latitude line, but on the opposite side of the world. It appears that much of the dirty data was due to a misentering of one or two characters in the latitude and longitude. However, without the time to confirm each data point with the DOT, I decided to filter it out of the data set. Overall, just 3% of the total Raleigh crash data was filtered out, leaving me with 395,240 crash data points within Raleigh. I defined the borders of Raleigh based on the parameters set by Google Maps. 
