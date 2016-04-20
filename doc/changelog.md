# ESP8266 Node changelog

## v0.1

 - First board design. Designed to have one [bmp180](https://www.adafruit.com/products/1603) sensor connected to RJ-11 connector.
 - Intended to be manufactured by [dirtypcbs.com](http://dirtypcbs.com/).
 - Powered by mini DC-DC power supply module ([LM2596](http://www.ti.com/lit/ds/symlink/lm2596.pdf) chip).
 - 5.5 mm center positive jack.
 - On-board programming connector.
 - Programming push button.
 - Jumper for enabling power supply module.
 - THT notification LED.

## v0.1.1

 - GPIO15 grounded with 12K resistor.
 - Board label changed to "ESP8266 NODE".
 - THT notification LED replaced with SMD 1206 package.
 - RJ-11 label changed to "SENSOR_CONN"
 - Changed pin order on ISP header. Now it chould be similiar to AVR ISP header.
 - Added ESP8266 RX and TX pins to unused RJ-11 pins (1 and 6).
 - GPIO0 is used only for entering programming mode. Not used in RJ-11 connector.
 - RJ-11 is connected to GPIO2 and GPIO14 pins.
 - ISP voltage pin is connected to 3-pin jumper. User can choose to connect it to 3V3, VIN or disconnect it.
