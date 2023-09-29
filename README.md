# Covid-19-Vaccination-Informatics
![Covid-19 Vaccination](https://github.com/KwadwoAgyemanAppiah/Covid-19-Vaccination-Informatics/blob/main/coronavirus%20vaccination.jpg)

## Introduction
  This is a Power BI project on COVID-19 vaccination analysis of some datasets I came across online and was really fascinated by the richness of the data. This project aims to analyze and derive insights to answer crucial questions about the whole vaccination exercise that was carried on globally.
  
  **_Disclaimer_**: I can't lay a claim on how factual this dataset is, but just a dummy dataset to demonstrate the capabilities of Power BI

  ## Problem statement
 1. which countries had the highest number of people vaccinated?
 2. which country had the highest number of people fully vaccinated?
 3.	Which countries received the highest vaccination supplies?
 4. What is the vaccination-supply rate per country?
 5.	Which institution supplied the most vaccines?

## Skills/ Concept Demonstrated:

The following Power BI features were incorporated
- Data cleaning
- DAX calculated measures
- Page navigation
- Tooltips
- Filters
- Modelling
- Map

## Data Transformation/ Cleaning
Data was efficiently cleaned and transformed with the power query editor of Power BI. (a screenshot of the applied steps) some of the applied steps included: 
 - Remove columns that were not relevant to the study.
 - Remove columns that were not relevant to the study.
 - Reordered columns
 - Removed duplicates
 - Some of the Data types were changed from text to whole number

![Data cleaning step](https://github.com/KwadwoAgyemanAppiah/Covid-19-Vaccination-Informatics/blob/main/data%20cleaning%20step2.png)

## Data Modelling
I created four Dimensional tables ‘DimCountry’, ‘DimDate’, ‘DimVaccine’, and ‘DimVaccine2’ from the Fact table ‘Covid Country Vaccination’ thereby allowing Power BI to automatically connect the related tables resulting in a snowflake model. 
![](https://github.com/KwadwoAgyemanAppiah/Covid-19-Vaccination-Informatics/blob/main/snokeflake%20model.png)

- Created a new column in the” DimVaccine” dimensional table to include various vaccine names  
- Created a separate table "DimVaccine2" to create a snowflake model relationship with the DimVaccine" table.
- 	Used DAX concept to create calculated columns and measures.

## Data Visualization 
This report comprises of two(2) pages 
1. Total Vaccinations and vaccine utilization rate
2. Type of vaccine supplied by various institutions
   
![](https://github.com/KwadwoAgyemanAppiah/Covid-19-Vaccination-Informatics/blob/main/Dashboard.png) 

![](https://github.com/KwadwoAgyemanAppiah/Covid-19-Vaccination-Informatics/blob/main/second%20dashboard.png) 
## Analysis
![](https://github.com/KwadwoAgyemanAppiah/Covid-19-Vaccination-Informatics/blob/main/Total%20vaccination.png)  

In terms of the Covid-19 vaccination exercise, China had the highest number of its citizens vaccinated. It was followed by India and the United States. These same countries led when it comes to those who received all their full shots of vaccinations.

![](https://github.com/KwadwoAgyemanAppiah/Covid-19-Vaccination-Informatics/blob/main/vaccine%20supplies.png)   

China, India, and the United States again receive the highest supply of vaccines worldwide

![](https://github.com/KwadwoAgyemanAppiah/Covid-19-Vaccination-Informatics/blob/main/utilization%20rate.png)  

In terms of countries that utilized most of the Covid vaccine supplied, Guinea Bissa, South Sudan, Central Africa Republic, and Gambia had the highest vaccine utilization rate

![](https://github.com/KwadwoAgyemanAppiah/Covid-19-Vaccination-Informatics/blob/main/source%20name.png)  

The National Health Commission, the Government of India, and the Center for Disease Control supplied most of the vaccines to various countries.




## Conclusion and Recommendation   

In conclusion, we noticed that the global utilization rate of the COVID-19 vaccine supplied to countries was only 39.09%. There were low vaccinations as compared to the total vaccines supplied.
### Recommendation  
In future projects, we may add the population numbers of each country to the dataset in order to find the vaccination rate per population of each country.



