# 🌤️ WeatherMap — React Native Weather App

A sleek, real-time weather app built with **React Native** and the **OpenWeatherMap API**. Search any city or tap anywhere on the interactive map to instantly get live weather data — temperature, humidity, wind, pressure, and more.

---

## 📱 Screenshots




---

## ✨ Features

- 🔍 **City Search** — Search weather for any city in the world
- 🗺️ **Interactive Map** — Tap anywhere on the map to fetch weather at that location
- 🌫️ **Fog Animation** — Animated overlay triggers automatically for cloudy, misty, or hazy conditions
- 📍 **Live Marker** — Map marker updates in real time to the searched or tapped location
- 🌡️ **Weather Stats** — Temperature, description, humidity, wind speed, pressure, and rainfall
- 📐 **Coordinates Display** — Shows precise lat/lon of the selected location

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | React Native (Expo) |
| Language | TypeScript |
| Maps | `react-native-maps` |
| HTTP Client | `axios` |
| Weather Data | OpenWeatherMap API |
| Animation | React Native `Animated` API |

---

## 🚀 Getting Started

### Prerequisites

- Node.js ≥ 18
- Expo CLI (`npm install -g expo-cli`)
- An [OpenWeatherMap API key](https://openweathermap.org/api) (free tier works)

### Installation

```bash
# Clone the repo
git clone https://github.com/your-username/weathermap.git
cd weathermap

# Install dependencies
npm install
```

### Add your API Key

Open `HomeScreen.tsx` and replace the API key:

```ts
const API_KEY = "your_openweathermap_api_key_here";
```

### Run the App

```bash
npx expo start
```

Scan the QR code with **Expo Go** on your phone, or press `a` for Android emulator / `i` for iOS simulator.

---

## 📂 Project Structure

```
weathermap/
├── app/
│   └── HomeScreen.tsx      # Main screen — all logic and UI
├── assets/                 # Icons and images
├── app.json                # Expo config
└── package.json
```

---

## 🔑 API Reference

This app uses the [OpenWeatherMap Current Weather API](https://openweathermap.org/current):

```
GET https://api.openweathermap.org/data/2.5/weather
  ?q={city}&appid={API_KEY}&units=metric          # by city name
  ?lat={lat}&lon={lon}&appid={API_KEY}&units=metric # by coordinates
```

---

## 🙋‍♂️ Author

**Arnav Jena**
B.Tech CSE — KIIT, Bhubaneswar
[LinkedIn](https://linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
