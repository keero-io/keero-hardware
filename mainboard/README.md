# Keero Bot – Mainboard

The Keero Bot Mainboard is the core hardware platform of the Keero AI system.  
It integrates processing, sensing, interaction, and power management into a single modular PCB designed for extensibility and experimentation.

This board is built around the ESP32-S3 and serves as the central unit that connects all external modules such as dock, tracks, buttons, and other expansion boards.

---

## Overview

The mainboard combines multiple subsystems into a compact and modular design:

- ESP32-S3 microcontroller (WROOM-1U)
- Camera interface (OV2640)
- OLED display interface
- Audio input/output (microphone + speaker)
- Haptic feedback
- Motion sensing (accelerometer)
- Advanced power management (LiPo + PMIC)
- Magnetic pogo-pin interface for expansion and charging

This makes it a complete foundation for building AI-powered embedded devices.

---

## Key Features

### 🧠 Processing
- ESP32-S3-WROOM-1U (WiFi + BLE)
- External antenna support
- Native USB for programming

### 📷 Vision
- OV2640 camera interface (CSI)
- Full parallel data bus routed

### 🖥 Display
- OLED display connector
- Dedicated boost converter for display voltage (VPP)

### 🔊 Audio
- I2S microphone (digital MEMS)
- MAX98357A I2S amplifier for speaker output

### 📳 Haptics
- DRV2605 haptic driver
- Supports vibration motors for feedback

### 📈 Motion Sensing
- LIS2DW12 accelerometer
- Interrupt-based motion detection

### 🔋 Power System
- AXP2101 PMIC
- LiPo battery charging and management
- Multiple regulated rails:
  - 3.3V
  - 2.8V
  - 1.5V

### 🔌 Connectivity & Expansion
- Magnetic pogo-pin interface
  - UART communication
  - Power delivery (charging/docking)
- Modular headers for:
  - Buttons
  - Microphone
  - Speaker
  - External modules

---

## Architecture

The board is designed as a modular hub:

- Mainboard → core processing and power
- Modules → external extensions (dock, tracks, sensors)

This allows flexible system configurations depending on the use case.

---

## Hardware Files

All production and design files are included:

- 📄 Schematic (PDF)
- 🧩 PCB layout renders
- 📦 Gerber files (for manufacturing)
- 📋 Bill of Materials (BOM)
- 🧭 Pick & Place files (CPL)
- 🛠 EasyEDA source files (project export)

---

## Manufacturing

This board is designed to be manufactured using standard PCB + PCBA services.

Recommended workflow:
1. Upload Gerber files for PCB fabrication
2. Use BOM + Pick & Place for assembly (PCBA)
3. Source components via LCSC or equivalent

---

## Status

- ✅ Schematic: completed  
- ✅ PCB layout: completed  
- 🚧 First revision: ready for manufacturing  
- 🚧 Testing: in progress  

---

## Notes

- Camera reset and power-down pins are fixed due to GPIO limitations
- Power system is fully managed via AXP2101 over I2C
- Board is optimized for modular expansion via pogo interface

---

## License

This project is open-source hardware.

---

## About Keero

Keero Bot is an open-source modular AI hardware platform focused on combining embedded systems with interactive AI capabilities.
