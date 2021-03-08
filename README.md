# SmartEVCharger

![Smartchager](images/smartcharger.png)

This repo contains some of the code snippets for [OpenHAB](https://www.openhab.org/) to link with an EV Charger based on [OpenEVSE](https://www.openevse.com/).

It monitors the energy taken from or delivered to the net using a ZWave Aeotec energy meter or an EM24 carlo gavazzi (or any other energy meter) to monitor the energy consumption and control the OpenEVSE using MQTT.



![System Schematic](images/schematics.png)

Use Materials:

- Old enclosure of EV charger with Type2 connector
- OpenEVSE components:  https://store.openevse.com/collections/all-products/products/openevse-international-combo-openevse-v3
- Raspberry Pi (I use rpi4 for openhab)
- Current sensor, e.g. EM24, but others work as well

Current options implemented:

![Options](images/3options.png)


More info on [Youtube](https://youtu.be/_YUrnYUuvRo).

