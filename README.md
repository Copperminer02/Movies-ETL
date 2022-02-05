# Movies-ETL

## Summary

  Created pandas scripts to import, parse and load data from Wikipedia, Kaggle, and Movie lens.  Data was merged to create tables for movie Hackathon.  Two tables were created and stored in postgresSQ: movies (holds all movie data 6052 entries) and ratings (holds movie id and viewer ratings).
  
  ![image](https://user-images.githubusercontent.com/91850824/152662249-e1e2d2b9-5090-48d2-b7b5-8712ac36ce1b.png)
  
  ![image](https://user-images.githubusercontent.com/91850824/152662258-a587c02e-8908-430c-82ce-1ae55ca497e5.png)

## Outputs

  1. **ETL_function_test.ipynb** - tests and confirms function to load raw data into pandas
  2. **ETL_clean_wiki_movies.ipynb** - loads code in ETL_function_test.ipynb and adds functions to clean and parse Wikipedia Movie JSON
  3. **ETL_clean_Kaggle_movies.ipynb** - Adds to ETL_clean_wiki_movies.ipynb and cleans Kaggle data, Ratings Data and merges data into Dataframes: movies_df and movies_with_ratings
  4. **ETL_create_database.ipynb** - Creates access and loads movies_df and ratings to postgresSQL Tables.
  5. **Resources/movies_query.png** - screeen shot of query and output confirminig 6052 rows 
  6. **Resources/ratings_query.png** - screeen shot of query and output confirminig 26,024,289 rows 
