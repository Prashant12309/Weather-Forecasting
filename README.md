# 🌦️ Weather Forecasting Web Application

A dynamic web application that provides real-time weather and air pollution forecasting using external APIs, with support for both city-based search and automatic location detection.

## 📖 Overview

This project fetches live weather and air quality data and presents it through a clean, responsive web interface. Users can search for any city manually or allow the app to auto-detect their current location using the Geolocation API for instant local forecasts.

## ✨ Features

- 🌍 Real-time weather data for any city worldwide
- 🌫️ Air pollution / Air Quality Index (AQI) tracking
- 📍 Automatic location detection via the Geolocation API
- 🔎 City-based search functionality
- 📱 Responsive design that works across devices
- ⚡ Fast, dynamic UI updates without page reloads

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Data:** External Weather & Air Pollution APIs
- **Browser API:** Geolocation API

## 🏗️ How It Works

1. On load, the app requests the user's location via the Geolocation API (or the user manually searches a city).
2. The app calls external weather and air pollution APIs with the location coordinates or city name.
3. The returned JSON data (temperature, conditions, AQI, etc.) is parsed and dynamically rendered on the page.
4. Users can search a different city at any time to get updated results.

## 📂 Project Structure

```
weather-forecasting-app/
├── index.html          # Main HTML structure
├── css/
│   └── style.css        # Styling
├── js/
│   └── script.js         # API calls, geolocation logic, DOM rendering
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- An API key from a weather data provider (e.g., OpenWeatherMap)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/prashant12309/<Weather-Forecasting>.git
   ```
2. Navigate into the project folder:
   ```bash
   cd weather-forecasting-app
   ```
3. Add your API key in `script.js` (or a config file, if used):
   ```javascript
   const API_KEY = "your_api_key_here";
   ```
4. Open `index.html` in your browser (or use a live server extension in VS Code).

## 🔑 API Configuration

> Update this section with the actual API(s) you used, e.g., OpenWeatherMap for weather data and OpenWeatherMap Air Pollution API for AQI.

- **Weather API:** [OpenWeatherMap](https://openweathermap.org/api)
- **Air Pollution API:** [OpenWeatherMap Air Pollution API](https://openweathermap.org/api/air-pollution)

Sign up on the provider's site to get a free API key, then plug it into your project as shown above.

## 📸 Screenshots

> Add screenshots of your app here to make the README more engaging.

```
| Home / Search | Weather Result | Air Pollution Data |
|----------------|-----------------|----------------------|
| ![home](screenshots/home.png) | ![weather](screenshots/weather.png) | ![aqi](screenshots/aqi.png) |
```

## 🔮 Future Improvements

- Add 5–7 day forecast view
- Add temperature unit toggle (°C / °F)
- Add weather-based background themes
- Add hourly forecast graphs
- Add PWA support for offline access

## 🤝 Contributing

Contributions are welcome! Fork the repo, create a feature branch, and submit a pull request.

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## 🙋 Author

**Prashant Lokhande**
- GitHub: [@prashant12309](https://github.com/prashant12309)
- LinkedIn: [Prashant Lokhande](https://www.linkedin.com/in/prashant-lokhande-0990a52b5)
- Email: plokhande886@gmail.com

---

⭐ If you found this project helpful, consider giving it a star on GitHub!
