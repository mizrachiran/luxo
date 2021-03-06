# luxo switch

The luxo switch is an ESP8266 based switch which can control up to 2 appliances.
It was design to be integrate in existing setups where the module can be hidden behind existing wall switches to control light or outlets.
The board support 90-240v input and outputs.

![Luxo 1](https://raw.githubusercontent.com/mizrachiran/luxo/master/product-images/side2.PNG)

[See more images](https://github.com/mizrachiran/luxo/tree/master/product-images)

# Software

Luxo support the following software:
* [Supla](https://www.supla.org/en/) - free cloud based open source software (offers ios & android apps)
* [Tasmota](https://github.com/arendst/Sonoff-Tasmota) - firmeware for controlling over MQTT

However, You can customize any ESP8266 open source project to work with the luxo switch

# Specification

* ESP8266 (ESP12E) WLAN module
* Wi-Fi 2.4GHz 802.11 b/g/n
* 90-240V I / O
* 2x outputs 10A, L switched
* 2x button connectors (to connect on \ off switches)
* Tempreture sensor input (DS18B20, DHT11 or DHT22)
* 1 ADC measurement input, e.g light intensity measurement from photoresistor
* 1 CFG button to enable the module into the configuration mode or assign custom action via software.
* 1 status LED
* Programming header pins (TX, RX, RST, 3.3v, GPIO0, GND)
* Size - 42 x 43 x 22 mm

# Schematic

![Luxo schematic](https://raw.githubusercontent.com/mizrachiran/luxo/master/Schematic.png)

