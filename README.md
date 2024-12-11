# PWM-GripHeat
Rugged PWM control for a grip heater using an attiny85 and a beefy NMOS, supporting a dual color or RGB indicator, with careful attention paid to power usage.

KiCad 8.0 Schematics and PCB files are (as expected) under the "hardware" folder, firmware is under the "firmware" folder.

Cost for a single board was TODO: fill in total costs

## Hardware
<img src="hardware/Images/PCB Front.png" alt="Front render of PCB" width="500"/><img src="hardware/Images/PCB Back.png" alt="Render of backside for PCB" width="500"/>

The BOM (bill-of-materials) is relatively short, holding all external components in TODO: Here, and the PCB components [here](<hardware/bom/BOM-PWM GripHeat-1.0.html>).

Assembly should take about an hour's work with the right tools. I use lead-free solder paste for all my work, with the PCB itself using ENIG for all pads. Soldering is sped up by using a hand-held hot air reflow gun, but all pads are big enough to facilitate hand soldering.

## Firmware
I'm using PlatformIO on VSCodium to write the fairly simple firmware, build steps:
1. Item 1
1. rr
1. te

## License
This project is:
- Software: GPL3 protected
- Hardware: CERN-OHL-S-2.0 (https://spdx.org/licenses/CERN-OHL-S-2.0.html)