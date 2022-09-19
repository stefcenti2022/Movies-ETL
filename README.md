# Extract Transform and Load Move Data into a PostgreSQL DB

## Overview
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Process
The following steps were taken for this project:
- An ETL Function was developed and tested to read 3 datafiles in various formats to create CSV files to load into our DB.
- Extract and Transform Wikipedia movie data.
- Extract and Transform Kaggle movie data.
- Extract and Transform Kaggle ratings data.
- Create a movie datbase with tables loaded from Wikipedia and Kaggle.

## Supporting Files/Folders
The top level files and folders are as follows:
### Data
This folder contains the CSV and other supporting text files that were used to populate the movie database.

### Initial Data
This folder contains the files from Kaggel and Wikipedia that were initially parsed to create the CSV files in the Data folder.

## Issues Encountered
The following issues with their resolutions are described in this section.

## Future Enhancements
Some future ehanancements suggested by the team will go here.
