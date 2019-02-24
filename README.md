# Snow-and-Temperature-Data-Analysis
A jupyter notebook analyzing open snow and temperature data from the Finnish meterological institute. 

A descriptive blog post is available here: https://janierkkilae.github.io/Snow-and-Temperature-Data-Analysis/ 

## Data
The data used was from the Finnish Institute of Meterology database - https://ilmatieteenlaitos.fi/havaintojen-lataus#!/. While there is not API, one can download data by weather station, some of which date back a long time ago. I chose 10 weather stations across the country that have historic data.  

## Cleaning
Most weather stations have some missing entries especially for snow depth observations (possibly due to holidays or summer period). Also certain weather stations were discontinued. To create comparable data, null entries were forward- and backwardfilled, the end date set to 2000 and the remaining nulls deleted. 

## Insights
Three variables were investigated like temperature, snow depths and extreme events. Mathematical observations were accompanied by matplotlib subplots. 
