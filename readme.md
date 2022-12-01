# Weather Trend Exploration Project
The objective of this project is to explore and visualize the data trying to find any trend in the data that supports the idea that the world and the city of madrid have warmed over time and to see if there are any patterns or similarities between them.

## Datasets
The data was supplied by Udacity from a database, to interact with the database, you'll need to write a SQL query and export the temperature data for the world as well as for Madrid city to csv file (madrid_and_global_temp.csv). This dataset has a dimension of 264 rows by 4 columns that includes information about:  


* Original variables in madrid_and_global_temp.csv:  
    + year: year in which the temperature is taken             
    + city: It has just one value (Madrid)             
    + city_avg_temp: average temperature of the city   
    + global_avg_temp: average of the global  temperature (average global temperature (all countries included in the study)  


* Variables created to enrich the analysis:  
    + madrid_moving_avg: Madrid moving 10 days average temperature.  


We got another dataset form the database using SQL and we exported as csv file (number_countries.csv) that has 271 rows a two columns.  


* Original variables in number_countries.csv:
    + year: year in which countries were adding to the dataset 
    + number_countries: numbers the countries added.

## Summary of Findings
By plotting the annual temperature differences, we see that the differences change from positive to negative around zero over the years. In the case of Madrid, volatility is more constant over time than in the world as a whole. When analyzing the data we realized that in the first hundred years the volatility in global temperature was higher and from then on the data presented less volatility. And this was due to the increase in the number of countries over time in the database. We use the moving average in some charts with the idea of smoothing the data series.  


## Conclusion
The conclusions of the data exploration can be found at the end of the explore_weather_trends.ipynb notebook or explore_weather_trends.html.


