# STM32 Microcontroller Development Board

## Overview

A custom STM32 microcontroller development board designed using KiCad to strengthen embedded systems and PCB design skills. The board is built around the STM32F103C8T6 microcontroller and integrates power
regulation, clock generation, reset circuitry, programming/debugging access, and GPIO expansion interfaces.

The project focuses on microcontroller-based hardware design, power distribution, peripheral integration, and PCB layout techniques.

---

## Features

- STM32F103C8T6 ARM Cortex-M3 microcontroller
- Micro-USB connector for 5V power input
- AMS1117-3.3V onboard voltage regulation
- External crystal clock circuit
- Reset and BOOT0 configuration circuits
- SWD programming and debugging interface
- GPIO expansion headers for external peripherals
- Onboard power and user status LEDs
- User input and reset push buttons
- Four M3 mechanical mounting holes
- Two-layer PCB layout with bottom-layer GND copper pour

---

## Design Considerations

- Implemented 3.3V power regulation using the AMS1117 regulator.
- Added decoupling capacitors near the microcontroller power pins to
  support stable power delivery.
- Integrated an external crystal circuit for the MCU clock.
- Included reset and BOOT0 configuration circuitry for microcontroller
  startup control.
- Provided an SWD header for external programming and debugging using
  an ST-Link interface.
- Added GPIO expansion headers for future sensor and peripheral
  interfacing.
- Optimized component placement, track widths, and routing for the
  compact PCB layout.
- Incorporated a bottom-layer GND copper pour and four mechanical
  mounting holes.
- Verified the schematic and PCB layout using KiCad ERC and DRC
  checks.

---

## Learnings

- Understanding STM32F103C8T6 microcontroller pin configuration and
  peripheral requirements.
- Designing microcontroller power supply and decoupling circuits.
- Understanding clock generation, reset, and boot configuration
  circuits.
- Learning SWD programming and debugging interface connections.
- Organizing GPIO expansion and external peripheral connections.
- Improving PCB routing techniques for fine-pitch LQFP microcontroller
  packages.
- Applying copper pours, clearance rules, and mechanical mounting
  considerations.
- Performing schematic verification and PCB design rule checks using
  KiCad.

---

## Images
