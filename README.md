# My-Udacity-Bikeshare-Project
My Udacity project that I have made to improve my skills in pandas for a nano-degree Udacity program.
 Please don't use it to copy the project. 
# overview

## Introduction
This Python script is written for Project 2 (Term 1) of Udacity's Data Analyst Nanodegree (DAND) and is used to explore data related to bike share systems for Chicago, New York City, and Washington. It imports data from csv files and compute descriptive statistics from the data. It also takes in users' raw input to create an interactive experience in the terminal to present these statistics.

## Dataset
The datasets used for this script contain bike share data for the first six months of 2017. Some data wrangling has been performed by Udacity's staff before being provided to the students of DAND. 
## The Requirements
![alt text](https://raw.githubusercontent.com/NidalShater/My-Udacity-Bikeshare-Project/master/req.jpg)


## Data Exploration on Bikeshare Data
#### Basic Udacity project using pandas library in Python for their bikeshare data exploration.

###Project Overview:
This project focuses on pandas library usage and simple statistics methods to perform a rudimentary analysis on 
the bikeshare data from three major U.S. cities - Chicago, Washington, and New York City - to display information 
such as most popular days or most common stations.


Program Details:
The program takes user input for the city (e.g. Chicago), 
month for which the user wants to view data (e.g. January; also includes an 'all' option), 
and day for which the user wants to view data (e.g. Monday; also includes an 'all' option).

Upon receiving the user input, it goes ahead and asks the user if they want to view the raw data 
(5 rows of data initially) or not. Following the input received, the program prints the following details:

Most popular month
Most popular day
Most popular hour
Most popular start station
Most popular end station
Most popular combination of start and end stations
Total trip duration
Average trip duration
Types of users by number
Types of users by gender (if available)
The oldest user (if available)
The youngest user (if available)
The most common birth year amongst users (if available)
Finally, the user is prompted with the choice of restarting the program or not.

### Requirements:
Language: Python 3.6 or above
Libraries: pandas, numpy, time
### Project Data:
chicago.csv - Stored in the data folder, the chicago.csv file is the dataset containing all bikeshare information for the city of Chicago provided by Udacity.

new_york_city.csv - Dataset containing all bikeshare information for the city of New York provided by Udacity.

washington.csv - Dataset containing all bikeshare information for the city of Washington provided by Udacity. Note: This does not include the 'Gender' or 'Birth Year' data.

### Built with:
Python 3.6.6 - The language used to develop this.
pandas - One of the libraries used for this.
numpy - One of the libraries used for this.
time - One of the libraries used for this.

### Acknowledgements:
- xhlow - xhlow's repository helped with understanding the structure and details of certain functions.
- philribbens - philribben's repository also added to better understanding of the structure for this project.
- pandas docs - pandas documentation was immensely helpful in understanding the implemention of pandas methods used in this project.
- Udacity - Udacity's Data Analyst Nanodegree program and their instructors were extremely helpful while I was pursuing this project.
- Finally, I'd like to mention my college courses on Principles of Econometrics and Intermediary Econometrics for introducing me to data analysis and R programming. 
- The concepts - embodied in the pandas library (e.g. data frame) were very similar to the ones used while I was working on my R projects for college assignments.
