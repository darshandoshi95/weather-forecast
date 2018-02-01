# weather-forecast
BeautifulSoup implementation for extracting weather forecasting information
Website used for data extraction- http://forecast.weather.gov/MapClick.php?lat=37.7772&lon=-122.4168#.WnObspM-d0u


Steps-
Download the web page containing the forecast.
Create a BeautifulSoup class to parse the page.
Find the div with id seven-day-forecast, and assign to seven_day
Inside seven_day, find each individual forecast item.
Extract and print the first forecast item.
