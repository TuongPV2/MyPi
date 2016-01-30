This project is based on Adafruit Python DHT Sensor Library
Copyright @ Adafruit
===============================================================================
##Project aim:
- Read room's temperature and humidity by using DHT11
- Update data to thingspeak.com
My channel is: https://thingspeak.com/channels/82606

===============================================================================
##How's to:

###Prepare:
- 01 Raspberry Pi (I am using Pi2, B) with power suppy and wifi dongle (or ethernet)
- 01 DTH11
- Breakboard, wire
- 1 4.7kOhm resister

###Installation:
Read Adafruit README

###Register an account on thingspeak.com. It's free!!
Create a channel
Read more here: https://www.mathworks.com/help/thingspeak/getting-started-with-thingspeak.html
###Run:
cd examples/
vi AdafruitDHT.py (or nano AdafruitDHT.py)
Add your API key (at line 61)
save and quit vi
-----
./AdafruitDHT.py 11 4 (11 - DHT11, 4 - pin 4th of Pi)

See the graph and customise you channel

Viel Spaß ^^
