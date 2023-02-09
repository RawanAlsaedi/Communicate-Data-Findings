# (Ford Gobike Dataset)
## by (Rawan Alsaedi)


## Dataset

This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In Part I, you will use Python visualization libraries to systematically explore Ford Gobike dataset and find variables and  data structure, outliers and relationships. The analysis in this part should be structured,  starting from plots of single variables and building up to plots of multiple variables.  In Part II, Explanatory data visualization,  I will produce a short presentation that illustrates interesting properties, trends, and relationships that I discovered in Ford Gobike dataset.

The Ford GoBike dataset 
This dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area and containing the trip data of the ford gobike approximately 183,412 with 16 features (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip). 
and with data types (float64(7), int64(2), object(7)).

For clean the dataset, I first do some assess by pandas functions such as : info(), describe() , isnull() , sum() , duplicated() , head().


## Summary of Findings

There is many factors affect for trips number and trips duration such as : Gender , Users type , weekday and age .
For gender, most bike trips users from males but them have lowest trips duration . For users type , 90 % of bike users are Subscriber users and they have lowest  trips duration than customer. People use bike rides on weekdays as well as on weekends. Most of bike users ages are between 20 to 60 years old and some of older age users have low trip duration than younger.


## Key Insights for Presentation

Distribution of trip duration: The duration of the trip varies according to many factors such as: gender, age ,user type , and weekday. In the mostly , males took average trip duration about 11 min while the female took around 12 minutes. Surprisingly, many older people, about 40 to 60, took less trips duration than young people. Subscriber people are very high but they took lower trip duration than customer.The trips duration are varies slightly during the days of the week , it tooks between 11 and 13  minutes.


Distribution of user age per weekday: In each day of week most bike users have ages between 20 to 60 . And the the average ages for most users over weekday is about 35 years old.