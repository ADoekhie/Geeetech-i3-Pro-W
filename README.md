# Geeetech i3 Pro W
 Use the Marlin firmware to restore to stock or upgrade to Marlin 1.1.9 
 
 Note that these are BLTouch enabled firmwares!
 
## Neccesary modifications
 Change the following to your setup specifications (as it is setup to mine)

	X_PROBE_OFFSET_FROM_EXTRUDER 
	Y_PROBE_OFFSET_FROM_EXTRUDER
	DEFAULT_AXIS_STEPS_PER_UNIT   {80,80,2560,93} --> {80,80,400,93} if you are using T8 leads screws for the Z-axis in your printer

## Other
 Both firmwares tested and functional on my Geeetech i3 Pro W.
 - Compile stock Marlin v1 firmware with Arduino 1.0.2
 - Compile Marlin 1.1.9 with Arduino 1.8.12
 * I used Octoprint to upgrade the firmware of the i3 Pro W, use the hex file <u>without</u> bootloader
 
