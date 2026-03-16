<div align="center">
  
# 🏠 Smart Home Automation System

### ATmega16 Microcontroller Based Bluetooth-Controlled Home Automation

[![Made with AVR](https://img.shields.io/badge/Made%20with-AVR-blue.svg)](https://www.microchip.com/en-us/products/microcontrollers-and-microprocessors/8-bit-mcus/avr-mcus)
[![ATmega16](https://img.shields.io/badge/MCU-ATmega16-orange.svg)](https://www.microchip.com/wwwproducts/en/ATmega16)
[![Bluetooth](https://img.shields.io/badge/Communication-Bluetooth%20HC--05-blue.svg)](https://components101.com/wireless/hc-05-bluetooth-module)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**Control your home appliances wirelessly using your smartphone via Bluetooth**

[Features](#-features) • [Demo](#-demo) • [Circuit](#-circuit-diagram) • [Installation](#-installation) • [Usage](#-usage)

</div>

---

## 🎯 Project Overview

This Smart Home Automation System allows users to control household electrical appliances (lights, fans, motors, etc.) wirelessly through a smartphone application using Bluetooth communication. The system is built around the ATmega16 microcontroller and HC-05 Bluetooth module.

### Key Highlights

- 🔌 Control up to **8 appliances** independently
- 📱 Android app for intuitive control
- 🔒 Password-protected access
- ⚡ Real-time appliance status feedback
- 💰 Low-cost implementation (~₹1500)
- 🔧 Easy to install and configure

---

## ✨ Features

### Hardware Features

- ✅ **ATmega16 Microcontroller** - 8-bit AVR with 16KB Flash
- ✅ **HC-05 Bluetooth Module** - Wireless communication (Class 2, 10m range)
- ✅ **8-Channel Relay Module** - Controls AC appliances (230V)
- ✅ **LCD Display (16x2)** - Shows system status
- ✅ **Manual Override Switches** - Physical control option
- ✅ **LED Indicators** - Visual feedback for each appliance
- ✅ **Over-current Protection** - Safety features

### Software Features

- ✅ **UART Communication** - Serial data transfer with Bluetooth
- ✅ **Command Parser** - Interprets mobile app commands
- ✅ **State Machine** - Manages appliance states
- ✅ **Timer-based Scheduling** - Auto ON/OFF functionality
- ✅ **Error Handling** - Validates commands and prevents faults
- ✅ **EEPROM Storage** - Saves settings and preferences

---

## 🛠️ Hardware Components

| Component | Quantity | Specification | Purpose |
|-----------|----------|---------------|---------|
| **ATmega16 Microcontroller** | 1 | 8-bit, 16MHz, 40-pin DIP | Main controller |
| **HC-05 Bluetooth Module** | 1 | Bluetooth 2.0, UART interface | Wireless communication |
| **8-Channel Relay Module** | 1 | 5V trigger, 10A/250VAC contacts | Appliance switching |
| **LCD Display** | 1 | 16x2 character, I2C/Parallel | Status display |
| **Crystal Oscillator** | 1 | 16 MHz | Clock source |
| **Voltage Regulator 7805** | 1 | 5V, 1A | Power supply |
| **Capacitors** | 4 | 22pF (2), 10µF (2) | Filtering & stability |
| **Resistors** | 10 | 330Ω, 10kΩ | Pull-ups & current limiting |
| **LEDs** | 8 | 5mm, assorted colors | Status indicators |
| **Push Buttons** | 8 | SPST, NO | Manual control |
| **Transformer** | 1 | 230V to 12V, 1A | AC to DC conversion |
| **Diode Bridge** | 1 | 1A | Rectification |
| **PCB/Veroboard** | 1 | General purpose | Circuit mounting |

**Total Cost:** Approximately ₹1200-₹1500

---

## 📐 Circuit Diagram

### Block Diagram
