# dimension1800

USB QMK-compatible PCB for the Siemens 10453443 / KBA-D2911

![overall](https://github.com/nearestexit/dimension1800/blob/main/Pictures/overall.jpg)


![PCB](https://github.com/nearestexit/dimension1800/blob/main/Pictures/PCB.png)



## Information

This PCB accepts THT or SMD diodes. It requires either the use of an elite-pi (https://docs.keeb.io/elite-pi-guide) or a Raspberry Pi Pico. The elite-pi is positioned so that when it is soldered correctly, the USB-C port is easily accessible from the back of the PCB. The elite-pi is the recommended MCU for this PCB. The Raspberry Pi Pico is the backup in case the elite-pi becomes no longer available - it is positioned further inside the keyboard, so it would result in a "fixed" cable.

I have not tested the PCB with SMD diodes or the Raspberry Pi Pico. Production files are included for SMD diode assembly at JLCPCB.

The keyboard originally uses a plate and PCB. This PCB is designed to be used plateless.

## Spacebar Stabilizer

My keyboard is a KBA-D2911**C** with a 7u PBT spacebar with nonstandard stabilizer spacing. You will most likely want to re-use the original spacebar stabilizer wire or make your own. Some other versions appear to have an ABS spacebar - I do not know what the spacing for the ABS spacebars is. The PCB can accept either the standard Cherry 7u spacing or the nonstandard PBT spacebar spacing.

## Elite-Pi soldering

In order for the USB-C port on the elite-pi to be accessible, you must solder the elite-pi away from the PCB like this:

![elitepi](https://github.com/nearestexit/dimension1800/blob/main/Pictures/elitepi.jpg)

![usb](https://github.com/nearestexit/dimension1800/blob/main/Pictures/usb.jpg)


## Arrow key position

On my prototype, the arrow keys appeared to be slightly too far up and to the right.

![arrows](https://github.com/nearestexit/dimension1800/blob/main/Pictures/arrows.png)


I have moved the arrow keys down and to the left by 0.25mm in the current version.

## Production files
To order, navigate to dimension-PCB/jlcpcb/production_files and copy what you need. If you choose THT diodes, just upload GERBER-dimension-PCB.zip. The BOM and CPL file are for SMD diode assembly at JLCPCB.
I have 4 prototypes with the slightly misaligned arrow keys. You can contact me on discord if you wish to purchase one for free + the cost of shipping.

## Firmware
Coming soon.







