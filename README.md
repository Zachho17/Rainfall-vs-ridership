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

### Explotary Data Analysis
As I explored the data, I identified that Singapore on average has about 14 days rainy day and 177mm total rainfall a month. Interestingly, there looks to be a month that only had one rainy day, and even a month that has total rainfall of merely 0.2mm. As I explored further, we can conclude that Februrary tends to have the lowest amount of rainfall, while the later part of the year tends to have higher rainfall. Expanding on this idea on number of rainfall in the months, I identified that most of the rainy days are concentrated in the month of September to November, while the drier period look to be concetnrated around January to March. 

This finding had been further supported by the report from Meteorological Services Singapore regading the monsoon seasonality in Singapore. 

## Business Case

I incorporated ridership data from SMRT with the rainfall seasonality analysis. It is worth noting that the ridership data would have been directly impacted by population growth in Singapore. In order to reduce the impact from the natural growth of population, I focused on the percentage change of the ridership data rather than the absolute change. 

However, due to covid, a particular period looks to have more fluctuation than the other. I decided to isolate the data before covid for cleaner analysis. I then identified that the month from July to December look to have a relatively higher ridership compared to the other month. This coincide with the months identified earlier where we see relatively larger rainfall. 

## Conclusion and suggestion

From the above analysis, though a relatively naive approach, we could conclude that durnig monsoon seasons, we could expect to see an increase in train ridership. This could due to the following reasons:

- Those who own cars might refrain from driving due to heavier traffic
- Some might not like to drive under rain condition, as they like their cars to stay clean
- Commutors who tend to take bus might change to train due to most train stations being sheltered

With the increase in ridership, it could put higher operational pressure in each station. SMRT can prevent any disruptions in service if appropriate planning and resource allocation were done beforehand. This project could act as a reference for SMRT to better plan for rainy seasons in Singapore, if they have not already done so. In order to maintain service quality, I would recommend an increase in train maintenance frequency and increase in staffing at the station during the monsoon seasons, particularly in the month of July and December where a consistent increase in ridership can be observed.

It might be worth noting that the increase in ridership could be due to numerous other factors, such as school holiday, year end holiday, festive seasons and more. By comparing two datasets, it is still insufficient to conclude that the increase in ridership is due to the monsoon seasonality. Therefore, a more robust and comprehensive studies would still be needed to decipher the reason for a change in ridership behaviour throughout the year. 
