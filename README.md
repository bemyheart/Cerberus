# Cerberus

## Basic project idea
Indoor air quality monitoring and user alerting device

## Project description
Device to sit in a room and monitor air quality. Data is viewable through a local server run on the same device.
Alert system for the user to be aware of dangerous concentration of gases.

## Functions
- monitor t, p, h, CO, CO2, Particulate matter, boonus gases(O3, SO2, NO2, others)
- output to a local sever and lcd screen
- logging hourly data 24/7
- alert user on exceeding air parameters

## Hardware
- esp32 as a controller
- bme280
- co2 sensor tbd MQ135
- extremities sensor tbd
- lcd tbd
- pushbutton

## Roadmap
Trying to push weekly at the very least.
- 0.0.1 - set up git, files, procure needed resources 
- 0.0.2 - resolve device functions under question, iron out project scope
- 0.0.3 - resolve hardware tbd's
- 0.0.4 - create project program structure
- 0.0.5 - create wiring diagramm\schematic 
- 0.0.6 - once over all hardware, voltage, signal levels compatability
- 0.0.7 - once over algorithm
- 0.1 - basic server and debugging through serial port
- 0.2 - air sensors
- 0.3 - lcd
- 0.4 - logging
- 0.5 - saving logs
- 0.6 - preetify server output
- 0.7 - alerting user
- 0.8 - casing and final wiring solution
- 1.0 - optimizations
