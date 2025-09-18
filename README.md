[![AUR](https://img.shields.io/aur/version/python-azure-iot-device)](https://aur.archlinux.org/packages/python-azure-iot-device)
[![PyPI version](https://img.shields.io/pypi/v/azure-iot-device.svg)](https://pypi.org/project/azure-iot-device/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# An Arch Linux AUR package for [Azure IoT Device SDK for Python](https://github.com/Azure/azure-iot-sdk-python).

## About This Package

This AUR package installs the official Azure IoT Device SDK for Python, which enables communication between IoT devices and Azure IoT Hub. It includes support for device-to-cloud messaging, cloud-to-device commands, and device twin synchronization.

## Installation

Use an [AUR helper](https://wiki.archlinux.org/title/AUR_helpers) like `yay`:

```bash
yay -S python-azure-iot-device
```

## Arch User Repository

Visit the [AUR](https://aur.archlinux.org/packages/python-azure-iot-device) page for more detailed information.

## Upstream Resources

- [Azure IoT SDK for Python (GitHub)](https://github.com/Azure/azure-iot-sdk-python)
- [PyPI: azure-iot-device](https://pypi.org/project/azure-iot-device/)
- [Microsoft Azure IoT Documentation](https://learn.microsoft.com/en-us/azure/iot-hub/)

## Manual Build

Clone this repo and run:

```bash
makepkg -si
```

## Contributing

Feel free to open issues or submit pull requests if you encounter problems or want to improve the packaging.
