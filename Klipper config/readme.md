### OrcaSlicer
In OrcaSlicer go to "Printer settings" -> "Machine start g-code" and update it to:
<br/>
<br/>
M104 S0 ; Stops OrcaSlicer from sending temp waits separately<br/>
M140 S0<br/>
print_start EXTRUDER=[first_layer_temperature] BED=[first_layer_bed_temperature]<br/> 



### rpi.cfg
only use the rpi.cfg if you are using the pi as an additional MCU
<br/>
I had a spare eddy i2c Eddy coil, so wired it stright through to the RPI. 
<br/>
I dont recommend this approach, i have built two of these conversions and I could only get 12c to work on one of them.
<br/>
switching out to a Eddy USB was much easier.
