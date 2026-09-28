# Fault Latching PCB

## Schematic and PCB

<img width="2141" height="1777" alt="IMG_5866 (1)" src="https://github.com/user-attachments/assets/34863d85-6794-4746-952d-369603972cfc" />


## Design Overview

The Fault Latching PCB is part of the Formula SAE Electric vehicle safety system.

The circuit is designed to detect critical fault signals and maintain the fault condition after it has been triggered, even if the original fault signal is no longer present.

The latched fault state is used to interface with the vehicle shutdown circuit and prevent the system from returning to normal operation until the appropriate reset condition occurs.

## Design

Hardware-based fault latching is used so critical safety faults do not depend only on software.

The board receives fault inputs from vehicle safety systems and uses latching circuitry to retain the fault state.

A reset circuit allows the latch to be cleared only after the fault condition has been addressed and the proper reset sequence is performed.

The design interfaces with the Formula SAE Electric shutdown circuit to help ensure the vehicle enters and remains in a safe state when a critical fault occurs.

## Main Functions

- Detect critical vehicle fault signals
- Latch fault conditions in hardware
- Interface with the shutdown circuit
- Prevent automatic recovery after a fault
- Provide controlled fault reset behavior
- Support reliable vehicle safety operation
