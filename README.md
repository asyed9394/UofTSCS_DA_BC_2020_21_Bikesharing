# NYC CitiBike data analysis- Business Case for a bike sharing program in Des Moines

## Project Overview:
 
Using NYC Citibike ridesharing program as a model to create a business case for starting a similar program in the city of  Des Moines.

Use the NYC data to understand:
1. who are the riders? (gender, age)
2. Riders usage pattern:
    .   How long bikes are checked out for all riders and genders.
    .   How many trips are taken by the hour for each day of the week, for all riders and genders.
    .   A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.
3. Undestand the community and neighbourhood of rental stations.

## Resources:

#### Data:
- NYC Citibike ride share data from [Citi Bike](https://www.citibikenyc.com/system-data)
- Use August 2019 ridesharing data. [Link to Aug 2019 CitiBike ride sharing data](https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip)


#### Software:
Software: Anaconda Jupyter notebook Python 3.7 , pandas
Visualization tool: Tableau Public 2021.1 . [Tableau public](https://public.tableau.com/en-us/s/)

#### Solution notes: 

1. Jupyter notebood is used to change the trip duraton from second to time to see how long the renters keep the bike before returning

2. Calcualted distance travelled in each trip by using latitudate and longitutude of start and stop locations. The formula is taken form the web link (https://kb.tableau.com/articles/howto/calculate-the-distance-between-points-on-a-map)



### Tableau Analysis
[Link to Tableau visualization](https://public.tableau.com/profile/aisha.syed#!/vizhome/NYCCitiBikeshareAug2019Analysis/NYCBikesharingAnalysis)

## Results:
1. Checkout Times by Users:  Based on this visualization we can conclude most of the checkouts are from 5 to 25 minutes.
2. Checkout Times by Gender: The trend of chekcout times by gender is simlar to checking out by all users. there is no impact of gender on the trend. However we can same male ridershup is much higher compare to female
3. Trips by Weekday per Hour: This visualization shows that 5-7 is the busiest rental time, while 2am to 4am is the slowest time. In addition Thursday is the busies day of the week.
4. Trips by Gender(Weekday per Hour): This visualization shows the same trend by Gender as over all trend for weekday and per hour. So gender doesn't impact the time of the day and weekday usage.However we can same male ridershup is much higher compare to female
5. User trips by Gender by Weekday: The weekday trend is same as in 2, i.e on Thursday we've higer ridership. In addtion we can see subscriber riders are more than individaul customer riders, as well as male riders have the higher proportion than female riders.
6. Trip Duration by weekday: The charts shows that while thursdays has the highest numbers of trips, but on Saturdays riders used the bikers for longer period of time.
7. Trip duration by Birth Year and Map of Starting Location & Meidan Age: These two visualization shows that bike riding is popular in younger generation (age 25-35). 

## Summary:
 
 1. Based on NYC Citibike ridership data, we understand that bikeriding is populate in male and younger generation. So for business case to start a program in Des Moines , we should analyze the demogrphic data to estimate ridership in this city.
 
 2. NYC data also shows that evening and morning times are the peak time for ridership , while usage is the lowest between 2am to 2 am. So this would be the best time for bike maintenance.

 3. In addtion to above analysis, we can see also create following visualization:

    1. Retnal Location map using outdoor map style with overlay of age. This will show the the what factors are improtant to decide the location of retnal stations. e.g parks, public transit stations, and median age of community
    
    2. No of bike map using outdoor map stype and population overlap. This show many number of bike would be enough to server a community based on the size of population
