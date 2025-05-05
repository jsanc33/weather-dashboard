# Weather Dashboard

## Description

This Weather Dashboard is a full-stack application that enables users to search for and view current and future weather conditions for multiple cities. The application leverages the OpenWeather API to fetch weather data and allows users to save their searches. Built with a pre-existing front end, the back end handles API requests, data storage, and deployment via Render.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Technologies Used](#technologies-used)
- [Deployment](#deployment)
- [Screenshot](#screenshot)
- [Credits](#credits)
- [License](#license)

## Installation

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Create a `.env` file and add your OpenWeather API key:

   ```env
   OPENWEATHER_API_KEY=your_api_key_here
   ```

## Usage

- Use the search bar to enter a city name.
- View the current weather and 5-day forecast.
- Cities are saved to local search history.
- Click a city in the history to reload its weather data.

## API Routes

### HTML Route

- `GET *`: Returns the `index.html`.

### API Routes

- `GET /api/weather/history`: Retrieves saved city searches from `searchHistory.json`.
- `POST /api/weather`: Accepts a city name, adds it to history, and returns weather data.
- `DELETE /api/weather/history/:id`: Deletes a city from history by ID (bonus feature).

## Technologies Used

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![OpenWeather API](https://img.shields.io/badge/OpenWeather-API-orange?style=for-the-badge)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=000)

## Deployment

- 🚀 [Live Site](https://weather-dashboard-bob1.onrender.com)
- 💻 [GitHub Repository](https://github.com/jsanc33/weather-dashboard)

## Screenshot

![App Screenshot](./Assets/09-servers-and-apis-homework-demo.png)

## Credits

- [OpenWeather](https://openweathermap.org/)
- [Render Deployment Guide](https://coding-boot-camp.github.io/full-stack/render/render-deployment-guide)

## License

MIT licence built by Joseph
