# Raydius - Outdoor Seating Weather

Personal weather app to check if it's nice enough to sit outside.

## What it does

- Shows current weather conditions (temp, feels like, cloud cover, UV)
- Displays nearby cafes, bars, pubs, and restaurants with outdoor seating
- Maps cloud cover variation across your area
- Helps you decide: "Should I sit outside right now?"

## Live Demo

[Your GitHub Pages URL will go here]

## Features

- **Adaptive weather grid**: 16-81 weather points based on search radius
- **Outdoor venues only**: Pubs 🍺, Bars 🍻, Restaurants 🍽️, Cafes ☕
- **Real feel temps**: See what it actually feels like at each venue
- **UV Index**: Know when you need sunscreen
- **Sunrise/Sunset times**: Plan your outdoor activities
- **PWA support**: Install on your phone like a native app

## Tech Stack

- React (via CDN)
- Mapbox GL JS
- OpenWeatherMap API
- OpenStreetMap Overpass API
- Service Worker for offline support

## Setup

1. Clone this repo
2. Edit `config.js` with your Mapbox token (or use fallback)
3. Open `index.html` in a browser or deploy to GitHub Pages

## Files

- `index.html` - Main app (rename from raydius.html)
- `manifest.json` - PWA manifest
- `service-worker.js` - Offline support
- `config.js` - Your Mapbox token (gitignored)
- `.gitignore` - Prevents config.js from being committed

## Deploy to GitHub Pages

1. Upload all files EXCEPT `config.js`
2. Settings → Pages → Source: main branch
3. Your app will be live at `yourusername.github.io/raydius`
4. Manually upload `config.js` via web interface

---

Built for personal use. Data from OpenWeatherMap & OpenStreetMap.
