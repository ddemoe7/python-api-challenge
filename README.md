# python-api-challenge
Python API Exercise - What's the Weather Like?
<i>A two part assignment.</i>

## WeatherPy
Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator.

### Requirements
Create a series of scatter plots to showcase the following:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

### Results
![Lat_vs_temp](https://user-images.githubusercontent.com/22499952/116168127-c1839800-a6cf-11eb-9717-fe6abde97073.png)

![Lat_vs_humidity](https://user-images.githubusercontent.com/22499952/116168143-c9dbd300-a6cf-11eb-9a7b-fadeaaa587f6.png)

![Lat_vs_cloudiness](https://user-images.githubusercontent.com/22499952/116168134-c47e8880-a6cf-11eb-96ee-da9494510c19.png)

![Lat_vs_windspeed](https://user-images.githubusercontent.com/22499952/116168155-cf391d80-a6cf-11eb-94d8-30289e4abeac.png)

Run linear regression on each relationship. Separate the plots into Northern Hemisphere and Southern Hemisphere.
* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

### Results
![NorthernHem_Temp_vs_Lat](https://user-images.githubusercontent.com/22499952/116168483-7ae26d80-a6d0-11eb-9f13-7cf00cb85ecc.png)
![SouthernHem_Temp_vs_Lat](https://user-images.githubusercontent.com/22499952/116168501-89c92000-a6d0-11eb-9b04-65a80cc658db.png)

![NorthernHem_Humidity_vs_Lat](https://user-images.githubusercontent.com/22499952/116168507-8e8dd400-a6d0-11eb-9306-db6e532a2e92.png)
![SouthernHem_Humidity_vs_lat](https://user-images.githubusercontent.com/22499952/116168511-90f02e00-a6d0-11eb-809d-42f56102d882.png)

![NorthernHem_Cloudiness_vs_Lat](https://user-images.githubusercontent.com/22499952/116168521-96e60f00-a6d0-11eb-9466-0bbbda768b39.png)
![SouthernHem_Cloudiness_vs_Lat](https://user-images.githubusercontent.com/22499952/116168529-9b122c80-a6d0-11eb-9323-dc9ac16dcce5.png)

![NorthernHem_WindSpeed_vs_Lat](https://user-images.githubusercontent.com/22499952/116168539-a1a0a400-a6d0-11eb-9375-e40e647bc2ec.png)
![SouthernHem_WindSpeed_vs_Lat](https://user-images.githubusercontent.com/22499952/116168544-a5342b00-a6d0-11eb-82c0-4660e486b873.png)

### Observations
1. There is a strong negative relationship between Temperature and Latitude in the Northern Hemisphere. As the latitude increases, the temperature decreases.
2. Each with an r-squared value of less than .25, it can be said that there is very little relationship (or a weak relationship) between humidity, cloudiness and/or windspeed in both the Nothern and Southern Hemispheres.
3. The closer one is to the equator (0 degrees), the higher the max temperature is.

## VacationPy
Use your skills in working with weather data to plan future vacations.

### Requirements
* Create a heat map that displays the humidity for every city from Part 1
* Narrow down the dataframe to find your ideal weather condition.
* Use Google Places API to find the first hotel for each city located within 5,000 meters of your coordinates.
* Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City and Country

### Results
Could not get gmaps to print to my jupyter notebook but will revisit to update analysis
