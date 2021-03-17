# FordGoBike
# Bike Data Exploration

## Dataset

 
This data set includes information about 183412 individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
This includes features like Trip Duration (seconds), Start Time and Date,Stop Time and Date,Start Station Name,End Station Name,Station ID,Station Lat/Long,Bike ID, User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member), Gender (Zero=unknown; 1=male; 2=female),Year of Birth

## Main features of the interest
I started exploring distributions and counts of station locations, trips times, user types, gender, age, hour of the day, day of the week for bike rental.

## Summary of Findings


In the exploration, 
The number of stations were huge so couldn't really understand the pattern other than top 10 and bottom 10 frequently used stations.
There was distinct difference in distribution of user types. 89% Subscriber vs 11% customers.
Trip time distribution was very vast so I used log form transformation to observe distinct peak around 10 min.
I also analyzed trip time distribution of customers and subscribers separately. 
The Customer peak usage time was 23 min and subscriber peak usage time was 10 min. But there are some fluctuations visible in log transformation.
I then analyzed start and end day for customers and subscribers.Overall more customers are starting and ending the trips on weekends than start of the week.
Where as more subscribers were starting and ending the trip on weekdays.I also analyzed number of trips taken on the hour of the day which peaked around 8am and 5pm. 
Age analysis didn't feel much significant except more millennial where using the rental.I also plotted  geological distribution of the location using latitudes and longitudes but the area encompassed was very vast to see significant insight.
Overall more male users are using bikes everyday than females and other gender.In total trips take by all genders peaked on Thursday.
I analyzed the renting by hour of the day on weekdays and weekends. It was clear that during week days peak time was at 8am and 5pm. Peak of the week end trips are in afternoon. Weekend rental is less than weekday rental.Though less but there is definite bike use during midnight hours on the weekends. 
Median use of the bikes is on the day 3.
Customers are using the bikes quite uniform over the week. More thick portion of the violin plot is on day 5 and 6.
I found that there are some long trip taken in wee hours but not that too many. Saturday 3am had highest duration time of 44.3 min.
My further analysis found that customer rental peaked on Sunday. Subscribers use more on weekdays with peak on Thursday.
I tried analyzing relation of rental on weekday and weekend with longitude and latitude. But due to vast area it is hard to get any meaningful insight.
Subscribers are using the rental on weekdays all over the region with some peak spots.Customers are not that well spread.

Its interesting to see that male are taking the bike trip in wee hours. Females customers are not riding bikes in weehours¶
Number of male subscribers > male customers
Male renters are taking trips for longer time than female and other renters

## Key Insights for Presentation

For the presentation, I focus on just the influence of the days of the week and time of the day on customer and subscriber	rental and leave out most of the other features.
I start by introducing the user distribution then pattern in duration for the users.I will then show the day of week analysis of the users.

Then I will show the countplots of the trip counts for weekday and weekend for each user type by day of the hour.I will show violin and box plot to
strengthen the findings.
I will then show the heat map between day of the week and hour with user type using strip plot and annotated heat map.I have added the boxen plots to show the relation between 
I will also add boxes plot to strengthen the relationship findings.


I've made sure to use different color palettes for each quality variable to make sure it
is clear that they're different between plots.
