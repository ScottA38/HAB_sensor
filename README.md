This is a project to use an ESP8266 module to collect data from both a DHT11 (humdity & temp) sensor and a light dependent resistor and send the data over a LAN network to a specific port

# Modules used:
 - [Adafruit_sensor](https://github.com/adafruit/Adafruit_Sensor) A library that provides an standardising the software interface to many different types of sensors
 - [DHT-Sensor-Library](https://github.com/adafruit/DHT-sensor-library) This library interfaces with different variants of the DHT sensor module. It stiplulates the usage of the Unified sensor library

# Building
 - run `./prepare.sh` to set up submodules and toolchain (only needed once)
 - run `make upload` to build the project and flash the esp8826
 
 This project will simply connect to the WiFi network specified in [src/DHT_Unified_sensor.ino](https://github.com/ScottA38/HAB_sensor) and display the IP address it got once it's connected.
