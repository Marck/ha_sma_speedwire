# SMA SpeedWire Integration

Custom integration for Home Assistant to connect SMA inverters via SpeedWire protocol

**This component will set up the following platforms.**

| Platform        | Description                         |
| --------------- | ----------------------------------- |
| `binary_sensor` | Show something `True` or `False`.   |
| `sensor`        | Show info from API.                 |
| `switch`        | Switch something `True` or `False`. |

{% if not installed %}

## Installation

1. Click install.
2. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "sma speedwire".

{% endif %}

## Configuration is done in the UI

You will be asked a number of questions, the IP address and user password of the inverter will be needed

<!---->

## Credits

This project was generated from [@eddso](https://github.com/eddso)'s [Home Assistant SMA Speedwire code](https://github.com/eddso/ha_sma_speedwire) repository.

Full credits to [@eddso](https://github.com/eddso).
