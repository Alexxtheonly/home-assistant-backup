This is my humble hass.io configuration repository. It is and will forever be a work in progress.  
My main goal is to automate as much as posible to a near perfect level of efficiency.

This readme will be gradually updated.

[![Build Status](https://travis-ci.org/Alexxtheonly/home-assistant-backup.svg?branch=master)](https://travis-ci.org/Alexxtheonly/home-assistant-backup)

*Last updated: 2019-03-10*

## Implemented automations

* Lights
  * On/Off based on movement and luminosity
  * Stay on in room with last movement
  * Adjust brightness and temperature based on [Circadian rhythm](https://en.wikipedia.org/wiki/Circadian_rhythm)
  * Hallway lights on when door is open and luminosity below threshold
  * While sleeping do not turn on bedroom lights, other lights use lowest brightness
  * All lights out as soon as no longer at home
* Alarm
  * Arm when not at home
  * Disarm when at home
  * Arm when asleep
  * Notification when alarm is triggered
* Climate
  * Set heat/eco based on presence
  * Set max heat in bathroom while showering
* Air purifier
  * Turn on/off LED based on sleep state
  * Set max every 5 hours for 30 minutes while not asleep
* Surveillance
  * Enable/Disable motion detection for indoor cameras if somebody is home
  * While alarm is armed every movement is recorded
* System
  * Automatic backup once a week. Backup is sent to a remote location.
* Push messages
  * Alarm has been triggered
  * Good time to air (outside humidity < inside humidity)
  * Commute time and weather on workdays

## Components

**Router**  
AVM FRITZ!Box 7530

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

**Air purifier**
Xiaomi Air Purifier Pro V7

## Floorplan
![Image of floorplan](/images/floorplan.png)