# DAPLink Hardware Firmware Assets

This repository contains firmware assets associated with Geehy DAPLink-compatible development and interface hardware.

## Repository contents

| File | Description |
| --- | --- |
| `apm32f103xb_bl.bin` | Bootloader firmware binary for an APM32F103xB-based target |
| `apm32f407ig_if.hex` | Interface firmware image for an APM32F407IG-based target |

## Before programming

Confirm all of the following before flashing a firmware image:

- The exact MCU part number on the target board
- The board revision and hardware design
- Whether the required image is a bootloader or interface firmware
- The correct programming address and flashing procedure
- That a recoverable backup of the existing firmware is available

Programming an image to an incompatible target may leave the debugger or board unusable until it is recovered with an external programmer.

## Usage

These files are prebuilt firmware images. Use a compatible programmer and the programming instructions supplied with the corresponding Geehy hardware. Do not flash either image solely based on a similar MCU family name.

## Support

For the correct firmware-to-hardware mapping, programming instructions, product information, and technical support, visit [www.geehy.com](https://www.geehy.com/).
