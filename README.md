# Udacity-Ford-GoBike-Data-Visualization
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process.
## Dataset
This project requires us to analyse the forgobike dataset. The forgobike dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. 

I found some tidiness and quality issues in the forgobike dataset and performed the following cleaning to get better analysis results.

1. Dropped the missing values in start_station_id, start_station_name, end_station_id, end_station_name,member_birth_year and member_gender.
2. Dropped start_station_latitude','start_station_longitude', 'end_station_latitude', 'end_station_longitude' columns which were not so signifacant in analysing the data.
3. Extracted new columns from the start time and end time columns.
4. Dropped the start-time and end-time columns.
5. Converted the start-time and end-time data type to datetime from string.
6. Created a new column 'age' from member_birth_date.
7. Changed the age datatype from float to int.


## Summary of Findings

Univariate Exploration
Variable distribution.

1. Most users are subsribers and not customers.
2. In terms of gender most users are males.
3. Most users are not enrolled in the trip program according to the distribution of the bike share users on all Trips.
4. Most users spend less than 30 minutes for a trip.
5. The age distribution is left skewed

Bivariate Exploration

1. The user-type customer go for longer trip compared to a subscriber.
2. The trip duration decrease with an increase in age.

Multivariate Exploration

1. Males have shorter bike trips as compared to other gender.
2. There is a negative correletaion between member birth year and age.

## Key Insights for Presentation

My main focus in this analysis is to check the distribution of the main features of interest in this dataset.

The features of interest include:
a. The user type distribution. The user type present in the bike sharing system is the subscriber amd customer. 

b. Checking on the gender distribution to determine the gender that is most involved in the bike sharing system. 

c. Checking on the trip duration and how it relates with the gender and user type. 

d. Check on the age distribution. 
