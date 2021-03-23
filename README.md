# ETL

The objective of this project is to extract data on European football. 

## Extract

Sources:
- https://www.kaggle.com/secareanualin/football-events in CSV format.
- https://www.kaggle.com/hugomathien/soccer in SQLite format.

## Transform

Data is cleaned using Pandas and SQL Alchemy. 

## Load

After all pandas dataframes are cleaned, they're uploaded as tables to PostgreSQL
