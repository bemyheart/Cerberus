# Cerberus

## Basic project idea
Indoor air quality monitoring and user alerting device

## Functions
- monitor t, p, h, co2, other gases(add extremities ppm)
- output to a local sever and lcd screen
- logging 24 hours
- alert user on exceeding air parameters
- ?drawing a graph

## Hardware
- esp32 as a controller
- bme280
- co2 sensor tbd MQ135
- extremities sensor tbd
- lcd tbd

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
- 0.8 - caseing and final wiring solution
- 1.0 - optimizations

## Progress 

### 0.0.1
#### done
- Started learning git, set up local and remote repositories. Managed to understand add, commit, push, pull...somewhat understand. Anyway got "getting started" docs and youtube playlist on the ready for further learning.  
- readme.md, .git, rsc - datasheets folder
- resources datasheet for esp32, bme280, tempLCD, esp pinout
- make a plan
- wrap head around license 

### 0.0.2
#### to do
- go over functions
- ressearch air quality measurment
- write simple work algorithm
#### done

### 0.0.3
#### to do
- resolve hardware tbd
- procure new hardware datasheets
#### done
- found mq135 for CO2 and extra gasses, got datasheet for it

### 0.0.4
#### to do
- write more sofisticated device work algorithm
- create project program structure
#### done

### 0.0.5
#### to do
- write project pinout
- create wiring diagramm\schematic 
#### done

### 0.0.6
#### to do
- check voltage levels
- check signal levels
- check pins compatability 
- check currents
- check wires gauge (check old psu wires for compatability)
#### done

### 0.0.7
- check scenarios
#### to do
#### done