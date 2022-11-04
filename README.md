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


## Questions for Analysis

Univariate Exploration

1. What is the gender distribution?

2. Checking the distribution of the trip duration in seconds.

3. What is the distribution of the users ages?

4. What is the distribution of the bike share users on all Trips?

5. What is the distribution for user Type?

6. What is the distribution of the trip duration in minutes?

Bivariate Exploration

1. How long is the duration of the trip for each gender in minutes?

2. How long is the duration of the trip for each user-type in minutes?

3. Check the user distribution depending on their age and gender.

4. Check the user distribution depending on their age and user-type.

Multivariate Exploration

1. Explore the relationship between start day of the week, gender and trip-durations (in minutes).

2. What is the correlation between specific numeric variables in the forgobike dataset?

3. Explore the relationship between age, gender and trip-durations (in minutes).

## Key Insights for Presentation

My main focus in this analysis is to check the distribution of the main features of interest in this dataset.

The features of interest include:

a. The user type distribution. The user type present in the bike sharing system is the subscriber amd customer. 

b. Checking on the gender distribution to determine the gender that is most involved in the bike sharing system. 

c. Checking on the trip duration and how it relates with the gender and user type. 

d. Check on the age distribution. 
