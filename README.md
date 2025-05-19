# Zigbee2MQTT Configuration

This repository contains a Docker Compose configuration for running Zigbee2MQTT, a bridge that allows you to use your Zigbee devices with any MQTT broker.

![image](https://github.com/user-attachments/assets/4e9c3e26-7478-4feb-b890-360ed63ce1e5)

## Setup

1. Ensure you have Docker and Docker Compose installed
2. Connect your Zigbee USB adapter to your system
3. Adjust the serial port in `docker-compose.yml` if needed (default: `/dev/ttyUSB0`)
4. Set your timezone in the environment variables
5. Run with `docker-compose up -d`

## Features

- Runs Zigbee2MQTT in a Docker container
- Persists configuration in the `./data` directory
- Exposes web interface on port 8080
- Automatic container restart unless explicitly stopped

## Requirements

- Docker and Docker Compose
- Zigbee USB adapter
- MQTT broker (not included in this configuration)

## Keywords

#zigbee #mqtt #home-automation #iot #smart-home #zigbee2mqtt #docker #docker-compose #home-assistant #homebridge #zigbee-bridge #mqtt-broker #smart-devices #zigbee-gateway #home-automation-tools
