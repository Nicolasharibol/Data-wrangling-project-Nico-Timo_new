# Data-wrangling-project-Nico-Timo
Title: Cancer cases and incidences in Chile & Germany 1990 - 2015
Introduction: Analysis of cancer incidences based on total number of cancer cases and population counts in Chile & Germany 1990 - 2015  
Dataset used (.csv file): Cancer Deaths by Country and Type (1990-2016)
https://www.kaggle.com/datasets/antimoni/cancer-deaths-by-country-and-type-1990-2016
Strength: complete total numbers of cancer cases, differentiation of cancer type possible
Weakness: no population counts included, thus relative analyses are not possible
Country Population Counts over time every 5 years (API):
https://www.worldometers.info/world-population/chile-population/
https://www.worldometers.info/world-population/germany-population/
Strength: complete total numbers of inhabitants per country 
Weakness: only quinquennial, but not annually

Importing pandas & numpy libraries
Importing csv data table

Hypotheses: 
1. Total cancer incidences are increasing in Chile & Germany between 1990 and 2015.
2. The stomach cancer incidence is decreasing in the Chilean population between 1990 - 2015, while liver cancer incidence is increasing.
3. The breast cancer incidence is decreasing in the German population between 1990 - 2015, while the liver cancer incidence is increasing.

API web scraping of population counts lists
Create data frames based on the population counts lists

Data Cleaning of cancer cases dataframe and population counts lists:
search and remove null values
search and remove duplicates
change object classifications (str --> int, float --> int)
column name renaming

Merging the data frames for cancer counts and population counts
Creating new smaller data frames containing only part of the data, dropping columns
including statistics in these data frames: calculating total numbers, incidences (%), increases (differences)

importing seaborn and mathplot libraries
create graphs of incidences and cancer case numbers over time to answer the hypotheses

Conclusions:
Chile: Moderate increment in total cancer incidence between 1990 - 2005.
Chile: Notorious increment in total cancer cases from 2000 to 2015.
Germany: little increase in total cancer incidence between 1990 - 2005
Germany: apparent increase in total cancer incidence between 2005 - 2015

Chile: 
liver
stomach

Germany:
Liver cancer case numbers (#) and incidence (%) in the German population are increasing from 0.0047% to 0.0098% (double!) between 1990 - 2015.
Breast cancer case numbers (#) and incidence (%) in the German population are not increasing, but rather stagnating between 1990 - 2015.

Presentation: https://docs.google.com/presentation/d/1GKCkAWXRDxgw6Yf5giWRLbMkxJzinMAXjBBc4AEhOJk/edit#slide=id.p