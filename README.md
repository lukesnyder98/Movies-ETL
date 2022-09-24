# Movies ETL
 
The purpose of this project was to clean, transform, and merge movie data from Wikipedia and Kaggle, and then load it into a database.

In ETL_function_test.ipynb, a function was created that forms three separate Pandas DataFrames for the Wikipedia data, Kaggle metadata, and MovieLens rating data.

In ETL_clean_wiki_movies.ipynb and ETL_clean_kaggle_data.ipynb, the TV shows were filtered out of the Wikipedia and Kaggle DataFrames, respectively, and new functions were created that perform cleaning of the remaining data.

In ETL_create_database.ipynb, a SQL database was created to hold 'movies' and 'ratings' tables, which use the cleaned movie data and a CSV file of movie ratings from MovieLens, respectively.