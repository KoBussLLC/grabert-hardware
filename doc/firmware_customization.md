# Firmware Customization
 
## QMK Firmware
 
The keyboard firmware shipped with all Grabert keyboard is QMK with VIA enabled. To see the latest firmware, see the [KoBuss QMK Fork](https://github.com/KoBussLLC/qmk_firmware).
 
The current firmware uses the OLED screen for WPM speed, caps lock indicator, and layer indicator. The images are hard coded using the `grabert.h` file and the [image2cpp](https://javl.github.io/image2cpp/) website to convert pixels into vertically packed bits.
 
By default the bottom-right modifiers and right shift are toggle-tap keys that are arrow keys on "tap" and modifiers on "hold".
 
## Rust Firmware
 
TODO: Fork an existing Rust keyboard firmware and write a Grabert implementation
 