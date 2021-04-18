# Ford GoBike Data Analysis and Visualization


## Dataset

The dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in february 2019.The dataset consists of 183412 rows and 16 features.

There are 7 object type features (start_time,end_time,start_station_name,end_station_name,user_type,member_gender,bike_share_for_all_trip), and 9 numeric features(duration_sec,start_station_id,start_station_latitude,start_station_longitude,end_station_id,end_station_latitude,end_station_longitude,bike_id,member_birth_year).
  
data wrangling and cleaning steps:
  
	- Make a copy of the dataset.
	
	- Remove null values from the dataset.
	
	- change stations id to integers.
	
	- separte start time into start date, start date and start time.
	
	- separte end time into end date and end time.
	
	- make new columns for trip duration in minutes and hours.
	
	- make a new column for user age.
	

## Summary of Findings

In the exploration, I found that trip duration is mostly less than 10 minutes. Most of the riders are males, however, females and others have longer rides than males.
Most riders are between 20 to 40 years and have longer rides than older riders. Most riders are subscribers,however, customers tend to have longer rides at average.
The most popular station is San Francisco Caltrain Station 2 is the most popular station at near 3500 trips in february. 

## Key Insights for Presentation

For the presentation, I focus on the effect of age,gender, and user type on trip duration. First I present average trip duration in minutes and seconds then I present historgrams for each of gender,age, and user types to present the most common category (in gender and user type) or value (in age).
Afterwards, I present the relation between each of the previous three variables and trip duration.
