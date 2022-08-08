# (Ford GoBike-Tripdata Exploration)
## by (Aminat Owodunni)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. 
> There are 183,412 columns in the dataset with 16 features (```duration_sec```, ```start_time```, ```end_time```, ```start_station_id```, ```start_station_name```, ```start_station_latitude```, ```start_station_longitude```, ```end_station_id```, ```end_station_name```, ```end_station_latitude```, ```end_station_longitude```, ```bike_id```, ```user_type```, ```member_birth_year```, ```member_gender```, ```bike_share_for_all_trip```). Most variables are string in nature, but the variables ```user_type``` and ```member_gender``` are categorical features.
> The ```start_time``` column was split to determine when most trips are taken in terms of time of day and day of the week. ```duration_min``` column was created to convert trip duration from seconds to minute.

## Summary of Findings

> Majority of the users use the bike for short time duration (usually 10mins). Younger members have a longer trip duration. Most common user type are subscribers. Male users are more than the other gender for both users_type. Users that are customers have a longer duration trip than subscribers. Subcribers usage is high on weekdays with Thursday being the highest usage while the customers highest usage is on Thursday. Customers spend more time than the subscribers. However both users spend more time on weekends. It can be observed that trips are taken in the morning on weekdays while trips are taken in the afternoon on weekends. Most trips are taken in the morning and afternoon, however,the trips are generally longer when started in the afternoon and evening.


## Key Insights for Presentation

> Majority of the users use the bike for short time duration (usually 10mins).
> Male users are more than the other gender for both users_type. Female spend longer time on trips than male, while the other gender spends the most time.
> Most trips are taken in the morning and afternoon, however,the trips are longer when started in the afternoon and evening. It can be observed that trips are taken in the morning on weekdays while trips are taken in the afternoon on weekends.
> Customers spend more time than the subscribers. However both users spend more time on weekends.