# Keero Bot Mainboard

The Keero Bot mainboard is the core hardware platform of the Keero system. It brings together compute, sensing, interaction, power management, and module connectivity in a compact reusable board.

## Overview

The mainboard is designed to act as the hardware foundation for:

- AI-oriented embedded interaction
- portable and dockable device concepts
- future external modules such as tracks and accessories
- repeated prototyping on top of one stable system core

## Public Feature Summary

At a high level, the board includes:

- ESP32-S3 based compute
- camera and display support
- audio input and output
- haptic and motion features
- managed portable power
- modular expansion interfaces

## Design Intent

This board is not presented as a generic development breakout. It is designed as the reusable core of a broader hardware platform.

That design intent matters because it supports:

- consistent firmware growth
- module experimentation
- sponsor-facing hardware demos
- future productization work

## Disclosure Boundary

This repository keeps the public mainboard story intentionally high level.

Publicly documented:

- architecture
- subsystem roles
- product direction
- prototyping status

Not publicly emphasized here as unrestricted release assets:

- full manufacturing packages
- editable design sources
- replication-grade implementation detail

## Status

- Architecture defined
- Core board implemented
- Prototype iteration in progress

## License Direction

Keero Bot is developed in an open-hardware spirit, but official hardware production details are shared in a more controlled way than the firmware layer.
