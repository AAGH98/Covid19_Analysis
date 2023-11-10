# Covid19_Analysis
Analysis of World Wide COVID-19 data, regarding cases and death rates.


Dataset: https://ourworldindata.org/covid-deaths

Data Visualisation: 


# Introduction

Coronavirus known as SARS-CoV-2 is the source of the extremely contagious respiratory disease known as COVID-19. When the virus was first discovered in Wuhan, China, towards the end of 2019, it quickly spread over the world and began to infect millions of individuals. Senior citizens and those with existing medical disorders are more susceptible to serious illnesses or fatalities from COVID-19, which can cause symptoms ranging from minor respiratory problems to severe pneumonia.

When discussing COVID-19, death rates relate to the percentage of confirmed cases that end in fatalities. Comprehending the mortality rates is essential for evaluating the gravity of the illness, directing public health measures, and putting plans in place to lessen the virus's effects. The effectiveness and accessibility of healthcare, population health in general, and demographics all have an impact on death rates. Analysing and tracking death rates is essential to directing international efforts to control and contain the COVID-19 epidemic.



### Analysis Process 

I will use the steps of the data analysis process: ask, prepare, process, analyse, share, and act to provide intresting insights regarding the Covid-19 data


# Ask

# Prepare

##### Data Source: 
To analyse and identify patterns, Our World In Data's public dataset of historical Covid-19 dat from Jan 2020 to November 2023 will be analysed.

##### Data Structure:
The corresponding column names are: iso_code, continent, location, date, population, total_cases, new_cases, new_cases_smoothed, total_deaths, new_deaths, new_deaths_smoothed, total_deaths_per_million, new_deaths_per_million, new_deaths_smoothed_per_million, total_tests, new_tests, total_vaccinations, people_vaccinated, people_fully_vaccinated, new_vaccinations, median_age, aged_65_older, aged_70_older, gdp_per_capita, extreme_poverty, cardiovasc_death_rate, diabetes_prevalence, female_smokers, male_smokers,, handwashing_facilities, hospital_beds_per_thousand, life_expectancy, human_development_index, excess_mortality_cumulative_absolute, excess_mortality_cumulative, excess_mortality, excess_mortalit. 

#### Process
Bigquery is used to perform SQL queries due to the size of the data set.



# Data Exploration

1. The total number of rows are checked in the table "covid_data" by using the query below.

![image](https://github.com/AAGH98/Covid19_Analysis/assets/141926743/b2d9886d-7d64-40c8-87a9-a980718ead3c)


2. The data is selected that i will start with
   
![image](https://github.com/AAGH98/Covid19_Analysis/assets/141926743/984e6e52-adee-4f0a-82e2-2102b558e6df)

3. Total cases vs total deaths is compared

![image](https://github.com/AAGH98/Covid19_Analysis/assets/141926743/9fffa8cc-2f3d-43e9-b4c4-58e740886f4c)


4. Total cases vs population is compared to show the percentage of people who had covid


![image](https://github.com/AAGH98/Covid19_Analysis/assets/141926743/53187712-cb83-425b-987a-132cb66f95b6)


5. Countries with the highest covid count in comparison to their population


![image](https://github.com/AAGH98/Covid19_Analysis/assets/141926743/1008116a-e693-4a3c-9b63-5d8dc7ae29f4)


6. Countries with the highest rate of covid deaths


![image](https://github.com/AAGH98/Covid19_Analysis/assets/141926743/df30b702-2a3d-442f-9308-9838fd91e6b0)


7. On a global scale, the total number of cases, deaths and the percentage of deaths is queried


![image](https://github.com/AAGH98/Covid19_Analysis/assets/141926743/cb5c3f16-3dce-40ee-8c72-04e10731496e)


