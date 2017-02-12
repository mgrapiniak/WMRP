# Hardware and Arduino Code for DIY WMRP-Solder Station
This is an attempt to implement some improvements:

* Replace LCD with 1.8 Inch Serial SPI TFT LCD Display Module
* Add SPI header onto PCB
* Code amendments

Contributors:
- Bartosz Wapniewski



Video: https://www.youtube.com/watch?v=le2HaKJ6B1A

If you have any questions, please feel free to contact me: flyglas (at) gmail (dot) com


__Features:__
* low offset op amp for soldering tip temperature measurement with type D thermocouple
* cold junction compensation using the PTC (KTY82-110) included in the WMRP soldering pencil
* input voltage measurement (for use with 3 cell lipo battery)
* soldering pencil current measurement 
* recognizing if the soldering pencil rests in the stand (--> standby)
* 3 buttons for save and recall temperature values
* rotary encoder to set soldering temperature
* illuminated 16x2 character LCD module
* USB for debugging and firmware update
* clean and small enclosure
* 4mm safety socket for +12V power input and a protective earth socket for connection to ESD protection


The BOM in the layout folder includes only the parts on the PCB(s).

__Parts (not on PCB):__
* lcd display from ebay "Blue I2C 1602"
* modified connector "Amphenol T 3437 000" (--> http://www.mikrocontroller.net/topic/143288#1500819)
* 4mm safety sockets (red, black, green/yellow) or any other suitable connector
* rotary encoder knob
* display frame "EA027-2UKE"
* aluminium enclosure "Proma 131020"

__Info:__
* close jumper JP1 (activates pullup resistors for I2C wires)
* close jumper JP3 (connection between power ground and analog ground)
* leave jumper JP2 open (alternative for JP3)

__Photos:__
![outside](https://github.com/FlyGlas/WMRP/blob/master/pictures/IMG_20150507_002144.jpg "outside")

![outside](https://github.com/FlyGlas/WMRP/blob/master/pictures/IMG_20150412_134210.jpg "outside")

The PCB is a little bit dirty. The Isopropanol was empty and now everything is in the enclosure.
![inside](https://github.com/FlyGlas/WMRP/blob/master/pictures/IMG_20150411_152047.jpg "inside")

![inside](https://github.com/FlyGlas/WMRP/blob/master/pictures/IMG_20150411_152116.jpg "inside")

Stand for enclosure Proma 131020:
![inside](https://github.com/FlyGlas/WMRP/blob/master/stand/IMG_20150928_124547.jpg "inside")

![inside](https://github.com/FlyGlas/WMRP/blob/master/stand/IMG_20150928_125554.jpg "inside")

![inside](https://github.com/FlyGlas/WMRP/blob/master/stand/wmrp_stand_30deg.png "inside")

__First picture of a replica:__

Thank you Dennis for the nice conversation and the picture.
![inside](https://github.com/FlyGlas/WMRP/blob/master/pictures/diy_wmrp_dennis.jpg "inside")
