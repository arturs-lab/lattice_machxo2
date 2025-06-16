# lattice_machxo2
lattice machxo2 256 breakout board

## Power Supply
All four VIO circuits are connected to 3V3 by traces on bottom of the board. 
In this configuration you do not have to populate VIO jumpers, voltaage regulator nor its capacitors.
If you want to use different VIO, cut corresponding trace(s), install jumper(s) and 
VIO voltage regulator and caps.

The 1Ohm resistors on the bottom of the board can be used to measure current draw of IO sections by 
measuring voltage drop on resistors. 0Ohm jumpers can also be installed.

## Oscillator
To use on-board oscillator, install it and jumper pin OSC to CLK.
To use off-board clock source, connect it between CLK and GND pins. 
In this case on-board oscillator does not have to be installed.

![pcb](lattice_machxo2_breakout_v2.png)

