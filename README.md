# LoRa-Shepherd
C code drivers for the Shepherd board (ESP8266 with LoRa RFM98). Drivers also run on the Raspberry Pi 

The Shepherd board is a general purpose piece of open source hardware/Software that connects the LoRa 434MHz transceiver to an ESP8266 ESP-07 chip. It was originally designed as a location tool for a High Altitude Balloon (HAB) project but gives access via headers to both chips and allows them to be used independently or together. It is a surface mount boad but soldering at home is quite possible as large descrete components have been used. Just add a USB cable to provide 5V power and you can experiment with the power of the LoRa device. 

Full details of the hardware (inc. schematics, parts list etc) can be found on the Shropshire Linux Users Group pages. This repository is just for the software drivers.

In order to program the ESP8266, you will need a USB to RS232 TTL level shifter and a USB cable to connect to your Windows or Linux machine, be familiar with the Arduino IDE for ESP8266.

