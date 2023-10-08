# Space-Mission-Dashboard-Using-Power-BI
Power BI Project

---

![Intro](https://github.com/soma-ramesh/Space-Mission-Dashboard-Using-Power-BI/assets/143477687/3a824e60-20bb-4584-b81c-903c657160cc)

----

## Introduction
This is a Power BI project on All Sapce Missions from 1957 to August 2022 called "SPACE MISSION ANALYSIS". 
This project is to analyze and derive the key insights, which are very interesting for Space Lovers.

**_Disclaimer_**: The Dataset, which is used for this project is public domain licenced dataset provided by Maven Analytics.
(https://mavenanalytics.io/data-playground?dataStructure=5wfxyeVf1etbP4TXdyPdG1&search=Space%20missions)

## Problem Statement:

1. How have rocket launches trended across time? Has mission success rate increased?

2. Which countries have had the most successful space missions? Has it always been that way?

3. Which rocket has been used for the most space missions? Is it still active?

------

## Skills Used:
The following Power BI features were incorporated.
1. Data Extraction
2. Data Transformation
3. Data Loading
4. Dax
5. Date Table (New Table)
6. Measures
7. Data Model
8. Report
9. Slicers
10. Dashboard
11. Bookmarks

----

## DAX 

Total Missions = COUNT(space_missions[Mission])

Total Price = SUM(space_missions[Price])

Total Rockets = DISTINCTCOUNT((space_missions[Rocket]))

Successful Missions = CALCULATE(COUNT(space_missions[Mission]), (space_missions[Mission Status] = "Success"))

Faiure Missions = CALCULATE(COUNT(space_missions[Mission]), (space_missions[Mission Status]= "Failure"))

---
SPACE MISSION ANALYSIS Dashboard

https://github.com/soma-ramesh/Space-Mission-Dashboard-Using-Power-BI/blob/main/Space-Missions.pbix


-----



Key Insights:
1. Out of 4630 Missions attempted,4162 Missions succeed with 90% of success rate.
2. Russia has the most successful missions, ie. 1323 missions and it is followed by USA with 1298 missions.
3. Max. missions done by "RVSN USSR" (Total of 1777) and followed by "CASC" (Total of 338) companies.
4. Only in the year of 2021, there are 157 Space Missions launched and 143 Missions are successful.
5. Cosmos-3M(Retired) Rocket was used for most space mission(446).
6. NASA spent nearly 76.28k millions of US dollars for all their space missions.



    
