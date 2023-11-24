# Bike Rental Data Management

This repository contains code to complete Codecademy's Bike Rental Data Management Portfolio project.

### Project Overview
Project to create a relational database with analytics-ready views connecting Citi Bike and weather datasets. The project involves:

- Inspecting and cleaning both datasets
- Developing a relational database structure
- Implementing the database in PostgreSQL and inserting the dataset
- Developing flexible analytics-ready views on top of the relational database

### Directory Structure
* /data
    * `newark_airport_2016.csv`: weather data from Newark Airport
    * `JC-2016XX-citibike-tripdata.csv`: tweleve files each containing each month's Citi bike data from Jersey City for 2016.

* /data dictionaries
    * `citibike.pdf`: details on the Citi bike data files from Citi Bike's website
    * `weather.pdf`: details on the weather from NOAA's website

- `bike rental.ipynb` : prepare the data for inserting into the database
- `tables.sql` : SQL queries to create the database tables
- `analytics views.sql` : SQL queries to create the database views
- `ER Schema.pdf` : entity relationship diagram for the database
