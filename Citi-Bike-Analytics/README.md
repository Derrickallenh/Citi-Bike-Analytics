# Citi-Bike-Analytics
https://public.tableau.com/profile/derrick.humphrey#!/vizhome/Citi_Bike_Analysis_Pub/CitiAnalysis

### Background

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

### The Citi Story

#### Map

The included story board shows the requested map for the station's popularity changes via month. Start 
stations are in blue and end stations are in red as they are seperate data set. (start stations and end stations). You can scroll through the monthly data for each map by adjusting the slide on the right. When you do so you will notice that there are random points out side the bulk of the points that don't have station names. One can assume that not all bikes make it back to a station. I suspect that these are those data points.


#### Phenomenons 

**Who commutes with CitiBike?**
New York City, like every other major American Metro area has a commute and rushhour. So I was curious to see which segment of user is grabbing a CitiBike for their commute? Who is also commuting the least? From here CitiBike would be able to identify maybe new subscribers or measure the usefulness of their marketing campaigns. 'CommuteStart' and 'CommuteStartTable' reflect this usage as they show the number of records during the considered "rush hour" times; 7-9Am and 4-6Pm. 

**Duration by age...then gender...then customer vs subscriber....**

I wanted to study the length of an average trip as the billing for this service is done by time, not distance. Given that, which sub groups of the CitiBike patrons have the longest and shortest trips by sub group. The 'AvgTripDurationAge' histogram shows that the 50-55 years old group has a much longer average ride than the others. About 10 minutes longer compared to the 45-50 group and the 55-60 group. 

To investigate further on why this is I created another visual, 'AvgTripDurationAgeGender' that breaks this age group up by gender. This histogram reflected that there was a large proportion of riders that didn't declare gender, especially compared to the other age groups. So naturally another visual, 'RecordsByGender' was created to get an actual count of records rather than trip durations. Here it shows that 48% of that age bracket has an undeclared gender. This statistic is staggering compared to the other age groups where an undeclared gender is only a few percent, not 48. 

'RecordsByGenderW/Usertype' shows that the undeclared genders of 50-55 majorly consists of customers rather than subscribers. Of the customer segment 94.8% have an undeclared gender. It's also worth noting that even the subscriber bin for the same age group has a large portion of undeclared gender relative to the other age bins in the chart. As we're narrowing this down there's one more question to ask; "When does this customer group utilize Citi Bike?"

'50-55Customers0GenderWeekday' will show that the bulk of the records committed by this age group are done on Saturdays and Sundays. This information coupled with the other attributes of this customer group would suggest that they're actually visitors of NYC and not actual residents, or residents that don't utilize Citi Bike share enough to warrant a subscription.
