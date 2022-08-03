# Movies-ETL

##Overview of the analysis: The purpose of the new analysis is well defined
An exercise in performing an Extract, Transform, Load data from disparate sources using Python. 

### The project included extracting a large data set from Kaggle, then transforming the data into a usable dataset and narrowed in scope for the hack-a-thon, the DataFrames were loaded into PostgresSQL.
Clean and transform data using Pandas, using regular expressions to parse data and to transform text into numbers.


##Resources
Software: Python 3.7.9, Anaconda 4.9.2, Jupyter Notebooks 6.1.4, PostgreSQL 4.28
Libraries: Pandas, SQLAlchemy, NumPy
Troubleshooting: Deleting Cache, Using Git LFS
Files: Wikipedia Json, Movie Database Metadata, and MovieLens Ratings

##Results
Ultimately, we were able to clean, merge the datasets and export the two new tables into PostgreSQL by using Python. The final results created a movies table with 6,052 rows. A 17% reduction from the original of 7,311 and a ratings table with 26,024,289 rows.
![ratings](https://user-images.githubusercontent.com/106544424/182723711-05da85e5-2c19-4241-a640-2e37d28f3b25.png)

 
##Summary:
A JSON file,a Wkikpedia file and a Kaggle files were extracted, then transformed, and joined. 
A movies and ratings file were loaded into a database for the hack-a-thon event. 
There were 6052 rows in the movies file, and 26024289 rows in the ratings data.
