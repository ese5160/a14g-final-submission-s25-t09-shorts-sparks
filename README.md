[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/AlBFWSQg)
# a14g-final-submission

    * Team Number: 9
    * Team Name: Shorts & Sparks
    * Team Members: James Steeman and Tim Zhang
    * Github Repository URL: https://github.com/ese5160/a14g-final-submission-s25-t09-shorts-sparks
    * Description of test hardware: Detkin Desktop (Windows 10), MacBook Pro M2 (Mac OS), Our PCBAs, LSM6DSO IMU, Servo Motor, DC motor, our mechanical assembly
    
    (development boards, sensors, actuators, laptop + OS, etc) 

## 1. Video Presentation

## 2. Project Summary

## 3. Hardware & Software Requirements

Note: Since we had a late project change, we have created new HRS and SRS for the new project (post-facto) based on our goals when this project was created. We are evaluating our final output relative to these goals of the ideal new project expectations.

### HRS

IMU shall sample at least at 200 Hz (we will request measurements at 200 Hz for kalman filter input)

MCU (capabilities?) (at least FM i2c?, WIFI, PWM, SPI, ..., flash space for bootloader and Application code)

SD card access at ... speed, sapce for application code files

DC motor driven at least 24V 5??A (MOSFET + gate drive) - show DC Eload as proof of capability

Use the PCBA made for the original project as much as possible

Stepper motor - Fail --> servo motor from another SAMW pin

### SRS

UART SAMW to SAMD for communication between mcus on board - Fail -->

PWM at 10khz (ish) for 

Ramp changes in dc motor PWM for ...

Node red / wifi interfacing for remote data show and user input

OTAFU implemented (show node red and / or cli) (note bootloader existance?)

Drivers?

Requests and receives imu data at 200 hz to input into 200hz kalman filter -> 100hz pid motor control loop


## 4. Project Photos & Screenshots

## Codebase

- A link to your final embedded C firmware codebases
- A link to your Node-RED dashboard code
- Links to any other software required for the functionality of your device

