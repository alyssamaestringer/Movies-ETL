# Movies-ETL

## Overview
In this project we performed an ETL process, extract, transform, load, to work through a large set of movie data for Amazing Prime. 

Because we had so many different data sets, we had to inpect and clean the data via Jupyter notebook. I refactored code to create on efunciton that takes in the three files, Wikipedia data, Kaggle metadata and the MovieLens rating data. I then performed the ETL process by adding the data to a PostgreSQL database. 

## Issues
I did run into a few issues while performing ETL. Because we were looking through such large data sets, I decided to put ratings.csv and the Wikipedia JSON file in the gitignore to save storage and speed up the upload process to Github. 

