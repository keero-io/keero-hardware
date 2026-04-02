# Keero Bot – Hardware

![Keero Bot](./assets/hero.png)

[![PCBWay Sponsorship](https://img.shields.io/badge/Sponsored%20by-PCBWay-red?style=for-the-badge&logo=pcbway)](https://www.pcbway.com/)

![Status](https://img.shields.io/badge/status-in%20development-orange)
![Hardware](https://img.shields.io/badge/hardware-open--source-blue)
![Platform](https://img.shields.io/badge/platform-ESP32--S3-green)


The Keero Bot hardware platform is a modular, open-source embedded system designed for building AI-powered devices.

This repository contains all hardware designs for the Keero ecosystem, including the mainboard and all supporting modules.

---

## 🚀 Project Overview

Keero Bot is built as a **modular AI hardware platform** that combines:

- Processing (ESP32-S3)
- Vision (camera)
- Audio (input/output)
- Haptics
- Motion sensing
- Power management
- Expandable hardware modules

The goal is to provide a **fully reproducible and extensible open hardware system** for developers, makers, and experimental AI projects.

---

## 📦 Repository Structure

```text
keero-hardware/
├── mainboard/
├── modules/
│   ├── dock/
│   ├── tracks/
│   └── ...

```

---

## 🧠 Mainboard

The central board that integrates all core functionality:

- ESP32-S3
- Camera interface (OV2640)
- OLED display interface
- Audio system (mic + speaker)
- Haptics driver
- Accelerometer
- AXP2101 PMIC power system
- Magnetic pogo pins (UART + charging)

👉 See: `mainboard/README.md`

---

## 🔌 Modules

External boards that extend the system:

- Dock (charging / development base)
- Tracks (mobility system)
- Future expansion modules

👉 See: `modules/README.md`

---

## 🛠 Included Files

Each hardware module contains:

- 📄 Schematic (PDF)
- 🧩 PCB layout renders
- 📦 Gerber files (ready for manufacturing)
- 📋 BOM (Bill of Materials)
- 🧭 Pick & Place (CPL)
- 🛠 EasyEDA source files (when available)

This ensures that the project is fully **open, reproducible, and manufacturable**.

---

## 🤝 Sponsored by PCBWay

This project is proudly supported by **PCBWay**, who are sponsoring PCB fabrication and helping bring this hardware to life.

Working with PCBWay has been an excellent experience:

- ⭐ Excellent PCB quality — clean finishes and precise manufacturing  
- ⚡ Fast turnaround times, even for complex designs  
- 🔧 Reliable PCBA service with accurate component placement  
- 📦 Well-packaged deliveries — everything arrived in perfect condition  
- 💬 Very helpful and responsive support team  

Their service made the transition from design to real hardware extremely smooth.

If you're working on embedded or open hardware projects, PCBWay is a highly recommended choice for both **PCB fabrication and assembly (PCBA)**.

Huge thanks to PCBWay for supporting this project 🙌

---

## 🧪 Manufacturing

The boards in this repository are designed for standard PCB + PCBA workflows:

1. Upload Gerber files for PCB fabrication  
2. Upload BOM + Pick & Place for assembly  
3. Select components (LCSC or custom sourcing)  
4. Order assembled boards  

All boards in this project are optimized for manufacturing via PCBWay.

---

## 📸 Previews

Render images and (later) real photos can be found in each module folder.

---

## 📊 Status

- Mainboard: ✅ Completed (ready for manufacturing)  
- Dock module: ✅ Prototype stage  
- Additional modules: 🚧 In development  

---

## 🎯 Goals

- Fully open-source hardware platform  
- Modular and expandable architecture  
- Easy reproducibility for the community  
- Integration with AI-driven firmware  


---

## 🌐 About Keero

Keero is focused on building experimental AI-driven hardware platforms that combine embedded systems with real-world interaction.

![PCBWay](./assets/pcbway.png)