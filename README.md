🌤️ Weather App
A simple and responsive weather web application that displays real-time weather data for any city using the OpenWeatherMap API.

🖼️ Demo

(Replace with actual screenshot if available)

🔧 Features
🌍 Search weather by city name

🌡️ Displays current temperature, humidity, and wind speed

🌥️ Dynamic weather icons for Clouds, Clear, Rain, Drizzle, and Mist

❌ Error message for invalid city input

📱 Responsive and mobile-friendly design

🚀 How to Run
Clone or download this repository.

Ensure all files (index.html, style.css, image/) are in the same project directory.

Open index.html in your web browser.

📁 Project Structure
bash
Copy
Edit
weather-app/
│
├── index.html           # Main HTML file
├── style.css            # Stylesheet for the app
├── image/               # Contains weather icon images
│   ├── search.png
│   ├── rain.png
│   ├── clouds.png
│   ├── clear.png
│   ├── drizzle.png
│   ├── mist.png
│   ├── humidity.png
│   └── wind.png
🧠 Built With
HTML5

CSS3

JavaScript (ES6+)

OpenWeatherMap API

🔑 API Key
This app uses a free API key from OpenWeatherMap.
Your current API key is embedded in the script:

js
Copy
Edit
const apikey = "9223b2dad715e9b129750adf98b36d04";
🔒 For security reasons, do not expose API keys in public repositories.

✨ Future Improvements
Add support for geolocation

Display weather forecast (hourly/daily)

Toggle between Celsius and Fahrenheit

Improve error handling and UX

📄 License
This project is open-source and free to use.
