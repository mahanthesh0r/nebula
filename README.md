# Nebula
High altitude balloon project

###### Version 2 

<img src="Images/Cubesat%20Parts(V2).jpg" alt="3D printed parts" width="400" height="300"/>.  

<img src="Images/v2cube.jpg" alt="3D printed parts" width="400" height="350"/>

###### Version 1
<img src="Images/V1%20nebula.jpeg" alt="Version 1" width="400" height="400"/>



## Hardware used
For the playload we have used 

* Raspberry pi
* Picam
* 3D Printer (for building an enclosure for the playload)
* BME280 temperature, pressure, and humidity sensor 
* MPU-6050 Accelerometer and Gyroscope module
* NEO-6m GPS module

#### Tracking 
for tracking the playload we are using Automatic Packet Reporting System ***(APRS)***. It's always a good idea to have an alternative tracking methods, as a contingency plan. Hence, after lot of research we decided to use LoRa (Long-Range) module.

<img src="Images/LORA%20RMF95.jpg" alt="LoRa RFM95" width="300" height="300"/>

### Pearks of using LoRa
* Cheap
* LoRa modules are transceiver i.e, can be used as both transmitter or receiver
* With a clear SOV (Sight Of View) has a range >100km. 

## Custom PCB Printed LoRa Breakout Board
<img src="Images/Lora%20break-out%20board.jpg" alt="Nebula Breakout board" width="300" height="300"/>




