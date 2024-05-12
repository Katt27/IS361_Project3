# IS380_Project3

# Tuberculosis Infection Rate Analysis

## Overview
This repository contains SQL scripts and related resources for analyzing tuberculosis (TB) infection rates by country and year. The analysis involves calculating the rate of TB cases per 100,000 people, allowing for comparisons across different regions and times.

## Contents

- **tb_population_analysis.sql**: SQL script that joins TB case data with population data to calculate infection rates. This script handles data from different years and ensures accurate calculations by considering possible NULL values in the case counts.

## Setup and Usage

### Prerequisites
- A SQL database management system (DBMS), such as MySQL.
- Access to a database where TB case data and population data are stored.
- Basic knowledge of SQL operations and how to run scripts in your DBMS.

### Database Setup
Ensure your database contains the following tables:
- **tb_cases**: Should contain columns for `country`, `year`, and `cases`.
- **population**: Should contain columns for `country`, `year`, and `population`.

If these tables do not exist or are not populated, you will need to create and fill them using the appropriate data.

### Running the SQL Script
1. Open your SQL client or access your database command line interface.
2. Load the `tb_population_analysis.sql` script.
3. Execute the script to perform the analysis. The script outputs data including the country, year, total TB cases, population, and calculated TB rate per 100,000 population.

### Exporting Data
- After running the script, export the results to a CSV file if you want to perform further analysis or create visualizations, for instance, using Excel or a BI tool.

## Contributing
Contributions to this project are welcome. Please ensure that you update tests as appropriate and maintain the integrity of the data.

## License
[MIT](https://choosealicense.com/licenses/mit/)

