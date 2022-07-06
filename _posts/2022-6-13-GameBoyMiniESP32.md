---
title: GameBoy Mini ESP32
excerpt: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
header:
  #overlay_color: "#333"
  overlay_image: /assets/images/teaser/mainteaser.jpg
  #overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  #overlay_filter: rgba(255, 0, 0, 0.5)
  #overlay_filter: linear-gradient(rgba(255, 0, 0, 0.5), rgba(0, 255, 255, 0.5))
  caption: "Finished Product"
  actions:
    - label: "Build Guide"
      url: "https://unsplash.com"
    - label: "More Info"
      url: "https://unsplash.com"
teaser_image_path: /assets/images/teaser/mainteaser.jpg
#sidebar:
#  - title: "Title"
#    image: http://placehold.it/350x250
#    image_alt: "image"
#    text: "Some text here."
#  - title: "Another Title"
#    text: "More text here."
---

Its running on a TTGO T8 board with custom compiled retro-go firmware which was originally intended for the Odroid-GO.

Some interesting features that set it apart from other similar devices:

Seperate SDCARD and LCD buses. LCD is controlled through SPI and SDCARD through sdmmc.

Small current draw of 0.04A allowing for theoretical 30 hour battery life from a 1200mAh l-ion battery.

From Retro-Go Github: Emulates NES, SNES, Gameboy, Gameboy Color

Sega: SG-1000, Master System, Mega Drive / Genesis, Game Gear, Colecovision, NEC: PC Engine, Atari: Lynx, DOOM

This is still very much a work in progress for me on the hardware side as I have yet to make a case and additional electronics like a battery life monitor. A full build guide will be coming after i do so (hopefully?).

Link to retro-go firmware: https://github.com/ducalex/retro-go
