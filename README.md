# Introduction 
General sensor node running Mongoose OS on either a ESP8266 or ESP32 based MCU.

# Hardware

The software has been tested on the following boards

 - NodeMCU ESP8266
 
# Getting Started

To configure the device sensors and the correct network and MQTT broker credentials, add the correct conf#.json file where # is a number from 1-9 (see Mongoose OS configuration for more details) in the fs directory. 

You can also provide a device id in the configuration.  See the sample config file for an example

Build with
```mos build --clean```

Now flash with:
```mos flash```

A web UI to configure the wifi and MQTT settings is in the works.

# The software
