# Product

<!-- impeccable:product-schema 1 -->

## Platform
web

## Users
Inferred from the brief: people who want a quick current-weather check and a five-day outlook for a searched city.

## Product Purpose
Inferred from the brief: show current conditions and a five-day forecast, with Tokyo as the default city. Success means users can find a city and scan its weather at a glance.

## Positioning
Inferred from the brief: a lightweight, single-file weather utility that retrieves live data from Open-Meteo without an API key and has hardcoded fallback data when the network request fails.

## Operating Context
Inferred from the brief: used in a browser, with city search as the primary interaction.

## Capabilities and Constraints
- City search.
- Current temperature and a five-day forecast displayed in cards.
- Tokyo is shown by default on load.
- Weather-appropriate accent colors; centered narrow-column layout.
- Live Open-Meteo data with a hardcoded fallback if fetching fails.
- The app is a single `index.html` file with no server or dependencies.
- Supports the user's `prefers-color-scheme` setting.

## Brand Commitments
No existing brand, name, or visual identity was supplied.

## Evidence on Hand
No real-world data assets or brand assets were supplied. Live weather data is obtained from Open-Meteo; fallback values are illustrative.

## Product Principles
- Make current conditions immediately scannable.
- Keep city lookup direct and lightweight.
- Clearly distinguish live results from fallback conditions.
- Keep the page self-contained and responsive.
