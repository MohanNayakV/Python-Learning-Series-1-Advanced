# 🌤️ Weather Dashboard

A professional weather dashboard application that fetches real-time weather data from the OpenWeatherMap API. Built with Python (Flask) and vanilla JavaScript, featuring advanced Python concepts like decorators, context managers, and more.

## Features

✨ **Core Features:**
- 🌍 Real-time weather information for any city worldwide
- 📊 5-day weather forecast display
- 🔄 Compare weather across multiple cities
- 🎨 Beautiful, responsive UI with animations
- 💾 Built-in caching system for API responses
- 📱 Mobile-friendly design
- 🌡️ Support for multiple temperature units (Celsius, Fahrenheit, Kelvin)

🔧 **Technical Features:**
- Context managers for resource management
- Property descriptors for lazy loading
- Error handling and logging
- RESTful API architecture
- CORS support
- Flask blueprints ready
- Type hints throughout

## Quick Start

1. **Get API Key** from [openweathermap.org](https://openweathermap.org/api)
2. **Clone & Setup:**
   ```bash
   cd Python-Learning-Series-1-Advanced/weather_dashboard
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   pip install -r requirements.txt
   cp .env.example .env
   # Edit .env and add your API key
   ```
3. **Run:**
   ```bash
   python app.py
   ```
4. **Visit:** http://localhost:5000

## API Endpoints

- `GET /api/weather/current?city=London&units=metric`
- `GET /api/weather/forecast?city=London&units=metric`
- `POST /api/weather/multiple` - Compare multiple cities
- `GET /api/cache/status`
- `POST /api/cache/clear`

## Advanced Python Concepts

- **Context Managers**: Resource management with `__enter__` and `__exit__`
- **Properties**: Lazy loading with `@property` decorator
- **Type Hints**: Full type annotations
- **Dataclasses**: Clean data representation
- **Error Handling**: Custom exceptions
- **Caching**: Memoization pattern

See full documentation in [weather_dashboard/README.md](weather_dashboard/README.md)
