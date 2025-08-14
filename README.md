# Wall Following RoboCar
A simple autonomous robot car that uses sensors to detect and follow walls while navigating through an environment.  
The project is built to demonstrate basic robotics concepts such as obstacle detection, path following, and real-time control.

## Features
- Detects walls using ultrasonic sensors
- Maintains a fixed distance from the wall while moving
- Avoids collisions
- Adjustable speed and distance parameters
- Code easily customizable for different robot chassis

## Hardware Requirements
- Arduino Uno (or compatible microcontroller)
- Ultrasonic sensors 
- Motor driver module (L298N or similar)
- DC motors + wheels
- Chassis frame
- Battery pack (Li-ion or LiPo)
- Jumper wires
## Software Requirements
- Arduino IDE

##  Installation & Setup
Just paste the code in the aurdino IDE and upload in the aurdino
## Things to Remember
- this code is for right wall following car so fix one sensor in front and one in right
- make trials to make the speed of two motors equal by changing ENA and ENB pin values(if your motors are brand new then you may need not do this).
------------------------------------------------------------------------------------------------------------------------------




# LINE FOLLOWER
- same as wall follower just use 2 IR sensors in the front and remove the ultrasonic sensors.
# OBSTACLE AVOIDANCE 
- same as wall following just use a servo, mount a ultrasonic sensor on the servo.
