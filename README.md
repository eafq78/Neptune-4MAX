# Neptune-4MAX
How to set up the Elegoo Neptune 4MAX with Orca Slicer
I get one issue with hard homing 
I change my X&Y stepper sensitivity on  printer.cfg  look for driver_SGTHRS:
My value on X is 65 and Y 45 bigger number more sensitive if you go up too much the printer moves to the other direction then try +5increments then +1
but is relative with the tightening on the wheels may will break in and they will need to do the adjustment again. 
in the link you will find the files needed, printer.cfg, start end gcode
open Orca slicer (last edition 1.7) add printer the elegoo Neptune 4, then change the printable area to x427 y426 printable height 497 (you must remove the Z bracket and replace it with the ziptie provided
change the Machine G-code start and end gcode, save and close the window
now hit the wifi logo on the right side to connect the printer, go to the printer in the wifi settings to get the IP address and use it on Orca, done, printer is connected, up and running 
