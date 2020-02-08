# hass_shutterbox
Homeassistant integration for shutterbox by blebox. To use, clone this entire repo to custom_components subdirectory of your Homessistant configuration directory.

## Configuration
To use this plugin, define each cover as follows in `configuration.yaml`:

    cover:
      - platform: hass_shutterbox
        host: 192.168.1.15
        name: salon1
        scan_interval: 15
      - platform: hass_shutterbox
        host: 192.168.1.16
        name: salon2
        scan_interval: 15