# homeassistant-enphase-to-chargehq
Configuration for sending Enphase solar generation and consumption data from Home Assistant to Charge HQ

This a user-contributed configuration for sending solar and home consumption data to Charge HQ via the Push API.

Adapt as required to suit your own setup:
  1. Generate an API key on app.chargehq.net, under Settings > My Equipment > Solar / Battery Equipment > Push API
  2. Insert the API key into the curl string in configuration.yaml
  3. Replace the sensor names in the curl string with the correct values from your Home Assistant installation
  4. Add Enphase battery sensor data to the string if you have it
