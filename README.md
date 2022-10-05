# Movies-ETL


## Overview

This project was an introduction ot the EXTRACT, TRANSFORM, and LOAD process. Movie data from Wikipedia, Kaggle, and aggregated ratings was used to assemble a movie database.

As mentioned, the ETL process was used to extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning rows and formating datatypes, preforming joins, and loading the cleaned dataset into a POSTGRESQL database

## Resources

Extract - ETL_function_test.ipynb

Transform - ETL_clean_wiki_movies.ipynb & ETL_clean_kaggle_data.ipynb

Load - ETL_create_database.ipynb

Languages: Python, SQL

Tools: Jupyter Notebook, JSON, Pandas, NumPy, sqlalchemy, psycopg2

Data Source(s): wikipedia.movies.json, movies_metadata.csv, ratings.csv (note: due to large file size, I am unable to push ratings.csv to repo).

## Process

Create an ETL pipeline using Jupyter Notebooks and PostgreSQL from raw data to SQL database.

Extract: read data from multiple sources using Python. Data sourced from:

Wikipedia: (format: .json, file size: 6.2MB) 7,311 thousand movie titles that include information about the movies, budgets, box office returns, cast/crew, production and distribution.
Kaggle: - 2 files (format: .csv)
a metadata file from The Movie Database containing movie details with 45.5 thousand entries. (File size: 34.4MB)
a dataset from MovieLens containing over 26 million movie ratings/review. (File size: 709.6MB)
Transform: Clean and structure data using Pandas and regular expressions (RegEx) to achieve desired form. (i.e. using RegEx to parse data and transform text into numbers.

Deleting bad data (corrupted or missing), removing duplicate rows, and consolidating columns.
Using RegEx to parse data and transform text into numbers.
Load: Export transformed data into a database.
