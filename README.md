
# Covid Data Analysis
This data was scraped from woldometers.info on 2022-05-14 by Joseph Assaker.

225 countries are represented in this data.

All of countries have records dating from 2020-2-15 until 2022-05-14 (820 days per country). That's with the exception of China, which has records dating from 2020-1-22 until 2022-05-14 (844 days per country), and Palau which has records dating from 2021-8-25 until 2022-05-14 (263 days per country)

There are two files in the dataset

1. **Summary Data Columns Description:**

* country: designates the Country in which the the row's data was observed.
* continent: designates the Continent of the observed country.
* total_confirmed: designates the total number of confirmed cases in the observed country.
* total_deaths: designates the total number of confirmed deaths in the observed country.
* total_recovered: designates the total number of confirmed recoveries in the observed country.
* active_cases: designates the number of active cases in the observed country.
* serious_or_critical: designates the estimated number of cases in serious or critical conditions in the observed country.
* total_cases_per_1m_population: designates the number of total cases per 1 million population in the observed country.
* total_deaths_per_1m_population: designates the number of total deaths per 1 million population in the observed country.
* total_tests: designates the number of total tests done in the observed country.
* total_tests_per_1m_population: designates the number of total test done per 1 million population in the observed country.
* population: designates the population count in the observed country.

2. **Daily Data Columns Description:**

* date: designates the date of observation of the row's data in YYYY-MM-DD format.
* country: designates the Country in which the the row's data was observed.
* cumulative_total_cases: designates the cumulative number of confirmed cases as of the row's date, for the row's country.
* daily_new_cases: designates the daily new number of confirmed cases on the row's date, for the row's country.
* active_cases: designates the number of active cases (i.e., confirmed cases that still didn't recover nor die) on the row's date, for the row's country.
* cumulative_total_deaths: designates the cumulative number of confirmed deaths as of the row's date, for the row's country.
* daily_new_deaths: designates the daily new number of confirmed deaths on the row's date, for the row's country.


