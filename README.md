# TuteDude

Assignments 


## Assignment 6 Weather Web Application

This is a simple weather web application that fetches and displays real-time weather information for a specified location using the OpenWeatherMap API.

## Features

- Displays the current weather description, temperature, and location.
- Shows a weather icon corresponding to the current weather condition.
- Refresh button to reload the weather data.
- Responsive design using Bootstrap for a clean and modern UI.

## Technologies Used

- **HTML**: For structuring the web page.
- **CSS**: For styling the application (via `weather.css` and Bootstrap).
- **JavaScript**: For fetching and displaying weather data.
- **OpenWeatherMap API**: For retrieving real-time weather information.
- **Bootstrap**: For responsive design and layout.
- **Google Fonts**: For custom typography.

## How It Works

1. The application sends a GET request to the OpenWeatherMap API using the `XMLHttpRequest` object.
2. The API response is parsed to extract weather details such as:
   - Location name
   - Weather description
   - Temperature (converted from Kelvin to Celsius)
   - Weather icon
3. The extracted data is dynamically displayed on the web page.

## Setup Instructions

1. Clone this repository or download the project files.
2. Open the `weather.html` file in your browser.
3. Ensure you have an active internet connection to load external resources (e.g., Bootstrap, Google Fonts, and OpenWeatherMap API).
## Output:
![Alt Text](Weather_App/webApp.png)

## API Key

The application uses the OpenWeatherMap API. Replace the `appid` parameter in the API URL with your own API key:

```javascript
link = "https://api.openweathermap.org/data/2.5/weather?q=pune&appid=YOUR_API_KEY";

