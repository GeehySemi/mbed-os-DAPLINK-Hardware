# DAPLink 硬件固件 / DAPLink Hardware Firmware Assets

[中文](#中文说明) | [English](#english)

## 中文说明

本仓库提供与极海 DAPLink 兼容开发及接口硬件相关的固件文件。

### 仓库内容

| 文件 | 说明 |
| --- | --- |
| `apm32f103xb_bl.bin` | 适用于 APM32F103xB 目标器件的 Bootloader 固件 |
| `apm32f407ig_if.hex` | 适用于 APM32F407IG 目标器件的接口固件 |

### 烧录前确认

烧录固件前，请确认：

- 目标板上的准确 MCU 型号
- 开发板版本及硬件设计
- 所需文件属于 Bootloader 固件还是接口固件
- 正确的烧录地址与操作流程
- 已备份现有固件，且具备可恢复方案

将固件烧录至不兼容的目标器件，可能导致调试器或开发板暂时无法使用，需要通过外部编程器恢复。

### 使用说明

本仓库中的文件为预编译固件。请使用兼容的编程器，并遵循对应极海硬件的烧录说明。请勿仅根据相似的 MCU 系列名称直接烧录。

### 技术支持

如需确认固件与硬件的对应关系、烧录方法、产品信息及技术支持，请访问：[www.geehy.com](https://www.geehy.com/)。

---

## English

This repository contains firmware assets associated with Geehy DAPLink-compatible development and interface hardware.

### Repository contents

| File | Description |
| --- | --- |
| `apm32f103xb_bl.bin` | Bootloader firmware binary for an APM32F103xB-based target |
| `apm32f407ig_if.hex` | Interface firmware image for an APM32F407IG-based target |

### Before programming

Confirm all of the following before flashing a firmware image:

- The exact MCU part number on the target board
- The board revision and hardware design
- Whether the required image is a bootloader or interface firmware
- The correct programming address and flashing procedure
- That a recoverable backup of the existing firmware is available

Programming an image to an incompatible target may leave the debugger or board unusable until it is recovered with an external programmer.

### Usage

These files are prebuilt firmware images. Use a compatible programmer and the programming instructions supplied with the corresponding Geehy hardware. Do not flash either image solely based on a similar MCU family name.

### Support

For the correct firmware-to-hardware mapping, programming instructions, product information, and technical support, visit [www.geehy.com](https://www.geehy.com/).
