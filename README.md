# Nepal Database Project SQLite

This project focuses on analyzing earthquake data from Nepal. The dataset used in this project is sourced from Open Source Nepal. The goal of this project is to extract insights and answer questions related to household demographics, building structures, building damages, and geographical information.

## Dataset Overview
The dataset consists of four tables:

**household_demographics**:Contains information about household demographics, including household ID, gender of household head, age of household head, caste/ethnicity of household, education level of household head, average monthly income, household size, and presence of a bank account in the household.

**building_structure**:Contains information about building structures, such as building ID, age of the building, actual condition post-earthquake, number of floors post-earthquake, number of floors pre-earthquake, type of foundation used, ground floor type, height of the building post-earthquake, height of the building pre-earthquake, land surface condition, type of construction used in other floors, building plan configuration, plinth area, position of the building, roof type, and superstructure type.

**building_damage**:Contains information about building damages, including building ID, nature of damage assessment, proportion of damage due to beam failure, cladding/glazing damage, column failure, corner separation, delamination failure, diagonal cracking, foundational damage, gable failure, in-plane failure, infill/partition failure, out-of-plane failure, parapet damage, roof damage, staircase damage, geotechnical risks, repair status, and the proposed technical solution.

**id_map**:Contains mapping information for building IDs, district IDs, household IDs, and municipality IDs.


## SQL Queries and Insights
This project uses SQL queries, including subqueries, Common Table Expressions (CTEs), and window functions, to analyze the dataset and derive insights. Some of the insights and questions answered include:

1. Average household size and average monthly income by education level of the household head.
2. Distribution of buildings by the number of floors and their condition post-earthquake.
3. The percentage of buildings with severe damage in each district.
4. Average age of buildings for each district, considering only buildings with severe damage.

These queries provide a starting point for exploring the dataset and gaining insights into various aspects of household demographics and building structures and damages.


## Tools Used
**SQLite**:Used as the database management system to store and query the dataset.

## Usage
1. The dataset used in this project is sourced from [Open Source Nepal](https://www.opensource.gov.np/data/).
2. Import the dataset into an SQLite database.
3. Run the SQL queries provided in the project to retrieve specific information and answer questions.
4. Modify or create new SQL queries to explore different relationships and derive further insights.

## Conclusion
This project demonstrates the analysis of earthquake data in Nepal using SQL queries. By combining information from multiple tables, it was possible to gain insights into household demographics, building structures, building damages, and geographical information. The provided SQL queries serve as a foundation for further analysis and exploration of the dataset.








