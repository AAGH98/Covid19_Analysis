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

<img width="435" alt="image" src="https://github.com/AAGH98/Covid19_Analysis/assets/141926743/5d94a3bd-dd4f-4089-95be-239814116d9e">



2. The data is selected that i will start with
   
<img width="569" alt="image" src="https://github.com/AAGH98/Covid19_Analysis/assets/141926743/e719c153-19ee-441a-9db5-e97916adfe30">


3. Total cases vs total deaths is compared

<img width="781" alt="image" src="https://github.com/AAGH98/Covid19_Analysis/assets/141926743/6e04a7aa-b42b-4ca4-8d1c-373f20b09d91">



4. Total cases vs population is compared to show the percentage of people who had covid


<img width="751" alt="image" src="https://github.com/AAGH98/Covid19_Analysis/assets/141926743/2be2f32f-efb1-4628-91a0-1681a5700a7d">



5. Countries with the highest covid count in comparison to their population


<img width="899" alt="image" src="https://github.com/AAGH98/Covid19_Analysis/assets/141926743/23356ac3-b69d-4378-aab0-a7b049a413f8">



6. Countries with the highest rate of covid deaths


<img width="511" alt="image" src="https://github.com/AAGH98/Covid19_Analysis/assets/141926743/a64bd16b-0305-44f6-bc26-ab18514d1f52">



7. On a global scale, the total number of cases, deaths and the percentage of deaths is queried


<img width="1129" alt="image" src="https://github.com/AAGH98/Covid19_Analysis/assets/141926743/ff78aca4-fbd4-4428-b456-9635c6b8a9a9">



8. The percentage of the population with atleast one vaccination is queried.

<img width="545" alt="image" src="https://github.com/AAGH98/Covid19_Analysis/assets/141926743/ca767417-93a8-46a3-835b-4692aa452218">




# Analysis

Multiple tables have been queried using SQL and they were visualised in Tableau.



<img width="997" alt="image" src="https://github.com/AAGH98/Covid19_Analysis/assets/141926743/bbc6e6f7-dd69-4424-ab1e-e912be84785d">

- Multiple charts are shown in the table above.
- Global numbers show the figures recieved from Jan 2020 to November 2023. The percentage of dying from covid-19 is 1%.
- Cyprus recorded the highest number of covid cases.
- In regards to continents, Europe had the highest percentage of covid deaths. 










