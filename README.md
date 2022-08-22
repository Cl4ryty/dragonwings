# dragonwings
An ergonomic unibody split keyboard made for steno.

- key layout generated using ![ergogen](https://github.com/ergogen/ergogen)
- PCB design in KiCad
- uses ![QMK Firmware](https://github.com/qmk/qmk_firmware) with ![Joshua Grams' steno extensions for first-up chord-send and tap-and-hold chord repeat](https://github.com/JoshuaGrams/qmk-steno-extensions)


![](pretty_pictures/perspective.jpg?raw=true)

## Features:
- for Pro Micro or compatible controllers
- choc spacing (for choc v1 switches)
- pcb backplate with holes for rubber feet and threaded insert – allows usage on desks as well as tripod mounting the keyboard
- approximate size: 31 x 11 x 2 cm
- 30 keys
  - 15 keys on each side
  - 3 thumb keys per side
  - for steno this means: 
    - 2 thumber keys (one per side)
    - split S and *: 2 S keys 4 * keys (2 per side)
    - 2 extra keys on the left, can be set arbitarily in firmware – for eample to switch between layers or used as modifier keys


## The built keyboard
![](pretty_pictures/top.jpg?raw=true)
![](pretty_pictures/side.jpg?raw=true)
![](pretty_pictures/back.jpg?raw=true)
### parts used:
- dragonwings pcb & backplate
- 30 pink choc switches (linear 20gf)
- 30 MCC keycaps
- Pro Micro
- 5 through hole rubber feet, 5mm diameter (search for glass table top spacers)
- 1 UNC 1/4" hex nut 
- 7 M2x5mm standoffs
- 14 M2x4mm screws
- 1 SMD button, 5x5x2mm
- 30 SMD diodes (1N4148W, SOD-123)


## repository file structure
- `pretty_pictures` contains renders and images of the built keyboard
- `dragonwings_backplate` contains KiCAD files for the backplate as well as the gebers 
  – the dagonwings_backplate_gerbers are tested but are missing a hole for the 5th rubber foot without which the board is not stable on a flat surface
  – the dragonwings_backplate_gerbers_updated are genreated from the updated kicad files and contain the additional hole for the 5th foot – these have not been tested but should work and one then would not have to drill the hole manually
- the dragonwings kicad files are contained in the root directory and the corresponding gerbers (tested and working) are in the `dragonwings_gerbers` directory, also available as a zip archive
- `compiled firmware` contains compiled firmware without or with first-up chord-send and tap-and-hold chord repeat – they contain two layers, one steno layer using GeminiPR and a qwerty steno layer which can be toggled with the lower key of the leftmost column
