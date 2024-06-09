---
title: GPD Win Mini Case with detachable grips
excerpt: "GPD Win Mini Case with detachable grips"
header:
  teaser: /assets/images/postphotos/gpdwinminicase/arrows.jpg
  #overlay_color: "#333"
  overlay_image: /assets/images/postphotos/gpdwinminicase/frontopen.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  #overlay_filter: rgba(255, 0, 0, 0.5)
  #overlay_filter: linear-gradient(rgba(255, 0, 0, 0.5), rgba(0, 255, 255, 0.5))
  #caption: "Finished Product"
  actions:
    - label: "3D Files"
      url: "https://www.printables.com/social/278875-wallnutts/models"
teaser_image_path: /assets/images/postphotos/gpdwinminicase/arrows.jpg #use .jpg files
#sidebar:
#  - title: "Title"
#    image: http://placehold.it/350x250
#    image_alt: "image"
#    text: "Some text here."
#  - title: "Another Title"
#    text: "More text here."
date: 2024-06-09
#last_modified_at: 2021-07-07
---
# Introduction

![](/assets/images/postphotos/gpdwinminicase/frontclosed.jpg "Front View") | ![](/assets/images/postphotos/gpdwinminicase/back1.jpg "Back View")

![](/assets/images/postphotos/gpdwinminicase/frontopen.jpg "Front View")

Problaby the first ever 3D printed GPD Win Mini case available! Comes with detachable screw-on flat grips. The added thickness of the case, even without the grips, also allows for great heat insulation between your hands and the console, allowing you to play at >20W comfortably. 

I didnt really like the smooth surface that my glass print bed imparted on the surface of the shell, hence I vinyl wrapped both surfaces with leather wrap for a nicer finish. Thats where the leather texture you can see in the pictures comes from!

# Instructions

Top half of the case is stuck on with 1mm thick VHB tape, while bottom half is attached on with both VHB tape and M2 screws.

![](/assets/images/postphotos/gpdwinminicase/VHB.jpg "VHB locations")

## Fuzzy Skin Tutorial

Additionally, I decided to try out the Fuzzy Skin feature in PrusaSlicer for a matte finish and better grip. However, just toggling the feature on would apply Fuzzy Skin to all surfaces, including the inner walls touching the Win Mini which was undesirable as I want the inner walls to be smooth.

![](/assets/images/postphotos/gpdwinminicase/fuzzyskin1.png "Undesirable")
![](/assets/images/postphotos/gpdwinminicase/fuzzyskin0.png "Desirable")

Hence I have included .3mf files with overlapping modifiers that block off the inner walls from generating Fuzzy Skin. The following are instructions on how to properly slice the models and get the modifiers working. Ive only tested this process on PrusaSlicer so Im not sure how this will work with other Slicers.

To start off, toggle Fuzzy Skin ON for the whole model under Print Settings > Layers and Perimeters > Fuzzy Skin (Bottom of the page). Im using 0.2 point distance and 0.2 point thickness. Then, import the .3mf under the Fuzzy Skin folder from Printables and press YES on the dialog box. 

![](/assets/images/postphotos/gpdwinminicase/fuzzyskin2.png "Dialog Yes")

Right click on the "fuzzy skin modifier" labelled models and change it to the "modifier" setting under "Change Type".

![](/assets/images/postphotos/gpdwinminicase/fuzzyskin3.png "Modifier")

Right click again on the "fuzzy skin modifier" model and click on Add Settings > Fuzzy Skin. Then, check show settings on "Fuzzy Skin".

![](/assets/images/postphotos/gpdwinminicase/fuzzyskin4.png "Drop Down")
![](/assets/images/postphotos/gpdwinminicase/fuzzyskin5.png "Checkbox")

Lastly, click on the "fuzzy skin modifier" model again and change the Fuzzy Skin setting to "None". Now you can slice the model and generate smooth inner walls!

![](/assets/images/postphotos/gpdwinminicase/fuzzyskin6.png "None")















