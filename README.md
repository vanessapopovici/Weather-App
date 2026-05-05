# Weather App
 
A simple weather application built with HTML, CSS, and JavaScript that displays real-time weather data for any city using the OpenWeatherMap API.
 
> Built by following the [GreatStack tutorial](https://www.youtube.com/watch?v=MIYQR-Ybrn4) on YouTube.

## Features
 
- Search weather by city name
- Displays current temperature (°C), humidity, and wind speed
- Dynamic weather icons that change based on conditions (Clear, Clouds, Rain, Drizzle, Mist)
- Error handling for invalid city names
- Supports search via button click or Enter key

## Demo
 
![Weather App Screenshot](images/weatherDemo.png)

## Tech Stack
 
- HTML5
- CSS3
- Vanilla JavaScript
- [OpenWeatherMap API](https://openweathermap.org/api)

### Prerequisites
 
- A free API key from [OpenWeatherMap](https://openweathermap.org/api)
### Installation
 
1. Clone or download this repository.
2. Open `config.js` and replace the API key with your own:
   ```js
   const config = {
       apiKey: "YOUR_API_KEY_HERE"
   };
   ```
3. Open `index.html` in your browser.

## Usage
 
1. Type a city name into the search box.
2. Press the search button or hit **Enter**.
3. The app will display the current temperature, weather condition, humidity, and wind speed.

## Acknowledgements
 
- Tutorial by [GreatStack](https://www.youtube.com/@greatstackdev) on YouTube
- Weather icons from [Freepik](https://www.freepik.com/)
- Weather data from [OpenWeatherMap](https://openweathermap.org/)
