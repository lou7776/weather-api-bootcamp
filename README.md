# Weather App

A small web app that shows the current temperature for any city. Type in a city and state, click the button, and get the temperature in Fahrenheit with a weather icon.

<img width="858" height="466" alt="Screenshot 2026-10-25 at 9 11 38 PM" src="https://github.com/user-attachments/assets/a0db63ff-83cf-436a-a43a-07aa21a83508" />


## Features

- Search by city and state
- Shows the location name and region
- Shows the current temperature in °F
- Shows the weather icon for current conditions
- Results stay hidden until you search
- Works on desktop and mobile

## Built With

- HTML
- CSS (flexbox)
- JavaScript (`fetch` and promises)
- [WeatherAPI](https://www.weatherapi.com/)

## How It Works

1. The user enters a city and state.
2. Clicking **Get Temp** sends a request to the WeatherAPI current weather endpoint.
3. The response comes back as JSON.
4. The page updates with the location, temperature, and icon.

## Run It Locally

1. Clone the repo:
   ```
   git clone https://github.com/lou7776/YOUR-REPO-NAME.git
   ```
2. Get a free API key at [weatherapi.com](https://www.weatherapi.com/).
3. Open `js/main.js` and put your key in the `key=` part of the `url`.
4. Open `index.html` in your browser.

## What I Learned

- Making API requests with `fetch` and reading JSON responses
- Updating the page from JavaScript with `querySelector` and `textContent`
- Laying out a card with flexbox
- Keeping API keys out of public repos
