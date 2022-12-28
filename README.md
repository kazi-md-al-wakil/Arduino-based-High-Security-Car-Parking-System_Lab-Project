# Arduino-based-High-Security-Car-Parking-System_Lab-Project_CSE360
## Project Title: 
Arduino based High Security Car Parking System
## Project Description:
It is not new that vehicles get stolen from parking lot even though there are security guards. That is where 
our project comes. We are intended to build a prototype where ensuring security will be our first priority. 
Firstly, when a car will arrive to the parking lot, the driver of the car will have to give his fingerprint, which 
will be stored in the database. A 16x2 LCD Display will be Welcoming the driver and will show how many 
slots are left to park. In this way, guards do not need to count if the parking lot is empty or not. Also, 
Temperature and Humidity Sensor will help to show temperature of the parking lot in the LCD display. 
This will help the automated system whether to turn on the heater.
If there are empty slots in the parking lot then the gate will be opened using Servo Motor and here, we will 
be using IR Proximity Sensor to sense the presence of the vehicle.
Main part of security comes when a car is to leave the parking lot. At that point, the driver will have to pass 
1 checkpoint. In the checkpoint, driver will have to give his fingerprint through Fingerprint sensor. If his 
fingerprint is on the database the Green Led light attached to the gate will be turned on and the gate will 
be opened. It will be automated by Servo Motor. Otherwise, the gate remains closed. Now, the vehicle is 
ready to leave the parking lot. 
We will do the project with Arduino Uno as our interfacing IC.

## Components Required: 
- Arduino UNO 
- IR Proximity Sensor 
- Fingerprint Sensor
- Temperature and Humidity Sensor 
- Servo Motor 
- 16x2 LCD i2c Display 
- LED light
- Jumpers

## Connection Diagram
<img src = "https://github.com/kazi-md-al-wakil/Arduino-based-High-Security-Car-Parking-System_Lab-Project_CSE360/blob/master/Fritzing/Car%20Parking%20System%20Diagram_bb%20(Connections).jpg" width = "726"/>

## Data Flow
<img src = "https://github.com/kazi-md-al-wakil/Arduino-based-High-Security-Car-Parking-System_Lab-Project_CSE360/blob/master/Data%20flow.jpg" >

## Project Display
<img src= "https://github.com/kazi-md-al-wakil/Arduino-based-High-Security-Car-Parking-System_Lab-Project_CSE360/blob/master/Project%20Display%20(2).jpg" width = "726"/>

