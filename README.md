# MAX-MSP-to-Arduino
Collection of Max patches for use in module Sensors &amp; Senses

Arduino to Max module (main Max patch, source and arduino code)
Basic info version 2023 
(baudrate is set to 9600) If you have connection problems while using multiple IO try changing arduino code IO)

On the topside of the module you have data inlets to write data to Arduino
On the bottom there data outlets. Here we read data from the arduino

!!!!!!!!!!!!!!!!FIRST: Upload the ArduinoSketchforMaxModule.ino sketch to your arduino IT WILL NOT WORK WITH OTHER ARDUINO CODE!!!!!!!!!

1. Press the 'SYSTEM ON / OFF' in module. If no connection is established the menu on the right will say "no arduino connected". A good connection will show you the serial port your arduino is connected to.
2. Enable analog and / or digtal READOUT and then individual pins (keep this OFF if you are only writing to arduino)
3. You can switch the function of data inlets 3, 5, 6, 9 & 10 on the topside of the module to be digital, analog or servo mode (default = digital. (Note: you can connect multiple servo motors but HAVE TO USE A EXTERNAL POWERSOURCE