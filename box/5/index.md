---
title: What's in the box?
lang: en
layout: generic
---

## Environmental exploration

This is a simple guide to get started with the content of the hardware kits!

### Base platform

 * Arduino Pro Mini 3.3V 8Mhz [Datasheet](https://www.arduino.cc/en/Main/arduinoBoardProMini), [Getting started](https://www.arduino.cc/en/Main/arduinoBoardProMini)
 * FTDI (USB to UART brige) [Video Howteo](https://www.youtube.com/watch?v=-Myj5yQvI_4)
 * Microchip RN2483 LoRaWAN modem [Datasheet](http://ww1.microchip.com/downloads/en/DeviceDoc/50002346B.pdf)
 * Breadboard power supply [Datasheet](https://hobbyking.com/media/file/403178644X1017066X57.pdf), [How to use](https://www.sunfounder.com/wiki/index.php?title=How_to_use_YwRobot_Power_Supply_Properly)

### Sensors

 * UV IR Visible Sensor SI1145 [Breakout info](https://cdn-learn.adafruit.com/downloads/pdf/adafruit-si1145-breakout-board-uv-ir-visible-sensor.pdf), [Datasheet](https://cdn-shop.adafruit.com/datasheets/Si1145-46-47.pdf)
 * Sensirion SHT21 temperature/humidity (by Decentlab) [Datasheet](http://staging1.unep.org/uneplive/media/docs/air_quality/aqm_document_v1/Blue%20Print/Components/Microcomputer%20and%20sensors/D.%20Supporting%20Sensors/D.1%20Temp%20&%20Humidity/Datasheet%20SHT21.pdf)
 * BME280 Temperature/humidity/pressure [Breakout info](https://cdn-learn.adafruit.com/downloads/pdf/adafruit-bme280-humidity-barometric-pressure-temperature-sensor-breakout.pdf), [Datasheet](https://cdn-shop.adafruit.com/datasheets/BST-BME280_DS001-10.pdf)
 * MQ-x gas sensors [Product information](http://playground.arduino.cc/Main/MQGasSensors)
 * Laser PM2.5 Sensor SDS011 [Datasheet](http://inovafitness.com/software/SDS011%20laser%20PM2.5%20sensor%20specification-V1.3.pdf), [Javascript library](https://github.com/chatch/nova-sds011), [Windows Drivers](http://inovafitness.com/en/download/Drive-Software-8.html)
 * 5-way flame sensor [Product description](http://hobbydistrict.com/en/product/5-way-flame-sensor-module/)


### Basic resources

 * LoRaWAN & The Things Network:
    * [Documentation](https://www.thethingsnetwork.org/docs/)
    * [Arduino devices](https://www.thethingsnetwork.org/docs/devices/arduino/)
    * [Forum](https://www.thethingsnetwork.org/forum/)
 * Hackathon community platform:
    * [Hackathon projects](https://now.makezurich.ch)
    * [Slack team](https://ttn-ch.slack.com/) (sign up here [here](https://ttn-ch.herokuapp.com/))
 * Various posts/articles:
    * [How to build your first TTN node](https://www.thethingsnetwork.org/forum/t/how-to-build-your-first-ttn-node-arduino-rn2483/1574)
    * [Building a TTN LoRaWAN node](https://www.vdsar.net/build-ttn-lora-node/)

### Additional resources

Provided by Umwelt- und Gesundheitsschutz and EMPA:

 * [Measurements, December 2016, EMPA](empa_december_2016.zip)
 * [Measurements, December 2016, UGZ](ugz_december_2016.zip)
 * [Alphasense Application Note - Environmental Changes: temperature, Pressure, Humidity](https://zueriluft.ch/makezurich/AAN110.pdf)
 * [Alphasense Application Note - Correcting For Background Currents In Four Electrode Toxic Gas Sensors](https://zueriluft.ch/makezurich/AAN803.pdf)
 * [Open Data, Hourly updated air quality measurements](https://data.stadt-zuerich.ch/dataset/luftqualitaet-stunden-aktuelle-messungen)
 * [Vertical temperature profile in Zurich area](http://awel.meteotest.ch/regionprofile/)
 * [Temperature profile](https://zueriluft.ch/makezurich/tprofil.csv)

> **NOTE:** Please keep in mind the voltage differences between the microcontroller and the different sensors when connecting them
