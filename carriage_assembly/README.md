# Carriage Assembly Mods.
There are 3 Goals to this mod
	1. Use heated inserts where possible instead of threading into plastic so things like replacing the Z switch easier
	2. Connect the front and back carriage plates over the crossbar to stablize the belt connection point
	3. Incorporate Mr. Hobbits mod for tool lock detection.
	
	
Individual step and stl files are saved for the front back and center top and bottom plates, the whole fusion project is saved as crossbar_mod_V##
	
	
Notes on the tool lock:

This is expiremental, the idea is that when the 3 balls make contact with the the 6 pins the ball will electrically connect each pin.
So by connecting the outside pins with wire we can have a closed circuit when tool is properly locked.  We can then use this detection to stop the printer.
Firmware for this has yet to be written and tested, any help here will be welcome.

To build the connection the intention here is to strip a couple mm of wire and put that in the hole behing the pin.
The press a M3 heated insert into the hole, when the plastic solidifes it will hold the wire firmly in place. 
Next use a 3mm set screw to press firmly into the pin. Test connections with multi meter. 