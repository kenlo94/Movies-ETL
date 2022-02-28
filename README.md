# Movies-ETL

### Overview of the Analysis

The purpose of this analysis was to:

1) Create an automated pipeline that takes in new data, perfroms the appropriate transformations, and loads the data into existing tables
2) Refactor the code from this module to create a function that takes in three files - Wikipedia data, Kaggle metadata, and the MovieLens rating data
3) Add the data to a PostgreSQL database

### Results

There are four deliverables for this project:

1) Deliverable 1: Write an ETL Function to Read Three Data Files
2) Deliverable 2: Extract and Transform the Wikipedia Data 
3) Deliverable 3: Extract and Transform the Kaggle Data
4) Deliverable 4: Create the Movie Database

### Summary

1. Deliverable 4 gave us the most issues when trying to refactor the code.
2. There is a discrepancy in the 'movies' table. It is stated that there should be 6,052 rows and I got 6,051 rows.
3. However, I was able to get my response for the 'ratings' table to match up at 26,024,289 rows.
4. Overall, this was a difficult challenge.