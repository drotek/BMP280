BMP280 Barometric Pressure and Temperature sensor
==================================================

[![BMP280 breakout board](http://www.drotek.com/shop/2550-thickbox_square_zen/bmp280-breakout-board.jpg)  
*BMP280 breakout board *](http://www.drotek.com/shop/fr/home/751-bmp280-breakout-board.html)

The Bosch BMP280 chip incorporates two sensors: a Barometric pressure sensor and an other one for temperature.
this cheap but accurate sensor is perfect for all weather applications thanks to the ± 1hPa / ± 1 ° C accuracy.
With the barometer, this sensor can also be used as an altimeter with an accuracy of ± 1 meter.
This sensor is also very versatile thanks to its I2C and SPI communication bus

More information for this repo can be found on the [Drotek.com product page](http://www.drotek.com/shop/fr/home/751-bmp280-breakout-board.html)

Wiring and Test
-------------------
On the exemple include with BMP280 arduino library you can use 3 types of wiring: I2C, Hardware SPI or Software SPI 
Just Uncomment 1 of the 3 lines and write the output used for Software SPI.

Use the image below to wire your card for I2C use. 
[![BMP280 breakout board](http://www.drotek.com/ftp/photo/drotek%20bmp280%20I2C.jpg)

Use the image below to wire your card for Hardware SPI. 
[![BMP280 breakout board](http://www.drotek.com/ftp/photo/drotek%20bmp280%20SPI%20hard.jpg)

For arduino Méga 2560 you need to change the numbers of outputs like this:

			#define BMP_SCK 52
			#define BMP_MISO 50
			#define BMP_MOSI 51 
			#define BMP_CS 53


Use the image below to wire your card for Software SPI. 
[![BMP280 breakout board](http://www.drotek.com/ftp/photo/drotek%20bmp280%20SPI%20soft.jpg)

In this case you need to change the numbers of outputs according to your wiring. 

Repository Contents
-------------------
* **/Software** - Any Adafruit Arduino library needed to used this product, 
* **/Hardware** - PDF design files

License Information
-------------------
The hardware is released under [Creative Commons Share-alike 3.0](http://creativecommons.org/licenses/by-sa/3.0/).  

Code is developped by Adafruit under open source, so why rewrite something that works fine :) 
