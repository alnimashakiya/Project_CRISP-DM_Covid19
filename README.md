# Project_CRISP-DM_Covid19

# **BUSINESS UNDERSTANDING**

In facing the COVID-19 pandemic, a deep understanding of data is a very valuable asset for various parties, including the government, health institutions and the general public. Data analysis on the Indonesian COVID-19 dataset aims to provide better insight into this pandemic, as well as assist in making effective decisions in dealing with the public health crisis. The COVID-19 dataset in Indonesia is arranged based on time series, national level and provincial level. , also accompanied by demographic data from that location/region. This dataset is a compilation of various open data sources, such as the official government website of the COVID-19 Task Force, the Central Statistics Agency, and the InaCOVID-19 Hub.

By utilizing this dataset, several important things that can be explored are:
1. On what date was the highest number of new COVID 19 cases reported in one day?
2. Which province had the highest number of new cases per day?
3. Which island had the highest number of COVID 19 cases per day?
4. Which province had the highest number of new cases per day? highest daily healing?
5. How Correlates Between New Deaths and New Recovery?

# **DATA UNDERSTANDING**

- COVID-19 data in Indonesia from March 1 2020 - September 16 2022. The dataset consists of 31,822 rows and 38 columns.
- Data source : https://www.kaggle.com/datasets/hendratno/covid19-indonesia
- Data dictionary :
1. 'Date' : Date reported
2. 'Location ISO Code' : Location code based on ISO standard
3. 'Location' : Location name
4. 'New Cases' : Daily positive cases
5. 'New Deaths' : Daily death cases
6. 'New Daily Recovered' : Daily cure cases
7. 'New Active Cases': Daily active cases
8. 'Total Cases': The accumulative number of positive cases up to the associated time
9. 'Total Deaths': The cumulative number of deaths up to the associated time
10. ‘Total Recovered': The cumulative number of cured cases up to the associated time
11. 'Total Active Cases': The cumulative number of active cases up to the associated time
12. 'Location Level': Regional or national location level
13. ‘City or Regency': Name of city or region
14. 'Province' : Name of the province of location
15. 'Country' : Country name of location
16. 'Island' : Name of the main island location
17. 'Time Zone' : Time zone location
18. 'Special Status' : Special status of location
19. 'Total Regencies' : The number of districts within the associated location
20. 'Total Cities' : Number of cities within the associated location
21. 'Total Districts' : Number of subdistricts within the corresponding location
22. 'Total Urban Village' : The number of villages within the associated location
23. 'Total Rural Villages' : Number of villages within the associated location
24. 'Area (km  )' : Area of location in square kilometers
25. 'Population' : The number of populations within a related location
26. 'Population Density' : The population density in a related location (formula = Population / Area)
27. 'Longitude' : Longitude of location
28. 'Latitude' : The latitude of the location
29. 'New Cases per Million' : Formula = (New Cases / Population) x 1,000,000
30. 'Total Cases per Million' : Formula = (Total Cases / Population) x 1,000,000
31. 'Total Deaths per Million' : Formula = (Total Deaths / Population) x 1,000,000
32. 'Case Fatality Rate' : Formula = (Total Deaths / Total Cases) x 100
33. 'Case Recovered Rate' : Formula = (Total Recovered / Total Cases) x 100
34. 'Growth Factor of New Cases': Less than 1 means decreased, 1 means none change, more than 1 means increase (formula = Today New Cases / Yesterday New Cases)
35. 'Growth Factor of New Deaths': Less than 1 means decreased, 1 means none change, more than 1 means increase (formula = Today New Deaths / Yesterday New Deaths)

# DATA CLEANSING
