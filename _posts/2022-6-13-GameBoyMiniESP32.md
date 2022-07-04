---
title: GameBoy Mini ESP32
---

Its running on a TTGO T8 board with custom compiled retro-go firmware which was originally intended for the Odroid-GO.

Some interesting features that set it apart from other similar devices:

Seperate SDCARD and LCD buses. LCD is controlled through SPI and SDCARD through sdmmc.

Small current draw of 0.04A allowing for theoretical 30 hour battery life from a 1200mAh l-ion battery.

From Retro-Go Github: Emulates NES, SNES, Gameboy, Gameboy Color

Sega: SG-1000, Master System, Mega Drive / Genesis, Game Gear, Colecovision, NEC: PC Engine, Atari: Lynx, DOOM

This is still very much a work in progress for me on the hardware side as I have yet to make a case and additional electronics like a battery life monitor. A full build guide will be coming after i do so (hopefully?).

Link to retro-go firmware: https://github.com/ducalex/retro-go
