# Home-Assistant-Config
Configuration files for my Home Assistant instance.

[![Build Status](https://travis-ci.org/nwesterhausen/Home-Assistant-Config.svg?branch=master)](https://travis-ci.org/nwesterhausen/Home-Assistant-Config)

## Environment
I have a server which I use as a Docker host. Alongside other fun things, it runs Home-Assistant and some add-ons:

- Home Assistant ([docs](https://www.home-assistant.io/docs/installation/docker/), [docker hub](https://hub.docker.com/r/homeassistant/))
   - My zwave device is passed through to the container
- Node-red (I built my own image based on node10, [docs](https://nodered.org/docs/platforms/docker))
- EMQTT (Using [emqx-docker](https://github.com/emqx/emqx-docker), [official site](emqtt.io))
   - I have a raspberry pi running [zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt/).
- InfluxDB/Grafana
   - I store all sensor data into InfluxDB
- Traefik (reverse-proxy based on Docker container labels, [official site](traefik.io))
- Cloud9 IDE (For easily editing Home-Assistant configuration files, [docker hub](https://hub.docker.com/r/kdelfour/cloud9-docker/))

## Home Assistant Customizations Used
For my floorplan panel I use [ha-floorplan](https://github.com/pkozul/ha-floorplan) which works brilliantly. I also use the [animated darksky weather card](https://community.home-assistant.io/t/custom-dark-sky-animated-weather-card/59816) in my Lovelace UI.

My Xiaomi sensors record temperature in Celcius, so I template them into Fahrenheit.

I have a custom "home occupancy" sensor which combines a few device trackers to see if at least one person is home.
