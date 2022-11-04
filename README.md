# QATechnicalTest
Technical Test


UI Automation
(Using Katalon Studio)
1. Navigate to https://www/service.nsw.gov.au/
2. Search for "Apply for a number plate"
3. Click on Locate us button
4. Enter suburb "Sydney 2000"
5. It Should use service center named as "Marrickville Service Center"


API Automation 
Register to get the API token key - https://www.weatherbit.io/account/create 
Navigate to https://www.weatherbit.io/api/swaggerui/weather-api-v2#!/andautomatebelowAPIs 
a. GET /current?lat={lat}&lon={lon} for values {lat} as 40.730610 and {lon} as -73.935242 
It should parse the response and get the value of the /data/state_code 

b. GET /forecast/3hourly?postal_code={postal_code} 
It should parse the response and get the value of the { timestamp_utc, weather} for all the data entries 
