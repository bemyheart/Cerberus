# Algorithm

initialization -> loop

## initialization 

initialize hardware, software

## loop

hourly loop

### every 15 mins or on button press 
- take measurments
- output data on screen and server
- if(button != PRESSED) save intermediate data in array
- alert user if readings exceed limits 

### every hour 
- reset clock
- calculate and save hourly data
- clean intermideate array

cannot do full sleep if i want it to be a local server, but can sleep sensors, lcd? can i make it wake up on sever connection or button press?