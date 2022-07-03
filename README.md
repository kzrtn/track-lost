# TRACK LOST
F12 TKL type-C PCB for the Duck Orion. Designed in KiCad 6.0

![track lost PCB front](https://user-images.githubusercontent.com/6176161/177023009-3f3b8d5d-573f-42c7-9e03-7f6c15ff65ed.png)
![track lost PCB back](https://user-images.githubusercontent.com/6176161/177023019-7bf96e1c-9cdb-4a73-b829-cf77385d8782.png)
![track lost PCB traces](https://user-images.githubusercontent.com/6176161/177023001-8a25e5e8-0e82-4c40-9ce6-0b3b61d71fbf.png)

## Features
- Uses an RP2040 MCU with 32MB of external flash
- Uses WS2812C-2020 LEDs for smaller footprint and less power usage
- Has more underglow LEDs for better LED diffusion
- Indicators use SK6812mini-e LEDs instead
- Multi-layout
- BOOTRESET button if bootmagic isn't available
- ESD chip to prevent damage from electrostatic discharge
- Polyfuse to prevent overcurrent
- Gerber and files available for manufacturing and assembly with JLCPCB (In `track-lost/JLCPCB folder`)
- Curved traces

## Firmware
WIP

## Multi-Layout Support
- Supports both ANSI and ISO layouts
- Supports both 6.25u and 7u spacebar
- Supports split backspace
- Supports split right shift

![Multilayout image](https://user-images.githubusercontent.com/23428162/173192900-2607653f-76fe-4558-9563-d40445c1b6b9.png)

## Indicator LEDs
The typical LEDs on the original Duck Orion PCB are TX LEDs that you have to solder in. But for this PCB, SK6812mini-e reverse-mount ARGB LEDs were used instead.
- Reverse mount to keep all components on the same side of the PCB for cheaper assembly
- RGB and programmable
- NOTE: Because these are surface mounted onto the PCB, they'll likely leak light (I'll update this when I test it out). Could be fixed with light pipes or something else to isolate the rays from each other.

![top left indicators](https://user-images.githubusercontent.com/6176161/177023300-dd77008a-560c-4b50-bc31-6fb274446e09.png)
![above arrow key indicators](https://user-images.githubusercontent.com/6176161/177023312-dbff45fc-4a72-4d81-ae3c-809b1537fcd7.png)

## WIP
- Add photos of PCBs
- Add photos of PCB in case
- Add photo of original PCB LED difussion vs TRACK LOST PCB LED difussion
- Create and add firmware to repo
