# New York Citibke Analysis using Tableau

## Background

Congratulations on your new job! As the new lead analyst for the New York Citi BikeLinks to an external site. program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to an external site. webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.


## Instructions

Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.

The following are questions you may wish to answer. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!

How many trips have been recorded in total during the chosen period?

By what percentage has total ridership grown?

How have the proportions of short-term customers and annual subscribers changed?

What are the peak hours when bikes are used during the summer months?

What are the peak hours when bikes are used during the winter months?

Today, what are the top 10 stations in the city for starting a journey? Based on data, why do you hypothesize these are the top locations?

Today, what are the top 10 stations in the city for ending a journey? Based on data, why?

Today, what are the bottom 10 stations in the city for starting a journey? Based on data, why?

Today, what are the bottom 10 stations in the city for ending a journey? Based on data, why?

How does the average trip duration change by the type of user? (This may be under "User Type" or "member_casual" depending on the period the data is from).

What is the average distance in miles for a bike trip?

Which bikes (by ID) are most likely due for repair or inspection in the timespan?

How variable is the utilization by bike ID?

Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.

Create one of the following visualizations for city officials:

Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.

Create your final presentation:

Create a Tableau story that brings together the visualizations, requested maps, and dashboards.

Ensure your presentation is professional, logical, and visually appealing.



## Data source

The project required us, due to the large size of each file, to select between 1 and 3 months, each consisting of a CSV file that can be found in the following link: [https://citibikenyc.com/system-data]. For the purposes of this excercise, I decided to work on data from July 2023.

The CSV I used contains 1048575 records with the following variables:

* Ride ID
* Rideable type
* Started at
* Ended at
* Start station name
* Start station ID
* End station name
* End station ID
* Start latitude
* Start longitude
* End latitude
* End Longitude
* Member or casual ride


## The New York Citibike Challenge

I created a total of 5 dashboards and a portrait with the title of the project created with Midjourney AI. In this project you'll be able to see how rides behave on each different station throughout New York, the time each type of user uses the bikes more and how this translates to the weekends, and lastly, identify what are the most important and least important stations in the city.



### 1. Title

<img width="990" alt="Dashboard 6" src="https://github.com/fmorenog/tableau-challenge/assets/135471756/3398ecdb-cd46-4a0d-be07-384705a22a3b">



### 2. Total rides daily

<img width="905" alt="dashboard 1" src="https://github.com/fmorenog/tableau-challenge/assets/135471756/ba3cb429-20de-47a0-a1f9-bc148cc9ccf8">


<img width="990" alt="dashboard 2" src="https://github.com/fmorenog/tableau-challenge/assets/135471756/f41ce52f-d720-4d61-b9db-09fc21ece0f9">


