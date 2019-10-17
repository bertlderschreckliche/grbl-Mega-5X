SD-Card fromated (FAT32)

http://smoothieware.org/flashing-smoothie-firmware

copied firmware.bin onto flash card

reset wait for the blinking to end

download Pronterface 

http://kliment.kapsi.fi/printrun/ (yes is old)



If GRBL than https://github.com/gnea/grbl-LPC

https://laserweb.yurl.ch/documentation/initial-configuration/65-grbl-lpc-1-1e



changed to firmware-cnc

need to change the name to firmware.bin



### Dual Motor

https://medium.com/@mark_85079/dual-axis-motors-with-smoothieware-b253be848fbc





## Changed my mind and switched to RAMPS 1.4

This convinced me

http://www.tridimake.com/2017/05/replacing-linuxcnc-with-smoothie-milling.html



Tried Paltform IO

https://platformio.org/install/ide?install=vscode

https://docs.platformio.org/en/latest/quickstart.html

failed to open the project



Download Arduino IDE



![img](http://domoticx.com/wp-content/uploads/2017/05/RAMPS-Shield-1.4-overzicht-connectors.png)

Had issues flashing something onto it

https://forum.arduino.cc/index.php?topic=73748.0

https://forum.arduino.cc/index.php?topic=473078.0

Changes the port, suddenly it worked





### Download GRBL

https://github.com/gnea/grbl

How to flash it? https://github.com/gnea/grbl/wiki/Compiling-Grbl

This seems to be what we want using motor controll  https://github.com/fra589/grbl-Mega-5X

That one has all to display stuff https://github.com/bdurbrow/grbl-Mega ; https://github.com/gnea/grbl-Mega/issues/77







### Limitswitch 

https://github.com/gnea/grbl/wiki/Wiring-Limit-Switches

### Autosquare

https://www.v1engineering.com/forum/topic/my-axis-is-hella-square/  Seem to be onto something

https://forum.repetier.com/discussion/3634/dual-endstops-for-x-and-y



### Cloning Axis

https://github.com/fra589/grbl-Mega-5X/issues/4 should allow to clone axis

