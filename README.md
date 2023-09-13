# Mass Shootings in USA (1982-2020) - Exploratory Analysis

Analysis made by Andra Maraciuc

## View this notebook in Jupyter nbviewer:
- <b> Click here to view the project:</b> https://nbviewer.jupyter.org/github/andramarac/us-mass-shootings/blob/master/Mass%20Shootings%20US%20Mother%20Jones%20Analysis.ipynb


## About this dataset

This analysis is based on data on US Mass Shootings provided by Mother Jones and it covers an in-depth look at mass shootings cases from 1982 to 2020 (February).

How Mother Jones defines mass shootings:

"Our research focused on <b>indiscriminate rampages in public places resulting in four or more victims killed by the attacker</b>. We exclude shootings stemming from more conventionally motivated crimes such as armed robbery or gang violence. (Or in which the perpetrators have not been identified.)"<br>
<br>
Source: https://www.motherjones.com/politics/2012/07/mass-shootings-map/ 

#### Dataset used (where to download):

- US Mass Shootings, 1982-2020: Data From Mother Jones’ Investigation (download link): https://www.motherjones.com/politics/2012/12/mass-shootings-mother-jones-full-data/

### What includes (after cleanup):

- <b>case</b>: the name of the shooting event
- <b>date</b>: date of the shooting
- <b>summary</b>: short description of the shooting
- <b>fatalities</b>: the number of people who have died <i>(doesn't include the attacker)</i>
- <b>injured</b>: the number of people who have been injured <i>(doesn't include the attacker)</i>
- <b>total_victims</b>: total number of cassualties (fatalities and injured together)
- <b>shooting_area</b>: the area where the incident happened (school, workplace, market etc) 
- <b>age</b>: age of the shooter
- <b>prior_signs_mental_health_issues</b>: information on if the perpator had mental health issues
- <b>weapons_obtained_legally</b>: shows if the shooter obtained the weapons legally or not
- <b>weapon_type</b>: type of weapon used in shooting
- <b>weapon_details</b>: details about the weapon
- <b>race</b>: the race of the shooter
- <b>gender</b>: the gender of the shooter
- <b>latitude</b>: latitude coordonates of the attack
- <b>longitude</b>: longitude coordonates of the attack
- <b>type</b>: type of shooting (mass or spree)
- <b>year</b>: year of the shooting
- <b>state</b>: full state name where the shooting happened
- <b>state_code</b>: two letter state code
- <b>city</b>: the city where the shooting took place

## Research Questions to Answer

- Are mass shootings on the rise? 
- What state/city had the most victims from mass shootings?
- What states have the highest number of mass shootings?
- What was the year with most mass shootings?
- What were the deadliest shootings in US?
- Are most mass killers males or females?
- Were the weapons used in shootings obtained legally?
- What is the age of the youngest / oldest shooter?
- What is the race of the shooters?
- How many school shootings have been since 1982?

### Rough Breakdown of Tasks

#### 1. Data Preparation and Cleaning
Load the dataset, clean the dataset, deal with missing values, drop columns, change data types, add new relevant columns.
#### 2. Data Exploration and Visualization
Analyze and explore the data to get answers to our research questions. Make visualizations (bar graphs, line graphs, pie charts, waffle charts, geo maps, histograms) of our data findings that will help us get a visual idea of patterns and trends.

***
