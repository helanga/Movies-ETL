# Movies-ETL

This project was an introduction ot the EXTRACT, TRANSFORM, and LOAD process. Movie data from Wikipedia, Kaggle, and aggregated ratings was used to assemble a movie database.

As mentioned, the ETL process was used to extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning rows and formating datatypes, preforming joins, and loading the cleaned dataset into a POSTGRESQL database

Resources
Extract - ETL_function_test.ipynb

Transform - ETL_clean_wiki_movies.ipynb & ETL_clean_kaggle_data.ipynb

Load - ETL_create_database.ipynb

Languages: Python, SQL

Tools: Jupyter Notebook, JSON, Pandas, NumPy, sqlalchemy, psycopg2

Data Source(s): wikipedia.movies.json, movies_metadata.csv, ratings.csv (note: due to large file size, I am unable to push ratings.csv to repo).
