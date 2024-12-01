# Weather API Server

A simple Go server that provides weather information using the [OpenWeatherMap API](https://openweathermap.org/api). This server includes an endpoint to query weather data for a specific city and another endpoint for basic testing.

---

## 🚀 Features

- Fetch real-time weather data for any city
- Simple and lightweight server
- JSON response format
- Easy-to-configure API key setup

---

## 📋 Requirements

- **Go**: Version 1.19 or later
- **OpenWeatherMap API Key**: Sign up for a free API key [here](https://openweathermap.org/api)

---

## 🛠 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/weather-api-server.git
cd weather-api-server

Create a appConfig file
{
    "OpenWeatherMapApiKey": "your_openweathermap_api_key"
}

Run a server
go run main.go