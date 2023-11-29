# Data-Exploration-In-SQL
An Exploratory data analysis (EDA) on COVID-19 dataset using Microsoft SQL Server Management System.
INTRODUCTION

Corona virus (COVID-19) is an infectious disease caused by the SARS-CoV-2 virus. The first known case was discovered in Wuhan, China in December 2019, which eventually spread worldwide resulting in the COVID-19 pandemic. In this project I carried out an exploratory data analysis (EDA) on COVID-19 dataset using Microsoft SQL Server Management Studio.

ABOUT THE DATASET

The dataset was sourced from https://ourworldindata.org/covid-deaths . It contains records of all cases, deaths and vaccinations between January 2020 and April 2021.

AIM

The aim of this project is to explore and derive meaningful insights on COVID-19 cases, COVID deaths and COVID vaccinations around the world from the COVID-19 dataset using SQL queries.

DATA PREPARATION

The dataset was first loaded into Microsoft excel where I separated the data into two different excel files. One for information about Covid deaths and the other contains information about Covid Vaccination. I created a new database on Microsoft SQL Server Management Studio, and both excel files were then imported as a table to this database. I named them as Codeath (for Covid Deaths) and Covac (Covid Vaccinations).

PROBLEM STATEMENTS

Using SSMS, I was able to run some queries on the dataset and get answers to some questions like

1. Total number of COVID-19 cases and deaths around the world

2. Rate at which an infected person in each country would die

3. Percentage of the total population in each country infected with the virus

4. Country with the highest infection rate compared to its total population

5. Country with the highest number of death cases

6. Top 5 African countries with the highest number of deaths from COVID-19

7. The total number of deaths in each continent

8. Rate at which people die per day from the virus

9. Which day was the highest number of deaths recorded?

10. Number on people vaccinated in each country per day?

11. Cumulative frequency of new vaccinations

12. Cumulative frequency of vaccinated people

All between January 2020 and April 2021.
