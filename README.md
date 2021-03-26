# ETL

The objective of this project is to extract data on European football. 

## Extract

Sources:
- https://www.kaggle.com/secareanualin/football-events in CSV format.
- https://www.kaggle.com/hugomathien/soccer in SQLite format.

## Transform

Data is cleaned using Pandas and SQL Alchemy. Two tables are used as a common link between both data sets.

## Load

After all pandas dataframes are cleaned, they're uploaded as tables to PostgreSQL
