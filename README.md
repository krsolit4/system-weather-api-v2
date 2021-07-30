This is a weather API.

- The API gives real time weather info by accepting IP address or Postal code. 
- The API has 3 resources defined as follows /postal-code/{ip-address}, /weather/postal-code/{postal-code}, /ip/{ip-address}
- The API uses following opensource APIs internally to fetch the details
    - api.ipgeolocation.io/ipgeo
        - to fetch geolocation details
    -api.openweathermap.org/data/2.5/weather
        - to fetch the weather details
- The API stores all the unique zipcode details in a opensource database. 
    - sql3.freesqldatabase.com

NOTE : The API uses free developer trial account to get the details from the opensource API, hence the accuracy of data may not be reliable all the time.

The API is developed using Mule 4.3.0.

Link to Anypoint Exchange : https://anypoint.mulesoft.com/exchange/portals/kidane-4/
