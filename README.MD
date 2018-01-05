# CiscoSPA custom component for Home Assistant

This is intended to be copied into your config directory for home-assistant.io

## Install

Copy the sensor folder and ciscospa.py into your config directory

## Home Assistant config

```
# Example configuration.yaml entry

sensor:
  - platform: ciscospa
    host: 192.168.1.6
    monitored_variables:
      - registration_state
      - hook_state
      - last_called_number
      - last_caller_number
      - call_state
      - call_peer_name
      - call_peer_phone
      - call_type
      - call_duration
```
