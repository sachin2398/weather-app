Weather App

This Weather App displays the current weather for your current location or a specified location. The app will fetch weather data using the WeatherAPI and OpenWeatherMap API.

Features

- Current Location Weather: Shows the current weather for your current location if location permission is granted.
- Location Input: Prompts the user to input a location if location permission is denied.
- Last Used Location: Remembers the last provided location and shows the weather for that location on subsequent visits.
- Location Search: Allows the user to search for and display weather for different locations.

Getting Started

Prerequisites

To run this project, you'll need:
- A web browser
- An internet connection

API Keys

You need API keys for both the OpenWeatherMap and WeatherAPI. Replace the placeholder strings 'your_openweathermap_api_key' and 'your_weatherapi_key' in the script.js file with your actual API keys.

Installation

1. Clone the repository:
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app

2. Replace API Keys:
    - Open src/script.js
    - Replace 'your_openweathermap_api_key' with your OpenWeatherMap API key.
    - Replace 'your_weatherapi_key' with your WeatherAPI key.

3. Open the App:
    - Open index.html in your web browser.

Usage

1. Allow Location Access: If prompted, allow the browser to access your location. This will fetch and display the current weather for your location.
2. Deny Location Access: If you deny location access, the app will check if you have previously provided a location. If not, it will prompt you to enter a location.
3. Search for a Location: Use the search bar to find and display the weather for a specific location.

Files

- index.html: The main HTML file for the app.
- src/script.js: JavaScript file containing the main logic for fetching and displaying weather data.
- src/setdates.js: JavaScript file for setting the current date and time.
- styles/style.css: CSS file for styling the app.

Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

License

This project is licensed under the MIT License.
