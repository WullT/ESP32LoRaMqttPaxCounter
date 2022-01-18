# ESP32LoRaMqttPaxCounter


Counts the number of active BLE devices (smartphones).
* LoRa or WiFi + MQTT as connectivity options
* Configuration via webserver on the MCU


## Hardware

[Adafruit Feather ESP32](https://www.adafruit.com/product/3405) or another ESP32 DevKit

If LoRa is used, a `RFM95W` LoRa Module e.g. [Radio FeatherWing](https://www.adafruit.com/product/3231)

## Setup

### Precompiled sketch

>todo...

### Using Arduino IDE

Set the Partition Scheme to `No OTA (Large APP)`

Following Libraries have to be installed:
* [CRC32](https://github.com/bakercp/CRC32)
* [PubSubClient](https://github.com/knolleary/pubsubclient)
* [AsyncTCP](https://github.com/me-no-dev/AsyncTCP)
* [ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer)
* [LMIC](https://github.com/mcci-catena/arduino-lmic)





## Configuration
