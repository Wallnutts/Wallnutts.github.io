---
title: GameBoy Mini
excerpt: "Featuring over 30 hours of battery life and powered by an ESP32, this is my take on the bridge between the Gameboy and the Gameboy Micro."
header:
  teaser: /assets/images/postphotos/GBESP32/cover.jpg
  #overlay_color: "#333"
  overlay_image: /assets/images/postphotos/GBESP32/cover.jpg
  #overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  #overlay_filter: rgba(255, 0, 0, 0.5)
  #overlay_filter: linear-gradient(rgba(255, 0, 0, 0.5), rgba(0, 255, 255, 0.5))
  caption: "Finished Product"
  actions:
    - label: "Build Guide"
      url: "https://unsplash.com"
    - label: "More Info"
      url: "https://unsplash.com"
teaser_image_path: /assets/images/postphotos/GBESP32/cover.jpg
#sidebar:
#  - title: "Title"
#    image: http://placehold.it/350x250
#    image_alt: "image"
#    text: "Some text here."
#  - title: "Another Title"
#    text: "More text here."
---

# <center> This Guide is Still Unfinished! </center>

Its running on a TTGO T8 board with custom compiled retro-go firmware which was originally intended for the Odroid-GO.

Some interesting features that set it apart from other similar devices:

Seperate SDCARD and LCD buses. LCD is controlled through SPI and SDCARD through sdmmc.

Small current draw of 0.04A allowing for theoretical 30 hour battery life from a 1200mAh l-ion battery.

From Retro-Go Github: Emulates NES, SNES, Gameboy, Gameboy Color

Sega: SG-1000, Master System, Mega Drive / Genesis, Game Gear, Colecovision, NEC: PC Engine, Atari: Lynx, DOOM

This is still very much a work in progress for me on the hardware side as I have yet to make a case and additional electronics like a battery life monitor. A full build guide will be coming after i do so (hopefully?).

Link to retro-go firmware: https://github.com/ducalex/retro-go
