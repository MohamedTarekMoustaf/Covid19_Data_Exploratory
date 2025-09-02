# Covid19_Data_Exploratory
COVID-19 Data Exploration (SQL Project)

This project contains exploratory SQL queries analyzing COVID-19 data using datasets on cases, deaths, and vaccinations. The goal is to uncover insights such as infection rates, death percentages, and vaccination progress across different countries and continents.

📂 Project Structure

Covid19_Data_Exploratory.sql
Main SQL script containing exploratory queries and transformations.

🔍 Key Analyses

The script includes queries for:

Total Cases vs. Total Deaths → likelihood of dying if infected with COVID-19.

Cases vs. Population → infection percentage of the population.

Death Rates per Population → highest death percentages by country and continent.

Vaccination Progress → accumulated vaccinations compared to population.

Data Cleaning → converting text fields to integers for proper numeric calculations.

Advanced SQL Techniques:

CTEs (Common Table Expressions)

Temporary Tables

Views

🗄️ Datasets Used

coviddeaths → COVID-19 cases and deaths by country and date.

covidvaccinations → vaccination progress by country and date.

🛠️ SQL Features Demonstrated

Aggregations (SUM, MAX)

Window functions (OVER (PARTITION BY ...))

Table joins

Data cleaning and type conversions

View and temporary table creation

🚀 How to Use

Clone this repository:

git clone https://github.com/yourusername/covid19-sql-exploration.git


Import the datasets into your SQL environment (e.g., MySQL, PostgreSQL).

Run the queries in Covid19_Data_Exploratory.sql sequentially.

📊 Insights You Can Gain

Which countries had the highest infection rates?

Which countries/continents had the highest death percentages?

How vaccination rollouts impacted infection and death rates.

⚠️ Disclaimer

This project is for educational and exploratory purposes only. The results depend on the dataset source and may not reflect the latest COVID-19 statistics.
