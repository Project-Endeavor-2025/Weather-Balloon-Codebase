# Weather Balloon Codebase
This repository contains all the code for the various sensors integrating with the controller in the weather balloon payload of the Endeavor 1 mission.

## Payload Layout
The Raspberry Pi is the controller used for communication with the 5 attached sensors. A battery pack will be attached for powering the controller. Additionally, two cameras will be used for recording footage, and a gps module will be incorporated for tracking the location of the balloon at all times.

The sensors will be connected to the Raspberry through its pinout slots, and log data onto its internal storage (SD card)

## Sensors

### 1. Temperature and Humidity Sensor
The DHT11 Temp & Humidity sensor shall be used to monitor the temperature & humidity in the various levels of the atmosphere.
