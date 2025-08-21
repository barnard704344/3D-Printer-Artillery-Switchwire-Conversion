### OrcaSlicer

In OrcaSlicer go to "Printer settings" → "Machine start g-code" and update it to:

```gcode
M104 S0 ; Stops OrcaSlicer from sending temp waits separately
M140 S0
print_start EXTRUDER=[first_layer_temperature] BED=[first_layer_bed_temperature]
```

### rpi.cfg

Only use the rpi.cfg if you are using the Pi as an additional MCU.

I had a spare Eddy I2C coil, so I wired it straight through to the RPi. 
I don't recommend this approach - I have built two of these conversions and I could only get I2C to work on one of them.
Switching out to an Eddy USB was much easier.
