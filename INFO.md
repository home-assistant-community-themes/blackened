# Blackened Theme

[![Build Status](https://www.travis-ci.org/home-assistant-community-themes/blackened.svg?branch=master)](https://www.travis-ci.org/home-assistant-community-themes/blackened)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)

> Blackened theme. Based on The Amoled Theme by Lance36

## Screenshots

### Overview


### Map


### Logbook


### History


### Developer Tools


### Configuration


### Profile


## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

1. Go to the Community Store.
2. Search for `Blackened`.
3. Navigate to `Blackened` theme.
4. Press `Install`.
5. Go to services and trigger the `frontend.reload_themes` service.
