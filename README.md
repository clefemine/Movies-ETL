# Movies-ETL

## Challenge Summary

Perform ETL on Wikipedia and Kaggle data to create a merged data set that can be used on a database. 

## Resources

- Data Source: wikipedia.movies.json, ratings.csv, movies_metadata.csv
- Software: Python 3.7.6, Visual Studio Code, 1.45.1

## Summary/Results

After gathering the data, filtering/cleaning, and exporting the database contains a thorough table that include both the data provided from Kaggle and Wikipedia. Based on the database table we can begin to make valid assumptions. First, we can assume that any analysis done using the data provide such as descriptive statistics or other that the results will have an accurate results because the data has been well sorted. Second, although there was data dropped due to missing fields, repeated data, or incorrect formatting this did not make any significant changes to the table which has a few million movies. Third, with more movies being released regularly the pipeline should be run regularly to ensure that it is up to date. Fourth, assuming that ratings can change overtime this should also be incentive to update the pipeline regularly. Last, we can make the assumption that more filtering and cleaning can be added so that less items are dropped and when new items are added they have a higher chance to fit the criteria. 
