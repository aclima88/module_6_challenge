# module_6_challenge

#WeatherPy
Imported needed modules and libraries.
Ignored warnings.
Generated a list of up to 1500 random cities by Using the citipy Library.
Used the OpenWeatherMap API to retrieve weather data from the cities list generated in the started code.
Displayed the data for the list of randomly generate cities.
Converted the list into a DataFrame and displyaed the number of records in each column of the DataFrame.
Exported City_Data as a CSV file.
Created scatter plots to compare Latitude vs. Temperature, Humidity, Cloudiness and Wind Speed individually.
Defined a function to create linnear regression plots.
Split the city_data_df into northern and southern hemispheres using latitude coordinates.
Created linnear regressions for each of the previously created scatter plots split into south and north hemi.
Added my linnear relationship analysis to each of the linnear regression plots created before. 

#VacationPy
Imported needed modules and libraries.
Ignored warnings.
Imported the api keys needed for the code.
Attempted to set the default encoding to UTF-8 but decided to not use that code.
Loaded the CSV file from the WeatherPy exercise and added the data into a DataFrame.
Created a map that displays a point for every city in the city_data_df DataFrame. Used the humidity in each city as the size for the map.
Cleaned the city_data_df DataFrame to get rid of any null values.
Copied some of the data from city_data_df DataFrame to create a smaller DataFrame that I used to specify specific criteria for my ideal vacation weather condition and used the information to find hotels within a 10,000 mile radius of each city location.
Attempted to translate hotel names into english but ran into an issue with pytranslate and googletrans modules. Both modules are experiencing bugs and currently being worked on by the developers.
Printed out a list of hotel names that fit my ideal vacation weather condition.
Created a map with the information from my hotel_df DataFrame and added hotenl name and country name as additional information in the map when the user hovers the mouse pointer over a specific point in the map.



# Notes
I worked with Bryant Grissel on this module and we helped each other get through places we got stuck.
I also worked with a few LAs who helped me answer some questions.
I used google bard and chatGPT to help with syntax correction and clean up.
