**Interactive-Wi-Fi-Deauther** is an Open Source Project, that can be used to:
* Scan Networks, 
* Deauthenticate Users from a Network, 
* Create Multiple Clones of a Network to confuse the users!

It also has an **OLED Display** and **Navigation Buttons on Board**, which can be used to display the networks, scan the packets, and launch the attacks

To make things better, it also has a web interface, which can be accessed by going to the following URL after connecting to the Deauther Board
```
192.168.4.1
```
## Disclaimer

This project is a proof of concept for testing and educational purposes.
Neither the ESP8266, nor its SDK was meant or built for such purposes. Bugs can occur!

Use it only against your own networks and devices!
Please check the legal regulations in your country before using it.
We don't take any responsibility for what you do with this program.

## Acknowledgements

Huge thanks to [@spacehuhnTech](https://github.com/SpacehuhnTech) for keeping this project open source!

## Libraries used for this project
* [esp8266-oled-ssd1306](https://github.com/ThingPulse/esp8266-oled-ssd1306)
* [ArduinoJson](https://github.com/bblanchon/ArduinoJson)
* [Adafruit_DotStar](https://github.com/adafruit/Adafruit_DotStar)
* [Adafruit_NeoPixel](https://github.com/adafruit/Adafruit_NeoPixel)
* [DS3231](https://github.com/NorthernWidget/DS3231)
* [my92xx](https://github.com/xoseperez/my92xx)

## Recommended Drivers for ESP8266 Boards
* [💾 CP2102](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads)
* [💾 CH340](https://sparks.gogo.co.nz/ch340.html)
