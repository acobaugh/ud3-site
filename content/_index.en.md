---
title: "UD3"
---

# UD3 Tesla Coil Driver

The UD3 Tesla Coil Driver is an advanced microcontroller-based  DRSSTC and QCW Tesla coil driver/interrupter originally designed by Steve Ward and Phil Slawinski, now maintained as an open source project.

## Features

* It runs FreeRTOS
* Commandline over serial
* Multi user commandline over MIN-Protocol
* Embedded interrupter with MIDI and SID audio modulation
* Dual voltage measurement (differential)
* Bus current measurement (current or voltage mode CT)
* Output for up to 4 relays
* Support for Teslaterm and UD3-node
* Telemetry over serial
* System fault interlocks for undervoltage/temperature/watchdog
* UART with support for manchester encoding/decoding for AC coupled connections
* Bootloader with serial/usb support (firmware update via Teslaterm or via Fibernet +FTP)
* Primary resonator fres measurement (frequency sweep)
* Alarm/Event system for fault tracing
* Primary peak current measurement over feedback CT
* Pulse skipping
* Serial over MIN over UDP via 100Mb Fiber Ethernet with the Fibernet add-on

## Links

* [UD3 Altium schematic/pcb](https://github.com/Netzpfuscher/UD3_PCB)
* [UD3 firmware](https://github.com/Netzpfuscher/UD3)
* [Teslaterm](https://github.com/Netzpfuscher/Teslaterm)
* [Fiber ethernet schematic/pcb](https://github.com/TMaxElectronics/UD3_Fibernet)
* [Fiber ethernet firmware](https://github.com/TMaxElectronics/UD3-Fibernet-Firmware)
* [UD3 wiki](https://github.com/Netzpfuscher/UD3/wiki)

## Wiring diagrams

![UD3](images/PXL_20210308_172545905.jpg?width=40pc)

