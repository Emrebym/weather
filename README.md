<div align="center">

# 🌤️ Weather

**A weather forecast app with real-time data, built with React and Tailwind CSS**

![React](https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

</div>

---

## 📖 About

A clean weather application that fetches real-time weather data via API and displays current conditions for any city. Features weather-specific icons, temperature readings, humidity, and wind speed in a responsive interface styled with Tailwind CSS.

## ✨ Features

- **City search** — look up current weather for any location worldwide
- **Live weather data** — temperature, humidity, wind speed from weather API
- **Dynamic icons** — weather condition icons change based on current state (sunny, cloudy, rain, snow, etc.)
- **Custom assets** — purpose-built weather icons and visual elements
- **Responsive layout** — Tailwind CSS for clean, mobile-friendly design
- **Error handling** — graceful handling of invalid city names or API errors

## 🏗️ Architecture

```
src/
├── components/
│   └── Weatherapp/
│       ├── WeatherApp.jsx    # Main weather component — API calls, state, display
│       └── WeatherApp.css    # Component-specific styles
├── components/Assets/        # Weather icons (clear, cloud, drizzle, humidity, etc.)
├── App.js                    # Root component
├── index.js                  # React entry point
└── index.css                 # Tailwind imports & global styles
```

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | React 18 (Create React App) |
| Styling | Tailwind CSS |
| API | OpenWeatherMap API |
| Testing | Jest, React Testing Library |

## 🚀 Getting Started

```bash
git clone https://github.com/Emrebym/weather.git
cd weather
npm install
npm start
```

Add your API key in the WeatherApp component, then open `http://localhost:3000`

## 📝 License

MIT
