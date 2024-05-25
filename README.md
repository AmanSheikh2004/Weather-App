# Weather-App

WeatherApp is a simple graphical weather application built using Python's Tkinter library. It fetches and displays real-time weather information for a specified city or zip code using the WeatherAPI.

## Features

Current Weather Information: Get up-to-date weather details including temperature, weather condition, and weather icons.
User Input Handling: Input city name or zip code to fetch weather data.
Visual Weather Icons: Display corresponding weather icons.
Error Handling: Basic error handling for invalid input or failed API requests.
Prerequisites
Python 3.x
requests library
tkinter library (usually included with Python installations)
Pillow library for image handling

## Installation

Clone the repository:
    git clone https://github.com/yourusername/WeatherApp.git
    cd WeatherApp
Install required libraries:
    pip install requests pillow
    API Key
To use the WeatherAPI, you need an API key. Obtain your API key from WeatherAPI.
Replace the placeholder API key in the code with your actual API key:
    API_KEY = 'your_actual_api_key'

## Usage

Run the application:
    python weather_app.py
Enter a city name or zip code:

Input the desired location in the text field.
Click the "Search" button to fetch and display the weather information.

## Code Structure

weather_app.py: The main script that contains the application code.

## Main Components

API Interaction:
get_weather_data(location): Fetches weather data from the WeatherAPI for the specified location.

## GUI Design:

WeatherApp: Main class that sets up the Tkinter interface.
search_weather(): Handles user input and fetches weather data.
display_weather(data): Updates the GUI with fetched weather information.

## Example

Input:
Enter "New York" in the text field and click "Search".
Output:
Display weather details like temperature, condition, and an icon representing the current weather in New York.
