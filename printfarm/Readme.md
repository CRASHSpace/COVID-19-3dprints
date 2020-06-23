# Crashspace Printfarm 

Crashspace received 10 Monoprice MP10 and 5 Monoprice MP10 Mini 3d printers from Monoprice. 


# GCode - Print files
Printer (Nozzle Diameter)

File         | MP10 (0.4mm)| MP10   (0.4mm)| MP10  (0.6mm)| MP10 (0.6mm)         |  MP10 Mini  (0.4mm)      |  MP10 Mini  (0.4mm)     | MP10 Mini  (0.6mm)   | MP10 Mini (0.6mm)     |
------------ | ---------- | -----------| -----------| ---------- | ------------- | ------------- | --------- | ---------   |
Filament Type| PETG       | PLA        | PETG       | PLA        | PETG          | PLA           | PETG      | PLA         | 
Budmen V5    | [4x Budmen PETG 0.4mm](https://github.com/CRASHSpace/COVID-19-3dprints/raw/master/printfarm/MP10/0.4%20Nozzle/PETG/PETG_04_4XshieldV5_MP10.gcode) | [4x Budmen PLA 0.4mm](https://github.com/CRASHSpace/COVID-19-3dprints/raw/master/printfarm/MP10/0.4%20Nozzle/PLA/PLA_04_100_4XshieldV5_MP10_r0421.gcode) |  [4x Budmen PETG 0.6mm](https://github.com/CRASHSpace/COVID-19-3dprints/raw/master/printfarm/MP10/0.6%20Nozzle/PETG/PETG_06_4XshieldV5_MP10.gcode) | [4x Budmen PLA 0.6mm](https://github.com/CRASHSpace/COVID-19-3dprints/raw/master/printfarm/MP10/0.6%20Nozzle/PLA/MP10_4X_shieldV5_0.6_Test.gcode) |  | [2x Budmen PLA 0.4mm](https://github.com/CRASHSpace/COVID-19-3dprints/raw/master/printfarm/MP10_Mini/0.4%20Nozzle/PLA/PLA_04_108_shieldV5_r042120.gcode)   
0.75" Strap Locks | |[72 Straplocks PLA](https://github.com/CRASHSpace/COVID-19-3dprints/raw/master/printfarm/MP10/0.4%20Nozzle/PLA/PLA_04_72Xstrap_lock_MP10.gcode) | | | |[42x Straplocks PLA] (https://github.com/CRASHSpace/COVID-19-3dprints/raw/master/printfarm/MP10/0.4%20Nozzle/PLA/PLA_04_42X_straplock_mini.gcode)

## Setup
NOTE! When you turn off the printer, it can lose it's Z-Offset. Make sure you check this after any power cycle.

## Cleaning
Clean the nozzle while it is heating up -- MORE INFORMATION TO FOLLOW

## Manual level process (tramming the bed)
You need to manually level the bed before printing!
- Zero out the system
  - Set the Z-Offset to 0 (Move -> Tune)
  - Pull print head out of seated position (this ensures nozzle cannot crash into bed and forces the use of mechanical limit switch)
  - Initiate Auto-Level from the touch screen (this will go over the bed using the mechanical level switch and zero out all mesh leveling data)
- Perform manual leveling
  - Lower the bed by tightening the 4 leveling knobs to ensure nozzle will not crash into bed during the leveling process (they are upside down, so remember righty tighty is relative :)
  - Ensure nozzle is clear of any ooze and place head back into place
  - Select the Manual Level Code from the print menu
  - The system will wait for the bed to heat up before continuing
    - The head will then go near each of the leveling knobs and lower to 0.28mm. Use your favorite leveling paper that is near this to check for friction and adjust at each stop
- When complete plug in the leveling probe and perform auto-leveling with bed preheated to printing temps
- Set the Z-offset upon the start of the next print

