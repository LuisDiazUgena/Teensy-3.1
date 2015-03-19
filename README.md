# Teensy-3.1
Teensy 3.1 library for kicad

## Library

This just contains library file with external pinout (not represented smd pins on bottom side).

## Module footprint

Footprint of external pinout (not represented smd pins on bottom side).

## How to: Add library

Go to *Preferences/Set Active libraries* then use *add* button and look for your libraries. It can be wherever you want.

If you move the library to another path, you must relocated it to keep using it.

## How to: Add Module

**In lasts versions you must store the module footprint on a *.pretty* folder.** 

1. Move module to your project folder and create a modules.pretty folder.
2. Go to *preferences/Edit Library Table* and and select *Append with wizard*
2. Select Kicad(*.Pretty folder) containing .kicad_mod files)
3. Click on Next and select *Use enviroment variable in path* and select your project folder path.
4. Clic on Next and click on *Add FP Libraries*. In the new window that just openned look for your *.pretty folder, click ok and Finish and you're done!


## License

This work is under CC-BY-SA 3.0 license 

![cc-by-sa License](/cc-by-sa_0.png)
