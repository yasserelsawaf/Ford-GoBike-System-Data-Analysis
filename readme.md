# Effect of Various Features on the Trip Duration
## by (Yasser El-Sawaf)


## Dataset

The data contains almost 175k datapoints of bike trips and has these features ['duration_min', 'start_time'end_time', 'start_station_id','end_station_id', 'bike_id', 'user_type', 'member_birth_year','member_gender'], Some data points were removed from the analysis due to inconsistencies or missing information.


## Summary of Findings


- while looking for the average durations for customers and subscribers it showed that the customers have higher average , this with confirmed in each of the bivariate and variate exploration.
- while looking at the effect of gender on trip duration not much difference was present,but during the multivariate exploration of duration against type and gender , it showed that female customers have the highest average overall (~20 mins) ,  while the male subscribers have the lowest average overall (~10 mins). 
- Seems that the average trip duration ranges for older users are lower than the ranges for younger users , most trips higher than 50 mins is seen from the year range (1965-1995) , but there were not much difference on the average age of diffrent user types or genders. 
- Even though saturday and sunday had the lowest count of all days almost by half , these two day had the higher average trip durations .
- After checking the average durations of custmors and subscribers against differnet days of the week , while subscribers maintaned a monotonic behaviour , the customers's average were much higher early week specially on sundys.


## Key Insights for Presentation

The presentation focus on the trip duration and the features affecting it. It starts by checking the Distrubtions of each variable of interst to the analysis which is the trip duration , gender , user type , member birth year and day of week.  
Then each of these variables is plotted against the main variable which in the trip duration , i checked the categorical variables which is gender gender ,user type and day of week , then i checked birth year ( which is numeric varibale) agaisnt the duration.
Finally I check multpile categorical variable againt the duration to see if they affect  each others while affectingthe average duration this includes plots of duration agaisnt user type and gender and duration against user type and day of week.
