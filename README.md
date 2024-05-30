# Personal Cloud Setup using Raspberry Pi and OwnCloud

## Overview

This repository contains detailed instructions and scripts for setting up a personal cloud using a Raspberry Pi and OwnCloud. By following these steps, you can create your own cloud storage solution, providing you with control over your data and offering an alternative to commercial cloud services.

## Screenshots

![Alt Text](Image_URL)

![Alt Text](Image_URL)

## Table of Contents

- [Setup Instructions](#setup-instructions)
  - [Raspberry Pi Setup](#raspberry-pi-setup)
  - [Setting up OwnCloud](#setting-up-owncloud)
- [Usage](#usage)
- [Features](#features)
- [Limitations](#limitations)
- [Contributing](#contributing)
- [License](#license)

## Setup Instructions

### Raspberry Pi Setup

To set up the Raspberry Pi for use as a personal cloud server, follow these steps:

1. **Headless Setup**: Configure the Raspberry Pi without a monitor, keyboard, or mouse using VNC over the network.
2. **OS Installation**: Download and install the Raspberry Pi OS (Raspbian Buster with desktop and recommended software) on an SD card.
3. **Network Configuration**: Enable SSH and configure Wi-Fi connectivity by adding appropriate files to the SD card.
4. **Initial Boot**: Insert the SD card into the Raspberry Pi, connect it to power, and boot it up.
5. **Find IP Address**: Use an IP scanner to find the IP address of the Raspberry Pi.
6. **SSH Access**: Use PuTTY to SSH into the Raspberry Pi using its IP address.

### Setting up OwnCloud

To install and configure OwnCloud on the Raspberry Pi, follow these steps:

1. **NGINX and PHP Installation**: Update and upgrade the Raspberry Pi, install NGINX, PHP, and required modules.
2. **SSL Configuration**: Generate SSL certificate and configure NGINX for HTTPS connections.
3. **PHP Configuration**: Update PHP configuration files to adjust upload and post sizes.
4. **Swap Memory Setup**: Add swap memory to the system to increase available memory.
5. **MySQL Database Setup**: Install MySQL, create a database, and a user for OwnCloud.
6. **OwnCloud Installation**: Download and extract the OwnCloud archive, configure permissions, and adjust settings.

## Usage

Once the setup is complete, you can access your OwnCloud instance through a web browser using the Raspberry Pi's IP address. You can upload, download, and manage files just like you would with any cloud storage service.

## Features

- **Self-Hosted**: Keep control over your data by hosting your own cloud server.
- **Secure**: Utilize SSL encryption for secure connections.
- **Customizable**: Adjust settings and configurations to suit your needs.
- **Low-Cost**: Use affordable hardware like Raspberry Pi for hosting.

## Limitations

- **Performance**: External access speed may be limited by upload speed.
- **Scalability**: Limited scalability compared to commercial cloud services.
- **Maintenance**: Requires regular maintenance and updates.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [GNU GPL v3.0](LICENSE).
