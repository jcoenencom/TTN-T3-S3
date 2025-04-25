# TTN-T3-S3
 LoRaWan TTGO T3-S3 on The Things Network

First shot at the project done on Arduino IDE on local Mac.

Time to go on GitHub to manage the code.

Using GitHub Desktop on OSX.

VLC can handilly be used for the editorial contents (README/WiKi)

Experimentation with TTN.

See the Wiki for further information on setup/configuration.

Using TTGo Modules on 868 MHz.

RadioLib used to manage the RF module.

A combined module AHT20 + BMP280 has been connected on PIN 15 and 16 defined as secondary I2C bus, the first bus being used for the SSD1306 OLED display, but as PIN 17 is not exposed on the board it cannot be used to connect additional I2C devices.

(The example RadioLib OTAA)[https://github.com/Xinyuan-LilyGO/LilyGo-LoRa-Series/tree/master/examples/LoRaWAN/RadioLib_OTAA] has been used to connect to TTN.