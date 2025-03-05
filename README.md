# Custom Systemd Services

This repository contains my custom **systemd** service files for managing various personal and system-wide tasks on my Linux setup.

## Features
- Custom services for automation and system monitoring
- Easily manageable and deployable service units
- Designed for Arch and Debian-based distributions

## Installation
To use a custom systemd service, copy the file to the appropriate directory and enable it:
```sh
sudo cp my-service.service /etc/systemd/system/
sudo systemctl daemon-reload
sudo systemctl enable my-service
sudo systemctl start my-service
```

## Managing Services
- **Start a service:** `sudo systemctl start <service-name>`
- **Stop a service:** `sudo systemctl stop <service-name>`
- **Restart a service:** `sudo systemctl restart <service-name>`
- **Check service status:** `sudo systemctl status <service-name>`
- **Enable on boot:** `sudo systemctl enable <service-name>`
- **Disable on boot:** `sudo systemctl disable <service-name>`

## License
These service files are licensed under the MIT License.
