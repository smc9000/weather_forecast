# weather_forecast
Provides the weather forecast.

In this program, we first define the OpenWeatherMap API URL and API key. 
We then define the city we want to get the weather data for, and construct the API URL with the city and API key. 
We then send a GET request to the API URL using the sendGetRequest() method, which returns the JSON response from the API. 
We then parse the JSON response using the JSONObject class, and extract the relevant weather data, such as temperature, humidity, and description.
Finally, we display the weather data to the user using the System.out.println() method.

Note that in order to use this program, you will need to sign up for an API key from OpenWeatherMap and replace the YOUR_API_KEY_HERE placeholder in the code with 
your actual API key.
