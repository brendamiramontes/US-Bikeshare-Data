# US BikeShare Data Project
This Python program allows users to explore and analyze US bikeshare data from three major cities: Chicago, New York City, and Washington. The program computes and displays various statistics on trip durations, popular stations, and user demographics.

## Contents
1. [Python Code](./bikeshare.py)

##Features
**Load Data:** Load data from CSV files for Chicago, New York City, and Washington.
**Time Statistics:** Calculate and display statistics on the most frequent times of travel.
**Station Statistics:** Calculate and display statistics on the most popular stations and trips.
**Trip Duration Statistics:** Calculate and display statistics on total and average trip durations.
**User Statistics:** Calculate and display statistics on bikeshare users, including user types, gender, and birth years.

##Data Files
The program uses the following CSV files:

- chicago.csv
- new_york_city.csv
- washington.csv
These files should be placed in the same directory as the bikeshare.py script.

##Example Output
Hello! Let's explore some US bikeshare data!
Would you like to see data for Chicago, New York, or Washington? chicago
Which month? all, january, february, march, april, may, or june? all
Which day? all, monday, tuesday, wednesday, thursday, friday, saturday, or sunday? all

Calculating The Most Frequent Times of Travel...

Most common month: June
Most common day of week: Wednesday
Most common start hour: 17

Calculating The Most Popular Stations and Trip...

Most commonly used start station: Streeter Dr & Grand Ave
Most commonly used end station: Streeter Dr & Grand Ave
Most frequent combination of start station and end station trip: Lake Shore Dr & Monroe St to Streeter Dr & Grand Ave

Calculating Trip Duration...

Total travel time: 280871787
Mean travel time: 940.94

Calculating User Stats...

Counts of user types:
Subscriber: 238889
Customer: 61110

This is all for now! Have a great day!

#Requirements
Python 3.x
Pandas library

#Acknowledgements
This project is part of a Udacity course on Python programming and data analysis.
