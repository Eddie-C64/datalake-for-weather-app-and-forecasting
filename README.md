# Datalake for Weather App and Forecasting
Creating app, database, and forecasting system all using python

## Dependencies
Install the necessary python libraries listed below:
- numpy
- pandas
- bokeh
- dask
- apache-dataflow
- statsmodels
- scikit-learn
- facebook-prophet

## Data Resources:
#### Data sources
https://www.weather.gov

https://www.drought.gov/drought/data-maps-tools

#### Actual climdiv data
ftp://ftp.ncdc.noaa.gov/pub/data/cirs/climdiv/
## Schema
This is the database design schema:

https://dbdiagram.io/d/5d700b0083427516dc0b5763

## AWS SetUp
Set up two S3 bucket to store all the data and another to place the wrangled data.

- The data wrangling uses Apache Spark to do ETL on the data.
- You will need to set up the AWS credentials 

## Access Database for EDA
- Once the data is all organized you'd like to visualize the data using Bokeh
- Statmodels and Scikit-learn for analysis

## Forecasting Magic
- Using Statsmodel and Facebook-Prophet to build a model