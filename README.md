# Movies-ETL

## Overview

Amazing Prime wants a database that can be updated on a daily basis. This project created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.  Code was refactored to create one function from three files.

## Results

- An ETL function was written to read in the three data files
  - Function converted Wikipedia JSON file to a Pandas DataFrame
  - Function converted Kaggle metadata file to a Pandas DataFrame
  - Function converted MovieLens rating data file to a Pandas DataFrame
- TV shows filtered out
  - Cleaned Wikipedia DataFrame created
- Extraction and transformation of Kaggle metadata
  - Kaggle metadata cleaned
  - Wikipedia and Kaggle DataFrames merged
  - Ratings count cleaned
- SQL database updated with current data in movies and ratings tables
