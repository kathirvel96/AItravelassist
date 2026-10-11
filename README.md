# TravelBuddy — HTML Travel Planner

A responsive, single-page travel planner built with HTML, CSS, Bootstrap 5, and vanilla JavaScript.

## Features
- Live current weather and 5-day forecast using Open-Meteo (no API key required for non-commercial use).
- City geocoding using Open-Meteo Geocoding API.
- Search any place and show current weather.
- Destination cards, destination detail modal, saved places, and itinerary ideas.
- Built-in rule-based travel assistant (not falsely presented as a generative AI service).
- Light/dark theme and responsive layout.
- Saved places and itinerary stored in the current browser's localStorage.
- No account, backend, secret API key, or payment required.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser while connected to the internet.
3. If your browser restricts requests when opened as a local file, run a local server:
   - VS Code: install/use Live Server and click **Go Live**, or
   - Python: run `python -m http.server 8000` inside this folder, then open `http://localhost:8000`.

## Free services used
- Open-Meteo Geocoding API: https://geocoding-api.open-meteo.com/
- Open-Meteo Forecast API: https://open-meteo.com/en/docs
- Bootstrap CDN and Bootstrap Icons CDN.
- Unsplash image URLs for decorative destination photography.

## Notes
- An internet connection is needed for live weather, fonts, Bootstrap assets, and remote photos.
- The assistant is rule-based and uses no AI API key. It provides sample plans, not verified reservations or live travel prices.
- Weather data may be delayed or unavailable; error messages are shown if requests fail.
- Saved content stays in localStorage on the device/browser and is not synced across devices.
- Before commercial deployment, check the current terms/licensing of each external service and image provider.
