OrcaSlicer
In OrcaSlicer go to "Printer settings" -> "Machine start g-code" and update it to:
<br/>
<br/>
M104 S0 ; Stops OrcaSlicer from sending temp waits separately<br/>
M140 S0<br/>
print_start EXTRUDER=[first_layer_temperature] BED=[first_layer_bed_temperature]<br/> 
