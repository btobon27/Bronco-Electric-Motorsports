# Bryan Tobon's FSAE Projects

# Low Voltage Switching PCB

## Schematic and PCB

<img width="3024" height="4032" alt="Low Voltage Switching PCB" src="https://github.com/user-attachments/assets/f222a4d2-173e-49c6-a485-ffc9fdbf7de2" />

## Design Overview

Designed for a 12 V, 100 Ah LiFePO4 low-voltage battery system.

The board was designed around a measured vehicle low-voltage current draw of approximately 20–25 A.

A gate driver is used to control high-current power MOSFETs for inductive loads such as cooling pumps and fans.

Flyback diode protection is included across inductive loads to protect the switching MOSFETs from voltage spikes generated during turn-off.

## Main Functions

- High-current low-voltage load switching
- MOSFET gate drive
- Pump and fan control
- Flyback protection for inductive loads
- Integration with the vehicle low-voltage system
