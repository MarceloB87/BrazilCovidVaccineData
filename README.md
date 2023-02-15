# BrazilCovidVaccineData
Repository for data on vaccine coverage, deaths caused by Covid, and population size in Brazil
 <br> 
##  COVID vaccination coverage
* File: vac_br.csv
* Source: Raw Data available from SI-PNI (Brazilian National Immunization Program Information System: https://opendatasus.saude.gov.br/dataset/covid-19-vacinacao).
Data compilation and processing by Observatório COVID-19 BR (https://covid19br.github.io/), made available at: https://github.com/covid19br/dados-vacinas
* Details: Doses are labeled according to the individual's pseudo-anonymised ID hash, arranged by application date, and classified according to the order of application.
* Variables
1. **Month** <br> 
First day of the month following application date. <br> 
Example: All doses applied between 2021-06-01 and 2021-06-30 will be accounted in the coverage of 2021-07-01.

2. **Age** <br> 
less_than_60: individuals with less than 60 years old. <br> 
60yo_or_more; individuals with 60 years old or more. <br> 
 
3. **Dose** <br> 
D1: individuals who received only one dose <br> 
D2: individuals who received exactly two doses <br> 
D3: individuals who received three doses or more <br> 
 
4. **n** <br>
Cummulative number of individuals who received N doses

## COVID Deaths
* File: covid_deaths_br.csv
* Source: Raw data from SIVEP-Gripe (SARI EPIDEMIOLOGICAL SURVEILLANCE INFORMATION SYSTEM, https://opendatasus.saude.gov.br/dataset/notificacoes-de-sindrome-gripal-leve-2020).
Data compilation and processing by Observatório COVID-19 BR (https://covid19br.github.io/)

* Variables:
1. **Date** <br> 
First day of the month in which death occured. <br> 
Example: All deaths that occurred between 2021-06-01 and 2021-06-30 will be accounted in 2021-06-01.

2. **Age** <br> 
less_than_60: individuals with less than 60 years old.
60yo_or_more; individuals with 60 years old or more.

3. **n** <br> 
Number of deaths that occured at a specific month

## Population size
* File: population_size.csv
* Source: population estimates from IBGE (Brazilian Institute for Geography and Statistics), available at https://datasus.saude.gov.br/populacao-residente/.
* Variables
1. **Age** <br> 
< 60: individuals with less than 60 years old. <br> 
">=" 60: individuals with 60 years old or more.

2. **2020** <br> 
Population size estimated for 2020

3. **2021** <br> 
Population size estimated for 2021







