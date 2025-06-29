# 2024 Iowa Liquor Sales Analysis
### Table of Contents
- [Overview](#Overview)
  - [Summary](#Summary)
  - [Data Source](#Data-Source)
  - [Tools](#Tools)
  - [Data Dictionary](#Data-Dictionary)
  - [Objectives](#Objectives)
  - [References](#References)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Descriptive Statistics](#Descriptive-Statistics)
- [Data Analysis](#data-analysis)
  - [RFM Analysis](#RFM-Analysis)
  - [Per Capita Sales Analysis](#Per-Capita-Sales-Analysis)
  - [Product Performance Analysis](#Product-Performance-Analysis)
  - [Quarterly Market Basket Analysis](#Quarterly-Market-Basket-Analysis)
- [Results](#results)
- [License](#license)


## Overview

### Summary
This data analysis project aims to analyze and draw insights into the Pennsylvanian mail ballot application requests made for the 2020 General Election. Requests that were recorded by the Pennsylvanian Department of State. By doing so, we seek to get a better understanding of the trends brought from these requests, and how they are affected by different aspects of the people making them and where they live. 

### Objectives 
- Find whether party registration of the requester has any affect on how long it takes for their mail ballot to be received
- Find whether the county, congressional or state district that the person who is requesting a mail in ballot affects how long it takes for their request to be processed
- Find whether age and the requester's generation has an affect on whether a person chooses to make their request online, overseas, by mail or on paper
- Find whether a specific party made requests for mail ballots more than others did  
### Tools
- DB Browser (SQLite) - Data Cleaning, Exploration, Analysis and Manipulation
  - Utilized to process the data and enhance it so it is in a better format for visualization and further analysis.
- Excel - Data Preparation
  - Utitlized to prepare the data in supplementary tables to be used for analyzing the dataset.
- Tableau - Data Visualization
  - Utilized to create visualizations and interactive dashboards to help others have a firmer understanding of the data.
- Python - Data Visualization and Analysis
  - Utilized to create more complex visualizations that Tableau is less able to create, and to perform statistical and complex data analyses.
### References
- 
## Data Source
2020 General Election Mail Ballot Requests: The primary dataset being analyzed can be found in the '.csv' file. It contains data on the mail ballot requester's county residence, their party designation, date of birth, the type of mail ballot their request is for, the day it is submitted, processed, along with when the ballot is sent and received, and which legislative districts they reside in. These results allow for an analysis that can focus on the age of the voter requesting a mail ballot, their party, the time it takes for it to be processed, and their geographical location.

The dataset can be found in Pennsylvania's Open Data Portal, [here](https://data.pa.gov/Government-Efficiency-Citizen-Engagement/2020-General-Election-Mail-Ballot-Requests-Departm/mcba-yywm/about_data).

County, Congressional, State Senate, State House Supplementary: A group of supplementary tables I made for getting further insights on how geographical results from the 2020 General Election could have an effect on the amount of mail ballot requests each party made. 


## Exploratory Data Analysis


## Data Analysis

### Quarterly Market Basket Analysis


#### Quarter 1

##### Results

###### Most Frequent Pairs


###### Association Rules
![Q1 Association Rules](https://github.com/user-attachments/assets/affb436a-f513-4fd1-a88a-2ab53451cbd2)

#### Quarter 2
##### Results
###### Most Frequent Pairs
![Q2 Frequent Pairs](https://github.com/user-attachments/assets/488177bc-3693-48ea-aa9d-fd3e9530a351)


###### Association Rules
![Q2 Association Rules](https://github.com/user-attachments/assets/242f8c38-2d05-48cf-8329-d35d85a0eab4)




#### Quarter 3
##### Results

###### Most Frequent Pairs
![Quarter 3 Most Frequent Pairs](https://github.com/user-attachments/assets/0252acc6-0cf4-4607-ba4a-5df56e028cc1)



###### Association Rules
![Quarter 3 3D Scatterplot of Association Rules](https://github.com/user-attachments/assets/a8ab1af1-f534-41c7-bc73-bc7559068b3c)


#### Quarter 4
##### Results
###### Most Frequent Pairs
![Q4 Frequent Pairs](https://github.com/user-attachments/assets/16a8deca-8784-4430-add6-f4dd2952a84c)


###### Association Rules
![Q4 Association Rules](https://github.com/user-attachments/assets/d04eee27-9872-45f1-b087-bf443f1404ff)


