This is my humble hass.io configuration repository. It is and will forever be a work in progress.  
My main goal is to automate as much as posible to a near perfect level of efficiency.

This readme will be gradually updated.
*Last updated: 2020-09-29*

## Implemented automations

* Lights
  * On/Off based on movement and sun elevation
  * Stay on in room with last movement
  * Adjust brightness and temperature based on [Circadian rhythm](https://en.wikipedia.org/wiki/Circadian_rhythm)
  * Hallway lights on when door is open and sun elevation below threshold
  * While sleeping do not turn on bedroom lights, other lights use lowest brightness
  * All lights out as soon as no longer at home
  * Schedule on/off of aquarium light
* Alarm
  * Arm when not at home
  * Disarm when at home
  * Arm when asleep
  * Notification when alarm is triggered
* Climate
  * Set heat/off based on presence and inside temperature
* Air purifier
  * Turn on/off LED based on sleep state
  * Set speed based on sleep state an frontend slider settings
* Surveillance
  * Enable/Disable motion detection for indoor cameras if somebody is home
  * While alarm is armed every movement is recorded
* System
  * Automatic backup once a week. Backup is sent to a remote location.
* Push messages
  * Alarm has been triggered
  * Videos of detected movement, mostly cats
* Modes
  * Sleep: Disable lights except hallway and toilet; Turn off all lights; Turn off entertainment and computer switches
  * Entertainment: Disable living room lights
  * Air: Turn off heaters - This mode is bound to the door open state, but can also be turned on manually

## Components

**Router**  
AVM FRITZ!Box 7530

**Lights**  
IKEA TRÅDFRI

**Power/Switch**  
TP-Link HS110

**Sensors**  
Aeon Labs MultiSensor 6  
Aeon Labs AEOTEC Door/Window

**Thermostats**  
AVM FRITZ!DECT 301

**Camera**  
Tenvis T8810

**Air purifier**  
Xiaomi Air Purifier Pro V7

## Floorplan
![Image of floorplan](/images/floorplan.png)