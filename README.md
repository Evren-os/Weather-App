# Weather App

![image](https://github.com/Evre-nos/Weather-App/assets/138004078/9c271fcb-e90d-46b3-8842-e0828e6e10f6)

A simple, responsive weather application created with Vanilla JavaScript and the OpenWeather API.

## Features

- Real-time weather data for any city worldwide
- Displays current temperature, feels like temperature, humidity, wind speed, and pressure
- Shows minimum and maximum temperatures
- Presents weather forecast and corresponding weather icon
- Displays date and time of weather data
- Search functionality to look up weather for any city

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- OpenWeather API

## How to Use

1. Clone this repository to your local machine.
2. Open `index.html` in your web browser.
3. By default, the app shows weather for Mecca.
4. To check weather for a different city, enter the city name in the search bar and press Enter.

## Code Structure

The JavaScript code is organized into several key components:

- Selectors: DOM elements are selected and stored in variables for easy access.
- Functions: 
  - `getCountryName()`: Converts country codes to full country names.
  - `timeConverter()`: Converts Unix timestamps to readable date and time.
  - `getWeatherData()`: Fetches weather data from the OpenWeather API and updates the UI.
- Event Listeners: 
  - Handles form submission for city search.
  - Loads weather data when the page loads.

## API Used

This app uses the [OpenWeather API](https://openweathermap.org/api) to fetch weather data. You'll need to sign up for a free API key to use this app.

## Future Improvements

- Add geolocation to get user's current location weather
- Implement a 5-day forecast
- Add more weather details like sunrise/sunset times
- Improve error handling for invalid city names

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
