# Components Used
Here is a long list of the Home Assistant Components I use, and my thoughts.

- Device Tracker
  - GPSLogger
  - Unifi
  - Tile
  - Google Home Bluetooth

## GPSLogger
GPSLogger has worked amazingly well. We were using Owntracks MQTT prior, but had a lot of issues with Owntracks deciding we suddenly were half a mile away from where we were at (stationary). I really like that GPSLogger stops sending updates when your phone is still. It uses barely any battery on top of the improved reliability.

Also now that it is an integration with a webhook it is **even easier** to get going, and we don't have to create a LLAT for each user.

## Tile
Tile is a neat idea in principle but in practice it was not. The updates were quite delayed and often came at useless times. There may be usefulness later, perhaps, but not sure at the moment.