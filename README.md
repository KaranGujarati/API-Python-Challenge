# Python-API-Challenge

This repository uses the [Open Weather Map API](https://openweathermap.org/api), and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

API interactions, Pandas, Matplotlibs, and a Python script was used to build a series of scatter plots to showcase trends of the following relationships:
  - Temperature (F) vs. Latitude
  - Humidity (%) vs. Latitude
  - Cloudiness (%) vs. Latitude
  - Wind Speed (mph) vs. Latitude

The final notebook have:

 - Randomly selected at least 500 unique (non-repeat) cities based on latitude and longitude
 - Performed a weather check on each of the cities using a series of successive API calls
 - Included a print log of each city as it's being processed with the city number and city name
 - Saved both a CSV of all data retrieved and png images for each scatter plot

 
Three observable trends based on the observable data are as follows:

 - The places with the latitude of 0 (equator), had the highest max temp, while going more north or south correlates with a drop in temperature

 - There is no correlation between latitude and cloudiness. However, different places at different latitudes can have the same cloudiness. The most notable percentages of cloudiness are as  follows: 0% (no clouds), 40%, 75%, and 100% (high clouds). There also looks to be a cloud system that spends the southern hemisphere at 90% cloud coverage on 2019/11/17

 - There was no correlation between latitude and humidity, or windspeeds. This suggests that these 2 factors are independent from each other