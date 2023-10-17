# Neptune-4MAX
How to set up the Elegoo Neptune 4MAX with Orca Slicer
I get one issue with hard homing 
I change my X&Y stepper sensitivity on  printer.cfg  look for driver_SGTHRS:
My value on X is 65 and Y 45 bigger number more sensitive if you go up too much the printer moves to the other direction then try +5 increments then +1
but is relative with the tightening on the rollers, belt, break in period.  may will break in and they will need to do the adjustment again. 
Here you will find the files needed, printer.cfg, start end gcode.
Open Orca slicer (last edition 1.7) add printer the elegoo Neptune 4, then change the printable area to x427 y426 printable height 497 (you must remove the Z bracket and replace it with the ziptie provided
change the Machine G-code start and end gcode, save and close the window
or use my printer config file (.json) open orca then file, import.
Now hit the wifi logo on the right side to connect the printer, go to the printer, look the touchscreen in the wifi settings to get the IP address and use it in Orca, done, printer is connected, up and running, now you can see fluid inside the OrcaSlicer when you hit device.

I also drill up the original nozzle to .6mm with a cheap small drill bit kit, first I use .5mm then the .6mm (I already did the same with my bambulab X1C stell nozzle) the elegoo original is brass, it is easy to drill. then I get 27mm3 flow rate (the priter comes with 2 brass nozzle, I still have the .4) I dont remove the nozzle from the printer, I drill it installed 
