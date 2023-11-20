# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goals for this project are to build up a dataset examining the usage of the bike share program in Chicago Illinois (Divvy), and to see the relationship between that program and public transit, specifically the CTA's L system. This will be done by pulling usage data from the City Bike API before and during morning and evening rush-hour periods.

## Process
### Query City Bike API
### Match bike station locations to proximity to CTA stations via Four Square and Yelp
### Join the data, sort and evalute obvious links
### Apply statistical models to check for correlations.

## Results
The initial data retrieved does not provide any conclusive evidence of a relationship between Chicago Transit Authority stations and bike share stations or usage

## Challenges 
While the APIs for Four Square and City Bikes are rather easy to use, the data retrieved was inconsistent. At times, calls made in relatively short periods would produce different results.
In the case of City Bikes, it seemed that the function of stations reporting data would breakdown at times, resulting in nulls or totally absent data. 

Similarly, Four Square would seem to provide different information for the same latitude and longitude on different days. 
Whether these issues were encountered due to the frequency of queries or being flagged deliberately due to the same cannot be determined at this time.

Also, Yelp simply did not track informatoin about the locations I was interested in.

## Future Goals
(what would you do if you had more time?)
