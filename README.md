# Pad-Printing-machine
Industrial automation project featuring a fully automated pad printing machine using microcontrollers, pneumatic actuators, proximity sensors, and custom PCB control. Includes complete project report, hardware documentation, and demo videos.

## Automated Pad Printing Machine – Industrial Automation Project

This project presents the design and implementation of an automated pad printing machine developed for Indus Engineering, Bangalore. The system automates the traditional pad printing process using microcontrollers, pneumatic systems, proximity sensors, and sensor-driven control logic.

<img width="527" height="971" alt="image" src="https://github.com/user-attachments/assets/95e460a3-78b7-40cb-9b56-dbc9ce5116a4" />

## Project Overview

Pad printing is a widely used technique for printing 2D images on 3D objects such as pens, keychains, and small industrial parts.
This project automates the process using:

* Silicone printing pad
* Etched ink plates
* Pneumatic cylinders (X–Y–Z motion)
* Inductive proximity sensors
* PIC16F887A microcontroller
* Custom Designed PCB
* LCD-based user interface

Goal: Increase speed, reliability, accuracy, and repeatability compared to manual pad printing and replacing expensive PLC

## Features

* Automated pad printing using 3 pneumatic actuators
* Supports both single-color and dual-color printing modes
* 7 inductive proximity sensors for position feedback
* 8 push-button switches + 1 toggle switch for mode selection
* LCD interface for real-time process monitoring
* Microcontroller-based motion and timing control
* Custom PCB designed for industrial-level reliability
* Capable of printing on various 3D objects (pens, keychains, electronic housings, etc.)

## Technologies & Tools Used
### Hardware

* PIC16F887A microcontroller
* Kinco HMI
* Inductive proximity sensors
* Pneumatic cylinders
* Pneumatic solenoid valves
* LCD display
* Custom PCB
* Ink cup, etched plate, silicone pad

### Software / Development Tools

* Pickit2 (microcontroller flashing)
* Microcontroller IDE 

### Programming Concepts

* Embedded system design
* Sensor interfacing
* Pneumatic and solenoid-based actuator control
* Control logic implementation on microcontrollers
* Industrial automation workflows


##  **Project 1: Classic Pad Printing Machine Automation**

This project automates a traditional pad printing machine using pneumatic cylinders, a microcontroller, and inductive sensors. It supports multiple printing and testing cycles for reliable operation and easy troubleshooting.

<img width="527" height="971" alt="image" src="https://github.com/user-attachments/assets/95e460a3-78b7-40cb-9b56-dbc9ce5116a4" />

### ** Operations Implemented**

#### **Main Production Cycles**
- **Normal Cycle**
- **Single Cycle**

#### **Testing / Alignment Cycles**
- **Vertical Front**
- **Vertical Back**
- **Horizontal Cycle**

These test cycles help the operator verify actuator movement, alignment, and sensor accuracy before production.

### **🎥 Demo Videos**
Videos are available in the `classic-model-videos/` folder.

##  **Project 2: HMI + Index Table Integrated Model**

This upgraded version integrates an **HMI (Human Machine Interface)** and an **Index Table** with the pad printing system to significantly enhance productivity, usability, and operational flow.

### **Highlights**
- HMI integrated with a custom microcontroller  
- Multi-station index table designed for faster production cycles  
- Touch-based UI for simple machine operation  
- Better workflow visualization and real-time status updates  

### **Communication**
- **RS485 communication between HMI and microcontroller**
    - Industrial-grade, noise-resistant communication  
    - Supports commands, mode selection, and status monitoring  

### **Improvements Over Classic Model**
- Higher speed and throughput  
- Less manual intervention  
- Intuitive HMI interface replacing physical switches  
- More consistent and repeatable cycle performance  

### **Demo Videos**
Videos are available in the `hmi-index-table-model-videos/` folder.



