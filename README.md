# Investigate Lung Cancer data 
This project was completed as part of Udacity's Data Analyst Nanodegree certification.

## Overview
The project explores data provided by Gapminder to recognize the patterns. The project analyses the lung cancer data per gender, per country income and geographical location. The considered data of lung cancer rate is normalized over 100,000 citizens of specific country.

The following data sets are considered:

- Lung cancer, death per 100,000 women;
- Lung cancer, death per 100,000 men; 
- Lung cancer, new cases per 100,000 women;
- Lung cancer, new cases per 100,000 men;
- Income per person (GDP/capia, PPP$ inflation-adjusted); 
- Country-continent data

## Getting Started
- Clone or download the repository.

## Prerequisites
- Python
- Pandas
- Numpy
- Matplotlib

## Key findings
The data used in this project is limited to 13 years only (1993-2016). That is not sufficient to observe any clear cancer rate patterns over years and make conclusions of increase/decrease of cancer in specific country and gender.

However the following is concluded:
- Female and male death range range lies in different interval, for female it's in interval [2 - 50] and for male in interval [4.5 - 106]. Furthermore, countries with minimum death rate differs per gender;
- For both genders African countries has the lowest death rate due to lung cancer and Europe shows the highest death rate;
-Correlation coefficient and t-test p-value shows strong correlation between new and death cases due to lung cancer for women;
- The highest female death rate due to lung cancer is observed in North Korea and the lowest in Djibouti;
- The highest male death rate due to lung cancer is observed in North Korea and Hungary, and lowest in Kenya;
- Correlation coefficient and t-test p-value don't show correlation between death rate due to lung cancer and income
