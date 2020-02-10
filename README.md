<a href="https://www.buymeacoffee.com/dkit" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a>

## light modern

Light theme with transparant cards and green colors for [Home Assistant](https://www.home-assistant.io)

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=flat-square)](https://github.com/custom-components/hacs) 

## Screenshot

Default view
![](screenshot/default.JPG)

History 
![](screenshot/history.JPG)

Settings
![](screenshot/settings.JPG)


## Installation

#### Manual Installation
1. copy the `themes` folder into your home-assistant folder
2. add this to your `configuration.yaml`

```yaml
frontend:
  themes: !include_dir_merge_named themes
```
3. copy www/bg/lmod.jpg to your config folder
4. restart home-assistant
5. select the theme in your user's profile (bottom left)

#### HACS

1. Go to the Community Store.
2. Search for `Light Modern`.
3. Navigate to `Light Modern`.
4. Press Install.
