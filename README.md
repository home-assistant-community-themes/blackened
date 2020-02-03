# Blackened Theme

[![Build Status](https://www.travis-ci.org/home-assistant-community-themes/blackened.svg?branch=master)](https://www.travis-ci.org/home-assistant-community-themes/blackened)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)

> Blackened Theme - Based on The Amoled Theme by Lance36

Disclaimer: first theme(-adaptation) and very early stages!
  Still a lot of "in-progress" variables left from troubleshooting etc.              #   Will remove in due course.
  ... But it works, as it is, for my purposes.

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

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/home-assistant-community-themes/blackened.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/home-assistant-community-themes/blackened.git
```
