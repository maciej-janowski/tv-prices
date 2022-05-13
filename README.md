# Extraction of data for predicting model (with saving into database) - TV sets

## Assumption of the project
I came up with an idea to extract data regarding tv sets from one shop selling electronic devices and load it to database (with possibility to using extracted data in some price prediting model)

## Overview
* 1. Looping over all pages for tv sets and saving extracted, raw data into pandas dataframe
* 2. Adjusting the data so that it can be easily used in models (i.e. adjusting values to floats/integers or extracting data in a way that can be further used in column transformers)
* 3. Loading the data to database 

## Technologies
* Python (BeautifulSoup, pandas, re, SQLAlchemy)