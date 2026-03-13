# MCU Datalogger Board

## Overview
This repository contains the KiCad PCB design files for a custom MCU Datalogger board. This board integrates robust non-volatile memory, real-time tracking capabilities, and essential communication interfaces. It serves as a reliable hardware foundation for capturing, storing, and transmitting sensor data in embedded systems.

![Board Top View](media/images/MCU_Datalogger.png)

## Hardware Features

* **Microcontroller**: Powered by the ATMEGA328P-AU 8-bit AVR microcontroller, running on a 16MHz external crystal.
* **Timekeeping**: Features an integrated DS1337S Real-Time Clock (RTC) equipped with a dedicated 32.768kHz crystal for precise timestamping of logged data.
* **Memory & Storage**: 
    * Dual 24LC1025 EEPROMs (U1 and U2) provide extensive, reliable onboard data storage over the I2C bus.
* **User Interface & Expansion**:
    * Dedicated headers for standard communication protocols: I2C and Serial UART.
    * Accessible GPIO breakout header for rapid prototyping and connecting external sensors.
    * Standard 6-pin ICSP header for direct programming and bootloader flashing.
    * Dual status LEDs (D1, D2) for easy visual debugging.

## Visuals & Documentation

### 3D Slanted View
![Board 3D Slanted View](media/images/MCU_Datalogger_C.png)

### Board Layout & Routing
![Layout View 1](media/images/Screenshot%202026-02-16%20164305.png)
![Layout View 2](media/images/Screenshot%202026-02-16%20164509.png)

### Schematic
The complete circuit design can be viewed here: [Schematic PDF](media/schematic.pdf)