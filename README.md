# Movies-ETL
Module 8 Movies_ETL


## Project Overview & Challenge
On this module, Britta needs help to create an automated pripeline that takes in the new data, performs the appropriate transformation and loads the data into existing tables. 

ETL to collect, import and process data



For this analysis, we used the following breakdown:

    1. Write an ETL function to read three data files
    2. Extract and Transform the Wikipedia Data
    3. Extract and Transform the Kaggle Data
    4. Create the Movie Database


## Resources
    * Data Source:  wikipedia-movies.json, movies_metadata.csv, 
    * Software: Python 3.8.5, PostgresSQL pgAdmin4 Version 4.30,    
      Jupyter Notebook

## Results

### Write an ETL function to read three data files

From the Wikipedia JSON, the Kaggle metadata and MovieLens csv files created three separate DataFrames.

### Extract and Transform the Wikipedia data
Code refactoring the Wikipedia data so it can be merge with the Kaggle metadata removed the duplicates, formatted and grouped the data.
 
### Extract and Transform the Kaggle metadata and MovieLens
Code refactoring the Kaggle metada and MovieLens rating data then convert to transform data into separate DataFrames .

### Database Creation
Create and connect to the database then import data.
Load the data to a PostgreSQL Movie Database

## Summary
The ETL function created collects and cleans movie data from different sources (Wikipedia JSON and Kaggle and ratings csv files). It transforms and merges the data and loads it into two updatable PostgreSQL dataset tables ready to be used by the hackathon participants for their analysis.

