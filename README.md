# CAME Domotic

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![License][license-shield]](LICENSE)

_Integration to integrate with [came_domotic][came_domotic]._

**This integration will set up the following platforms.**

| Platform        | Description                         |
| --------------- | ----------------------------------- |
| `binary_sensor` | Show something `True` or `False`.   |
| `sensor`        | Show info from CAME Domotic API.    |
| `switch`        | Switch something `True` or `False`. |

## Installation

1. Using the tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
1. If you do not have a `custom_components` directory (folder) there, you need to create it.
1. In the `custom_components` directory (folder) create a new folder called `came_domotic`.
1. Download _all_ the files from the `custom_components/came_domotic/` directory (folder) in this repository.
1. Place the files you downloaded in the new directory (folder) you created.
1. Restart Home Assistant
1. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "CAME Domotic"

## Configuration is done in the UI

...

## Contributions are welcome!

If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)

***

[came_domotic]: https://github.com/camedomotic-unofficial/came_domotic
[commits-shield]: https://img.shields.io/github/commit-activity/y/camedomotic-unofficial/came_domotic.svg?style=for-the-badge
[commits]: https://github.com/camedomotic-unofficial/came_domotic/commits/main
[exampleimg]: example.png
[license-shield]: https://img.shields.io/github/license/camedomotic-unofficial/came_domotic.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/camedomotic-unofficial/came_domotic.svg?style=for-the-badge
[releases]: https://github.com/camedomotic-unofficial/came_domotic/releases
