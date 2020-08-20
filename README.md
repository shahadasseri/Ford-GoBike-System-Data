# Ford-GoBike-System-Data
Ford GoBike System Data project 7 from Udacity.
## by eng.Shahad Asseri


## Dataset
The chosen dataset includes 519700 trips(rows) with 13 features (columns) as below: trip duration in seconds , start time, end time, start station id, start station name, start station latitude, start station longitude, end station id, end station name, end station latitude, end station longitude, bike id, user type.
Most variables are numeric as shown:(duration_sec,start_station_id,start_station_latitude,start_station_longitude,end_station_id,end_station_latitude,end_station_longitude,bike_id).
while (start_time,end_time,start_station_name,end_station_name,user_type) are string object. ### What is/are the main feature(s) of interest in your dataset?
What is The month that provides the most service
What is the distribution of the user type variable
Does being a customer or subscriber differ in the average time duration of driving a bicycle
What is The relationship between trip duration and seasons
How does the average trip duration diff between the user based on the day of the week ### What features in the dataset do you think will help support your investigation into your feature(s) of interest?
The Trip duration and The user type.


## Summary of  Exploration

 #### Univariate  Exploration: 
The October month is the most month that provides more of rides
The Member is the most frequent.
No, I don't need to perform any transformations,everything was normal.

 #### Bivariate  Exploration: 
I notice that in genera,There is higer concentration customers that a high travel duration (1500s - 4000s) than subscriber and There is higer concentration subscriber that a low travel duration (0 - 750s) than customers. So, yes it does make a diffrence in the average duration time.

In the seasons plot that Summer season has the longest trip duration.

 #### Multivariate  Exploration: 

The Casual users take longer trips than member users in terms of average hours and minuts.
