### Date created
#Include the date you created this project and README file.
The project is created on Friday, the 28 of June 2019

### Project Title
#Replace the Project Title
Python Script to Explore US Bikeshare Data

### Description
#Describe what your project is about and what it does
The datasets used for this script contain bike share data for the first six months of 2017. Some data wrangling has been performed by Udacity's staff before being provided to the students.The file sizes are too big to be uploaded on GitHub, so they were uploaded on Google Drive instead. After downloading the datasets, place them in the same folder with this Python script.
.The data files for all three cities contain the same six columns:
•	Start Time
•	End Time
•	Trip Duration (in seconds)
•	Start Station
•	End Station
•	User Type (Subscriber or Customer)
The Chicago and New York City files also contain the following two columns:
•	Gender
•	Birth Year
The script answers the following questions about the bike share data:
•	What is the most popular month for start time?
•	What is the most popular day of week (Monday, Tuesday, etc.) for start time?
•	What is the most popular hour of day for start time?
•	What is the total trip duration and average trip duration?
•	What is the most popular start station and most popular end station?
•	What is the most popular trip?
•	What are the counts of each user type?
•	What are the counts of gender?
•	What are the earliest (i.e. oldest person), most recent (i.e. youngest person), and most popular birth years?


### Files used
#include the files used
We have used chicago csv, washington csv and new_york_city csv Files
### Credits
It's important to give proper credit. Add links to any repo that inspired you or blogposts you consulted.

Use parse_dates to recognize datetime columns:
•	https://stackoverflow.com/questions/21269399/datetime-dtypes-in-pandas-read-csv
•	https://stackoverflow.com/questions/17465045/can-pandas-automatically-recognize-dates
•	https://pandas.pydata.org/pandas-docs/stable/generated/pandas.read_csv.html
Assess datetime series:
•	https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.html
•	https://stackoverflow.com/questions/29366572/pandas-how-to-filter-most-frequent-datetime-objects
Filter date:
•	https://stackoverflow.com/questions/29370057/select-dataframe-rows-between-two-dates
Check validity of date:
•	https://stackoverflow.com/questions/9987818/in-python-how-to-check-if-a-date-is-valid/9987935
Add a day to a date:
•	http://www.pressthered.com/adding_dates_and_times_in_python/
Read day of week, month, hour etc.:
•	https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.html
•	https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.dayofweek.html
Convert seconds to hours, minutes and seconds:
•	https://stackoverflow.com/questions/775049/how-to-convert-seconds-to-hours-minutes-and-seconds
•	https://docs.python.org/3/library/functions.html#divmod
Convert pandas series or dataframes to string:
•	https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.to_string.html
•	https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.to_string.html
Concatenate strings of two columns:
•	https://stackoverflow.com/questions/19377969/combine-two-columns-of-text-in-dataframe-in-pandas-python
•	http://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.str.cat.html#pandas.Series.str.cat
