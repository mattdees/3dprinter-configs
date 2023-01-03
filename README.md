
Klipper configuration for an Ender3 v2 with the following mods:

SKR e3 mini v3 motherboard
Creality Sprite Extruder Pro
CR touch

Configured for Fluidd with all the required macros in place
G29 GCODE Macro for backwards compatibility
CRTouch z-homing

This file contains common pin mappings for the BIGTREETECH SKR mini
E3 v3.0. To use this config, the firmware should be compiled for the
STM32G0B1 with a "8KiB bootloader" and USB communication.

The "make flash" command does not work on the SKR mini E3. Instead,
after running "make", copy the generated "out/klipper.bin" file to a
file named "firmware.bin" on an SD card and then restart the SKR
mini E3 with that SD card.
