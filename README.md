# ArtilleryX1-Switchwire

Repository to document my journey to convert my X1 to a Voron switchwire

### STL's are largely complete, just a few final tests on the HDMI screen holder. 
I have sourced/updated, created everything needed to print out, with the exception of the stealthburner.
https://github.com/VoronDesign/Voron-Stealthburner

### You will also need the BTT cable holders for the canbus cable: 
"CW2 cable bridge" and "printed part for can cable" <br>
https://github.com/bigtreetech/EBB/tree/master/EBB%20SB2240_2209%20CAN/STL 
<br>
<br>
<br>
<br>
<br>
### The plan:
keep the following:
  - base and frame
  - heatbed and glass bed *WIll need a steel sprung plate for Eddy sensor
  - Y motion
  - Z steppers
  - mks gen L board and electronics
  - Optical endstop on Z and Y

### To add:
- Voron Stealthburner
- Voron revo hotend
- micro switch for X on toolhead
  
### CanBus
  - BTT U2C USB bridge
  - BTT EBB sb2209 or Rp2040
    - I used a RP2040 as the JST connectors are bigger (I still bought pre crimped pigtails though) 
  - BTT Eddy coil U2c
    
  - MGN 9 Rails for X and Z
    - 450mm
  - MGN 12 Rail for Y
    - 350mm - cut down to 340mm 
  - Raspberry Pi 4
      - Standard RPI install with KIAUH install script to install mainsail, klipperscreen, crowsnest etc.
        - https://github.com/dw-0/kiauh
  - 5 Inch HDMI Touch screen
  - 5 volt meanwell power supply for Raspberry Pi

### 2020 Vslot rail  
  This replaces the 2060 X gantry
  - 400mm cut to 380mm 

![Switchwire](images/image1.png)

 
  
     
