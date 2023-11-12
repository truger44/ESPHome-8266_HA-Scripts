# ESPHome-8266_HA-Scripts

Freezer_sensor.yaml
A yaml script to alert the user of a high temperature before food is spoiled.

DoorBell.yaml
A basic yaml script to publish a message after a current is sensed in the current clamp

To utilize:
- Be sure to swap in your wifi SSID / password
- create a unique 44 character key for your encryption api in order to connect to home assistant
    - You could also do a initial install using ESPHome ( https://esphome.io/projects/) and utilize the key provided.
-  Fill in MQTT broker address and credentials
-  Add MQTT integration in home assistant if not already installed.
