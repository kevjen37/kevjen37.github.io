## Automatic Grow System

[![Grow System Demo]()](growsystem_demo.mov "Grow System Demo")

Automatic control system designed to automate the lighting, temperature, and humidity of apartment plants. 

System is controlled by a PLC (microcontroller) and leverages digital relays in addition to DC voltage analog outputs.

## Climate Control:

A combination temperature/humidity sensor is used to monitor the plant's current climate. These two signals are in turn used as inputs to dictate the temperate and humidity outputs. Outputs are two seperate 4-20ma signals, controlled by a PID loop (proportional–integral–derivative) for effective continuous modulated control.

## Lighting Control:

Plant lights are put on a schedule to simulate a natural amount of sunlight (~10 hours). A digital relays breaks the light's 120V circuit, allowing for effective digital control. 

## Front-end design:

User can control the system by logging into the PLC's IP adddress directly. Home network's LAN was modified such that a user who is connected to the home network is also able to log into the PLC. 

Front-end was written in JavaScript/HTML/CSS. 