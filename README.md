# Basic Switch Interface with Pull-Down Resistors Using PIC16F877A (Proteus Simulation)

## Project Overview
This project demonstrates interfacing push-button switches with a PIC16F877A microcontroller using **pull-down resistors** for stable digital input signals. The microcontroller reads the switch states and controls LEDs accordingly. The entire setup is simulated using **Proteus** software.

## Features
- Interface switches with PIC16F877A input pins using pull-down resistors
- Read switch states and control LEDs based on input
- Stable input readings avoiding floating states due to pull-down resistors
- Proteus simulation for testing the circuit without physical hardware

## Components
- PIC16F877A microcontroller
- Push-button switches
- Pull-down resistors (10kΩ recommended)
- LEDs with current limiting resistors
- Proteus simulation environment

## Circuit Description
- Switch connected between input pin and +5V
- Pull-down resistor connected between input pin and GND
- Input pin reads HIGH when switch pressed, LOW when released
- LED outputs controlled based on switch inputs

## How to Run
1. Open the Proteus simulation file (`.DSN`) included in this repository.
2. Load the PIC16F877A hex file into the microcontroller.
3. Start the simulation.
4. Press and release switches in the simulation to see corresponding LED behavior.

## Code Overview
- Configure PIC I/O ports (inputs for switches, outputs for LEDs)
- Poll switch states continuously
- Control LEDs based on switch inputs

## References
- [PIC16F877A Datasheet](http://ww1.microchip.com/downloads/en/DeviceDoc/39582b.pdf)

---

Feel free to clone this repository and experiment with the code and Proteus simulation!

---

