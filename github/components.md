# Components Used
Here is a long list of the Home Assistant Components I use, and my thoughts.

- Device Tracker
  - Google Home BLE
  - [GPSLogger](#gpslogger)
  - [Tile](#tile)
  - Unifi
- Image Processing
  - Tensorflow
- Sensors
  - 17Track
  - command_line
  - Darksky
  - imap_email_content
  - min_max
  - Moon
  - Nest
  - pi_hole
  - Season
  - Tautulli
  - Template
  - Version
  - zigbee2mqtt
  - Z-Wave
- Media Players
  - Roku
  - Google Cast
- Lights
  - Yeelight
  - Z-Wave
- Switches
  - TP Link
  - zigbee2mqtt
  - Z-Wave
- Binary Sensors
  - MQTT
  - zigbee2mqtt
- Cameras
  - Generic
  - MJPEG 
- Cloud
  - Google Assistant

## Device Trackers

### GPSLogger
GPSLogger has worked amazingly well. We were using Owntracks MQTT prior, but had a lot of issues with Owntracks deciding we suddenly were half a mile away from where we were at (stationary). I really like that GPSLogger stops sending updates when your phone is still. It uses barely any battery on top of the improved reliability.

Also now that it is an integration with a webhook it is **even easier** to get going, and we don't have to create a LLAT for each user.

- [Official Home Assistant Documentation](https://www.home-assistant.io/components/gpslogger/)
- [GPSLogger on Google Play Store]()

### Tile
Tile is a neat idea in principle but in practice it was not. The updates were quite delayed and often came at useless times. There may be usefulness later, perhaps, but not sure at the moment.

- [Official Home Assistant Documentation]()

### Google Home BLE
Expo on component

- [Offical Home Assistant Documentation]()

### Unifi
Expo on component

- [Offical Home Assistant Documentation]()

## Image Processing

### Tensorflow
Expo on component

- [Offical Home Assistant Documentation]()

## Sensors

### 17Track
Expo on component

- [Offical Home Assistant Documentation]()

### command_line
Expo on component

- [Offical Home Assistant Documentation]()

### Darksky
Expo on component

- [Offical Home Assistant Documentation]()

### imap_email_content
Expo on component

- [Offical Home Assistant Documentation]()

### min_max
Expo on component

- [Offical Home Assistant Documentation]()

### Moon
Expo on component

- [Offical Home Assistant Documentation]()

### Nest
Expo on component

- [Offical Home Assistant Documentation]()

### pi_hole
Expo on component

- [Offical Home Assistant Documentation]()

## Season
Expo

[Official Home Assistant Documentation]()

## Tautulli
Expo

[Official Home Assistant Documentation]()

## Template
Expo

[Official Home Assistant Documentation]()

## Version
Expo

[Official Home Assistant Documentation]()

## zigbee2mqtt
Expo

[Official Home Assistant Documentation]()

## Z-Wave
Expo

[Official Home Assistant Documentation]()


# Media Players
## Roku
Expo

[Official Home Assistant Documentation]()

## Google Cast
Expo

[Official Home Assistant Documentation]()


# Lights
## Yeelight
Expo

[Official Home Assistant Documentation]()

## Z-Wave
Expo

[Official Home Assistant Documentation]()


# Switches
## TP Link
Expo

[Official Home Assistant Documentation]()

## zigbee2mqtt
Expo

[Official Home Assistant Documentation]()

## Z-Wave
Expo

[Official Home Assistant Documentation]()


# Binary Sensors
## MQTT
Expo

[Official Home Assistant Documentation]()

## zigbee2mqtt
Expo

[Official Home Assistant Documentation]()


# Cameras
## Generic
Expo

[Official Home Assistant Documentation]()

## MJPEG 
Expo

[Official Home Assistant Documentation]()


# Cloud
## Google Assistant
Expo

[Official Home Assistant Documentation]()
