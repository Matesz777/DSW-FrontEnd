# DSW-FrontEnd

A modern weather-focused frontend application built with **React** and **Vite**.  
The project provides a clean client-side experience for searching weather by city, browsing selected cities, viewing detailed forecasts, and managing favorite locations.

## Overview

DSW-FrontEnd is a single-page application designed to present weather data in a simple and interactive way.  
It combines client-side routing, global state management, and persistent local storage to create a responsive weather dashboard experience.

The application includes:

- weather search by city,
- a set of popular cities with quick access,
- detailed city weather views,
- a favorites page,
- temperature unit switching,
- local persistence for history and favorites.

## Features

- **City weather search** with live API requests
- **Popular cities section** for quick navigation
- **Detailed city page** with:
  - current weather,
  - humidity,
  - wind speed,
  - precipitation summary,
  - 5-day forecast
- **Favorites management** using Redux state
- **Temperature unit toggle** between metric and imperial
- **Persistent local storage** for:
  - selected unit,
  - recent weather history,
  - favorite cities
- **Custom 404 page** for unknown routes

## Tech Stack

- **React 19**
- **Vite 7**
- **React Router DOM 7**
- **Redux Toolkit**
- **React Redux**
- **Framer Motion**
- **Lucide React**
- **ESLint**

## Project Structure

```text
DSW-FrontEnd/
├── public/
├── src/
│   ├── components/
│   ├── redux/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
