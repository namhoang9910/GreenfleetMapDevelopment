# GreenfleetMapDevelopment

## Feature 2

### 2.1 Forest locations ("forest-locations.json")

You can access this file to add new locations for forest based on latitude and longitude. Please add new entries in the following format, as an example:
"{ "lat": -35.282, "lng": 149.128, "city": "Canberra" },"


### 2.2 Map custom themes: dark, light, retro 

map_custom_theme_dark.json; map_custom_theme_light.json; map_custom_theme_retro.json

These files are not to be editted manually. You can make changes on https://mapstyle.withgoogle.com and then copy the code over.


### 2.3 Feature 2 Liquid ("feature-2-map-slider.liquid")

This file implements the basic structure of the map and initalizing assets. You can change an asset's name, e.g. "tree.png", to a new asset, e.g. "tree2.png". This will change the icon display on the screen.


### 2.4 Feature 2 JavaScript ("feature-2-map-slider.js")

This file implements the interactive elements for the different map features like dark mode, aboriginal map, and tree markers.


### 2.5 Feature 2 CSS ("feature-2-map-slider.css")

This file has the styling of the map features & texts.

### 2.6 Images ("assets/images")

You can add your new images assets and change their names in the liquid file.

```bash