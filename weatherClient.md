# Code Kata: Command Line Weather Client

## Objective
Create a simple command-line weather client that fetches current weather data for a city using cURL or a similar HTTP client library.

## Requirements
1. Build a command-line tool that:
   - Accepts a city name as a command-line argument
   - Makes a request to a weather API (such as OpenWeatherMap)
   - Parses the JSON response
   - Prints formatted weather information to the console

2. The output should include:
   - City name and country
   - Current temperature
   - Weather description
   - Humidity and wind speed
   - Appropriate error messages for failed requests or cities not found

## Constraints
- Use a server-side language of your choice (Node.js, Python, PHP, Ruby, etc.)
- Make HTTP requests using cURL, axios, requests, fetch, or a similar library
- Format the output for easy reading in a terminal
- Handle network errors and API errors gracefully

## Learning Focus
- Making HTTP requests from a server-side environment
- Parsing and processing JSON responses
- Command-line argument handling
- Error handling for network operations
- Pretty-printing data to the console

## Example Usage
```
$ ./weather.js "New York"

Weather for: New York, US
Temperature: 72°F (22°C)
Conditions: Partly cloudy
Humidity: 65%
Wind: 8 mph NW

$ ./weather.js "InvalidCityName"
Error: City not found. Please check the city name and try again.
```

This kata is perfect for practicing backend HTTP client operations without the complexity of building a full UI, while still focusing on the core network communication aspects of web development.
