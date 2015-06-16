## Subaru Homelink mirror USB power adapter

This is a simple device to step-down the 12V used by the Homelink mirror in my Subaru to 5V and output it to a USB cable. This can technically work for any mirror that has 12V and GND.

## Schematic

There's a minor error in the schematic that doesn't affect operation: The three wires on the connector are labeled "12V", "12V_SWITCHED", and "GND". On the actual wire there are two grounds and 12V that gets applied when you turn the key to accesory. It doesn't matter because the "12V" wire is just a pass-through anyway so this is really just an error in the naming of the net in the schematic.

![schematic](https://raw.githubusercontent.com/jotux/SubaruHomelinkUsbAdapter/master/pics/schematic.png "schematic")

## Board

![Board](https://raw.githubusercontent.com/jotux/SubaruHomelinkUsbAdapter/master/pics/board.png "Board")

## Installed


![i1](https://raw.githubusercontent.com/jotux/SubaruHomelinkUsbAdapter/master/pics/wiring.jpg "i1")

![i2](https://raw.githubusercontent.com/jotux/SubaruHomelinkUsbAdapter/master/pics/installed.jpg "i2")

