## NYPD Arrest Data Analysis and Visualization Project

Overview
This project analyzes NYPD arrest data through a complete data pipeline, from initial data acquisition to final visualization. The pipeline includes data profiling, cleaning, dimensional modeling, data warehousing in Snowflake, and visualization with Power BI.

Project Architecture

End-to-End Process:

Raw NYPD arrest data acquisition
Data profiling and cleaning with Alteryx
Dimensional model design
Stage tables creation and loading to Snowflake
Fact and dimension tables creation using Azure Data Factory
Final data warehouse in Snowflake
Interactive visualizations in Power BI

Key Components
1. Data Acquisition and Profiling

Source: NYPD arrest dataset
Initial data profiling to understand structure, quality issues, and patterns
Documentation of data quality findings

2. Data Cleaning (Alteryx)

Standardization of values and formats
Handling of missing values
Deduplication of records
Data type conversions
Validation of business rules

3. Dimensional Modeling

Star schema design with:

Fact tables for arrest events
Dimension tables for time, location, demographics, offense types



4. Data Pipeline
Stage tables in Snowflake for initial data landing
Azure Data Factory data flows for ETL processes
Orchestrated loading of dimension and fact tables

5. Data Warehouse (Snowflake)
Optimized storage with appropriate clustering keys
Table structures designed for analytical queries
Documentation of schema and relationships

6. Visualization (Power BI)
Interactive dashboards showing:

Arrest trends over time
Geographic distribution
Demographic analysis
Offense type analysis
Predective Analysis


## Technologies Used
Data Cleaning: Alteryx
Data Integration: Azure Data Factory
Data Warehouse: Snowflake
Visualization: Power BI

