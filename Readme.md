# CMPE255_FinalProject

## Olympic Medal Prediction

## Objective of the Project:

The Olympic Games are the world’s biggest multi-sport, athletic competitions with participation
among 200 countries. The main objective of our project is to explore at how several aspects of
the participant determine the effective impact on medal count in the Olympic games. This model
will also help in predicting a country's success at the Olympic games while illustrating how the
Olympic games have evolved over the years with how women's participation , representation
and performance have improved over the years, as well as the involvement of different nations,
sports, and events.

# Dataset 
We have gathered the Dataset from Kaggle https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results
We have two datasets that were used in the project, the first "athlete_events.csv" with 271116 rows and 15 columns and the NOC_regions dataset that Each row corresponds to an individual athlete competing in an individual Olympic event (athlete-events). 

The columns are:
ID - Unique number for each athlete
Name - Athlete's name
Sex - M or F
Age - Integer
Height - In centimeters
Weight - In kilograms
Team - Team name
NOC - National Olympic Committee 3-letter code
Games - Year and season
Year - Integer
Season - Summer or Winter
City - Host city
Sport - Sport
Event - Event
Medal - Gold, Silver, Bronze, or NA

## Approach 

Steps followed are:

1. Collection of Data
2. Cleaning and Preprocessing the data
3. Exploratory Data Analysis
4. Feature Selection
5. Training and testing on multiple models to find the best accurate prediction.

## Teammates: 
Pranav Chellagurki (015221310) <br/>
Shail Brijeshkumar Patel (016114839) <br/>
Vishwa Tejendra Pernapati (016701009) <br/>
Rakesh Reddy Sanagala (016698734) <br/>

Models used:

1. Logistic Regression
2. K nearest neighbor 
3. Decision Tree
4. Random Forgest Regression
5. XG Boost