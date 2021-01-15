# Printing with Tevo Tarantula (2017)
This was the first attempt to in PETG. Some tinkering was needed to make it work. Here I'll share my gcode and and my Ultimaker Cura Profile for PETG on the Tevo Tarantula.

## Prerequisites
1. I'm using a glass print bed covered in glue stick. The glass influences the print bed temperature. This is why I print with 90℃. If you do not have a glass print bed, the temperature might have to be adjusted.
2. I upgraded to a cooling fan. https://www.thingiverse.com/thing:2186095

## Filament
I'm using esun PETG in orange (EAN 6 922572 264083) and solid black (EAN 6 922572 264083).

## gcode files
| File | Print Time \* |
| :--- | ---: |
| *Orange* | |
| [TT_z-axis-top.gcode](gcode/Orange/TT_z-axis-top.gcode)          | 2h |
| [TT_z-axis-bottom.gcode](gcode/Orange/TT_z-axis-bottom.gcode)    | 4h |
| [TT_x-end-idler.gcode](gcode/Orange/TT_x-end-idler.gcode)        | 3.5h |
| [TT_x-end-motor.gcode](gcode/Orange/TT_x-end-motor.gcode)        | 4.5h |
| [TT_LCD-and-y-items.gcode](gcode/Orange/TT_LCD-and-y-items.gcode)| 12h |
| *Black* | |
| [TT_Heatbed.gcode](gcode/Black/TT_Heatbed.gcode)                 | 1.5h |
| [TT_Extruder.gcode](gcode/Black/TT_Extruder.gcode)               | 6h |
| [TT_Einsy-base-and-hinches.gcode](gcode/Black/TT_Einsy-base-and-hinches.gcode) | 6h |
| [TT_fan-shroud_fs-cover-leveler.gcode](gcode/Black/TT_fan-shroud_fs-cover-leveler.gcode) | 1.25h |
| [TT_plug-aligner_print-fan-support.gcode](gcode/Black/TT_plug-aligner_print-fan-support.gcode) | 0.5h |
| [TT_x-carriage-front-back.gcode](gcode/Black/TT_x-carriage-front-back.gcode) | 4.75h |
| [TT_Ensy-doors_cable-holder_z-screw_cover_adapter-printer.gcode](gcode/Black/TT_Ensy-doors_cable-holder_z-screw_cover_adapter-printer.gcode) | 4.25h |
|||






\* just a rough measure. Sometimes includes heat up/cool down and sometimes not.

## Notice
While I had trouble getting the orange filament to stick to the print bed, black was the opposite. On the first attempt, I broke the model while pealing it off. This is why I use a brim on the orange parts and only a skirt on the black parts.
Defiantly use a lot of glue stick. This helps the orange models to stick and makes it easier to remove the black ones.

I'm not done yet, printing all the parts. And I have not assembled the printer yet. I'll keep this repo up do date.
