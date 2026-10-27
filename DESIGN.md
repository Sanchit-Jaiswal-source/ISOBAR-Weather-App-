# Isobar design system

## Surface and mode
Weather lookup, operated as a quick glance on desktop or mobile. The centered column puts city search first, makes current conditions the visual anchor, and closes with a five-day scan.

## Visual direction
An atmospheric weather console: the sky itself becomes the live-conditions panel, surrounded by subtle isobar contour rings. Forecasts remain a compact five-stop strip that reads like a clear daily outlook.

## Color
- The page follows the system light/dark preference with cool, low-contrast blue-gray surfaces.
- Vivid sky blue marks the current-conditions scene; its hue shifts for rain, fog, cloud, snow, and storms.
- Sun amber marks clear-weather imagery and the primary search action.
- White text stays high contrast against the saturated current-weather scene.

## Typography and layout
- Native system sans-serif; tabular figures for weather measurements.
- Centered column capped at `536px`.
- A strong, oversized title and search lead into a prominent current-conditions panel and five evenly spaced forecast cards.
- Compact forecast cards preserve the five-day scan at narrow widths.

## Components and states
- Search form with visible keyboard focus and disabled/loading feedback.
- Current conditions panel includes local time, temperature, condition, feels-like temperature, humidity, wind, and today's range.
- The current scene uses weather-coded colors and a condition icon.
- Five forecast cards include weekday, weather icon, high/low, and rain probability when meaningful.
- Source indicator distinguishes live results from illustrative fallback conditions.
- Errors and fallback data are announced through a live status message.

## Motion and accessibility
- Forecast cards enter with a short, staggered rise; cards lift slightly on hover; reduced-motion preferences disable authored motion.
- Semantic headings, labeled search, live status regions, text weather descriptions, and visible focus are retained.
- All essential behavior and assets are self-contained in `index.html`; no external libraries or server are required.
