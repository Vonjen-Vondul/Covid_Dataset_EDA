# COVID-19 Data Exploration using SQL

This repository contains a collection of SQL queries used to explore and analyze COVID-19 data. The queries cover a range of data manipulation, calculations, and visualizations, with the goal of gaining insights into the pandemic's impact on different regions and the progress of vaccination efforts.

## Table of Contents

- [Overview](#overview)
- [Data Sources](#data-sources)
- [Queries](#queries)
- [Data Preprocessing](#data-preprocessing)
- [Visualizations](#visualizations)
- [Contributing](#contributing)
- [License](#license)

## Overview

The SQL queries provided in this repository are designed to work with COVID-19 data from various sources. They utilize SQL features such as joins, CTEs (Common Table Expressions), temp tables, and window functions to perform data exploration and analysis. The queries cover topics such as infection rates, vaccination progress, and population insights.

## Data Sources

The data used in these queries is sourced from the `ProjectPortfolio` database. Two main tables are utilized:

- `CovidDeaths`: This table contains information on COVID-19 cases and deaths by location and date.
- `CovidVaccinations`: This table provides data on COVID-19 vaccinations by location and date.

## Queries

The queries are categorized into different sections, each with a specific focus. Here's a summary of the sections:

- **Data Exploration**: Initial queries to display and sort COVID-19 data.
- **Infection Analysis**: Queries to calculate and analyze infection rates, likelihood of death, and population impact.
- **Continent Analysis**: Queries to explore data at the continent level, including death counts per population.
- **Global Analysis**: Queries for global statistics and trends.
- **Vaccination Analysis**: Queries related to vaccination data, including rolling vaccination statistics.

## Data Preprocessing

Data preprocessing is an essential step in these queries. It involves handling missing values, converting data types, and creating views for visualization. The preprocessing ensures that the data is ready for analysis and reporting.

## Visualizations

To support data visualization, this repository includes SQL queries for creating views. The views store calculated metrics, such as the percentage of the population vaccinated. You can use these views to build charts and graphs using your preferred data visualization tools.

## Contributing

Contributions are welcome! If you have additional SQL queries, improvements, or suggestions for data visualization, please feel free to open an issue or create a pull request. Your contributions can help enhance the COVID-19 data exploration process.

Feel free to explore the SQL queries and adapt them to your own data exploration needs. If you have any questions or need assistance, please don't hesitate to reach out.

Stay safe and informed!

