# Blackened Theme

> Blackened theme. Based on The Amoled Theme by Lance36

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

1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

2. Go to the Community Store.
3. Search for `Blackened`.
4. Navigate to `Blackened` theme.
5. Press `Install`.
6. Go to services and trigger the `frontend.reload_themes` service.
