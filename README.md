# ETO5513 Collaborative and Reproducible Practices - Assignment 2

## Project Description 
Alcohol Consumption data sets from OurWorldInData.org to provide a report on alcohol consumption around the world and their effects 

### Jane's Section 
Using the Total Alcohol Consumption per Capita data set to find trends and patterns in the global alcohol usage over time. Identified the changes of total alcohol consumption by geographical regions from 2000 to 2018. Further analysed the underlying relationship between religion and total alcohol consumption in regions. This analysis provided valuable insights into consistently low alcohol usage locations were countries where Islam is the predominant practice. 

### Gloria's Section
In an attempt to further understand how much alcohol abuse impacts people's health and life, we investigated the death caused by alcohol use disorders directly (excluding suicide cases) per country/region from 2010-2019. "Entity", "Year", "Code" and "Death_alcohol_use_disorders" were selected for analysis and NA values were excluded in calculation. The geographical distribution and trend over the years were examined, which provides us insights into how we could better offer support.

### Tony's Section
While it is commonly assumed males are the primary consumers of alcohol, this report goes beyond geographical considerations and investigates the prevalence of alcohol disorders among both males and females across various income groups. The aim is to identify any variations and temporal trends in alcohol-related issues. To do this, the following variables were used: Entity, Year, Prevalence_alcohol_use_disorders_male amnd Prevalence_alcohol_use_disorders_female while filtering only the major regions and income groups under the variable Entity. 

### Naveed's Section

-The data set X has details on various countries, GDP Per Capita, population, household alcohol expense, road traffic deaths and crime attributed to alcohol consumption, disorders and deaths caused by alcohol consumption, average pure alcohol consumption per person for the time period 2000 to 2020.

-Since the raw data set was large, some of the functions used were the filter(), select() and arrange() functions to obtain the information required to construct both the linear regression and multiple linear regression models used and to carry out the required analysis.

***Variables***

The variables that may be used to investigate the research questions are:

-Entity, which shows the name for each country

-Year, which indicates the year

-GDP_per_capita, which is the income per person across countries and over time

- Alcohol_expenditure_rate_per_household, which is the percentage of the annual household expense spent on alcohol

- Death_alcohol_use_disorders, which is the percentage deaths from alcohol use disorders

- Total_alcohol_consumption_per_capita, which is the average annual amount of pure alcohol consumed per person

-to help answer question 1, a scatter plot and a linear regression model has been used to examine the relationship between alcohol consumption per person and income, outliers based on total alcohol consumption per person have been examined, some countries with both the highest and lowest GDP Per Capita and their corresponding alcohol consumption per capita values have been analyzed. 

-to investigate question 2, a multiple linear regression model has been used to examine the relationship between death, consumption, income and household alcohol expense. In addition, scatter plots of death vs consumption per capita, death vs GDP Per Capita, death vs household alcohol expense have been explored, the top 7 countries with the highest percentage deaths in alcohol use disorders have also been analyzed.


