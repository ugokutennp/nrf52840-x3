# nrf52840-x3
DIY Multiple Connection Watchman Dongle for SteamVR
![dongle](https://github.com/ugokutennp/nrf52840-x3/blob/main/images/DSC03066_.JPG)

## Hardware
It includes data for PCBs made with Kicad7, Gerber data for manufacturing, 3D models of cases, and labels.   
USB2.0 Hub chip with four downstream ports (SL2.1s) running three nrf52840 (MS88SF2) and one USB Type A connector.

BOM can be viewed [here](https://htmlpreview.github.io/?https://github.com/ugokutennp/nrf52840-x3/blob/main/Hardware/PCB/nrf52840_hub.html).Other data are below.

[schematic](images/schematic.pdf),
[layout](images/schematic.pdf)

## Bootloader

The hex file in the Bootloader file is a build of [Adafruit_nRF52_Bootloader](https://github.com/adafruit/Adafruit_nRF52_Bootloader).
Using J-Link to write the bootloader via SWD, the uf2 firmware created with [Watchman-uf2](https://github.com/ugokutennp/watchman-uf2) can be written via USB.
