# Life-Expectency-Prediction

Life Expectancy Prediction
This project aims to predict life expectancy based on various health, economic, and demographic factors. The dataset used for this project contains indicators from multiple countries spanning the years 2000 to 2015. Below is a detailed explanation of each variable in the dataset.

Variable Descriptions
country (Nominal)
The country in which the indicators are from (e.g., United States of America, Congo).

year (Ordinal)
The calendar year the indicators are from, ranging from 2000 to 2015.

status (Nominal)
Indicates whether a country is considered 'Developing' or 'Developed' by WHO standards.

life_expectancy (Ratio)
The life expectancy of people in years for a particular country and year.

adult_mortality (Ratio)
The adult mortality rate per 1000 population. This represents the number of people dying between the ages of 15 and 60 per 1000 population. For example, a rate of 263 means that out of 1000 individuals, 263 will die between the ages of 15 and 60.

infant_deaths (Ratio)
The number of infant deaths per 1000 population.

alcohol (Ratio)
A country's alcohol consumption rate measured as liters of pure alcohol consumption per capita.

percentage_expenditure (Ratio)
Expenditure on health as a percentage of Gross Domestic Product (GDP).

hepatitis_b (Ratio)
The number of 1-year-olds with Hepatitis B immunization over all 1-year-olds in the population.

measles (Ratio)
The number of reported measles cases per 1000 population.

bmi (Interval/Ordinal)
The average Body Mass Index (BMI) of a country's total population.

under-five_deaths (Ratio)
The number of deaths of children under the age of five per 1000 population.

polio (Ratio)
The number of 1-year-olds with Polio immunization over the number of all 1-year-olds in the population.

total_expenditure (Ratio)
Government expenditure on health as a percentage of total government expenditure.

diphtheria (Ratio)
The Diphtheria tetanus toxoid and pertussis (DTP3) immunization rate of 1-year-olds.

hiv/aids (Ratio)
The number of deaths per 1000 live births caused by HIV/AIDS for children under five years old.

gdp (Ratio)
Gross Domestic Product per capita.

population (Ratio)
The population of a country.

thinness_1-19_years (Ratio)
The rate of thinness among people aged 10-19 (Note: variable should be renamed to thinness_10-19_years to more accurately represent the variable).

thinness_5-9_years (Ratio)
The rate of thinness among people aged 5-9.

income_composition_of_resources (Ratio)
The Human Development Index in terms of income composition of resources, ranging from 0 to 1.

schooling (Ratio)
The average number of years of schooling of a population. ICOR (Income Composition of Resources) measures how effectively a country utilizes its resources.




Project Goals
The primary goal of this project is to develop a predictive model that can accurately forecast life expectancy based on the provided variables. By understanding the relationship between life expectancy and various factors such as healthcare expenditure, immunization rates, and economic indicators, we aim to provide insights that can inform policy decisions and improve public health outcomes.
