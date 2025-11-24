# Pirate Weather Card Examples

This directory contains example Home Assistant dashboard card configurations for displaying Pirate Weather data.

## weather-card-dual-temperature.yaml

A compact markdown card that displays temperature in both Celsius and Fahrenheit with an emoji weather icon.

**Features:**
- Shows current weather condition as an emoji icon (☁️ ☀️ 🌧️ etc.)
- Displays temperature in both units: `☁️ 7.8°C / 46°F`
- Celsius with 1 decimal place, Fahrenheit as integer
- Large, readable 28px font
- Right-aligned layout
- Transparent background
- Icon automatically updates based on weather condition

**Requirements:**
- [card-mod](https://github.com/thomasloven/lovelace-card-mod) custom component installed
- Pirate Weather integration configured

**Installation:**
1. Copy the entire YAML content from `weather-card-dual-temperature.yaml`
2. In Home Assistant, edit your dashboard
3. Add a new Markdown card or edit an existing one
4. Switch to "Show Code Editor"
5. Paste the configuration
6. Replace `weather.pirateweather` with your actual entity ID if different
7. Save

**Example Display:**
```
☁️ 7.8°C / 46°F
```

**Supported Weather Icons:**
- ☀️ Clear day / Sunny
- 🌙 Clear night
- ☁️ Cloudy
- 🌫️ Fog
- ⛅ Partly cloudy
- 🌧️ Rainy
- 🌨️ Snowy / Hail
- 💨 Windy
- ⛈️ Thunderstorm
- 🌡️ Default (if condition not recognized)
