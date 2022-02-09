
![beta_badge](https://img.shields.io/badge/State-Beta-orange?style=for-the-badge)

# Material 3 Theme for Home Asistant: #07, Dark Olive Green

## What is it
A Material 3 based extended Dark & Light theme for Home Assistant.

Currently tested for compatibility with Material 2 which is what Home Assistant uses... In other words: in BETA 😄

## Installation via HACS
TODO

## Manual Installation
Get the yaml file and put int into your `themes` folder.

If you have the following in your `configuration.yaml`:
```yaml
frontend:
  themes: !include_dir_merge_named themes/
```

The theme will be automatically available once you have reloaded the themes using the Home Assistant 'Developer Tools' > 'Services' > 'frontend.reload_themes' service.

## Theme Preview:
Below the definition of the theme, generated and displayed using the Swiss Army Knife custom card for Home Assistant (NYR).

![m3-07-palettes](https://github.com/AmoebeLabs/ha-theme_m3-07-darkolivegreen/blob/main/preview/m3-07-palettes.png)

![m3-07-surfaces](https://github.com/AmoebeLabs/ha-theme_m3-07-darkolivegreen/blob/main/preview/m3-07-surfaces.png)

![m3-07-light](https://github.com/AmoebeLabs/ha-theme_m3-07-darkolivegreen/blob/main/preview/m3-07-light.png)

![m3-07-dark](https://github.com/AmoebeLabs/ha-theme_m3-07-darkolivegreen/blob/main/preview/m3-07-dark.png)

## Some real-world screenshots:
A Light and Dark example made with the Swiss Army Knife custom card.

Note that the card background in the light theme is white instead of the lightest theme background. Will be corrected...

![m3-07-sake12-light](https://github.com/AmoebeLabs/ha-theme_m3-07-darkolivegreen/blob/main/screenshots/Mockup%20Home%20Assistant%20-%20Example%2012m3-07-light%20Detail.png)

![m3-07-sake12-dark](https://github.com/AmoebeLabs/ha-theme_m3-07-darkolivegreen/blob/main/screenshots/Mockup%20Home%20Assistant%20-%20Example%2012m3-07-dark%20Detail.png)

