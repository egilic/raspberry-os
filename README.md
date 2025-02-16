# Attempting to build a robust raspberry pi operating system that runs on hardware...

## Overview (02/15/25)
This will include:
- A basic bootloader in assembly (`start.S`).
- A simple kernel entry point (`main.c`).
- A linker script (`linker.ld`)
- Other misc files (Makefile, etc)

## Running (QEMU)
To test on QEMU (ARM) for now

# Design Documentation

## Planned Features
1. Initialize UART for debugging
2. Setup the interrupt controller
3. Simple scheduler and multitasking
4. Basic drivers (GPIO, timers, etc.)

## References
- [BCM2835 ARM Peripherals manual](https://www.raspberrypi.org/documentation/)
- [ARMv7 Architecture Reference Manual](https://developer.arm.com/documentation/)
