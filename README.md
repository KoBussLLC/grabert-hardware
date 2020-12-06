# Grabert Keyboard Hardware

## PCB

This project uses KiCad 6 for electrical CAD

### Electrical Design Constraings
- No diode matrix enabled by LQFP 100 Footprint
- STM32 Based Microcontroller
- USB-C
- PCB Mount Switches
- PCB Mount Stabilizers
- Push-Button Encoder
- 0.91" I2C OLED Display

## CAD

This project uses FreeCAD 0.19 for mechanical CAD.

### Required Addons
- Assembly 4
- fasteners
- kicadStepUpMod

### Mechanical Design Contraints
- 60% Keyboard Layout
- Layout Options
- Push Button Encoder
- OLED Screen
- Fully Laser Cut Case
- 2mm diameter fasteners

### Acrylic Sheet Stackup

Main Case Stackup. 0 is the bottom of the case.

| Sheet Number | FreeCAD "Part" | Thickness | Material |
| - | - | - | - |
| 0 | bottom | 0.125 in | Acrylic |
| 1 | closed_spacer | 0.125 in | Acrylic |
| 2 | usb_spacer | 0.125 in | Acrylic |
| 3 | usb_spacer | 0.125 in | Acrylic |
| 4 | switch_plate | 0.0625 in | POM/Acetal |
| 5 | closed_spacer | 0.125 in | Acrylic |
| 6 | colored_top | 0.125 in | Acrylic |
| 7 | clear_top | 0.125 in | Acrylic |

Angled Foot Stackup

Foot stackup. O is closest to the case and is on the "top"

| Sheet Number | FreeCAD "Part" | Thickness | Material |
| - | - | - | - |
| 0 | foot_0 | 0.125 in | Acrylic |
| 1 | foot_1 | 0.125 in | Acrylic |
| 2 | foot_2 | 0.125 in | Acrylic |
