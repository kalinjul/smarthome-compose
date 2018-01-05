# smarthome-compose
Inspired by https://github.com/henfri/docker

This is a docker-compose file with required config directories for running:
- smarthome-ng
- smartvisu
- knxd

Currently not running (but originally included in henfri's compose file):
- owfs (one wire)
- influxdb
- grafana
- openhab

To run this, you will need git and docker-compose.

# Install docker compose

# Clone this repository

```git clone git@github.com:julakali/smarthome-compose.git```

# Configuration of KNXd

# Configuration of smarthome-ng

# Installation/Configuration of smartvisu

Change to the directory in which docker-compose.yml is located.
```
wget http://www.smartvisu.de/download/smartVISU_2.8.zip
unzip smartVISU_2.8.zip
```
SmartVISU files should now be in <directory of docker-compose.yml>/smartVISU.
The smarthome-ng plugin 'smartvisu' will generate its pages to smartVISU/pages/.

# Startup

```docker-compose up```
