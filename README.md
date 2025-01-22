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
Creating new smaller data frames containing only part of the data
including statistics in these data frames


Presentation: https://docs.google.com/presentation/d/1GKCkAWXRDxgw6Yf5giWRLbMkxJzinMAXjBBc4AEhOJk/edit#slide=id.p