# PiPlay
PiPlay is a Raspberry Pi Zero 2W-based Game Boy, with full RetroPie capabilities. It can play any Retropie-supported game, as long as it doesn't require joysticks. 
# Bill of Materials
~12 6x6mm pushbuttons
~1 Raspberry Pi Zero 2W
~1 Adafruit 1000C Li-ion battery charger
~1 DPI or HDMI 3.5-inch screen
~1 copy of the PCB
~1 Li-ion battery with the correct header for the charger
~Tools for assembly: 
~1 soldering iron
~1 spool of solder
~1 3d printer
~1 spool of filament
# Setup the Pi
I will post this section when I get to build the project, most likely in a couple of weeks.
# To build:
The Gerber files are in the ZIP file piplay_gbr.zip. Load this ZIP into either:
~A PCB manufacturer
~Your PCB manufacturing setup, if you have one.
While you wait for that, you can go ahead and purchase the parts listed in the Bill of Materials.
Once you have all of the parts, assemble as follows:
1. Solder the buttons to the PCB. Note that the L and R buttons go on the back of the board(L and R are the ones on the same line. L is under the Pi, and R is under nothing, but parallel to L. These will be the shoulder buttons, but on the back instead of up top.
2. Solder the battery charger to the board. Solder the USB-A port to the charger.
3. Solder the Pi to the board, with the Micro-SD card in the slot already. BE SURE NOT TO PLUG THE PI IN BACKWARDS!!!!!
4. Attach the screen to the board. Run the HDMI cable to the Pi. You may have to run it along the outer edge, but you shouldn't have to.
5. Plug in and attach the battery to the board. BE SURE NOT TO PLUG IT IN BACKWARDS!!!!!
7. Plug in. If all went well, it should turn on. You can now either use it or turn on the screensaver and let it charge.
# Use
Load up ROMS of your choice, following the guide that RetroPie has put on their docs. Play games. 
