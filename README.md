# Weather Forecast Application

![as2 1](https://github.com/user-attachments/assets/5bdfe0d4-c3d0-4ab1-89cb-56aa0212f669)




## Overview

This project is a dynamic web application that allows users to retrieve real-time weather data for any city, view forecasts for the next five days, and get a detailed breakdown of current weather conditions such as temperature, humidity, wind speed, and more. The application is powered by the OpenWeatherMap API and provides users with the option to switch between Celsius and Fahrenheit for temperature display.

## Key Features

- **Real-Time Weather Data:** Fetches the latest weather data for any city using the OpenWeatherMap API.

![as2 2](https://github.com/user-attachments/assets/3adae9df-d04b-4d8a-bc54-8601b945e2c9)


- **5-Day Forecast:** Displays a forecast for the next five days, showing weather trends for better planning.
  
![as2 3](https://github.com/user-attachments/assets/1ac603a0-baaa-47ce-beba-dd6ceb696d43)



- **Temperature Unit Conversion:** Users can switch between Celsius and Fahrenheit based on their preference.
  
![as2 4](https://github.com/user-attachments/assets/98659148-c2b6-4317-aabf-658125faacb9)



- **Detailed Weather Information:** Includes additional weather parameters such as humidity, wind speed, and atmospheric pressure.
  
![as2 5](https://github.com/user-attachments/assets/153b88ea-d0ad-4714-8fda-ea903a52cdc4)



- **User-Friendly Interface:** Easy-to-use search functionality to quickly get weather updates by city name.
- **Responsive Design:** The application adjusts seamlessly across different screen sizes and devices.

## Design and Implementation

- **API Integration:** The weather data is fetched from the OpenWeatherMap API with API calls that retrieve the current weather and the five-day forecast. 
- **Modular Structure:** The application is organized into functions that handle API requests, temperature conversions, and the display of weather information, making it easy to scale or modify.
- **Dynamic Content Rendering:** Weather information and forecasts are dynamically updated based on user input, with real-time data refreshing upon new searches.
- **Error Handling:** Proper error handling is implemented to notify users when the requested city is not found or when there are issues fetching data from the API.

## Project Requirements

- **OpenWeatherMap API Key:** You'll need an API key from OpenWeatherMap to fetch weather data.
- **Node.js (Optional):** Required for running the application locally with a live server setup.

## Setup and Installation

### Prerequisites

Ensure that the following tools are installed:

- **Node.js** (for running the app locally)

### Installation

1. **Clone the Repository**
   ```bash
   git clone "https://github.com/Tereshaa/Weather-App.git"
   ```
2. **Install Dependencies**
   If you are running the app locally and need to install any dependencies:
   ```bash
   npm install
   ```

3. **Run a Local Server**
   If you prefer to run the application using a live server locally:
   ```bash
   npm install http-server -g
   http-server -p {any port number}
   ```

## Usage

1. Search for any city using the search bar.
2. Select the desired temperature unit (Celsius/Fahrenheit/Kelvin) from the dropdown menu.
3. View the current weather conditions, along with a five-day forecast.

## Running Tests

You can add and run tests to ensure everything is working correctly.
