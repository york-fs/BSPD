# Brake System Plausibility Device

![Revision](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Fbspd%2Finfo.json&query=%24.revision&label=Revision)
![Pad Count](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Fbspd%2Finfo.json&query=%24.pad_count&label=Pad%20Count)
![Via Count](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Fbspd%2Finfo.json&query=%24.via_count&label=Via%20Count)
![ERC Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fyork-fs.github.io%2Fbspd%2Ferc.json)
![DRC Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fyork-fs.github.io%2Fbspd%2Fdrc.json)

Uses non-programmable logic to implement the Brake System Plausibility Device required by FSUK rules. The BSPD opens the low-voltage shutdown circuit in the event of current being delivered to the motor while hard braking occurs.

## Features
- TODO

## PCB Notes
- Designed in KiCad 9.0

<img width="1920" height="1080" alt="BSPDv1 3" src="https://github.com/user-attachments/assets/0f96b930-b63e-4375-bd16-d9c2972771f0" />

## Cloning

A recursive clone must be used to download the `kicad-library` repository:

    git clone --recursive https://github.com/york-fs/bspd.git
