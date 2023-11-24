## Citi Bike Rental Management
This repository contains code to complete Codecademy's Bike Rental Data Management project that involves the exploration, cleaning, and merging of Citi bike ridership and NOAA weather data to produce a PostgreSQL database with analytics ready views.

### Scenario
 I'm  a Data Engineer for a bike rental company and have been tasked with creating a database to help the analysts understand the effects of weather on bike rentals. I've been provided with a year of bike rental data by the company and will source the weather data from the government.

--- 
 
 ### Project Objectives
 Create a relational database with analytics-ready views connecting Citi Bike and weather datasets. This involves:
 - Inspecting and cleaning both datasets
 - Developing a relational database schema
 - Implementing the database in PostgreSQL and inserting the dataset
 - Develop flexible analytics-ready views on top of the RDB


 ---
 ### Directory Structure
 * /data
    * `newark_airport_2016.csv` : weather data from Newark airport
    * `JC-2016XX-citibike-tripdata.csv`: twelve files each containing one month of Citi Bike data frorm Jersey City. The `xx` represents dual-digit representation of each month of the year

* /data dictionaries
    * `citibike.pdf`: details on Citi Bike data from Citi Bike's website
    * `weather.pdf`: details on the weather data from NOAA's website

* `writeup.md`:
* `analyticsviews.sql`:
* `tables.sql`:
*