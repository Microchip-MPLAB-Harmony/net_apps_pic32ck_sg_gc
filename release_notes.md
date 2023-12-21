![Microchip logo](https://raw.githubusercontent.com/wiki/Microchip-MPLAB-Harmony/Microchip-MPLAB-Harmony.github.io/images/microchip_logo.png)
![Harmony logo small](https://raw.githubusercontent.com/wiki/Microchip-MPLAB-Harmony/Microchip-MPLAB-Harmony.github.io/images/microchip_mplab_harmony_logo_small.png)

# Microchip MPLAB® Harmony 3 Release Notes

## Network Application Examples for PIC32CK GC01 Family, v3.1.0

### New Features
- Support for MAC RX/TX Checksum offload feature
- Addition of IPERF demo for PIC32CK GC01 Curiosity Ultra.


### Improvements and Bug Fixes
- IPERF throughput improvement.
- Fix for GMAC driver critical section access issue.
- ETHPHY driver write function.
- Fix for bind operation in berkeley module.
- Fix for 'IntegerSymbol not found' MCC failure.
- Updated demo documentation.

### Known Issues
None


### Development Tools

- [MPLAB® X IDE, v6.15](https://www.microchip.com/mplab/mplab-x-ide) or later
- [MPLAB® XC32 C/C++ Compiler, v4.35](https://www.microchip.com/mplab/compilers) or later
- [MPLAB® Code Configurator(MCC) Plugin, v5.3.7](https://www.microchip.com/en-us/tools-resources/configure/mplab-code-configurator) or later
- [MPLAB® Harmony v3 net repository, v3.11.0](https://github.com/Microchip-MPLAB-Harmony/net/tree/v3.11.0)
- [MPLAB® Harmony v3 net\_apps\_pic32ck\_sg\_gc demo apps repository, v3.1.0](https://github.com/Microchip-MPLAB-Harmony/net_apps_pic32ck_sg_gc/tree/v3.1.0)

### Development Kit Support

This release supports applications for the following development kit.

| Development Kits |
| --- |
| [PIC32CK GC01 Curiosity Ultra](https://www.microchip.com/en-us/development-tool/EA23J82A) |


## Net Release Notes

- See the [Net 3.11.0 Release Notes](https://github.com/Microchip-MPLAB-Harmony/net/tree/v3.11.0)

---

## Harmony 3 Network Application Examples for PIC32CK GC01 Family v3.0.0
The applications demonstrate the typical usage of Harmony 3 TCP/IP Stack on a hardware board with PIC32CK2051GC01144 device.
- All applications use MCC for configuration.
- All applications created with TCP/IP Configurator Plugin.

### New Features
- None

### Known Issues
- XC32 v4.30 compiler has a known issue wherein applications built with certain configurations could cause a runtime exception. It is recommended to use v4.21 of the XC32 compiler until a newer version becomes available.

### Development Tools

- [MPLAB® X IDE v6.15](https://www.microchip.com/mplab/mplab-x-ide) or later
- [MPLAB® XC32 C/C++ Compiler v4.21](https://www.microchip.com/mplab/compilers)
- [MPLAB® Code Configurator (MCC) 5.3.7](https://www.microchip.com/en-us/tools-resources/configure/mplab-code-configurator) or later
- [Harmony net repository, 3.10.1](https://github.com/Microchip-MPLAB-Harmony/net/tree/v3.10.1)
- [Harmony net\_apps\_pic32ck\_sg\_gc demo apps repositories, 3.0.0](https://github.com/Microchip-MPLAB-Harmony/net_apps_pic32ck_sg_gc/tree/v3.0.0)

### Development Kit Support

This release supports applications for the following development kit.

| Development Kits |
| --- |
| [PIC32CK GC01 Curiosity Ultra](https://www.microchip.com/en-us/development-tool/EA23J82A) |


## Net release notes

- See the [Net 3.10.1 Release notes](https://github.com/Microchip-MPLAB-Harmony/net/tree/v3.10.1)



