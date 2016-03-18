# Additional data available for WFP hackaton

I mark with a :+1: the data that I believe is the most promising.

## World Bank
http://datatopics.worldbank.org/consumption/home 

Data on household consumption of goods in different sectors (Food / Beverage / Health / Clothing / etc), by country and subregions (Rural/Urban)

Unfortunately limited to 2010 only.

## FAO :+1:
http://faostat3.fao.org/browse/E/*/E 

Many datasets on food prices, food security, livestock, etc

Preliminary exploration here:
https://github.com/mattiaf/WFP/blob/master/OtherData/FAOStat/FAO.ipynb

More details on the datasets:

_Food prices_ 

Monthly prices: not enough available data.

Year by year data: 1997 to 2014, number of NaNs depends on country.

_Food security_  :+1:

Yearly data on Average protein supply, Prevalence of anaemia, Percentage of adults who are underweight, etc.

Depending on category, most recent data between 2011 and 2013

_Livestock_ :+1:

Yearly data on number of different animals.

Depending on category, most recent data between 2011 and 2013


## OECD / 1 
http://www.oecd.org/dac/stats/idsonline.htm

Data on international aid. :+1:

I query amount of dollars received per recipient country from http://stats.oecd.org/qwids/

Prelimiary exploration at https://github.com/mattiaf/WFP/blob/master/OtherData/OECD/OECD.ipynb
You can see which countries got more aid and when. Potentially total aid can be broken down in categories (Dev. Food Aid/Food Security Ass. and Agriculture the most relevant)


## OECD / 2
https://data.oecd.org/api/

*to be done*

## EFSA
http://www.efsa.europa.eu/en/datexfoodcdb/datexfooddb

A working link is http://www.efsa.europa.eu/en/food-consumption/comprehensive-database
Data on consumption of food in EU countries. Interesting but not too relevant to developing countries if we don't have the same data there.

## USDA  :+1:
http://www.ers.usda.gov/data-products.aspx 

A lot of data from the US dept of agricolture, clearly mostly US based.

What I do find potentially very interesting for hunger studies are the projections of growth in terms of population and GDP for different countries

A bit of exploration here: https://github.com/mattiaf/WFP/blob/master/OtherData/USDA/USDA.ipynb

## NL Overheid
https://www.rijksoverheid.nl/opendata/ontwikkelingssamenwerking 

*to be done*
