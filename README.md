# Smart-Temperature-Controlled-Heater
Temperature controlled heater using PIC18F4520, LM35 sensor, keypad input, LCD display and relay control.

This project implements a temperature controlled heating system using the PIC18F4520 microcontroller.

## Features
- Temperature sensing using LM35 sensor
- User input through 4x3 keypad
- LCD display for temperature monitoring
- Relay control for heater/bulb
- Automatic ON/OFF based on set temperature

## Components Used
- PIC18F4520 Microcontroller
- LM35 Temperature Sensor
- 16x2 LCD
- 4x3 Keypad
- Relay Module
- 230V Bulb / Heating Element
- Power Supply

## Working Principle
The LM35 sensor measures the current temperature and sends an analog signal to the microcontroller. The PIC converts this signal using its internal ADC. The user enters a desired temperature using the keypad. The system compares the measured temperature with the set temperature and activates the relay to turn the heater ON or OFF accordingly.

## Software Used
- MPLAB X IDE
- XC8 Compiler
- Proteus 8

## Simulation
The circuit simulation was designed and tested in Proteus before implementing it on hardware.

## Author
TanishqS
