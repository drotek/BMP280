﻿BMP280 Barometric Pressure and Temperature sensor
==================================================


The Bosch BMP280 chip incorporates two sensors: a Barometric pressure sensor and an other one for temperature.
this cheap but accurate sensor is perfect for all weather applications thanks to the ± 1hPa / ± 1 ° C accuracy.
With the barometer, this sensor can also be used as an altimeter with an accuracy of ± 1 meter.
This sensor is also very versatile thanks to its I2C and SPI communication bus

More information for this repo can be found on the [Drotek.com product page](http://www.drotek.com/shop/en/home/751-bmp280-breakout-board.html)

Wiring and Test
-------------------
On the exemple include with BMP280 arduino library you can use 3 types of wiring: I2C, Hardware SPI or Software SPI with Arduino UNO or Arduino MEGA2560.
In this program you simply need to follow the 3 steps configuration, everything is explained.

Use the image below to wire your card for I2C use. 
[![BMP280 breakout board](http://www.drotek.com/ftp/photo/drotek%20bmp280%20I2C.jpg)

Use the image below to wire your card for Hardware SPI. 
[![BMP280 breakout board](http://www.drotek.com/ftp/photo/drotek%20bmp280%20SPI%20hard.jpg)

Use the image below to wire your card for Software SPI. 
[![BMP280 breakout board](http://www.drotek.com/ftp/photo/drotek%20bmp280%20SPI%20soft.jpg)

Repository Contents
-------------------
* **/Software** - Any Arduino library needed to used this product. !!please note that the two library include in this folder are required.
* **/Hardware** - PDF design files

License Information
-------------------
The hardware is released under [Creative Commons Share-alike 4.0](http://creativecommons.org/licenses/by-sa/4.0/).  

Code is developped under open source, so why rewrite something that works fine :) 
