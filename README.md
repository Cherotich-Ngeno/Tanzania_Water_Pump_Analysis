![image](https://user-images.githubusercontent.com/85990318/181903849-f2eaac99-e661-4894-849a-589d652bab1a.png)


# Tanzania Water Pump Analysis

#### Data Science Project, May 2022

#### By **Nelly Ng’eno**

## Introduction

This analysis contains an analysis of Tanzanian water pump data in order to provide the Tanzania Government a tool with which to determine water pump functionality and information on how to improve pump maintenance efficiency. This analysis will focus to determining which factors needs attention to increase efficiency of the water pumps. The Tanzanian Government can use this analysis to improve prediction and identification of which pumps are non functional or may need repair, therefore increasing access to potable water across Tanzania.

## Business Problem

The Tanzania Government is trying to improve their water pump maintenance operations in order to ensure that clean, potable water is available to communities across Tanzania. In order to accomplish this, the Government wants to be able to better predict which pumps will fail, and to better identify pumps that need repair and what factors need to be considered in the future. This will help in improving maintenance efficiency and water access.

## Data

The data set contains 41 variables describing pump functionality status (the target variable), pump geographic location, what kind of pump is operating, when it was installed, how it is managed, etc. It includes data on 59,400 individual pumps recorded from 2011-2013.

## Method

Data cleaning-replacing of  missing values, changing of some values to integers and strings
Exploratory Data analysis techniques
Modelling-Use of Decision trees, Random forest and Knearest neighbours.

## Results

Random forest was the best model for the analysis  with an accuracy of 0.78 and f1 scores of 0.41, 0.80, and 0.83.Longitude, latitude, gps height, population, quantity, and construction year were the most important features in this model.

## Visualization

# Population vs the status of the pump

![image](https://user-images.githubusercontent.com/85990318/181903391-1cfb23a5-210d-4fb8-8e2e-8b6b5e9ec982.png)
The figure above shows how pumps in areas of lower population may be more likely to be needing repair or non functional

# Water quantity vs the status of the pump

![image](https://user-images.githubusercontent.com/85990318/181903461-fd402928-dcd0-4913-859a-ace79bfe580b.png)
The figure above shows how as water quantity decreases, pumps are more likely to be non functional

# Location vs the status of the pump

![image](https://user-images.githubusercontent.com/85990318/181903523-b3e4c9e5-3ef5-4535-8e18-77959c9abe8b.png)

The figure above shows that pumps in lower altitude areas may be more likely to be non functional

# Construction year vs the status of the pump

![image](https://user-images.githubusercontent.com/85990318/181903716-1b8c06ab-e7ff-4892-8c80-36e5c5745dea.png)

The figure above shows how older pumps are more likely to be nonfunctional or needing repair

## CONCLUSIONS & RECOMMENDATIONS

Based on this random forest classifier model two, I would provide four recommendations to the Tanzania Government as they look to improve pump status prediction and maintenance efficiency:

Construction Year: Construction Year was one of the most important features in the random forest classifier. Analysis showed that older pumps may be more likely to be nonfunctional or needing repair. The government should focus resources on modernizing older pumps.

Location: Longitude, latitude, and gps height were some of the most important features in the random forest classifier. Based on the analysis, pumps in lower altitude areas may be more likely to need repair or be non functional. The government should focus resources on lower altitude pumps.

Quantity: Quantity was one of the most important features in the random forest classifier. Analysis showed that pumps with lower quantities of water were more likely to be non functional or needing repair. The government should focus resources on pumps with low quantities of water.

Population: Population was one of the most important features in the random forest classifier. Analysis showed that pumps in lower population areas may be more likely to be non functional or needing repairs. The government should focus resources on low population areas, as they may not be receiving enough.

## Technologies Used
Jupyter notebook

### License
Copyright (c) 2022
