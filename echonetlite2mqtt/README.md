# ECHONETLite2MQTT

ECHONET Lite to MQTT bridge.

## Description


This application publishes ECHONET Lite devices to MQTT.
And uses MQTT to work with ECHONET Lite devices.
This will allow you to operate your ECHONET Lite device from a smart home application that supports MQTT.

![topimage](images/topimage.jpg)


The supported devices are as follows.
* Emergency button (0x0003)
* Human detection sensor (0x0007)
* Temperature sensor (0x0011)
* Humidity sensor (0x0012)
* Bath heating status sensor (0x0016)
* CO2 sensor (0x001B)
* VOC sensor (0x001D)
* Electric energy sensor (0x0022)
* Current sensor (0x0023)
* Illuminance sensor (0x00D0)
* Home air conditioner (0x0130)
* Ventilation fan (0x0133)
* Air conditioner ventilation fan (0x0134)
* Air cleaner (0x0135)
* Package-type commercial air conditioner (indoor unit) (except those for facilities) (0x0156)
* Package-type commercial air conditioner (outdoor unit) (0x0157)
* Electrically operated rain sliding door/shutter (0x0263)
* Electrically operated window (0x0265)
* Electric water heater (0x026B)
* Electric lock (0x026F)
* Instantaneous water heater (0x0272)
* Bathroom heater dryer (0x0273)
* Household solar power generation (0x0279)
* Cold or hot water heat source equipment (0x027A)
* Floor heater (0x027B)
* Fuel cell (0x027C)
* Storage battery (0x027D)
* EV charger and discharger (0x027E)
* Watt-hour meter (0x0280)
* Water flowmeter (0x0281)
* Gas meter (0x0282)
* Power distribution board metering (0x0287)
* Low-voltage smart electric energy meter (0x0288)
* High-voltage smart electric energy meter (0x028A)
* Smart electric energy meter for sub-metering (0x028D)
* General lighting (0x0290)
* Mono functional lighting (0x0291)
* EV Charger (0x02A1)
* Lighting system (0x02A3)
* Extended lighting system (0x02A4)
* Hybrid water heater (0x02A6)
* Refrigerator (0x03B7)
* Cooking heater (0x03B9)
* Rice cooker (0x03BB)
* Commercial showcase (0x03CE)
* Washer and dryer (0x03D3)
* Commercial show case outdoor unit (0x03D4)
* Switch (supporting JEM-A/HA terminals) (0x05FD)
* Controller (0x05FF)
* Television (0x0602)


## DEMO

![demo-webui](demo/demo_webUI.gif)

![demo-aircon](demo/demo-AirCnditioner-daikin.gif)

For more demo movies and settings examples, please refer to the [ECHONETLite2MQTT page](https://github.com/banban525/echonetlite2mqtt).

## Third party use

* The images in the repository use materials such as "いらすとや" (https://www.irasutoya.com/).
* Machine Readable Appendix (MRA) Version 1.1.1 is ​​used as the definition of ECHONET Lite. (https://echonet.jp/spec_mra_rp1/)

## LISENCE

[MIT](LICENSE)

## Author

[banban525](https://github.com/banban525)

