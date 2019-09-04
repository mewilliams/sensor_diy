
Where to get parts for DIY sensors in Chile?

Atlas Scientific: via [Caleuche Tecnologias](http://www.caleuchetecnologias.cl/index.html)

Arduino: 
*	[MCI Electronics](www.mcielectronics.cl/) - with a location in Viña del Mar (Avenida Viana).
*	[Mouser.cl](mouser.cl) - these prices are in USD.

Various sensors:

*	aliexpress
*	[altronics.cl](https://altronics.cl) - online only. They have a [pressure sensor for 9500CLP](https://altronics.cl/instrumentacion-industrial/medicion-presion/sensor-presion-hk1100c) on an analog signal: 0 - 1.2MPa. A [temperature sensor](https://altronics.cl/sensor-sonda-temperatura-ds18b20) . This page has links for how to use these sensors.
*	[Tienda 8](tienda8.cl) - in Concepción. They have some sensors: barometric pressure, carbon monoxide, temperature.
*	Real time clock DS3231 [Max Electronica](http://www.maxelectronica.cl/45-rtc-memorias)

***

The internet is full of blogs with useful information. 

Some to check out: 

[The Cave Pearl Project - underwater arduino data loggers](https://thecavepearlproject.org) in general.
Specifics from that site, [How to Build an Arduino Data Logger](https://thecavepearlproject.org/how-to-build-an-arduino-data-logger/) 
[Open wave height logger](https://lukemiller.org/index.php/2014/08/open-wave-height-logger/) and the [OWHL github page](https://github.com/millerlp/OWHL)


***
On temperature sensors, from the Cave Pearl Project comments:

>To date I have been working with I2C breakouts (Sparkfuns tmp102 & Adafruits MCP9808) and one-wire DS18b20’s. All give you 0.0625C resolution but the MCP9808 gives a reasonably decent ±0.25 accuracy. The DS18s take quite a bit of calibration because there is a large amount of quality variation, but they have the strength that you can hook so many of them to very long wires. This multi-drop aspect of the DS18B20’s keeps bringing me back to that sensor over and over again. To be honest, all of them are ‘just OK’ as most of the caves we work in have less than 1 degree Celsius of variation all year. But what I really want for the cave work is an affordable sensor that can give me ±0.1C accuracy and 0.01C resolution. RTDs and Thermistors can deliver that but I have not had a chance to play with them yet.

>[Update] In 2017 I got the thermistors working at high resolution with better than ±0.2C accuracy .
***



The OpenCTD project



***


Things I need for an OpenCTD: 

arduino and logger. If not the adafruit, maybe 

Nano logger [here](http://www.maxelectronica.cl/shield-arduino/555-shield-arduino-nano-data-logging-con-rtc-ds1307-y-slot-micro-sd.html) with the [Nano](http://www.maxelectronica.cl/tarjetas-arduino/397-arduino-nano-atmega328-version-de-pines-sin-soldar.html), the real time clock (http://www.maxelectronica.cl/rtc-memorias/57-modulo-i2c-rtc-ds3231-con-memoria-eeprom-atmel24c32-y-bateria-incluida.html) 

Prototype board [on MCI electronics](https://www.mcielectronics.cl/en_US/shop/product/prototype-pcb-compatible-con-modulos-xbee-23409?search=prototype+pcb)



***
UK supplier of Adafruit
Pimeroni.com: 

Product image	Description	Quantity	Price

Adafruit Perma-Proto - pack of 3
Quarter size
1	£6.50

DS3231 Precision RTC FeatherWing - RTC Add-on For Feather Boards
1	£10.75

Adafruit Feather M0 Adalogger
1	£15.25



