# ISM6427c

## Weather app

A responsive weather app built as a single static `index.html`, using the free, keyless [Open-Meteo](https://open-meteo.com/) forecast and geocoding APIs.

- Greets the visitor by name with a time-of-day greeting
- Current conditions, 24-hour and 7-day forecast
- City search and "My location" (browser geolocation)
- Light, Dark and System themes (saved per browser)
- °F / °C toggle
- Defaults to Boca Raton, FL

### Run locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

### Deploy to Netlify

No build step. Connect this repo in Netlify with branch `main`; `netlify.toml` publishes the repo root. Or drag the folder into Netlify Drop.
