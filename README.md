# Rainfall-vs-ridership
## Summary

In this project, I attempted to explore the relationship between train ridership and monsoon seasonality in Singapore. This is done by first identifying the monsoon period in Singapore, and compare the change in train ridership during those periods. It was identified in the project that the monsoon seasons in Singapore typically range from November to December, and from May to August. This information was cross examined with the report from Meteorological Services Singapore regarding monsoon seasons. Ridership information was obtained from SBS transit, and it was discovered that there look to be an increase in ridership during the monsoon period. Further investigation is definitely required given the change in ridership could be affected by numerous other factors. 

## Problem Statement

I hope to provide insights on the relationship between monsoon seasonality and train ridership in Singapore. Such insights could provide inferential information for SBS Transit when it comes to resource management and maintenance of its high operational standard during monsoon seasons. 

## Workflow

### Data

There are 3 datasets included in the data folder for this project.
- rainfall-monthly-number-of-rain-days.csv: Monthly number of rain days from 1982 to 2022. A day is considered to have “rained” if the total rainfall for that day is 0.2mm or more.
- rainfall-monthly-total.csv: Monthly total rain recorded in mm(millimeters) from 1982 to 2022
- smrt_ridership.csv: Monthly average ridership from 2014 to 2023

### Data Cleaning
Monthly rainfall data is combined into one set of data. Added columns in respect to the "month" and "year" data for analysis later. Other than this I did not find any need to clean the rainfall data. On the ridership data, since the numerical values are stored as string and have "," in them, I needed to convert them into integer. No further cleaning was performed on the ridership data.

### Explotary
(More to come, stay tuned)
