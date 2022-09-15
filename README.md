# ESPWater
An ESP8266 based garden watering computer running [ESPHome](https://esphome.io)

## Sponsor
![image](https://user-images.githubusercontent.com/13995143/184159660-3a476f93-58ee-4487-b305-6b044c7b1c4e.png)

This project has been sponsored by [PCBWay](https://www.pcbway.com/)!

You can order this project from PCBWay at a $5 discount by using my [referal link](https://www.pcbway.com/setinvite.aspx?inviteid=590728)

## Pinout
- Valve 1: GPIO14 (D5)
- Valve 2: GPIO12 (D6)
- Valve 3: GPIO13 (D7)
- Valve 4: GPIO15 (D8)
- Sensor Ports (Don't use both simultaneously if your sensors aren't connected over I²C): SCL - GPIO5 (D1), SDA - GPIO4 (D2)

## Tested components
- WeMos D1 Mini ESP8266
- 5V BME680 sensor
- 3.3V SHT3X-D sensor
- 2-pin KF301 connectors
- LM2596HV based 24VAC to 5VDC PSU
- 24VAC Galcon Valves
- 220VAC to 24VAC Galcon Transformer

## Safety
For your own safety, do not mess with mains voltage unless you're an electrician!
