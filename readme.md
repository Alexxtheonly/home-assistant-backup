This is my humble hass.io configuration repository. It is and will forever be a work in progress.  
My main goal is to automate as much as posible to a near perfect level of efficiency.

This readme will be gradually updated.

[![Build Status](https://travis-ci.org/Alexxtheonly/home-assistant-backup.svg?branch=master)](https://travis-ci.org/Alexxtheonly/home-assistant-backup)

## Components
All components are planned, nothing is currently bought or installed.

**Router**  
AVM FRITZ!Box 7590

**Lights**  
IKEA TRÅDFRI

**Power**  
TP-Link HS110

**Sensors**  
Aeon Labs MultiSensor 6  
Aeon Labs AEOTEC Door/Window

**Thermostats**  
AVM FRITZ!DECT 301

**Camera**  
Tenvis T8810

**Flower monitor**  
Xiaomi Mi Plant Flower Care

## Floorplan
![Image of floorplan](/images/floorplan.png)

## Abbreviations
### Rooms
|Name|Short|
|---|---|
|Living room|rLi|
|Hallway|rHa|
|Toilett|rTo|
|Bathroom|rBa|
|Bedroom|rBe|
|Study|rSt|
|Kitchen|rKi|

### Sensors

|Name|Short|
|---|---|
|Movement|sMo|
|Luminance|sLu|
|Humidity|sHu|
|Temperature|sTe|
|Ultraviolet|sUl|
|Battery|sPo|
|Moisture|sMi|
|Fertilizer|sFe|
|Ampere|sAm|
|Watt|sWa|
|TotalEnergy|sTo|
|Voltage|sVo|

### Entitytypes

|Name|Short|
|---|---|
|Powersocket|eSo|
|Multisensor|eMu|
|DoorSensor|eDo
|Light|eLi|
|Flower|eFl|
|Camera|eCa|
|Thermostat|eTh|

## Naming convention

`Room_EntityType_(**)_Sensor`  

Example:  
`rLi_eMu_sLu` = Living room luminance  
`rLi_eSo_00_sWa` = Living room power socket 00 Watt